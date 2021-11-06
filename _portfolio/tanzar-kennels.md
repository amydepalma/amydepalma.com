---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 0

thumb-src: tanzar-kennels/thumb.jpg
description: "Screenshot of tanzarkennels.com"
callout: "Website design and development for a local pet groomer and boarding facility"

title: "Tanzar Kennels"
# subtitle:
theme-color: "#0ca3da"

company: 2206 Design
sort-year: 2018
year: 2018
item-short-url: tanzarkennels.com
# item-short-desc:
tech: Content Audit, Information Architecture, UX, Visual Design (Photoshop), HTML5, CSS3 (LESS), JavaScript/jQuery, Jekyll, Git

permalink: portfolio/tanzar-kennels/

one-col-imgs:
- {url: 'tanzar-kennels/tanzar-kennels-Home.png', alt: 'Homepage'}
- {url: 'tanzar-kennels/tanzar-kennels-Boarding.png', alt: 'Boarding'}
- {url: 'tanzar-kennels/tanzar-kennels-Contact.png', alt: 'Contact'}

three-col-imgs:
- {url: 'tanzar-kennels/tanzar-kennels-Home-mobile.jpg', alt: 'Homepage'}
- {url: 'tanzar-kennels/tanzar-kennels-Boarding-mobile.jpg', alt: 'Boarding'}
- {url: 'tanzar-kennels/tanzar-kennels-Contact-mobile.jpg', alt: 'Contact'}
---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
           <p>In 2018 Tanzar Kennels, a local pet groomer and boarding facility, came under new management and they were looking to update their online presence with a new website design and additional content.</p>

            <p>2206 Design worked with Tanzar Kennels to design and develop a new website as well as provide continuing maintenance. Due to the primarily static content that the site would provide, we developed it using Jekyll, a static site generator, for a fast and secure experience.</p>
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