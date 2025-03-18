---
layout: default
---

<section id="about" class="section">
    <h2>About the Event</h2>
    <p>Join leading AI and Edge computing developers for two days of technical talks, hands-on workshops, and networking. Explore the latest trends in:</p>
    <ul class="topics">
        <li>Edge AI Deployment</li>
        <li>TinyML Implementations</li>
        <li>AI Model Optimization</li>
        <li>IoT Edge Solutions</li>
    </ul>
</section>

<section id="schedule" class="section dark">
    <h2>Schedule</h2>
    <div class="schedule-grid">
        <div class="time-slot">
            <h3>Day 1: AI Optimization</h3>
            <p>9:00 AM - Keynote: Future of Edge AI</p>
            <p>11:00 AM - Model Quantization Workshop</p>
            <p>2:00 PM - Edge Hardware Panel</p>
        </div>
        <div class="time-slot">
            <h3>Day 2: Deployment Strategies</h3>
            <p>9:00 AM - Edge Deployment Patterns</p>
            <p>11:00 AM - Real-world Case Studies</p>
            <p>2:00 PM - Open Source Tools Roundup</p>
        </div>
    </div>
</section>

<section id="speakers" class="section">
    <h2>Featured Speakers</h2>
    <div class="speakers-grid">
        {% for speaker in site.data.speakers %}
        <div class="speaker">
            <img src="{{ speaker.image }}" alt="{{ speaker.name }}">
            <h3>{{ speaker.name }}</h3>
            <p>{{ speaker.bio }}</p>
        </div>
        {% endfor %}
    </div>
</section>

<section id="register" class="section dark">
    <h2>Register Now</h2>
    <p>Free admission for all developers</p>
    <a href="https://eventbrite.com/..." class="cta-button">Secure Your Spot</a>
</section>
