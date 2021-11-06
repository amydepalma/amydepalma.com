---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 3

thumb-src: kl-gates/thumb.jpg
description: "In-House Designer for K&L Gates"
callout: During my time at K&amp;L Gates, I was part of the firm-wide Marketing Graphics team where I worked across 45 fully integrated offices spanning five continents.

title: "K&amp;L Gates"
# subtitle: 
theme-color: "#653366"

company: In-house
sort-year: 2016
year: 2014-2016
item-short-url: klgateshub.com
# item-short-desc:
tech: Branding, Graphic Design, Web Design, Photoshop, Illustrator, InDesign, UX, HTML5, CSS3 (SASS)

permalink: portfolio/kl-gates/

one-col-imgs:
- {url: 'kl-gates/3.jpg', alt: 'Home Page of klgateshub.com'}
- {url: 'kl-gates/5.jpg', alt: "CLE Page of klgateshub.com"}
- {url: 'kl-gates/1.jpg', alt: "Pro Bono Report 2015 Redesign"}
- {url: 'kl-gates/2.jpg', alt: 'Pro Bono Report 2015 Redesign'}
- {url: 'kl-gates/WhyKLG_infosheet.png', alt: 'Why K&amp;L Gates? An industry-targeted infosheet'}
- {url: 'kl-gates/4.jpg', alt: 'Global Boardroom Risk Solutions Brochure'}
- {url: 'kl-gates/6.jpg', alt: "Partners' Retreat 2016 Branding - Wall Decals"}
- {url: 'kl-gates/7.jpg', alt: "AIRMIC Conference Booth Branding + Brochure Design (pictured: not me)"}
---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
           <p>During my time at K&amp;L Gates, I was part of the firm-wide Marketing Graphics team where I worked across 45 fully integrated offices spanning five continents. I create branded promotional materials including advertisements, brochures, publications, and trade show materials.</p>
        
            <p>In 2014, I designed the firm's Continuing Legal Education website, <a href="http://www.klgateshub.com" target="_blank">K&amp;L Gates Hub</a>. In addition to the design, I was responsible for the initial CSS-framework and template structure, which I then worked closely with our web development vendor during implementation to ensure the site met our original design specs and brand. Hub won first place for the category of "Total Website Refresh / Overhaul / Rebrand and Individual Website" in the 2015 New England Legal Marketing Association YourHonor Awards.</p>
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