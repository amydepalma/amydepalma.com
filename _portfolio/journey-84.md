---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 1

thumb-src: journey-84-lumber/thumb.jpg
description: "Screenshot of journey84.com, 84 Lumber's 2017 Super Bowl Microsite"
callout: "Brunner created one of the most memorable spots of the 2017 Super Bowl&mdash;and I was lucky enough to be part of the digital campaign team."

title: "Journey84.com"
subtitle: "84 Lumber 2017 Super Bowl"
theme-color: "#142840"

company: Brunner
sort-year: 2017
year: 2017
# item-short-url:
item-short-desc: <em>journey84.com was taken offline in late 2017</em>
tech: HTML5, CSS3 (LESS), JavaScript/jQuery, C#, ASP.NET MVC, Team Foundation Server, Caffeine, Late nights

permalink: portfolio/journey-84-lumber/

one-col-imgs:
- {url: 'journey-84-lumber/84-Lumber-Journey84-Home.jpg', alt: 'Homepage'}
- {url: 'journey-84-lumber/84-Lumber-Journey84-Who-We-Are.jpg', alt: 'Who We Are'}
- {url: 'journey-84-lumber/84-Lumber-Journey84-Careers.jpg', alt: 'Careers'}

three-col-imgs:
- {url: 'journey-84-lumber/84-Lumber-Journey84-Home-mobile.jpg', alt: 'Homepage'}
- {url: 'journey-84-lumber/84-Lumber-Journey84-Who-We-Are-mobile.jpg', alt: 'Who We Are'}
- {url: 'journey-84-lumber/84-Lumber-Journey84-Careers-mobile.jpg', alt: 'Careers'}
---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
           <p>84 Lumber, a western Pennsylvania-based building materials supplier, challenged Brunner to create a 2017 Super Bowl advertisement to introduce the company to the world. Not only was the Brunner-created spot named <a href="https://www.adweek.com/brand-marketing/the-5-best-ads-of-super-bowl-li/" target="_blank" rel="noreferrer">AdWeek’s Best 2017 Super Bowl advertisement</a>&mdash;our accompanying microsite servers crashed due to the phenomenal influx of traffic.</p>

            <p>I had the opportunity to be a part of the amazing team that worked on journey84.com as well as accompanying Super Bowl-related content on 84lumber.com. My responsibility was to develop the microsite’s UI based on designed provided via our creative department, ensuring consistency across all aspects of the campaign.</p>
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