---
layout: portfolio-page

grid-publish: true
home-publish: false

thumb-src: kiva-han-coffee/thumb.jpg
description: "Coffe bag and label for Kiva Han Coffee product"
callout: "Coffee bag label designs"

title: "Kiva Han Coffee"
# subtitle: 
theme-color: "#e69738"

company: 2206 Design
sort-year: 2013
year: 2013
tech: Branding, Illustrator, InDesign

permalink: portfolio/kiva-han-coffee/

one-col-imgs:
 - {url: 'kiva-han-coffee/1.jpg', alt: "Final Label Design for the Green Unroasted Bean Line"}
 - {url: 'kiva-han-coffee/2.jpg', alt: 'Final Label Design for the Green Unroasted Bean Line'}
 - {url: 'kiva-han-coffee/3.jpg', alt: 'Mock Label Design for the Saudi Arabian Bags'}
 - {url: 'kiva-han-coffee/4.jpg', alt: 'Mock Label Design for the Saudi Arabian Bags'}
 - {url: 'kiva-han-coffee/5.jpg', alt: "Mock Label Design for the Saudi Arabian Bags"}
---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
           <p>In 2013, I worked with local roaster and wholesaler, Kiva Han Coffee, to design a new label for their coffee's release in Saudi Arabia as well as for their new green unroasted bean product.</p>
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