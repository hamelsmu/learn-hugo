---
title: Notebook Test
---
## Below is shortcodes in the `index.md` markdown:

HTML:
{{< rawhtml >}}
    <h5>This is h5</h5>
    <p>Hello <strong>World!</strong></p>
{{< /rawhtml >}}


{{% notice info %}}
An information disclaimer
{{% /notice %}}

Another example of a short code:
{{< gist spf13 7896402 >}}

[full_test](full_test.html)

Issues researched re: processing shortcodes from data:
 
 - In [6094](https://github.com/gohugoio/hugo/issues/6094): A `shortcodify` template function was requested.  bep mentiones that this is not easy because the shortcode API requires a `Page`.   There is something called the [sawmill layout technique](https://forestry.io/blog/sawmill-layout-composer-for-hugo-and-forestry/) which might help, but didn't quite grasp that completely, maybe come back to this.
 - [6904](https://github.com/gohugoio/hugo/issues/609) was closed in favor of [6703](https://github.com/gohugoio/hugo/issues/6703)

http://localhost:1313/notebook/full_test
http://localhost:1313/notebook/full_test/

# End of Markdown / Beginning of Notebook