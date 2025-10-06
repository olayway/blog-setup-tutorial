---
title: Blog
description: A collection of my blog posts
showToc: false
---

<List dir="/blog" slots={{ headline: "title", summary: "description", eyebrow: "date", media: "image" }} />

<div className="mt-8">
<CustomHtml html={`<iframe data-tally-src="https://tally.so/embed/3yVE90?alignLeft=1&transparentBackground=1&dynamicHeight=1" loading="lazy" width="100%" height="314" frameborder="0" marginheight="0" marginwidth="0" title="Newsletter sign-up"></iframe>
<script>var d=document,w="https://tally.so/widgets/embed.js",v=function(){"undefined"!=typeof Tally?Tally.loadEmbeds():d.querySelectorAll("iframe[data-tally-src]:not([src])").forEach((function(e){e.src=e.dataset.tallySrc}))};if("undefined"!=typeof Tally)v();else if(d.querySelector('script[src="'+w+'"]')==null){var s=d.createElement("script");s.src=w,s.onload=v,s.onerror=v,d.body.appendChild(s);}</script>`} />
</div>
