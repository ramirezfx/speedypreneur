---
layout: funnel-page
title: MD-Editor
imglogo: Logo_Speedypreneur_new-mhY.png
favicon: speedypreneur-favicon.jpg
apple-favicon: speedypreneur-apple-touch.jpg
hide: true
permalink: /mdeditor/
htmlbeforeheadend: funnel/before-head-end-page.html
htmlbeforebodyend: funnel/before-body-end-page.html
---
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="/editor.md/editormd.min.js"></script>
<script src="/editor.md/languages/en.js"></script>
<link rel="stylesheet" href="/editor.md/css/editormd.min.css" />
<div id="editor">
    <!-- Tips: Editor.md can auto append a `<textarea>` tag -->
    <textarea style="display:none;">### Hello Editor.md !</textarea>
</div>

<script type="text/javascript">
    $(function() {
        var editor = editormd("editor", {
            // width: "100%",
            height: "500px",
            emoji: "true",
            // markdown: "xxxx",     // dynamic set Markdown text
            path : "/editor.md/lib/"  // Autoload modules mode, codemirror, marked... dependents libs path
        });
    });
</script>
