---
layout: page
title: Portfolio
---

<div class="container">
    <section id="portfolio">
        <div class="portfolio-intro">
            <h1>Portfolio</h1>
            <p>A collection of my technical projects and explorations. I enjoy building tools and analyzing data to solve interesting problems.</p>
        </div>

        <div class="portfolio-grid">
            {% for project in site.data.projects %}
            <div class="project-card">
                <div class="project-content">
                    <span class="project-category">{{ project.category }}</span>
                    <h2>{{ project.title }}</h2>
                    <p>{{ project.description }}</p>
                    <div class="project-tech">
                        {% for tech in project.tech_stack %}
                        <span class="tech-chip">{{ tech }}</span>
                        {% endfor %}
                    </div>
                    <div class="project-actions">
                        <a href="{{ project.github_link }}" target="_blank" class="btn btn-github">
                            <i class="fa fa-github"></i> Code
                        </a>
                        {% if project.writeup_link %}
                        <a href="{{ project.writeup_link }}" class="btn btn-details">
                            <i class="fa fa-file-text"></i> Details
                        </a>
                        {% endif %}
                    </div>
                </div>
            </div>
            {% endfor %}
        </div>
    </section>
</div>
