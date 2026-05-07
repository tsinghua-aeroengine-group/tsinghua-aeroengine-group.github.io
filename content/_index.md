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
      title: "最新研究"
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
      title: "研究成员"
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
          <h3 class="member-section-heading">教师</h3>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/wang-baotong.jpg" alt="王宝潼" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/members/wang-baotong/">王宝潼</a> 研究员</p>
              <p class="member-list-text">清华大学研究员，航空发动机研究院副院长。主要从事航空发动机性能、气动稳定性及气动弹性研究。近五年承担“两机”重大专项、基础加强计划等项目13项，发表SCI论文40余篇，申请及授权专利29项。</p>
              <p class="member-list-text" style="margin-bottom:0;">邮箱：wangbaotong@tsinghua.edu.cn</p>
            </div>
          </div>
          <h3 class="member-section-heading">在研学生</h3>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/sun-yiheng.jpg" alt="孙一蘅" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/members/sun-yiheng/">孙一蘅</a> 2025级硕士生</p>
              <p class="member-list-text">清华大学航空发动机研究院硕士生，研究方向为航空发动机智能算法与数字孪生。</p>
              <p class="member-list-text" style="margin-bottom:0;">邮箱：sun-yh25@mails.tsinghua.edu.cn</p>
            </div>
          </div>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/zhu-haoyuan.jpg" alt="朱昊元" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/members/zhu-haoyuan/">朱昊元</a> 2024级硕士生</p>
              <p class="member-list-text">清华大学航空发动机研究院硕士生，研究方向为航空发动机体积力仿真及飞发一体化设计。</p>
              <p class="member-list-text" style="margin-bottom:0;">邮箱：hy-zhu24@mails.tsinghua.edu.cn</p>
            </div>
          </div>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/ding-zechen.jpg" alt="丁泽琛" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/members/ding-zechen/">丁泽琛</a> 2023级硕士生</p>
              <p class="member-list-text">清华大学航空发动机研究院硕士生，研究方向为航空发动机整机气动稳定性仿真与试验。</p>
              <p class="member-list-text" style="margin-bottom:0;">邮箱：dingzc23@mails.tsinghua.edu.cn</p>
            </div>
          </div>
          <h3 class="member-section-heading">毕业学生</h3>
          <p style="margin:0 0 40px 0;">暂无</p>
          <h3 class="member-section-heading">行政助理</h3>
          <div style="display:flex;gap:30px;align-items:flex-start;margin-bottom:40px;">
            <img class="member-list-photo" src="/media/members/liu-xi.jpg" alt="刘熹" />
            <div style="flex:1 1 auto;">
              <p class="member-list-name"><a href="/members/liu-xi/">刘熹</a> 行政助理</p>
              <p class="member-list-text">清华大学航空发动机研究院课题组行政助理，负责课题组日常事务。</p>
              <p class="member-list-text" style="margin-bottom:0;">邮箱：XXX</p>
            </div>
          </div>
        </div>
    design:
      columns: "1"

  - block: markdown
    id: achievements
    content:
      title: "成果发表"
      subtitle: ""
      text: |-
        {{< achievements-list >}}
    design:
      columns: "1"

  - block: markdown
    id: gallery
    content:
      title: "活动相册"
      subtitle: ""
      text: |-
        {{< gallery-list >}}
    design:
      columns: "1"

  - block: markdown
    id: activity
    content:
      title: "招募信息"
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
            <p>清华大学航发院王宝潼老师课题组是一个充满活力、追求卓越的学术共同体。我们拥有<strong>充足的科研经费</strong>支持，鼓励学生勇于探索前沿课题，并<strong>全额资助</strong>学生参加顶级国际学术会议。在这里，<strong>氛围融洽</strong>且自由，导师与学生交流无间。我们不仅提供实现个人科研志趣的顶尖平台，更致力于构建一个让<strong>志同道合</strong>的伙伴共同成长的家园。</p>
          </section>
          <section class="recruit-section">
            <h3>硕士生岗位</h3>
            <p>欢迎具有航空宇航、动力工程、流体力学、机械工程、人工智能、应用数学等相关背景，且具备较强自我驱动力的同学申请清华大学航空发动机研究院的硕士研究生项目。本课题组目前招收以下两类硕士：</p>
            <ul>
              <li><strong>两年制低空经济专项硕士：</strong>紧扣国家低空经济战略需求，聚焦新型动力系统研发与优化。</li>
              <li><strong>三年制校企联合培养工程硕士：</strong>深度依托行业资源，在解决航空发动机实际工程问题的过程中培养科研与应用能力。</li>
            </ul>
            <p><strong>申请要求：</strong>有意者请通过“联系方式”页面与我们取得联系，并随信附上个人简历、成绩单以及一份研究兴趣与计划。在研究计划中，请重点说明：</p>
            <ol>
              <li>您感兴趣的研究方向；</li>
              <li>您选择加入本课题组的初衷；</li>
              <li>您对未来大致的学术和职业规划。</li>
            </ol>
          </section>
          <section class="recruit-section">
            <h3>本科生岗位</h3>
            <p>我们鼓励有科研热情的清华大学在校本科生加入我们，接触航空动力领域的最前沿交叉学科研究。</p>
            <ul>
              <li><strong>SRT项目报名：</strong>欢迎对课题组相关方向感兴趣的同学联系报名SRT项目。</li>
              <li><strong>日常科研活动：</strong>我们也长期支持学有余力的同学参与实验室日常科研讨论与实验，提前体验学术氛围。</li>
            </ul>
            <p>有意者请通过“联系方式”页面联系我们，来信请附上您的个人简历、研究兴趣及成绩单。</p>
          </section>
        </div>
    design:
      columns: "1"

  - block: markdown
    id: contact
    content:
      title: "联系方式"
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
          <div class="contact-row"><strong>地址</strong><p>清华大学李兆基科技大厦A区223-2室</p></div>
          <div class="contact-row"><strong>邮编</strong><p>100084</p></div>
          <div class="contact-row"><strong>电话</strong><p>010-62795170</p></div>
          <div class="contact-row"><strong>邮箱</strong><p>wangbaotong@tsinghua.edu.cn</p></div>
        </div>
        <div class="visit-panel" style="width:min(94vw,800px);margin:240px auto 0;">
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
            #contact.hbb-section { padding-bottom:0 !important; }
            body:has(.visit-panel) .page-footer footer { margin-top:0 !important; }
            @media (max-width:760px) { .visit-grid { grid-template-columns:1fr; } }
          </style>
          <h2 class="visit-title">来访情况</h2>
          <div class="visit-grid">
            <section class="visit-counter">
              <p class="visit-label">来访总数</p>
              <div class="visit-digits" aria-label="来访总数"><span class="visit-digit">0</span><span class="visit-digit">0</span><span class="visit-digit">0</span><span class="visit-digit">0</span><span class="visit-digit">0</span></div>
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
