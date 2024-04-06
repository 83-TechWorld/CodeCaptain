---
layout: home
---

<div class="profile">
    <img src="{{ '/assets/images/logo.jpg' | relative_url }}" alt="Profile Picture">
    <h2>About Me</h2>
    <p>Add a brief introduction about yourself here.</p>
</div>

<div class="projects">
    <h2>Projects</h2>
    <ul>
        {% for project in site.projects %}
            <li>{{ project.title }}</li>
        {% endfor %}
    </ul>
</div>

<div class="innovations">
    <h2>Innovations</h2>
    <ul>
        {% for innovation in site.innovations %}
            <li>{{ innovation.title }}</li>
        {% endfor %}
    </ul>
</div>

<div class="experience">
    <h2>Company Experience</h2>
    <ul>
        {% for experience in site.experience %}
            <li>{{ experience.title }}</li>
        {% endfor %}
    </ul>
</div>

<div class="personal-works">
    <h2>Personal Works</h2>
    <ul>
        {% for work in site.works %}
            <li>{{ work.title }}</li>
        {% endfor %}
    </ul>
</div>
