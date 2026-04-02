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
  margin-bottom: 1.4rem;
}

.members-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
  gap: 1.4rem;
  margin-bottom: 3rem;
}

.member-card {
  display: block;
  text-decoration: none;
  color: inherit;
  border: 1px solid rgba(128,128,128,.18);
  border-radius: 14px;
  padding: 1.6rem 1rem 1.2rem;
  text-align: center;
  transition: border-color .2s, transform .2s, box-shadow .2s;
  background: var(--card-bg, rgba(255,255,255,.02));
}
.member-card:hover {
  border-color: var(--link-color, #6ea8fe);
  transform: translateY(-3px);
  box-shadow: 0 6px 20px rgba(0,0,0,.2);
  color: inherit;
  text-decoration: none;
}
.member-card img {
  width: 88px;
  height: 88px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
  border: 2px solid rgba(128,128,128,.2);
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.member-card .name {
  font-weight: 700;
  font-size: .95rem;
  margin-bottom: .25rem;
}
.member-card .role {
  font-size: .78rem;
  opacity: .55;
}
</style>

<div class="about-intro">
  <h1>私たちについて</h1>
  <p>Unreal Engine 5を専門とする東京拠点の開発スタジオです。ゲームプレイの設計から実装・リリースまで、プロジェクトに深く関わることを大切にしています。</p>
</div>

<div class="members-heading">Members</div>

<div class="members-grid">

  <a class="member-card" href="/marcode_aulinux/members/marcode/">
    <img src="/marcode_aulinux/assets/img/members/marcode.svg" alt="marcode aulinux">
    <div class="name">marcode aulinux</div>
    <div class="role">Founder · Lead Engineer</div>
  </a>

</div>
