---
# the default layout is 'page'
title: Services
icon: fas fa-briefcase
order: 5
---

<style>
/* ── Hero ── */
.sv-hero {
  text-align: center;
  padding: 3rem 1rem 2.5rem;
  border-bottom: 1px solid rgba(128,128,128,.15);
  margin-bottom: 3rem;
}
.sv-hero .label {
  font-size: .75rem;
  letter-spacing: .14em;
  text-transform: uppercase;
  opacity: .5;
  margin-bottom: .6rem;
}
.sv-hero h1 {
  font-size: 2rem;
  font-weight: 800;
  margin-bottom: 1rem;
  line-height: 1.3;
}
.sv-hero p {
  max-width: 560px;
  margin: 0 auto;
  opacity: .7;
  line-height: 1.8;
  font-size: .95rem;
}

/* ── Service blocks ── */
.sv-block {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 3rem 4rem;
  align-items: start;
  padding: 2.5rem 0;
  border-bottom: 1px solid rgba(128,128,128,.1);
}
.sv-block:last-of-type { border-bottom: none; }
.sv-block.reverse { direction: rtl; }
.sv-block.reverse > * { direction: ltr; }

@media (max-width: 768px) {
  .sv-block, .sv-block.reverse { grid-template-columns: 1fr; direction: ltr; gap: 1.5rem; }
}

