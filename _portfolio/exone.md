---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 0

thumb-src: exone/thumb.jpg
description: "Screenshot of exone.com"
callout: "ExOne was seeking to expand their brand recognition and company capabilities within the industry and Brunner was thrilled to take on the challenge."

title: "ExOne"
# subtitle:
theme-color: "#406518"

company: Brunner
sort-year: 2019
year: 2019
item-short-url: exone.com
# item-short-desc:
tech: HTML5, CSS3 (LESS), JavaScript/jQuery, C#, ASP.NET MVC, Kentico, Git

permalink: portfolio/exone/

one-col-imgs:
- {url: 'exone/home.jpg', alt: 'Homepage'}
- {url: 'exone/system-detail.jpg', alt: 'System Detail'}
- {url: 'exone/desktop-navigation.jpg', alt: 'Desktop Navigation'}
- {url: 'exone/tablet-navigation.jpg', alt: 'Tablet Navigation'}

three-col-imgs:
- {url: 'exone/mobile-navigation.jpg', alt: 'Mobile Navigation'}
- {url: 'exone/home_mobile.jpg', alt: 'Homepage'}
- {url: 'exone/system-detail_mobile.jpg', alt: 'System Detail'}

---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
           <p>ExOne, one of the first manufacturers of metal and sand 3D printing machines, was seeking to expand their brand recognition and company capabilities within the industry and Brunner was thrilled to take on the challenge. Part of this brand refresh was a new website, which included an overhauled look and feel, an improved user experience, and Kentico CMS integration.</p>

            <p>As the lead UI developer for this project, I developed the user interface by creating a modular CSS-framework and component system for use across templates and within the Kentico page-builder system.</p>
        </div>
    </div>
</div>

<div class="row">
    {% for img in page.one-col-imgs %}
        <div class="col-12">
            <figure class="lv-mar-bottom-25 lv-text-center">
                <img src="/portfolio/assets/{{ img.url }}" alt="{{ img.alt }}" />
                <figcaption class="p lv-mar-top-5">{{ img.alt }}</figcaption>
            </figure>
        </div>
    {% endfor %}
</div>

<div class="row">
    {% for img in page.three-col-imgs %}
        <div class="col-12 col-md-4">
            <figure class="lv-mar-bottom-25 lv-text-center">
                <img src="/portfolio/assets/{{ img.url }}" alt="{{ img.alt }}" />
                <figcaption class="p lv-mar-top-5">{{ img.alt }}</figcaption>
            </figure>
        </div>
    {% endfor %}
</div>