<h2 id="news" style="margin:30px 0px 10px;">News</h2>

<style>
  #scrollableDiv {
    /* 将基础高度调整为 105px 左右，正好可以容纳 4 条新闻 */
    min-height: 105px;
    height: 105px;
    overflow-y: hidden;
    opacity: 1;
    transition: height 0.5s ease-in-out, opacity 0.5s ease-in-out;
    margin: 0;
    padding-left: 20px; /* 确保列表圆点正常显示 */
  }
</style>

<ul id="scrollableDiv" onmouseover="showScrollbar()" onmouseout="hideScrollbar()">
  <li>[07/2026] One paper has been accepted to ACM MM'26 ! Congratulations!</li>
  <li>[05/2026] One paper has been accepted to ACM KDD'26 ! Congratulations!</li>
  <li>[01/2026] One paper has been accepted to ACM WWW'26 ! Congratulations!</li>
  <li>[06/2025] One paper has been accepted to IEEE TMC'25 ! Congratulations!</li>
  <li>[01/2025] One paper has been accepted to ACM WWW'25 ! Congratulations!</li>
  <li>[12/2024] One paper has been accepted to IEEE INFOCOM'25 ! Congratulations!</li>
  <li>[10/2024] One paper has been accepted to IEEE TSC'24 ! Congratulations!</li>
  <li>[11/2023] One paper has been accepted to IEEE TSC'23 ! Congratulations!</li>
</ul>

<script>
  function showScrollbar() {
    var div = document.getElementById('scrollableDiv');
    // 鼠标悬停时展开显示全部新闻
    div.style.height = div.scrollHeight + 'px';
    div.style.opacity = 1;
  }
  
  function hideScrollbar() {
    var div = document.getElementById('scrollableDiv');
    // 鼠标移出时恢复为显示 4 条新闻的高度 (105px)
    div.style.height = '105px';
    div.style.opacity = 1;
  }
</script>
