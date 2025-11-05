# Hidden History of Suzhou 🕯️  
> “History lives quietly in the stones, bridges, and alleys.”

<div id="toc"></div>

---

欢迎来到我的数字笔记馆。  
这里收藏着苏州那些被时光轻抚的角落——  
古街、老桥、园林与故事。

---

## 📜 目录
- [平江路：石桥下的水声](old-streets/pingjiang-road.md)
- [沧浪亭：风过古水](ancient-buildings/canglang-pavilion.md)

---

<script>
document.addEventListener("DOMContentLoaded", function() {
  const toc = document.getElementById("toc");
  const headers = document.querySelectorAll("h2, h3");
  if (headers.length > 0) {
    const ul = document.createElement("ul");
    headers.forEach(h => {
      const li = document.createElement("li");
      li.style.marginLeft = h.tagName === "H3" ? "1em" : "0";
      const a = document.createElement("a");
      a.textContent = h.textContent;
      a.href = "#" + h.id;
      li.appendChild(a);
      ul.appendChild(li);
    });
    const title = document.createElement("h3");
    title.textContent = "📖 页面导航";
    toc.appendChild(title);
    toc.appendChild(ul);
  }
});
</script>
