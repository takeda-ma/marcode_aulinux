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
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
  gap: 1.8rem;
  margin-bottom: 3rem;
}

.member-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-decoration: none;
  color: inherit;
  padding: 2rem 1rem 1.6rem;
  text-align: center;
  transition: transform .2s;
}
.member-card:hover {
  transform: translateY(-4px);
  color: inherit;
  text-decoration: none;
}
.member-card:hover .member-avatar {
  border-color: var(--link-color, #6ea8fe);
  box-shadow: 0 8px 24px rgba(0,0,0,.25);
}
.member-avatar {
  width: 110px;
  height: 110px;
  border-radius: 50%;
  overflow: hidden;
  border: 2.5px solid rgba(128,128,128,.25);
  margin-bottom: 1.1rem;
  transition: border-color .2s, box-shadow .2s;
  flex-shrink: 0;
}
.member-avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
.member-card .name {
  font-weight: 700;
  font-size: 1rem;
  margin-bottom: .3rem;
  line-height: 1.3;
}
.member-card .role {
  font-size: .78rem;
  opacity: .5;
  line-height: 1.5;
}
</style>

<div class="about-intro">
  <h1>About Us</h1>
  <p>Marcode Aulinux is a group of developers who are passionate about developing games using Unreal Engine.</p>
</div>

<div class="members-heading">Members</div>

<div class="members-grid">

  <a class="member-card" href="{{ '/members/johji/' | relative_url }}">
    <div class="member-avatar">
      <img src="/assets/img/members/johji.svg" alt="Johji">
    </div>
    <div class="name">Johji</div>
    <div class="role">Founder · Lead Engineer</div>
  </a>

</div>
