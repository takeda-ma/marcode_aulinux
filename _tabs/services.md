---
# the default layout is 'page'
title: Services
icon: fas fa-briefcase
order: 5
---

<style>
.services-hero {
  text-align: center;
  padding: 2.5rem 1rem 2rem;
}
.services-hero h1 {
  font-size: 2rem;
  font-weight: 700;
  margin-bottom: .6rem;
}
.services-hero p {
  opacity: .7;
  max-width: 520px;
  margin: 0 auto;
  line-height: 1.7;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.4rem;
  margin: 2.5rem 0;
}
.service-card {
  border: 1px solid rgba(128,128,128,.2);
  border-radius: 12px;
  padding: 1.6rem 1.4rem;
  background: var(--card-bg, rgba(255,255,255,.03));
  transition: border-color .2s, transform .2s;
}
.service-card:hover {
  border-color: var(--link-color, #6ea8fe);
  transform: translateY(-3px);
}
.service-card .icon {
  font-size: 1.8rem;
  margin-bottom: .9rem;
  color: var(--link-color, #6ea8fe);
}
.service-card h3 {
  font-size: 1.05rem;
  font-weight: 700;
  margin-bottom: .5rem;
}
.service-card p {
  font-size: .88rem;
  opacity: .7;
  line-height: 1.65;
  margin: 0;
}
.service-tags {
  display: flex;
  flex-wrap: wrap;
  gap: .4rem;
  margin-top: .9rem;
}
.service-tag {
  font-size: .72rem;
  padding: .2rem .55rem;
  border-radius: 999px;
  border: 1px solid rgba(128,128,128,.3);
  opacity: .75;
}

.services-cta {
  text-align: center;
  padding: 2rem 1rem 1rem;
  border-top: 1px solid rgba(128,128,128,.15);
  margin-top: 1rem;
}
.services-cta p {
  opacity: .7;
  margin-bottom: 1.1rem;
  font-size: .95rem;
}
.services-cta a {
  display: inline-block;
  padding: .6rem 1.8rem;
  border-radius: 999px;
  background: var(--link-color, #6ea8fe);
  color: #fff;
  font-weight: 600;
  font-size: .9rem;
  text-decoration: none;
  transition: opacity .15s;
}
.services-cta a:hover { opacity: .8; color: #fff; }
</style>

<div class="services-hero">
  <h1>Services</h1>
  <p>12 years of software engineering applied to game development. I take on focused projects where deep technical work matters.</p>
</div>

<div class="services-grid">

  <div class="service-card">
    <div class="icon"><i class="fas fa-gamepad"></i></div>
    <h3>Unreal Engine 5 Development</h3>
    <p>End-to-end UE5 game feature development — gameplay systems, AI behaviour, ability systems (GAS), and real-time performance optimisation for shipping titles.</p>
    <div class="service-tags">
      <span class="service-tag">Unreal Engine 5</span>
      <span class="service-tag">C++</span>
      <span class="service-tag">Blueprints</span>
      <span class="service-tag">GAS</span>
    </div>
  </div>

  <div class="service-card">
    <div class="icon"><i class="fas fa-robot"></i></div>
    <h3>Game AI Systems</h3>
    <p>Custom AI controllers, behaviour scoring systems, and enemy/companion logic that scales to hundreds of agents without tanking frame time.</p>
    <div class="service-tags">
      <span class="service-tag">AI Controllers</span>
      <span class="service-tag">Behaviour Trees</span>
      <span class="service-tag">Custom AI</span>
      <span class="service-tag">Performance</span>
    </div>
  </div>

  <div class="service-card">
    <div class="icon"><i class="fas fa-bolt"></i></div>
    <h3>Gameplay Ability Systems</h3>
    <p>Scalable ability frameworks built on GAS — skills, buffs, debuffs, targeting pipelines, and proc systems designed for both players and AI-controlled characters.</p>
    <div class="service-tags">
      <span class="service-tag">GAS</span>
      <span class="service-tag">Abilities</span>
      <span class="service-tag">Targeting</span>
      <span class="service-tag">Multiplayer</span>
    </div>
  </div>

  <div class="service-card">
    <div class="icon"><i class="fas fa-users"></i></div>
    <h3>Character & Animation Systems</h3>
    <p>Modular character pipelines, skeletal mesh setup, rigging integration, and skinning workflows connecting Blender and Marvelous Designer to UE5.</p>
    <div class="service-tags">
      <span class="service-tag">Blender</span>
      <span class="service-tag">Marvelous Designer</span>
      <span class="service-tag">Rigging</span>
      <span class="service-tag">UE5</span>
    </div>
  </div>

  <div class="service-card">
    <div class="icon"><i class="fas fa-server"></i></div>
    <h3>Backend & Tools Engineering</h3>
    <p>12 years of software engineering across backend systems, automation, and internal tooling. Available for consulting on architecture, code review, and technical planning.</p>
    <div class="service-tags">
      <span class="service-tag">Backend</span>
      <span class="service-tag">Architecture</span>
      <span class="service-tag">Consulting</span>
      <span class="service-tag">Code Review</span>
    </div>
  </div>

  <div class="service-card">
    <div class="icon"><i class="fas fa-cube"></i></div>
    <h3>Technical Prototyping</h3>
    <p>Fast, focused prototypes to validate game mechanics, AI approaches, or system designs before committing to a full implementation.</p>
    <div class="service-tags">
      <span class="service-tag">Prototyping</span>
      <span class="service-tag">R&D</span>
      <span class="service-tag">UE5</span>
      <span class="service-tag">Feasibility</span>
    </div>
  </div>

</div>

<div class="services-cta">
  <p>Have a project in mind? Reach out and let's talk about it.</p>
  <a href="/marcode_aulinux/contact/">Get in touch</a>
</div>
