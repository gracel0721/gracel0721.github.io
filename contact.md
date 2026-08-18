---
title: Contact
layout: page
---


<div class="contact-container">
    <div class="email-section">
        <h2>Get in Touch</h2>
        <a href="{{ site.data.socials.email.href }}{{ site.data.socials.email.id }}" class="email-link">
            <i class="{{ site.data.socials.email.fa-icon }}"></i>
            <span>{{ site.data.socials.email.id }}</span>
        </a>
    </div>

    <div class="social-grid">
        <a href="{{ site.data.socials.linkedin.href }}{{ site.data.socials.linkedin.id }}" class="social-item" title="LinkedIn">
            <i class="{{ site.data.socials.linkedin.fa-icon }} fa-3x"></i>
            <span>LinkedIn</span>
        </a>
        <a href="{{ site.data.socials.github.href }}{{ site.data.socials.github.id }}" class="social-item" title="GitHub">
            <i class="{{ site.data.socials.github.fa-icon }} fa-3x"></i>
            <span>GitHub</span>
        </a>
        <a href="{{ site.data.socials.twitter.href }}{{ site.data.socials.twitter.id }}" class="social-item" title="X">
            <i class="{{ site.data.socials.twitter.fa-icon }} fa-3x"></i>
            <span>X</span>
        </a>
    </div>
</div>

<style>
.contact-header {
    text-align: center;
    margin-bottom: 30px;
}

.contact-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 40px;
    margin-top: 30px;
}

.email-section {
    text-align: center;
    margin-bottom: 20px;
}

.email-link {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 15px;
    font-size: 24px;
    text-decoration: none;
    color: inherit;
    padding: 15px 25px;
    border: 1px solid #30363d;
    border-radius: 12px;
    transition: background 0.3s, transform 0.2s;
}

.email-link:hover {
    background: rgba(255, 255, 255, 0.05);
    transform: translateY(-2px);
}

.email-link i {
    font-size: 30px;
}

.social-grid {
    display: flex;
    gap: 30px;
    flex-wrap: wrap;
    justify-content: center;
}

.social-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    text-decoration: none;
    color: inherit;
    transition: transform 0.2s, opacity 0.2s;
}

.social-item:hover {
    transform: scale(1.1);
    opacity: 0.8;
}

.social-item span {
    font-size: 16px;
    font-weight: 500;
}
</style>
