+++
date = "2018-04-15"
title = "Hugo Syntax Highlighting"
writer = "Dian Sadulloh"
draft = false
noread = true
categories = ["Development"]
weight = 1
description = "Syntax Highlighting example test article that shows how to creating and highlighting code blocks in Hugo-generated site"
keywords = "html,theme,syntax"
author = "Dian Sadulloh"
authorlink = "https://diansadulloh.com"
authorfacebook = "https://fb.me/mr.waktu"
authortwitter = "https://twitter.com/diansadulloh"
authorlinkedin = "https://id.linkedin.com/in/emozonic"
ogtitle = "Hugo Syntax Highlighting"
socialsharing = true
totop = true
+++

You can have code snippets highlighted so that they are easier to read on your site using Chroma, Hugo's default syntax highlighter. It is built in Go lang and is really, really fast – and for the most important parts compatible with Pygments. Chroma takes source code and other structured text and converts it into syntax highlighted HTML, ANSI-coloured text, etc.
<!--more-->

The example below shows a simple HTML code snippet highlighted with the Hugo [highlight](https://gohugo.io/content-management/shortcodes/#highlight) built-in shortcode:

{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

The following code snippet was used to achieve that result:

```
{{</* highlight html */>}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{</* /highlight */>}}
```

For more information, see "[Hugo Syntax Highlighting](https://gohugo.io/content-management/syntax-highlighting)" from official Hugo docs.
