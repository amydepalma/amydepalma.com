---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 2

thumb-src: codefest/thumb.png
description: "Screenshot of a user interface developed during the Steel City Codefest"
callout: "Proud participant, and part of the first-place team in 2015, of the Steel City Codefest"

title: "Steel City Codefest"
# subtitle: 
theme-color: "#4a851d"

company: Personal
sort-year: 2016
year: 2014-2016
item-short-url: github.com/PaperOut/paperout
item-short-desc: <small><em>Not currently maintained</em></small>
tech: HTML5, CSS3 (SASS), PHP, Git

permalink: portfolio/codefest/

one-col-imgs:
- {url: 'codefest/1.jpg', alt: 'Registration Page'}
- {url: 'codefest/3.jpg', alt: 'Admin Dashboard'}
- {url: 'codefest/2.jpg', alt: 'Manage Events'}

three-col-imgs:
- {url: 'codefest/4.jpg', alt: 'Mobile Admin Dashboard'}
- {url: 'codefest/5.jpg', alt: 'Mobile Events Management'}
- {url: 'codefest/6.jpg', alt: 'Mobile User Management'}
---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
           <p>The Steel City Codefest is a city-wide app building event that brings together coders, designers, and innovation enthusiasts to create apps for local government, citizens, and community organizations over a 24-hour period. I've participated in this event from 2014-2016.</p>

            <h3>2015 First Place Winner</h3>
            <p>Our team created responsive web app for Rebuilding Together Pittsburgh (a local nonprofit that repairs homes for disadvantaged individuals) that allows them to collect their volunteers information via a mobile app rather than their current paper form process. We are currently working with the organization to complete this app.</p>
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