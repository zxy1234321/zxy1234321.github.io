<h1 id="misc"></h1>

<h2 style="margin: 30px 0px 10px;">Misc</h2>

<p>
<strong>Reading Note</strong>
<a onclick="toggleContent('readingNote')" style="cursor: pointer; text-decoration: none;">▼</a>
<div id="readingNote" style="display: none;">
    <!-- 原有的Reading Note内容 -->
</div>
<br />

<strong>Reading List</strong>
<a onclick="toggleContent('readingList')" style="cursor: pointer; text-decoration: none;">▼</a>
<div id="readingList" style="display: none;">
    <p>2024 Reading List:</p>
    <p>1. 《书名1》</p>
    <p>2. 《书名2》</p>
</div>
</p>

<script>
function toggleContent(id) {
    var content = document.getElementById(id);
    var arrow = event.target;
    if (content.style.display === "none") {
        content.style.display = "block";
        arrow.textContent = "▼";
    } else {
        content.style.display = "none";
        arrow.textContent = "▶";
    }
}
</script>




<br />