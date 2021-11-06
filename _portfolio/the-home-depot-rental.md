---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 0

thumb-src: the-home-depot-rental/thumb.jpg
description: "Screenshot of compactpowerrents.com"
callout: "In 2018, Brunner worked to update Compact Power Rental’s site design to reflect their new parent brand, The Home Depot Rental."

title: "The Home Depot Rental"
# subtitle:
theme-color: "#f96302"

company: Brunner
sort-year: 2019
year: 2019
item-short-url: compactpowerrents.com
# item-short-desc:
tech: HTML5, CSS3 (LESS), JavaScript/jQuery, C#, ASP.NET MVC, Umbraco, Team Foundation Server

permalink: portfolio/the-home-depot-rental/

one-col-imgs:
- {url: 'the-home-depot-rental/home.png', alt: 'Homepage'}
- {url: 'the-home-depot-rental/locations.png', alt: 'Find a Location page, using CSS Grid'}
- {url: 'the-home-depot-rental/store-detail.png', alt: 'Store Detail'}

three-col-imgs:
- {url: 'the-home-depot-rental/home_mobile.png', alt: 'Homepage'}
- {url: 'the-home-depot-rental/locations_mobile.png', alt: 'Find a Location page, using CSS Grid'}
- {url: 'the-home-depot-rental/store-detail_mobile.png', alt: 'Store Detail'}

---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
            <p>In 2018, The Home Depot acquired Compact Power Rental, a large equipment rental company with whom Brunner was currently providing an active web presence. As a result of this acquisition, our team worked to update Compact Power Rental’s site design to reflect their new brand, The Home Depot Rental. For the first phase of this update, our team created new designs for select high-traffic pages, a style overhaul to reflect the new brand, UX improvements, codebase optimization, and CMS upgrades.</p>
            <p>After auditing the existing UI patterns across the site, I refactored and optimized the HTML and CSS in order to create a modular component library. Additionally, I implemented the new brand styling, created  reusable page-builder components for the Umbraco CMS, and integrated Google Analytics tagging across the site in coordination with our SEO specialist.</p>
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