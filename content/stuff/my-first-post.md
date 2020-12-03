---
title: "Root - First Post"
url: foo
draft: false
aliases:
  - "/first/"

---


Markdown

![](/park.jpg)


Figure 


{{< figure src="/park.jpg" title="Hamel's Park" >}}

gist


{{< gist spf13 7896402 >}}

higlight

{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}

Okay what is {{< param "title" >}}


## Ref

[some link]({{< ref "another_post.md" >}})

[relref link]({{< ref "another_post#second" >}})

Does relative stuff work in the folder?

![](fastlinkcheck.png)

