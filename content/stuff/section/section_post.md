---
title: 'In Section #1'
alias:
    - /posts/section/
---

The first section post

Can you put pictures in a section post?

![](fastlinkcheck.png)


Print resources:

{{ with .Resources.ByType "image" }}
{{ range . }}
{{ .RelPermalink }}
{{ end }}
{{ end }}
