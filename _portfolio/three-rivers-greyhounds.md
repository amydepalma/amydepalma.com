---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 4

thumb-src: three-rivers-greyhounds/thumb.jpg
description: "Screenshot of gpathreeriversgreyhounds.org"
callout: "Three Rivers Greyhounds is a local non-profit serving the greater Pittsburgh area with the goal to promote adoption of retired racing Greyhounds in Pittsburgh and other regions of western Pennsylvania. "

title: "Three Rivers Greyhounds"
# subtitle:
theme-color: "#5c8a03"

company: 2206 Design
sort-year: 2015
year: 2015
item-short-url: gpathreeriversgreyhounds.org
# item-short-desc:
tech: Content Audit, Information Architecture, UX, Visual Design (Photoshop), HTML5, CSS3 (SASS), JavaScript/jQuery, PHP, Wordpress, Git

permalink: portfolio/three-rivers-greyhounds/

one-col-imgs:
- {url: 'three-rivers-greyhounds/home.png', alt: 'Homepage'}
- {url: 'three-rivers-greyhounds/adoption-form.png', alt: 'Adoption form using local storage to save sessions'}
- {url: 'three-rivers-greyhounds/adopt.png', alt: 'Adoption information'}

three-col-imgs:
- {url: 'three-rivers-greyhounds/home_mobile.png', alt: 'Homepage'}
- {url: 'three-rivers-greyhounds/adoption-form_mobile.png', alt: 'Adoption form using local storage to save sessions'}
- {url: 'three-rivers-greyhounds/adopt_mobile.png', alt: 'Adoption information'}

---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
            <p>Three Rivers Greyhounds is a local non-profit serving the greater Pittsburgh area with the goal to promote adoption of retired racing Greyhounds in Pittsburgh and other regions of western Pennsylvania. </p>
            <p>2206 Design worked with the organization to design and develop a Wordpress-powered website which gave the organization the possibility to make the updates to the site themselves, something their previous website was lacking. A much-needed feature to the new site was the development of an online application form for adoptable greyhounds.</p>
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