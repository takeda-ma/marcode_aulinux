---
# the default layout is 'page'
title: Contact
icon: fas fa-envelope
order: 7
---

<form
  action="https://formspree.io/f/YOUR_FORM_ID"
  method="POST"
  style="max-width:540px;margin:0 auto;display:flex;flex-direction:column;gap:1rem;"
>
  <div style="display:flex;flex-direction:column;gap:0.3rem;">
    <label for="name" style="font-size:0.9rem;opacity:0.75;">Name</label>
    <input
      id="name"
      type="text"
      name="name"
      required
      placeholder="Your name"
      style="padding:0.6rem 0.8rem;border-radius:6px;border:1px solid var(--border-color,#444);background:var(--card-bg,#1e1e2e);color:inherit;font-size:1rem;width:100%;box-sizing:border-box;"
    />
  </div>

  <div style="display:flex;flex-direction:column;gap:0.3rem;">
    <label for="email" style="font-size:0.9rem;opacity:0.75;">Email</label>
    <input
      id="email"
      type="email"
      name="email"
      required
      placeholder="your@email.com"
      style="padding:0.6rem 0.8rem;border-radius:6px;border:1px solid var(--border-color,#444);background:var(--card-bg,#1e1e2e);color:inherit;font-size:1rem;width:100%;box-sizing:border-box;"
    />
  </div>

  <div style="display:flex;flex-direction:column;gap:0.3rem;">
    <label for="message" style="font-size:0.9rem;opacity:0.75;">Message</label>
    <textarea
      id="message"
      name="message"
      required
      rows="6"
      placeholder="What's on your mind?"
      style="padding:0.6rem 0.8rem;border-radius:6px;border:1px solid var(--border-color,#444);background:var(--card-bg,#1e1e2e);color:inherit;font-size:1rem;width:100%;box-sizing:border-box;resize:vertical;"
    ></textarea>
  </div>

  <button
    type="submit"
    style="align-self:flex-start;padding:0.6rem 1.6rem;border-radius:6px;border:none;background:var(--link-color,#6495ed);color:#fff;font-size:1rem;cursor:pointer;"
  >
    Send
  </button>
</form>
