<h2 id="news" style="margin:30px 0px 10px;">News</h2>

<style>
  #scrollableDiv {
    min-height: 100px;
    height: 100px;
    overflow-y: hidden;
    opacity: 1;
    transition: height 0.5s ease-in-out, opacity 0.5s ease-in-out;
  }
</style>

<ul id="scrollableDiv" onmouseover="showScrollbar()" onmouseout="hideScrollbar()">
  <li>[10/2024] One paper accepted to IEEE TSC'24 !</li>
  <li>[11/2023] One paper accepted to IEEE TSC'23 !</li>
</ul>
<script>
  function showScrollbar() {
    var div = document.getElementById('scrollableDiv');
    div.style.height = div.scrollHeight + 'px';
    div.style.opacity = 1;
  }
  function hideScrollbar() {
    var div = document.getElementById('scrollableDiv');
    div.style.height = '100px';
    div.style.opacity = 1;
  }
</script>
