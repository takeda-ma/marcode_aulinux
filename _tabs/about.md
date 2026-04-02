---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
---

<style>
.member-card-link {
  text-decoration: none !important;
  color: inherit !important;
  transition: transform .2s;
  display: block;
}
.member-card-link:hover {
  transform: translateY(-4px);
  color: inherit !important;
}
.member-card-link:hover .card {
  box-shadow: 0 8px 24px rgba(0,0,0,.25) !important;
  border-color: var(--bs-primary, #6ea8fe) !important;
}
.member-avatar {
  width: 96px;
  height: 96px;
  object-fit: cover;
}
</style>

<div class="text-center border-bottom pb-4 mb-4">
  <h1 class="fw-bold mb-2">About Us</h1>
  <p class="text-muted mx-auto" style="max-width:520px;line-height:1.8;">Marcode Aulinux is a group of developers who are passionate about developing games using Unreal Engine.</p>
</div>

<p class="text-uppercase text-muted small fw-semibold ls-1 mb-3">Members</p>

<div class="row row-cols-2 row-cols-sm-3 row-cols-md-4 g-3 mb-4">

  <a class="col member-card-link" href="{{ '/members/johji/' | relative_url }}">
    <div class="card h-100 text-center border rounded-3 p-3">
      <div class="card-body p-0 pt-2">
        <img src="/assets/img/members/johji.svg" alt="Johji"
             class="rounded-circle member-avatar mb-3">
        <h6 class="card-title fw-bold mb-1">Johji</h6>
        <p class="card-text text-muted small mb-0">Founder · Lead Engineer</p>
      </div>
    </div>
  </a>

</div>
