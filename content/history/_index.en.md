---
title: "Edit History"
---

<style>
  .history-wrap {
    width: min(94vw, 800px);
    margin: 0 auto;
    padding: 8px 0 48px;
  }
  .history-timeline {
    position: relative;
    margin: 24px 0 0;
    padding-left: 34px;
  }
  .history-timeline::before {
    content: "";
    position: absolute;
    left: 10px;
    top: 4px;
    bottom: 4px;
    width: 2px;
    background: linear-gradient(180deg, #8db9b2 0%, rgba(141, 185, 178, 0.2) 100%);
  }
  .history-item {
    position: relative;
    margin: 0 0 22px;
    padding: 18px 20px;
    border: 1px solid rgba(141, 185, 178, 0.34);
    border-radius: 14px;
    background: linear-gradient(135deg, #f2f8f6 0%, #f8fbfd 100%);
    box-shadow: 0 10px 24px rgba(15, 23, 42, 0.055);
  }
  .history-item::before {
    content: "";
    position: absolute;
    left: -30px;
    top: 24px;
    width: 12px;
    height: 12px;
    border: 3px solid #8db9b2;
    border-radius: 999px;
    background: #fff;
  }
  .history-date {
    margin: 0 0 6px;
    color: #0f172a;
    font-size: 1.08rem;
    font-weight: 700;
  }
  .history-text {
    margin: 0;
    max-width: none;
    color: #475569;
    font-size: 1.04rem;
    line-height: 1.6;
  }
  .dark .history-item {
    border-color: rgba(156, 203, 196, 0.3);
    background: linear-gradient(135deg, rgba(141, 185, 178, 0.18) 0%, rgba(120, 154, 181, 0.12) 100%);
  }
  .dark .history-item::before {
    background: #0f172a;
  }
  .dark .history-date {
    color: #f8fafc;
  }
  .dark .history-text {
    color: #cbd5e1;
  }
</style>

<div class="history-wrap">
  <div class="history-timeline">
    <section class="history-item">
      <p class="history-date">May 7, 2026</p>
      <p class="history-text">Website officially launched. Maintained and edited by Radon Ding.</p>
    </section>
  </div>
</div>
