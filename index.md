---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Test page

Hello world!

<div id="box" style="width:200px; height:200px"></div>

<script>

    document.addEventListener("keydown", (event) => {
        if (event.key == " ") {
            document.getElementById("box").style.backgroundColor = "red";
        }
    })

</script>