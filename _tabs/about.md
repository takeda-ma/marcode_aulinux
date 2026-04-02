---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

<style>
.about-intro {
  text-align: center;
  padding: 2rem 1rem 2.5rem;
  border-bottom: 1px solid rgba(128,128,128,.12);
  margin-bottom: 2.5rem;
}
.about-intro h1 {
  font-size: 1.8rem;
  font-weight: 800;
  margin-bottom: .7rem;
}
.about-intro p {
  max-width: 520px;
  margin: 0 auto;
  opacity: .7;
  line-height: 1.8;
  font-size: .95rem;
}

.members-heading {
  font-size: .72rem;
  letter-spacing: .14em;
  text-transform: uppercase;
  opacity: .45;
  margin-bottom: 1.6rem;
}

.members-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  margin-bottom: 3rem;
}

.member-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-decoration: none !important;
  color: inherit !important;
  text-align: center;
  transition: transform .2s;
  width: 140px;
}
.member-card:hover {
  transform: translateY(-4px);
}
.member-card:hover img {
  box-shadow: 0 8px 24px rgba(0,0,0,.3);
}
.member-card img {
  width: 112px;
  height: 112px;
  object-fit: cover;
  margin-bottom: .9rem;
  transition: box-shadow .2s;
}
</style>

<div class="about-intro">
  <h1>About Us</h1>
  <p>Marcode Aulinux is a group of developers who are passionate about developing games using Unreal Engine.</p>
</div>

<div class="members-heading">Members</div>

<div class="members-grid">

  <a class="member-card" href="{{ '/members/johji/' | relative_url }}">
    <img src="/assets/img/members/johji.svg" alt="Johji" class="rounded-circle">
    <span class="site-title d-block">Johji</span>
    <span class="site-subtitle fst-italic">Founder · Lead Engineer</span>
  </a>

</div>