.sv-block-icon {
  font-size: 3.5rem;
  color: var(--link-color, #6ea8fe);
  margin-bottom: 1rem;
  opacity: .85;
}
.sv-block-meta .category {
  font-size: .72rem;
  letter-spacing: .12em;
  text-transform: uppercase;
  color: var(--link-color, #6ea8fe);
  margin-bottom: .5rem;
}
.sv-block-meta h2 {
  font-size: 1.35rem;
  font-weight: 700;
  margin-bottom: 1rem;
  line-height: 1.35;
}
.sv-block-meta p {
  font-size: .9rem;
  opacity: .72;
  line-height: 1.85;
  margin-bottom: 1.2rem;
}
.sv-list {
  list-style: none;
  padding: 0;
  margin: 0 0 1.4rem;
}
.sv-list li {
  font-size: .88rem;
  opacity: .75;
  padding: .3rem 0;
  padding-left: 1.1rem;
  position: relative;
  line-height: 1.6;
}
.sv-list li::before {
  content: "–";
  position: absolute;
  left: 0;
  opacity: .4;
}
.sv-tags {
  display: flex;
  flex-wrap: wrap;
  gap: .4rem;
}
.sv-tag {
  font-size: .71rem;
  padding: .2rem .6rem;
  border-radius: 999px;
  border: 1px solid rgba(128,128,128,.3);
  opacity: .7;
}

/* ── Philosophy strip ── */
.sv-philosophy {
  background: rgba(128,128,128,.05);
  border-radius: 12px;
  padding: 2rem 2rem;
  margin: 3rem 0;
  text-align: center;
}
.sv-philosophy h3 {
  font-size: 1rem;
  font-weight: 700;
  margin-bottom: .6rem;
}
.sv-philosophy p {
  font-size: .9rem;
  opacity: .7;
  max-width: 560px;
  margin: 0 auto;
  line-height: 1.8;
}

/* ── Process ── */
.sv-process {
  margin: 2.5rem 0;
}
.sv-process h2 {
  font-size: 1rem;
  font-weight: 700;
  text-align: center;
  margin-bottom: 1.2rem;
  opacity: .8;
}
.sv-steps {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 0;
}
.sv-step {
  display: flex;
  align-items: center;
  gap: .5rem;
}
.sv-step-inner {
  text-align: center;
  padding: .5rem .9rem;
  border: 1px solid rgba(128,128,128,.2);
  border-radius: 999px;
  white-space: nowrap;
}
.sv-step .num {
  font-size: .62rem;
  letter-spacing: .08em;
  color: var(--link-color, #6ea8fe);
  display: block;
  margin-bottom: .1rem;
}
.sv-step .name {
  font-size: .8rem;
  font-weight: 600;
}
.sv-arrow {
  font-size: .75rem;
  opacity: .35;
  padding: 0 .3rem;
}
@media (max-width: 600px) {
  .sv-steps { flex-direction: column; gap: .4rem; }
  .sv-arrow { transform: rotate(90deg); }
}

/* ── CTA ── */
.sv-cta {
  text-align: center;
  padding: 2.5rem 1rem;
  border-top: 1px solid rgba(128,128,128,.15);
  margin-top: 2rem;
}
.sv-cta p {
  opacity: .7;
  margin-bottom: 1.1rem;
  font-size: .95rem;
  line-height: 1.7;
}
.sv-cta a {
  display: inline-block;
  padding: .65rem 2rem;
  border-radius: 999px;
  background: var(--link-color, #6ea8fe);
  color: #fff;
  font-weight: 600;
  font-size: .9rem;
  text-decoration: none;
  transition: opacity .15s;
}
.sv-cta a:hover { opacity: .8; color: #fff; }
</style>

<!-- Hero -->
<div class="sv-hero">
  <div class="label">Services</div>
  <h1>見て、考えて、一緒につくる。</h1>
  <p>私たちはUnreal Engine 5を専門とする開発スタジオです。ゲームの企画段階から実装・リリース後の改善まで、開発パートナーとしてプロジェクトに寄り添います。単なる受託開発ではなく、価値を生み出す仕組みをともに考えることが私たちのスタンスです。</p>
</div>

<!-- Service 1 -->
<div class="sv-block">
  <div class="sv-block-visual">
    <div class="sv-block-icon"><i class="fas fa-gamepad"></i></div>
  </div>
  <div class="sv-block-meta">
    <div class="category">Game Development</div>
    <h2>Unreal Engine 5<br>ゲーム開発</h2>
    <p>UE5を用いたゲーム機能の設計・実装を担います。戦闘システム、アビリティ設計、NPCのAI行動、キャラクターパイプラインまで、リリースを見据えた品質でお届けします。要件定義から納品・保守までワンストップで対応可能です。</p>
    <ul class="sv-list">
      <li>ゲームプレイシステム設計・実装（C++ / Blueprint）</li>
      <li>Gameplay Ability System（GAS）を用いたスキル・バフ・デバフ設計</li>
      <li>AI・NPCシステム（大規模NPC管理、コンパニオンAI）</li>
      <li>キャラクター＆アニメーションパイプライン構築</li>
      <li>リアルタイムパフォーマンス最適化</li>
      <li>マルチプレイヤー対応・レプリケーション設計</li>
    </ul>
    <div class="sv-tags">
      <span class="sv-tag">Unreal Engine 5</span>
      <span class="sv-tag">C++</span>
      <span class="sv-tag">Blueprints</span>
      <span class="sv-tag">GAS</span>
      <span class="sv-tag">AI</span>
      <span class="sv-tag">Multiplayer</span>
    </div>
  </div>
</div>

<!-- Service 2 -->
<div class="sv-block reverse">
  <div class="sv-block-visual">
    <div class="sv-block-icon"><i class="fas fa-comments"></i></div>
  </div>
  <div class="sv-block-meta">
    <div class="category">Consulting</div>
    <h2>UE5<br>テクニカルコンサルティング</h2>
    <p>社内でUE5開発を進めているチーム・スタジオを対象に、技術的な課題解決と意思決定をサポートします。アーキテクチャ設計の相談からコードレビュー、特定システムの改善提案まで、短期集中型のエンゲージメントで対応します。</p>
    <ul class="sv-list">
      <li>アーキテクチャレビュー・設計相談</li>
      <li>コードレビュー・品質改善提案</li>
      <li>GAS・AIシステムの設計指導</li>
      <li>パフォーマンスボトルネック調査・改善</li>
      <li>技術選定・第三者評価</li>
    </ul>
    <div class="sv-tags">
      <span class="sv-tag">コンサルティング</span>
      <span class="sv-tag">アーキテクチャ</span>
      <span class="sv-tag">コードレビュー</span>
      <span class="sv-tag">UE5</span>
    </div>
  </div>
</div>

<!-- Philosophy -->
<div class="sv-philosophy">
  <h3>私たちの考え方</h3>
  <p>技術力だけでなく、プロジェクトの目標と課題を深く理解した上で開発に臨みます。クライアントとともに考え、最適な解を提案する——それが私たちの開発スタイルです。</p>
</div>

<!-- Process -->
<div class="sv-process">
  <h2>進め方</h2>
  <div class="sv-steps">
    <div class="sv-step">
      <div class="sv-step-inner">
        <span class="num">01</span>
        <span class="name">ヒアリング</span>
      </div>
    </div>
    <span class="sv-arrow">›</span>
    <div class="sv-step">
      <div class="sv-step-inner">
        <span class="num">02</span>
        <span class="name">要件定義</span>
      </div>
    </div>
    <span class="sv-arrow">›</span>
    <div class="sv-step">
      <div class="sv-step-inner">
        <span class="num">03</span>
        <span class="name">設計・実装</span>
      </div>
    </div>
    <span class="sv-arrow">›</span>
    <div class="sv-step">
      <div class="sv-step-inner">
        <span class="num">04</span>
        <span class="name">テスト・QA</span>
      </div>
    </div>
    <span class="sv-arrow">›</span>
    <div class="sv-step">
      <div class="sv-step-inner">
        <span class="num">05</span>
        <span class="name">納品・保守</span>
      </div>
    </div>
  </div>
</div>

<!-- CTA -->
<div class="sv-cta">
  <p>プロジェクトのご相談、お見積もりのご依頼はお気軽にどうぞ。<br>まずはお話を聞かせてください。</p>
  <a href="/marcode_aulinux/contact/">お問い合わせ</a>
</div>
