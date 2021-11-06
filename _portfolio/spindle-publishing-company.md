---
layout: portfolio-page

grid-publish: true
home-publish: false
home-order: 4

thumb-src: spindle-publishing-company/thumb.jpg
description: "Baby Shop Magazine from Spindle Publishing Company"
callout: "I've partnered with TMC on various large and small graphic design projects throughout the years."

title: "Spindle Publishing Company"
# subtitle:
theme-color: "#b51725"

company: In-house
sort-year: 2012
year: 2010-2012
item-short-desc: "<em>Spindle Publishing Company has been out of operation since 2012</em>"
tech: Branding, Information Architecture, Photoshop, Illustrator, InDesign, HTML5, CSS3

permalink: portfolio/spindle-publishing-company/

one-col-imgs:
 - {url: 'spindle-publishing-company/4.jpg', alt: "Baby Shop Cover Design"}
 - {url: 'spindle-publishing-company/5.jpg', alt: "Baby Shop Spread Design"}
 - {url: 'spindle-publishing-company/6.jpg', alt: "Baby Shop Spread Design"}
 - {url: 'spindle-publishing-company/1.jpg', alt: "Expectant Mother's Guide Cover Design (Photo retouching and typography)"}
 - {url: 'spindle-publishing-company/2.jpg', alt: "Expectant Mother's Guide Layout and Branded Advertisement"}
 - {url: 'spindle-publishing-company/3.jpg', alt: "Expectant Mother's Guide - Layout and Advertisement Design"}
---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
           <p>Spindle Publishing was a Pittsburgh-based company that created publications that focused on offering resources to people within various stages of their lives with series such as <em>High School Graduate</em>, <em>Expectant Mother's Guide</em>, and <em>Senior Citizen's Guide</em>. Spindle produced over 65 editions a year across their five series and distributed in major U.S. cities. In addition, we produced a twice-a-year business magazine, <em>Baby Shop</em>, focusing on the latest trends and products in the juvenile products industry.</p>
        
            <p>As a graphic and web designer, I managed editorial schedules, created advertisements, worked with our sales team to design branded sales materials, and updated content across our web sites.</p>
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