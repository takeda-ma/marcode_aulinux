---
layout: page
title: Members
icon: fas fa-users
order: 5
---

<style>
  .members-page {
    display: grid;
    gap: 1rem;
    margin-top: 1.5rem;
  }

  .member-row {
    display: flex;
    align-items: center;
    gap: 1rem;
    padding: 1rem 1.25rem;
    border: 1px solid var(--main-border-color, #e5e5e5);
    border-radius: 14px;
    background: var(--card-bg, #fff);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.04);
    transition: transform 0.15s ease, box-shadow 0.15s ease;
  }

  .member-row:hover {
    transform: translateY(-2px);
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.08);
  }

  .member-icon {
    width: 56px;
    height: 56px;
    min-width: 56px;
    border-radius: 999px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 1rem;
    color: #fff;
    background: linear-gradient(135deg, #4f46e5, #7c3aed);
  }

  .member-content {
    display: flex;
    flex-direction: column;
    gap: 0.15rem;
    min-width: 0;
  }

  .member-name {
    font-size: 1.05rem;
    font-weight: 700;
    line-height: 1.2;
    margin: 0;
  }

  .member-role {
    font-size: 0.92rem;
    opacity: 0.8;
    margin: 0;
  }

  @media (max-width: 576px) {
    .member-row {
      padding: 0.9rem 1rem;
    }

    .member-icon {
      width: 48px;
      height: 48px;
      min-width: 48px;
      font-size: 0.9rem;
    }

    .member-name {
      font-size: 1rem;
    }

    .member-role {
      font-size: 0.88rem;
    }
  }
</style>

<div class="members-page">
  {% for member in site.data.members %}
    <div class="member-row">
      <div class="member-icon">
        {{ member.initials }}
      </div>

      <div class="member-content">
        <p class="member-name">{{ member.name }}</p>
        <p class="member-role">{{ member.role }}</p>
      </div>
    </div>
  {% endfor %}
</div>
