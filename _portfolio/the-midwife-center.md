---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 7

thumb-src: the-midwife-center/thumb.png
description: "The Midwife Center Capital Campaign logo"
callout: "I've partnered with TMC on various large and small graphic design projects throughout the years."

title: "The Midwife Center"
# subtitle:
theme-color: "#f79226"

company: 2206 Design
sort-year: 2016
year: 2012+
tech: Branding, Information Architecture, Photoshop, Illustrator, InDesign

permalink: portfolio/the-midwife-center/

one-col-imgs:
 - {url: 'the-midwife-center/1.jpg', alt: "Cover of The Midwife Center's Case for Support"}
 - {url: 'the-midwife-center/2.jpg', alt: 'Spread from the Case for Support'}
 - {url: 'the-midwife-center/3.jpg', alt: 'Naming Opportunities Insert'}
 - {url: 'the-midwife-center/4.jpg', alt: 'Pledge Form Insert'}
 - {url: 'the-midwife-center/5.jpg', alt: "Cover of The Midwife Center's 30th Anniversary Report"}
 - {url: 'the-midwife-center/6.jpg', alt: "Spread From The Midwife Center's 30th Anniversary Report"}
 - {url: 'the-midwife-center/7.jpg', alt: "Spread From The Midwife Center's 30th Anniversary Report"}
---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
            <p>The Midwife Center is western PA's largest and only freestanding birth center offering primary gynecological, prenatal, and childbirth care. I've been fortunate enough to work with this wonderful organization since 2012. Through the years, I've partnered with TMC on various graphic design projects, from larger publications such as their Capital Campaign and 30th Anniversary Report to small projects such as postcards and invitations. I’ve also been a proud materials-sponsor of their annual fundraiser and (delicious) cake decorating contest, Let Them Eat Cake.</p>
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