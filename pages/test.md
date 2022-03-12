---
layout: funnel-page
title: HTML Editor
imglogo: Logo_Speedypreneur_new-mhY.png
favicon: speedypreneur-favicon.jpg
apple-favicon: speedypreneur-apple-touch.jpg
hide: true
permalink: /test/
htmlbeforeheadend: funnel/before-head-end-page.html
htmlbeforebodyend: funnel/before-body-end-page.html
---
<h2>Speedypreneur HTML-Editor</h2>
<!-- Include Editor style. -->
<link href="https://cdn.jsdelivr.net/npm/froala-editor@latest/css/froala_editor.pkgd.min.css" rel="stylesheet" type="text/css" />

<!-- Create a tag that we will use as the editable area. -->
<!-- You can use a div tag as well. -->
<textarea></textarea>

<!-- Include Editor JS files. -->
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/froala-editor@latest/js/froala_editor.pkgd.min.js"></script>

<!-- Initialize the editor. -->
<script>
  new FroalaEditor('textarea');
</script>
