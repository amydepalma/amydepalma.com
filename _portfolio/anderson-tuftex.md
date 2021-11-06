---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 2

thumb-src: anderson-tuftex/thumb.jpg
description: "Screenshot from AndersonTuftex.com"
callout: "Shaw Industries, one of the world’s largest manufacturers of flooring, was preparing to launch a new brand: Anderson Tuftex."

title: "Anderson Tuftex"
# subtitle:
theme-color: "#cf7e4f"

company: Brunner
sort-year: 2018
year: 2018
item-short-url: andersontuftex.com
# item-short-desc:
tech: HTML5, CSS3 (LESS), JavaScript/jQuery, MkDocs, C#, ASP, Team Foundation Server

permalink: portfolio/anderson-tuftex/

one-col-imgs:
- {url: 'anderson-tuftex/homepage.jpg', alt: 'Homepage'}
- {url: 'anderson-tuftex/hardwood.jpg', alt: 'Hardwood Products'}
- {url: 'anderson-tuftex/find-a-location.jpg', alt: 'Find a Location'}
- {url: 'anderson-tuftex/styles-doc.png', alt: 'Styles Documentation'}
- {url: 'anderson-tuftex/user-controls-docs.png', alt: 'User Controls Documentation for Integration into Kentico'}

three-col-imgs:
- {url: 'anderson-tuftex/homepage_mobile.jpg', alt: 'Homepage'}
- {url: 'anderson-tuftex/hardwood_mobile.jpg', alt: 'Hardwood Products'}
- {url: 'anderson-tuftex/find-a-location_mobile.jpg', alt: 'Find a Location'}
---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
            <p>Shaw Industries, one of the world’s largest manufacturers of flooring, was preparing to launch a new brand: Anderson Tuftex. Brunner won a bid to design a web experience centered around the Anderson Tuftex’s story. The primary challenge of this build was to present both hard and soft floor surfaces, which each have their own unique specifications, in one site. We developed the front-end of the website and partnered with the client’s developers to integrate our assets with their existing CMS, Kentico.</p>

            <p>My role was to identify patterns across the site’s design and develop a modular CSS-framework and component library to be integrated into the CMS. In addition, I developed a documentation site for hand-off of the components using the static site generator, <a href="https://www.mkdocs.org/" target="_blank">MkDocs</a>.</p>
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