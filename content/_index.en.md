---
title: ""
summary: ""
date: 2026-05-04
type: landing

sections:
  - block: markdown
    id: home
    content:
      title: ""
      subtitle: ""
      text: |-
        <style>
          [lang^="zh"] .en-only { display:none; }
          [lang^="en"] .zh-only { display:none; }
        </style>
        <div style="width:min(94vw,800px);margin:0 auto;">
          <div style="display:flex;align-items:center;justify-content:space-between;gap:56px;">
            <div style="flex:0 0 44%;">
              <img src="/media/group-photo.jpg" alt="group photo" style="width:100%;height:auto;border-radius:16px;display:block;" />
              <p class="zh-only" style="margin:0;">课题组合影</p>
              <p class="en-only" style="margin:0;">Group Photo</p>
              <p class="zh-only" style="margin:0;">2025年11月</p>
              <p class="en-only" style="margin:0;">Nov 2025</p>
            </div>
            <div style="flex:1 1 auto;">
              <h1 class="zh-only" style="margin:0;line-height:1.08;">航空先进动力性能与稳定性课题组</h1>
              <h1 class="en-only" style="margin:0;line-height:1.08;">Advanced Aero-Propulsion Performance and Stability Group</h1>
            </div>
          </div>
            <div style="margin-top:24px;width:100%;max-width:none;">
              <h3 class="zh-only">课题组简介</h3>
              <h3 class="en-only">Group Introduction</h3>
              <p class="zh-only" style="max-width:none;"><strong>航空发动机性能与稳定性课题组</strong>依托于清华大学航空发动机研究院，在王宝潼研究员的带领下，不断探索航空发动机性能、气动稳定性及气动弹性等领域的前沿问题。</p>
              <p class="zh-only" style="max-width:none;">我们致力于发展航空发动机整机气动稳定性与性能预测的新理论与计算模型，设计基于多维耦合与机器学习的高精度降阶分析方法，并探索这些系统性方法在先进航空动力研发中的实际应用。我们的研究重点集中在建立秒级整机快速失稳预测模型、基于局部流动参数的准三维体积力建模，以及面向下一代变循环发动机的多维缩放与耦合预测等领域。相关成果已在多款在役在研重点型号中得到充分验证与应用。如果您想了解更多关于我们的研究内容，欢迎与我们联系。</p>
              <p class="en-only" style="max-width:none;"><strong>The Aero-Engine Performance and Stability Group</strong>, affiliated with the Institute for Aero Engine at Tsinghua University and led by Researcher Baotong Wang, focuses on frontier challenges in aero-engine performance, aerodynamic stability, and aeroelasticity.</p>
              <p class="en-only" style="max-width:none;">We develop new theories and computational models for whole-engine aerodynamic stability and performance prediction, design high-accuracy reduced-order methods based on multi-dimensional coupling and machine learning, and translate these systematic methods into advanced aero-propulsion R&D practice. Our key topics include second-level rapid instability prediction models, quasi-3D body-force modeling based on local flow parameters, and multi-dimensional scaling and coupled prediction for next-generation variable-cycle engines. These outcomes have been validated and applied in multiple key in-service and in-development engine programs. Feel free to contact us for more details on our research.</p>
            </div>
        </div>
    design:
      columns: "1"

  - block: markdown
    id: latest-research
    content:
      title: "Latest Research"
      subtitle: ""
      text: |-
        <style>
          [lang^="zh"] .en-only { display:none; }
          [lang^="en"] .zh-only { display:none; }
        </style>
        {{< latest-research-list >}}
    design:
      columns: "1"

  - block: markdown
    id: members
    content:
      title: "Members"
      subtitle: ""
      text: |-
        <div style="width:min(94vw,800px);margin:0 auto;">
          <style>
            .member-section-heading { margin:0 0 24px 0;padding:10px 18px;border-left:6px solid #8db9b2;background:linear-gradient(90deg,#eef7f4 0%,#f6fafc 100%);color:#475569;font-size:1.275rem;line-height:1.35;font-weight:700; }
            .dark .member-section-heading { border-left-color:#9ccbc4;background:linear-gradient(90deg,rgba(141,185,178,0.22) 0%,rgba(120,154,181,0.12) 100%);color:#e2e8f0; }
            .member-list-photo { width:40mm;height:auto;flex:0 0 40mm;margin:0;align-self:flex-start; }
            .member-list-name { margin:0 0 8px 0;font-size:1.08rem;line-height:1.55; }
            .member-list-text { margin:0 0 8px 0;max-width:none;font-size:1.08rem;line-height:1.55; }
          </style>
          <h3 class="member-section-heading">Faculty</h3>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/wang-baotong.jpg" alt="Baotong Wang" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/en/members/wang-baotong/">Baotong Wang</a> Researcher</p>
              <p class="member-list-text">Researcher at Tsinghua University and Vice Dean of the Institute for Aero Engine. His research focuses on aero-engine performance, aerodynamic stability, and aeroelasticity. Over the past five years, he has led 13 projects including major national aero-engine programs and foundational research programs, published over 40 SCI papers, and filed or authorized 29 patents.</p>
              <p class="member-list-text" style="margin-bottom:0;">Email: wangbaotong@tsinghua.edu.cn</p>
            </div>
          </div>
          <h3 class="member-section-heading">Current Students</h3>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/sun-yiheng.jpg" alt="Yiheng Sun" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/en/members/sun-yiheng/">Yiheng Sun</a> Master student, 2025 cohort</p>
              <p class="member-list-text">Master student at the Institute for Aero Engine, Tsinghua University. Research interests include intelligent algorithms and digital twins for aero-engines.</p>
              <p class="member-list-text" style="margin-bottom:0;">Email: sun-yh25@mails.tsinghua.edu.cn</p>
            </div>
          </div>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/zhu-haoyuan.jpg" alt="Haoyuan Zhu" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/en/members/zhu-haoyuan/">Haoyuan Zhu</a> Master student, 2024 cohort</p>
              <p class="member-list-text">Master student at the Institute for Aero Engine, Tsinghua University. Research interests include aero-engine body-force simulation and integrated airframe-engine design.</p>
              <p class="member-list-text" style="margin-bottom:0;">Email: hy-zhu24@mails.tsinghua.edu.cn</p>
            </div>
          </div>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/ding-zechen.jpg" alt="Zechen Ding" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/en/members/ding-zechen/">Zechen Ding</a> Master student, 2023 cohort</p>
              <p class="member-list-text">Master student at the Institute for Aero Engine, Tsinghua University. Research interests include whole-engine aerodynamic stability simulation and experiments.</p>
              <p class="member-list-text" style="margin-bottom:0;">Email: dingzc23@mails.tsinghua.edu.cn</p>
            </div>
          </div>
          <h3 class="member-section-heading">Alumni</h3>
          <p style="margin:0 0 40px 0;">None yet</p>
          <h3 class="member-section-heading">Administrative Assistant</h3>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/liu-xi.jpg" alt="Xi Liu" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/en/members/liu-xi/">Xi Liu</a> Administrative Assistant</p>
              <p class="member-list-text">Administrative assistant of the group at the Institute for Aero Engine, Tsinghua University, responsible for daily group affairs.</p>
              <p class="member-list-text" style="margin-bottom:0;">Email: XXX</p>
            </div>
          </div>
        </div>
    design:
      columns: "1"

  - block: markdown
    id: achievements
    content:
      title: "Publications"
      subtitle: ""
      text: |-
        {{< achievements-list >}}
    design:
      columns: "1"

  - block: markdown
    id: gallery
    content:
      title: "Gallery"
      subtitle: ""
      text: |-
        {{< gallery-list >}}
    design:
      columns: "1"

  - block: markdown
    id: activity
    content:
      title: "Open Positions"
      subtitle: ""
      text: |-
        <div class="recruit-panel" style="width:min(94vw,800px);margin:0 auto;">
          <style>
            .recruit-panel { color:#334155; }
            .recruit-intro { margin:0 0 22px;padding:18px 20px;border:1px solid rgba(141,185,178,0.34);border-radius:10px;background:linear-gradient(135deg,#f2f8f6 0%,#f8fbfd 100%);box-shadow:0 10px 24px rgba(15,23,42,0.055); }
            .recruit-section { margin:0 0 24px; }
            .recruit-section h3 { margin:0 0 12px;padding:10px 18px;border-left:6px solid #8db9b2;background:linear-gradient(90deg,#eef7f4 0%,#f6fafc 100%);color:#475569;font-size:1.275rem;font-weight:700;line-height:1.35; }
            .recruit-panel p { margin:0 0 10px;max-width:none;font-size:1.08rem;line-height:1.58; }
            .recruit-intro p { font-size:1.12rem;line-height:1.62; }
            .recruit-panel ul,.recruit-panel ol { margin:8px 0 0 1.25rem;padding:0;font-size:1.08rem;line-height:1.58; }
            .recruit-panel li { margin:4px 0; }
            .dark .recruit-panel { color:#cbd5e1; }
            .dark .recruit-intro { border-color:rgba(156,203,196,0.3);background:linear-gradient(135deg,rgba(141,185,178,0.18) 0%,rgba(120,154,181,0.12) 100%); }
            .dark .recruit-section h3 { color:#cbd5e1;border-left-color:#9ccbc4;background:linear-gradient(90deg,rgba(141,185,178,0.22) 0%,rgba(120,154,181,0.12) 100%); }
          </style>
          <section class="recruit-intro">
            <p>Researcher Baotong Wang's group at the Institute for Aero Engine, Tsinghua University is a vibrant academic community committed to excellence. The group has <strong>strong research funding</strong>, encourages students to explore frontier topics, and fully supports students in attending leading international conferences. We offer an open and supportive atmosphere with close interaction between advisor and students, providing not only a first-rate platform for research ambitions but also a home for like-minded collaborators to grow together.</p>
          </section>
          <section class="recruit-section">
            <h3>Master's Positions</h3>
            <p>We welcome self-motivated applicants with backgrounds in aerospace engineering, power engineering, fluid mechanics, mechanical engineering, artificial intelligence, applied mathematics, or related fields to apply for master's programs at the Institute for Aero Engine, Tsinghua University. The group currently recruits two types of master's students:</p>
            <ul>
              <li><strong>Two-year Low-Altitude Economy Program:</strong> focusing on new propulsion-system development and optimization in response to national strategic needs.</li>
              <li><strong>Three-year Industry-University Joint Engineering Program:</strong> developing research and application capabilities through real aero-engine engineering problems.</li>
            </ul>
            <p><strong>Application materials:</strong> please contact us through the contact information below and include your CV, transcript, and a brief research-interest and plan statement. In the statement, please briefly explain:</p>
            <ol>
              <li>Your research interests;</li>
              <li>Your motivation for joining this group;</li>
              <li>Your preliminary academic and career plan for the future.</li>
            </ol>
          </section>
          <section class="recruit-section">
            <h3>Undergraduate Positions</h3>
            <p>We encourage Tsinghua undergraduate students with research enthusiasm to join us and explore frontier interdisciplinary research in aero-propulsion.</p>
            <ul>
              <li><strong>SRT Projects:</strong> students interested in our research directions are welcome to contact us for SRT opportunities.</li>
              <li><strong>Daily Research Activities:</strong> we also support motivated students in joining regular research discussions and experiments to experience academic work early.</li>
            </ul>
            <p>Please contact us and include your CV, research interests, and transcript.</p>
          </section>
        </div>
    design:
      columns: "1"

  - block: markdown
    id: contact
    content:
      title: "Contact"
      subtitle: ""
      text: |-
        <div class="contact-panel" style="width:min(94vw,800px);margin:0 auto;">
          <style>
            .contact-panel { color:#334155;border-top:1px solid rgba(141,185,178,0.45);border-bottom:1px solid rgba(141,185,178,0.45);background:linear-gradient(90deg,rgba(242,248,246,0.7) 0%,rgba(248,251,253,0.7) 100%); }
            .contact-row { display:grid;grid-template-columns:96px 1fr;gap:18px;align-items:center;padding:13px 18px;border-bottom:1px solid rgba(141,185,178,0.22); }
            .contact-row:last-child { border-bottom:0; }
            .contact-row strong { color:#0f172a;font-size:1.02rem; }
            .contact-row p { margin:0;max-width:none;font-size:1.12rem;line-height:1.55; }
            .dark .contact-panel { color:#cbd5e1; }
            .dark .contact-panel { border-color:rgba(156,203,196,0.35);background:linear-gradient(90deg,rgba(141,185,178,0.12) 0%,rgba(120,154,181,0.08) 100%); }
            .dark .contact-row { border-bottom-color:rgba(156,203,196,0.22); }
            .dark .contact-row strong { color:#f8fafc; }
            @media (max-width:640px) { .contact-row { grid-template-columns:1fr;gap:4px; } }
          </style>
          <div class="contact-row"><strong>Address</strong><p>Room 223-2, Area A, Lee Shau Kee Science and Technology Building, Tsinghua University</p></div>
          <div class="contact-row"><strong>Postcode</strong><p>100084</p></div>
          <div class="contact-row"><strong>Phone</strong><p>010-62795170</p></div>
          <div class="contact-row"><strong>Email</strong><p>wangbaotong@tsinghua.edu.cn</p></div>
        </div>
        <div class="visit-panel" style="width:min(94vw,800px);margin:240px auto 80px;">
          <style>
            .visit-panel { color:#334155;padding:0;border:0;border-radius:0;background:transparent;box-shadow:none;overflow:visible; }
            .visit-title { position:relative;width:100%;margin:0 0 18px;padding:9px 18px;text-align:center;color:#0f172a;font-size:1.48rem;font-weight:700;line-height:1.28;border-radius:0;background:linear-gradient(90deg,#eef7f4 0%,#f6fafc 100%); }
            .visit-grid { display:grid;grid-template-columns:276px minmax(0,1fr);gap:14px;align-items:stretch;margin:0; }
            .visit-counter,.visit-map { border-top:1px solid rgba(141,185,178,0.45);border-bottom:1px solid rgba(141,185,178,0.45);background:linear-gradient(90deg,rgba(242,248,246,0.7) 0%,rgba(248,251,253,0.7) 100%); }
            .visit-title::before,.visit-title::after { content:"";position:absolute;top:0;bottom:0;width:6px;background:#8db9b2; }
            .visit-title::before { left:0;border-radius:0; }
            .visit-title::after { right:0;border-radius:0; }
            .visit-counter { display:flex;flex-direction:column;justify-content:center;align-items:center;padding:10px 14px 10px 18px; }
            .visit-label { margin:0 0 16px;text-align:center;color:#475569;font-size:1.36rem;font-weight:700;line-height:1.24; }
            .visit-digits { display:flex;justify-content:center;gap:8px; }
            .visit-digit { min-width:48px;padding:16px 6px 18px;border-radius:8px;background:linear-gradient(180deg,#111827 0%,#020617 100%);color:#f8fafc;text-align:center;font-family:'Times New Roman','Georgia','Noto Serif SC',serif;font-size:2.42rem;font-weight:700;line-height:0.92;letter-spacing:-0.01em;box-shadow:inset 0 -14px 0 rgba(255,255,255,0.055),0 8px 18px rgba(15,23,42,0.12); }
            .visit-source { position:absolute;left:-9999px;width:1px;height:1px;overflow:hidden; }
            .visit-map { display:flex;align-items:center;justify-content:center;min-height:206px;padding:2px 0;overflow:hidden; }
            .visit-map > div,.visit-map > a { width:100%;display:flex;justify-content:center; }
            .visit-map #clustrmaps-widget,.visit-map .clustrmaps-map-control { width:540px !important;max-width:100% !important;margin:0 auto !important; }
            .visit-map script + a,.visit-map canvas,.visit-map iframe,.visit-map img { max-width:100% !important;height:auto !important; }
            .dark .visit-panel { color:#cbd5e1;background:transparent;box-shadow:none; }
            .dark .visit-title { color:#f8fafc;background:linear-gradient(90deg,rgba(141,185,178,0.22) 0%,rgba(120,154,181,0.12) 100%); }
            .dark .visit-counter,.dark .visit-map { border-color:rgba(156,203,196,0.35);background:linear-gradient(90deg,rgba(141,185,178,0.12) 0%,rgba(120,154,181,0.08) 100%); }
            .dark .visit-title::before,.dark .visit-title::after { background:#9ccbc4; }
            .dark .visit-label { color:#cbd5e1; }
            @media (max-width:760px) { .visit-grid { grid-template-columns:1fr; } }
          </style>
          <h2 class="visit-title">Visitor Statistics</h2>
          <div class="visit-grid">
            <section class="visit-counter">
              <p class="visit-label">Total Visits</p>
              <div class="visit-digits" aria-label="Total Visits"><span class="visit-digit">0</span><span class="visit-digit">0</span><span class="visit-digit">0</span><span class="visit-digit">0</span><span class="visit-digit">0</span></div>
              <span class="visit-source" id="vercount_value_site_uv">Loading</span>
              <script defer src="https://events.vercount.one/js"></script>
              <script>
                (function () {
                  function renderVisitDigits() {
                    var source = document.getElementById('vercount_value_site_uv');
                    var digits = document.querySelectorAll('.visit-panel .visit-digit');
                    if (!source || !digits.length) return;
                    var value = parseInt((source.textContent || '').replace(/\D/g, ''), 10);
                    if (!Number.isFinite(value)) value = 0;
                    String(value).padStart(5, '0').slice(-5).split('').forEach(function (n, i) {
                      if (digits[i]) digits[i].textContent = n;
                    });
                  }
                  renderVisitDigits();
                  var source = document.getElementById('vercount_value_site_uv');
                  if (source) new MutationObserver(renderVisitDigits).observe(source, { childList: true, characterData: true, subtree: true });
                  setTimeout(renderVisitDigits, 1200);
                  setTimeout(renderVisitDigits, 3000);
                })();
              </script>
            </section>
            <section class="visit-map">
              <script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=540&t=n&d=d2pytb3r24WXEqLTkp2g45ha0i1wLP-0tn4hDpQvjwY&co=2d78ad&cmo=3acc3a&cmn=ff5353&ct=ffffff"></script>
            </section>
          </div>
        </div>
    design:
      columns: "1"
---
