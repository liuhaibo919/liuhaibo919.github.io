<h2 id="news" style="margin:30px 0px 10px;">News</h2>

<style>
  #scrollableDiv {
    min-height: 50px;
    height: 50px;
    overflow-y: hidden;
    opacity: 1;
    transition: height 0.5s ease-in-out, opacity 0.5s ease-in-out;
  }
</style>

<ul id="scrollableDiv" onmouseover="showScrollbar()" onmouseout="hideScrollbar()">
  <li>[01/2025] Congratulations! One paper accepted to ACM WWW'25 !</li>
   <li>[12/2024] Congratulations! One paper accepted to IEEE INFOCOM'25 !</li>
  <li>[10/2024] Congratulations! One paper accepted to IEEE TSC'24 !</li>
  <li>[11/2023] Congratulations! One paper accepted to IEEE TSC'23 !</li>
</ul>
<script>
  function showScrollbar() {
    var div = document.getElementById('scrollableDiv');
    div.style.height = div.scrollHeight + 'px';
    div.style.opacity = 1;
  }
  function hideScrollbar() {
    var div = document.getElementById('scrollableDiv');
    div.style.height = '50px';
    div.style.opacity = 1;
  }
</script>
