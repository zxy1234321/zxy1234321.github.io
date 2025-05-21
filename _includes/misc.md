<h1 id="misc"></h1>

<h2 style="margin: 30px 0px 10px;">Misc</h2>

<ul style="line-height: 1.5; margin: 0;">
<li>
    <div class="collapsible">
        <div class="header" onclick="toggleContent(this)">
            <span>▶</span> Reading Note
        </div>
        <div class="content" style="display: none;">
            <!-- 原有内容 -->
        </div>
    </div>
</li>

<li>
    <div class="collapsible">
        <div class="header" onclick="toggleContent(this)">
            <span>▶</span> Reading List
        </div>
        <div class="content" style="display: none;">
            <p>2024 Reading List:</p>
            <p>1. 《书名1》</p>
            <p>2. 《书名2》</p>
        </div>
    </div>
</li>
</ul>

<style>
.collapsible .header {
    cursor: pointer;
    padding: 5px;
}
.collapsible .header:hover {
    background-color: #f5f5f5;
}
</style>

<script>
function toggleContent(element) {
    const content = element.nextElementSibling;
    const arrow = element.querySelector('span');
    if (content.style.display === "none") {
        content.style.display = "block";
        arrow.textContent = '▼';
    } else {
        content.style.display = "none";
        arrow.textContent = '▶';
    }
}
</script>



<br />