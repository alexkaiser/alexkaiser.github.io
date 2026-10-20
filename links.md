---
layout: page
title: Contact
permalink: /links/
icons: true
---

<style>
  .icon-list { list-style: none; margin-left: 0; }
  .icon-list i { width: 1.4em; text-align: center; margin-right: 0.4em; }
</style>


* <i class="fa-solid fa-envelope" style="color:#555"></i>[alexdkaiser@stanford.edu](mailto:alexdkaiser@stanford.edu)

* <i class="fa-regular fa-envelope" style="color:#555"></i><span id="gmail">adkaiser [at] gmail [dot] com</span>

* <i class="fa-solid fa-building-columns" style="color:#8C1515"></i>[Stanford Profile](https://profiles.stanford.edu/alexander-kaiser)

* <i class="ai ai-google-scholar" style="color:#4285F4"></i>[Google Scholar Profile](https://scholar.google.com/citations?user=E30qvtkAAAAJ&hl=en)

* <i class="fa-brands fa-youtube" style="color:#FF0000"></i>[YouTube Channel](https://www.youtube.com/channel/UCWsLmHAiQFnYILsgI8WwJXg) with movies from many publications 

* <i class="ai ai-orcid" style="color:#A6CE39"></i>[ORCID](https://orcid.org/0000-0001-7241-9773)
{: .icon-list}

<!-- Builds the gmail link in the browser so the address never appears whole in the page source. -->
<script>
  (function () {
    var user = "adkaiser", domain = ["gmail", "com"].join(".");
    var a = document.createElement("a");
    a.href = "mailto:" + user + "@" + domain;
    a.textContent = user + "@" + domain;
    document.getElementById("gmail").replaceWith(a);
  })();
</script>
