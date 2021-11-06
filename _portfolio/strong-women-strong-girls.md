---
layout: portfolio-page

grid-publish: true
home-publish: true
home-order: 1

thumb-src: strong-women-strong-girls/thumb.jpg
description: "Screenshot of swsg.org"
callout: "Brunner worked with Strong Women, Strong Girls, a local non-profit with a focus on multi-generational mentoring for women and girls, in 2019 to provide the organization with a new website."

title: "Strong Women, Strong Girls"
# subtitle:
theme-color: "#a3196e"

company: Brunner
sort-year: 2019
year: 2019
item-short-url: swsg.org
# item-short-desc:
tech: HTML5, CSS3 (LESS), JavaScript/jQuery, PHP, Wordpress, Git

permalink: portfolio/strong-women-strong-girls/

one-col-imgs:
- {url: 'strong-women-strong-girls/home.jpg', alt: 'Homepage'}
- {url: 'strong-women-strong-girls/pittsburgh-programs.jpg', alt: 'City-specific program sites'}
- {url: 'strong-women-strong-girls/news-with-filter.jpg', alt: 'News (filter panel opened)'}

three-col-imgs:
- {url: 'strong-women-strong-girls/news-no-filter_mobile.jpg', alt: 'News (filter panel no opened)'}
- {url: 'strong-women-strong-girls/pittsburgh-programs_mobile.jpg', alt: 'City-specific program sites'}
- {url: 'strong-women-strong-girls/home_mobile.jpg', alt: 'Homepage'}

---

<div class="row lv-mar-bottom-30">
    <div class="col-12">
        <div class="lv-pad-all-20 lv-bkg-white lv-bs">
            <p>Brunner worked with Strong Women, Strong Girls, a local non-profit with a focus on multi-generational mentoring for women and girls, in 2019 to provide the organization with a new website. When developing the custom Wordpress theme, we focused on building an adaptable and flexible system whereby editors could easily add new locations as the organization grows into new cities. </p>

            <p>We took advantage of the popular and versatile plugin Advanced Custom Fields Pro to create a highly flexible page builder and global settings. In addition, we took into account any reusable content across the site and created custom post types for this type of content to enhance the editor experience.</p>

            <p>My role in this project was to develop the user interface as well as implement the Advanced Custom Fields Pro functionality.</p>
        </div>
    </div>
</div>

<div class="row">
    {% for img in page.one-col-imgs %}
        <div class="col-12">
            <figure class="lv-mar-bottom-25 lv-text-center">
                <img src="/portfolio/assets/{{ img.url }}" alt="{{ img.alt }}" class="lv-bs" />
                <figcaption class="p lv-mar-top-5">{{ img.alt }}</figcaption>
            </figure>
        </div>
    {% endfor %}
</div>

<div class="row">
    {% for img in page.three-col-imgs %}
        <div class="col-12 col-md-4">
            <figure class="lv-mar-bottom-25 lv-text-center">
                <img src="/portfolio/assets/{{ img.url }}" alt="{{ img.alt }}" class="lv-bs" />
                <figcaption class="p lv-mar-top-5">{{ img.alt }}</figcaption>
            </figure>
        </div>
    {% endfor %}
</div>