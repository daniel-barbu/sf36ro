# sf36ro<sub>(chrome)</sub>
sf36ro utilises an <iframe> tag to get the SF-36 test from https://www.orthotoolkit.com/sf-36/ which it then translates to romanian via Javascipt code.

### Screenshot
![/img/screenshot.png not loaded correctly](/img/screenshot.png)

<script>
  document.body.innerHTML='<iframe src="https://sf36.daniel-barbu.cf/sf36.html" width="100%" height="100%" style="border:0px; postion:absolute;">';
  
  document.getElementsByTagName("title")[0].textContent="sf36.daniel-barbu.cf";
  var link=document.createElement("link"); link.rel="icon"; link.href="/img/favicon.png?"; document.getElementsByTagName("head")[0].appendChild(link);
</script>
