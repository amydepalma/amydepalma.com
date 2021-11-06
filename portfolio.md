---
layout: default
title: Portfolio
permalink: /portfolio/
---

<section class="left">
    <h1 class="h1-large">Portfolio</h1>
    <a href="/" class="btn btn-icon btn-icon-left lv-mar-top-20">
        <span>Back to Home</span><i class="fas fa-angle-left"></i>
    </a>
    <a href="/" class="site-name">amydepalma.com</a>
</section>

<section class="right lv-bkg-pattern">
    <div class="portfolio-grid is-three-up">
        {% assign sorted_pages = site.portfolio | sort: "sort-year" | reverse %}
        {% for item in sorted_pages %}
        {% if item.grid-publish == true %}
            <a href="{{ item.url }}" class="portfolio-item card lv-bs">
                <div class="card-image">
                    <img src="assets/{{ item.thumb-src }}" alt="{{ item.description }}" />
                </div>
        
                <div class="card-copy">
                    <div class="card-copy-inner" style="border-color: {{ item.theme-color }}">
                        <h2 style="color: {{ item.theme-color }}">{{ item.title }}</h2>
                        <p>{{ item.callout }}</p>
                    </div>
                </div>
            </a>
        {% endif %}
        {% endfor %}
    </div>     
</section>