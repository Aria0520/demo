<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>展期功能 APP 原型图 v3.0 · 中西对照 · HolaFina</title>
<style>
* { margin:0; padding:0; box-sizing:border-box; -webkit-font-smoothing:antialiased; }
t { display:inline; }
body { font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif; background:#eef1f5; color:#1a1a1a; }

/* ═══ 顶部栏 ═══ */
.topbar { background:#fff; border-bottom:1px solid #e4e8ee; padding:14px 28px; display:flex; align-items:center; justify-content:space-between; position:sticky; top:0; z-index:200; box-shadow:0 1px 3px rgba(0,0,0,.04); }
.topbar h1 { font-size:17px; font-weight:700; display:flex; align-items:center; gap:8px; }
.topbar .meta { font-size:12px; color:#8a939e; }

/* ═══ 页签 ═══ */
.tabs { background:#fff; border-bottom:1px solid #e4e8ee; padding:0 28px; display:flex; overflow-x:auto; position:sticky; top:53px; z-index:199; }
.tabs::-webkit-scrollbar { height:0; }
.tab { padding:13px 18px; cursor:pointer; font-size:13px; color:#69727d; border-bottom:2.5px solid transparent; white-space:nowrap; transition:.18s; font-weight:500; }
.tab:hover { color:#0a84ff; }
.tab.active { color:#0a84ff; border-bottom-color:#0a84ff; font-weight:600; }
.badge { display:inline-block; font-size:9px; padding:2px 6px; border-radius:4px; margin-left:6px; font-weight:600; }
.badge.app { background:#e5f2ff; color:#0a84ff; }
.badge.cs { background:#f3e8ff; color:#8b5cf6; }

/* ═══ 主区 ═══ */
.stage { display:none; padding:24px 28px 40px; }
.stage.active { display:block; }
.stage-inner { display:flex; gap:26px; align-items:flex-start; }

/* ═══ 双语对照容器 ═══ */
.pair { display:flex; gap:22px; flex-shrink:0; }
.ph-wrap { display:flex; flex-direction:column; align-items:center; }
.ph-lbl { font-size:12.5px; font-weight:700; padding:6px 18px; border-radius:16px; margin-bottom:13px; display:flex; align-items:center; gap:6px; white-space:nowrap; }
.ph-lbl.zh { background:#fff1f0; color:#d4380d; border:1.4px solid #ffc9c5; }
.ph-lbl.es { background:#e8f9ed; color:#1da750; border:1.4px solid #bfe9cd; }

/* ═══ iPhone ═══ */
.iphone { width:352px; min-width:352px; background:#000; border-radius:42px; padding:9px; box-shadow:0 20px 56px rgba(0,0,0,.26), 0 0 0 2px #2c2c2e; }
.screen { background:#fff; border-radius:34px; overflow:hidden; height:790px; display:flex; flex-direction:column; position:relative; }

.statusbar { height:42px; display:flex; align-items:flex-end; justify-content:space-between; padding:0 24px 7px; flex-shrink:0; z-index:5; }
.statusbar .t { font-size:14.5px; font-weight:600; letter-spacing:-.2px; }
.statusbar .r { display:flex; align-items:center; gap:5px; }
.sig { display:flex; align-items:flex-end; gap:2px; }
.sig i { width:3px; background:#000; border-radius:1px; display:block; }
.sig i:nth-child(1){height:4px} .sig i:nth-child(2){height:6px} .sig i:nth-child(3){height:8px} .sig i:nth-child(4){height:10px}
.batt { width:23px; height:11.5px; border:1.4px solid #000; border-radius:3px; position:relative; padding:1.3px; }
.batt::after { content:''; position:absolute; right:-3.5px; top:3.2px; width:2px; height:4px; background:#000; border-radius:0 1px 1px 0; }
.batt i { display:block; height:100%; width:85%; background:#000; border-radius:1.3px; }

.body { flex:1; overflow-y:auto; background:#f4f6f9; }
.body::-webkit-scrollbar { width:0; }

.tabbar { height:72px; background:#fff; border-top:1px solid #eef0f3; display:flex; padding-bottom:16px; flex-shrink:0; }
.tabbar .it { flex:1; display:flex; flex-direction:column; align-items:center; justify-content:center; gap:3px; cursor:pointer; }
.tabbar .ic { width:25px; height:25px; border-radius:8px; display:flex; align-items:center; justify-content:center; font-size:12.5px; color:#b0b8c1; background:#f2f4f7; }
.tabbar .it.on .ic { background:#0a84ff; color:#fff; }
.tabbar .lb { font-size:9.5px; color:#b0b8c1; font-weight:500; }
.tabbar .it.on .lb { color:#0a84ff; font-weight:600; }
.homebar { position:absolute; bottom:7px; left:50%; transform:translateX(-50%); width:126px; height:5px; background:#000; border-radius:3px; opacity:.85; }

.actionbar { background:#fff; border-top:1px solid #eef0f3; padding:11px 15px 24px; flex-shrink:0; }
.btn-lg { width:100%; height:48px; border-radius:24px; border:none; font-size:15.5px; font-weight:700; cursor:pointer; transition:.18s; }
.btn-lg.orange { background:#ff6a13; color:#fff; box-shadow:0 4px 13px rgba(255,106,19,.3); }
.btn-lg.orange:hover { background:#f05f0a; }
.btn-lg.blue { background:#0a84ff; color:#fff; box-shadow:0 4px 13px rgba(10,132,255,.28); }
.btn-lg.ghost { background:#fff; color:#0a84ff; border:1.6px solid #0a84ff; box-shadow:none; margin-top:8px; }

/* ═══ 我的账户与借据历史 ═══ */
.account-body { background:#f1f5fd; padding:0 14px 18px; }
.account-head { text-align:center; padding:17px 0 16px; }
.account-avatar { width:58px; height:58px; border-radius:50%; margin:0 auto 8px; background:linear-gradient(135deg,#ff9a76,#ffcfb0); border:2px solid #0a84ff; display:flex; align-items:center; justify-content:center; font-size:29px; }
.account-phone { font-size:12px; color:#1f2937; font-weight:700; }
.account-greet { font-size:23px; color:#ff4d26; font-weight:900; margin-top:8px; }
.account-tabs { display:flex; gap:10px; margin-bottom:12px; }
.account-tab { flex:1; background:#fff; border-radius:14px; padding:13px 12px; font-size:12px; font-weight:700; box-shadow:0 1px 4px rgba(0,0,0,.04); }
.account-tab.active { border:2px solid #1890ff; padding:11px 10px; }
.account-tab .num { color:#ff4d26; font-size:14px; margin-top:3px; }
.account-limit { background:#fff; border-radius:14px; padding:13px; display:flex; align-items:center; justify-content:space-between; margin-bottom:12px; }
.account-limit .label { font-size:11px; color:#69727d; }
.account-limit .amount { font-size:20px; font-weight:800; margin-top:3px; }
.account-limit .arrow { width:31px; height:31px; border-radius:9px; background:#0a84ff; color:#fff; display:flex; align-items:center; justify-content:center; font-size:20px; }
.account-section { background:#fff; border-radius:14px; padding:14px 13px; margin-bottom:12px; }
.account-section-title { font-size:15px; font-weight:800; margin-bottom:13px; }
.account-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:15px 8px; }
.account-item { text-align:center; color:#4b5563; font-size:10px; cursor:pointer; }
.account-item .icon { width:34px; height:34px; border-radius:50%; background:#f1f4f8; display:flex; align-items:center; justify-content:center; margin:0 auto 6px; font-size:17px; }
.account-item.active .icon { background:#e5f2ff; color:#0a84ff; }
.account-item.active { color:#0a84ff; font-weight:700; }
.account-menu { background:#fff; border-radius:14px; padding:7px 13px; }
.account-menu-row { display:flex; align-items:center; justify-content:space-between; padding:13px 0; border-bottom:1px solid #f0f2f5; font-size:12px; color:#374151; }
.account-menu-row:last-child { border-bottom:none; }
.account-menu-row .arrow { color:#9aa3ad; font-size:17px; }
.account-footer { text-align:center; color:#a8b0b9; font-size:10px; padding:25px 0 13px; line-height:1.6; }
.history-body { background:#f1f5fd; padding:13px 17px 20px; }
.history-nav { height:48px; display:flex; align-items:center; justify-content:space-between; background:#fff; padding:0 16px; flex-shrink:0; }
.history-nav .back { font-size:25px; color:#27313d; cursor:pointer; }
.history-nav .title { font-size:18px; font-weight:800; }
.history-nav .head-icon { font-size:20px; color:#27313d; }
.history-card { background:#fff; border-radius:17px; padding:15px 17px; margin-bottom:13px; box-shadow:0 1px 4px rgba(0,0,0,.035); cursor:pointer; transition:transform .16s, box-shadow .16s; }
.history-card:hover { transform:translateY(-1px); box-shadow:0 4px 12px rgba(10,132,255,.12); }
.history-card .top { display:flex; align-items:center; justify-content:space-between; border-bottom:1px solid #edf0f3; padding-bottom:10px; }
.history-card .label { font-size:13px; font-weight:700; color:#344054; }
.history-card .period-link { color:#0a84ff; font-size:13px; font-weight:700; }
.history-card .loan-no { color:#5a7ca8; font-size:11px; font-weight:700; margin-top:9px; letter-spacing:.2px; }
.history-card .money { font-size:25px; font-weight:800; color:#202733; margin-top:8px; }
.history-card .date { font-size:11.5px; color:#69727d; margin-top:6px; }
.history-card .old { color:#a8b0b9; text-decoration:line-through; margin-left:7px; font-size:12px; }
.history-card .info { color:#a8b0b9; display:inline-flex; width:14px; height:14px; border-radius:50%; background:#e4e8ee; align-items:center; justify-content:center; font-size:9px; margin-left:3px; }
.loan-summary .row { padding:6px 0; }
.loan-plan { background:#fff; }
.loan-plan .plan-subtitle { color:#8a939e; font-size:10.5px; margin:-5px 0 10px; line-height:1.45; }
.loan-plan-row { border:1px solid #eef0f3; border-radius:9px; padding:9px 10px; margin-bottom:7px; background:#fafbfc; }
.loan-plan-row:last-child { margin-bottom:0; }
.loan-plan-row .plan-top { display:flex; align-items:center; justify-content:space-between; gap:8px; font-size:11.5px; font-weight:700; color:#2c333d; }
.loan-plan-row .plan-date { color:#5a7ca8; font-weight:700; white-space:nowrap; }
.loan-plan-row .plan-bottom { display:flex; align-items:center; justify-content:space-between; margin-top:6px; font-size:10.5px; color:#8a939e; }
.loan-plan-row .plan-bottom b { color:#2c333d; font-size:12px; }
.loan-plan-row .plan-bottom .paid { color:#1da750; }

.hf-head { padding:3px 17px 13px; background:linear-gradient(175deg,#eaf4ff 0%,#f4f6f9 78%); position:relative; overflow:hidden; }
.hf-head::after { content:''; position:absolute; right:-40px; top:-56px; width:165px; height:165px; border-radius:50%; background:radial-gradient(circle,rgba(10,132,255,.09),transparent 68%); }
.hf-brand { display:flex; align-items:flex-start; justify-content:space-between; position:relative; z-index:2; }
.hf-logo { font-size:24px; font-weight:800; letter-spacing:-.7px; }
.hf-logo .a { color:#111; } .hf-logo .b { color:#0a84ff; }
.hf-swoosh { height:5px; width:70px; margin-top:-1px; border-radius:3px; background:linear-gradient(90deg,#ffb020,#ff6a13); }
.hf-slogan { font-size:11px; color:#7c848f; margin-top:6px; display:flex; align-items:center; gap:4px; }
.hf-icons { display:flex; gap:13px; align-items:center; padding-top:4px; }
.hf-ic { width:25px; height:25px; display:flex; align-items:center; justify-content:center; font-size:16px; color:#3b4350; position:relative; cursor:pointer; }
.hf-dot { position:absolute; top:-3px; right:-6px; background:#ff3b30; color:#fff; font-size:8.5px; font-weight:700; min-width:16px; height:16px; border-radius:8px; display:flex; align-items:center; justify-content:center; padding:0 4px; border:1.5px solid #f4f6f9; }

.promo { margin:13px 17px 0; background:linear-gradient(118deg,#1a8fff,#0a6ede); border-radius:15px; padding:14px 15px 15px; color:#fff; box-shadow:0 7px 20px rgba(10,110,222,.28); position:relative; overflow:hidden; }
.promo::before { content:''; position:absolute; right:-24px; bottom:-34px; width:104px; height:104px; border-radius:50%; background:rgba(255,255,255,.1); }
.promo-top { display:flex; align-items:center; justify-content:space-between; gap:8px; position:relative; z-index:2; }
.promo-q { font-size:15.5px; font-weight:800; line-height:1.25; }
.timer { display:flex; align-items:center; gap:3px; flex-shrink:0; }
.timer b { background:rgba(0,0,0,.26); border-radius:5px; padding:3px 5px; font-size:11px; font-weight:700; min-width:22px; text-align:center; }
.timer i { font-size:10.5px; font-weight:700; opacity:.9; font-style:normal; }
.promo-sub { font-size:11px; opacity:.94; margin-top:6px; line-height:1.45; position:relative; z-index:2; }
.promo-btn { width:100%; height:38px; background:#fff; color:#0a6ede; border:none; border-radius:19px; font-size:14px; font-weight:700; margin-top:11px; cursor:pointer; position:relative; z-index:2; }

.pend { padding:20px 17px 0; }
.pend-h { font-size:23px; font-weight:800; line-height:1.26; letter-spacing:-.5px; }
.pend-amt { display:flex; align-items:baseline; gap:8px; margin-top:11px; }
.pend-amt .n { font-size:39px; font-weight:800; letter-spacing:-1.5px; line-height:1; }
.pend-amt .ar { font-size:21px; color:#9aa3ad; font-weight:400; }
.pend-due { font-size:12px; color:#6d7580; margin-top:8px; }
.pend-due .late { color:#ff3b30; font-weight:600; }

.waiver { margin:13px 17px 0; background:#fff8e8; border:1px solid #ffe4ab; border-radius:11px; padding:10px 12px; display:flex; align-items:center; gap:9px; }
.waiver .ic { width:25px; height:25px; border-radius:7px; background:linear-gradient(135deg,#ffc53d,#ff9500); color:#fff; display:flex; align-items:center; justify-content:center; font-size:12.5px; font-weight:800; flex-shrink:0; }
.waiver .tx { flex:1; font-size:11px; color:#8a5a00; line-height:1.4; }
.waiver .lk { font-size:11px; color:#ff8c00; font-weight:700; white-space:nowrap; cursor:pointer; }

.dual { display:flex; gap:10px; margin:13px 17px 0; }
.dual button { flex:1; height:45px; border-radius:23px; font-size:13.5px; font-weight:700; cursor:pointer; border:none; padding:0 4px; }
.dual .w { background:#fff; color:#2c333d; border:1.4px solid #e2e6eb; }
.dual .o { background:#ff6a13; color:#fff; box-shadow:0 4px 13px rgba(255,106,19,.28); }
.pend-help { text-align:center; font-size:11.5px; color:#6d7580; margin-top:12px; cursor:pointer; }

.sec-t { font-size:19px; font-weight:800; padding:24px 17px 11px; letter-spacing:-.4px; }
.credit { margin:0 17px; background:#eaf3ff; border-radius:14px; padding:14px 15px; }
.credit-r { display:flex; align-items:center; justify-content:space-between; gap:8px; }
.credit .lb { font-size:11px; color:#5d7fa8; }
.credit .n { font-size:25px; font-weight:800; margin-top:2px; letter-spacing:-.7px; }
.credit .b { height:36px; padding:0 15px; background:#0a84ff; color:#fff; border:none; border-radius:18px; font-size:12.5px; font-weight:700; cursor:pointer; white-space:nowrap; }
.credit-tip { font-size:10.5px; color:#5d7fa8; padding:8px 17px 0; line-height:1.5; }

.safe { margin:0 17px; background:linear-gradient(112deg,#e9e4ff,#f2effe); border-radius:14px; padding:14px 15px; display:flex; align-items:center; gap:11px; }
.safe .tx { flex:1; }
.safe .h { font-size:13.5px; font-weight:800; color:#2c2361; }
.safe .d { font-size:10.5px; color:#5b5090; margin-top:4px; line-height:1.5; }
.safe .em { font-size:35px; }

.adv { display:flex; padding:4px 17px 0; }
.adv .it { flex:1; text-align:center; }
.adv .c { width:45px; height:45px; border-radius:50%; background:#f0f3f7; display:flex; align-items:center; justify-content:center; margin:0 auto 7px; font-size:18px; }
.adv .l { font-size:10px; color:#6d7580; line-height:1.4; }
.fmark { text-align:center; padding:28px 0 20px; }
.fmark .l { font-size:20px; font-weight:800; color:#dde2e9; letter-spacing:-.6px; }
.fmark .s { font-size:10.5px; color:#e2e7ed; margin-top:3px; }

/* ═══ 展期入口 ═══ */
.ext-entry { margin:15px 17px 0; background:#fff; border:1.6px solid #bcdcff; border-radius:15px; padding:13px 14px; display:flex; align-items:center; gap:11px; cursor:pointer; box-shadow:0 3px 13px rgba(10,132,255,.1); transition:.2s; position:relative; overflow:hidden; }
.ext-entry:hover { border-color:#0a84ff; box-shadow:0 6px 19px rgba(10,132,255,.18); transform:translateY(-1px); }
.ext-entry::after { content:''; position:absolute; right:-30px; top:-30px; width:92px; height:92px; border-radius:50%; background:radial-gradient(circle,rgba(10,132,255,.08),transparent 70%); }
.ext-ic { width:42px; height:42px; border-radius:12px; background:linear-gradient(140deg,#2b9bff,#0a6ede); color:#fff; display:flex; align-items:center; justify-content:center; font-size:20px; flex-shrink:0; box-shadow:0 4px 10px rgba(10,110,222,.3); }
.ext-tx { flex:1; position:relative; z-index:2; min-width:0; }
.ext-h { font-size:13.5px; font-weight:800; color:#11305c; display:flex; align-items:center; gap:6px; flex-wrap:wrap; }
.ext-pill { background:#ff6a13; color:#fff; font-size:8.5px; font-weight:700; padding:2px 5px; border-radius:4px; }
/* 展期入口倒计时 */
.ext-cd { display:inline-flex; align-items:center; gap:2px; margin-left:4px; flex-shrink:0; }
.ext-cd b { background:rgba(10,110,222,.12); color:#0a6ede; font-size:9.5px; font-weight:800; padding:1.5px 4px; border-radius:3px; min-width:18px; text-align:center; line-height:1.3; }
.ext-cd i { font-style:normal; font-size:9px; color:#5a7ca8; font-weight:700; }
.ext-d { font-size:10.5px; color:#5a7ca8; margin-top:4px; line-height:1.45; }
.ext-ar { color:#0a84ff; font-size:20px; font-weight:300; position:relative; z-index:2; }

/* ═══ 还款页 ═══ */
.rp-nav { height:46px; display:flex; align-items:center; padding:0 15px; background:#fff; flex-shrink:0; border-bottom:1px solid #f0f2f5; }
.rp-nav .bk { font-size:22px; color:#2c333d; cursor:pointer; width:26px; font-weight:300; }
.rp-tabs { flex:1; display:flex; justify-content:center; gap:32px; }
.rp-tab { font-size:15.5px; color:#9aa3ad; font-weight:600; cursor:pointer; position:relative; padding-bottom:3px; }
.rp-tab.on { color:#111; font-weight:800; }
.rp-tab.on::after { content:''; position:absolute; bottom:-2px; left:50%; transform:translateX(-50%); width:22px; height:3.5px; background:linear-gradient(90deg,#ffb020,#ff6a13); border-radius:2px; }
.rp-nav .qm { width:23px; height:23px; border-radius:50%; border:1.5px solid #c8cfd7; color:#8a939e; display:flex; align-items:center; justify-content:center; font-size:12px; cursor:pointer; flex-shrink:0; }

.plan-head { display:flex; align-items:center; justify-content:space-between; padding:18px 17px 5px; gap:8px; }
.plan-head .t { font-size:19.5px; font-weight:800; letter-spacing:-.4px; }
.plan-head .pre { font-size:11.5px; color:#5d6570; cursor:pointer; white-space:nowrap; }
.disc-pill { display:inline-flex; align-items:center; gap:4px; background:#ffeadd; color:#e2590c; font-size:10.5px; font-weight:700; padding:4px 10px; border-radius:11px; margin:0 17px 11px; }
.mon { display:flex; align-items:center; gap:8px; padding:11px 17px 8px; }
.mon .bar { width:3.5px; height:14px; background:#0a84ff; border-radius:2px; }
.mon .tx { font-size:14px; font-weight:800; }
.inst { margin:0 17px 8px; background:#fff; border-radius:12px; padding:12px 14px; display:flex; align-items:center; gap:11px; box-shadow:0 1px 4px rgba(0,0,0,.045); }
.inst-l { flex:1; min-width:0; }
.inst-d { font-size:11px; color:#8a939e; }
.inst-d .late { color:#ff3b30; font-weight:600; }
.inst-d .today { color:#34c759; font-weight:600; }
.inst-d .left { color:#0a84ff; font-weight:600; }
.inst-a { font-size:18.5px; font-weight:800; margin-top:5px; display:flex; align-items:center; gap:5px; letter-spacing:-.4px; }
.inst-a .ar { color:#c8cfd7; font-size:14px; font-weight:400; }
.inst-was { font-size:11px; color:#a8b0b9; text-decoration:line-through; margin-top:3px; }
/* 还款页分期项：两行布局 */
.inst-top { font-size:12px; font-weight:700; color:#2c333d; display:flex; align-items:center; gap:5px; margin-bottom:4px; }
.inst-top .inst-id { color:#5a7ca8; font-weight:600; letter-spacing:.3px; font-size:12px; }
.inst-top .inst-term { color:#8a939e; font-size:11px; font-weight:500; }

/* 还款页分组卡：同一借据编号下多个期次 */
.loan-grp { margin:0 17px 9px; background:#fff; border-radius:13px; box-shadow:0 1px 4px rgba(0,0,0,.045); overflow:hidden; }
.loan-grp-h { display:flex; align-items:center; justify-content:space-between; padding:11px 14px 8px; border-bottom:1px solid #f4f6f9; }
.loan-grp-h .gid { font-size:13px; font-weight:800; color:#2c333d; letter-spacing:.2px; }
.loan-grp-h .ginfo { font-size:10.5px; color:#8a939e; }
.loan-grp .inst { margin:0; border-radius:0; box-shadow:none; border-bottom:1px solid #f4f6f9; padding:11px 14px; }
.loan-grp .inst:last-child { border-bottom:none; }
.inst-term2 { display:inline-flex; align-items:center; justify-content:center; height:18px; background:#eef2f7; color:#5a7ca8; font-size:10px; font-weight:700; border-radius:4px; padding:0 6px; margin-right:6px; flex-shrink:0; white-space:nowrap; letter-spacing:.2px; }
.rad { width:22px; height:22px; border-radius:50%; border:1.8px solid #dde2e9; flex-shrink:0; }
.rad.on { background:#0a84ff; border-color:#0a84ff; position:relative; }
.rad.on::after { content:'✓'; position:absolute; inset:0; display:flex; align-items:center; justify-content:center; color:#fff; font-size:12px; font-weight:800; }
.rad.half { background:#a8d4ff; border-color:#a8d4ff; position:relative; }
.rad.half::after { content:'✓'; position:absolute; inset:0; display:flex; align-items:center; justify-content:center; color:#fff; font-size:12px; font-weight:800; }
.refl { text-align:center; font-size:11px; color:#8a939e; padding:8px 17px 0; }
.refl .lk { color:#0a84ff; font-weight:600; cursor:pointer; }
.save-bar { background:#fffce4; padding:9px 17px; font-size:11px; color:#7d6a00; text-align:center; margin-top:13px; }
.pay-bar { background:#fff; padding:12px 15px 24px; display:flex; align-items:center; gap:12px; border-top:1px solid #f0f2f5; flex-shrink:0; }
/* 一级页面：支付栏上方叠 TabBar 时，去掉为 homebar 预留的底部留白 */
.pay-bar.tabbar-above { padding-bottom:12px; }
.nav-pad { width:26px; flex-shrink:0; }
/* 还款页固定区：常驻顶部，不随内容滚动 */
.rp-sticky { flex-shrink:0; background:#f4f6f9; padding:12px 0 13px; box-shadow:0 3px 8px -4px rgba(0,0,0,.12); position:relative; z-index:3; }
.rp-sticky .promo { margin-top:0; }
.rp-sticky .ext-entry:first-child { margin-top:0; }
.rp-sticky + .body { padding-top:2px; }

/* ═══ Banner 轮播 ═══ */
.car-track {
  display:flex; overflow-x:auto; scroll-snap-type:x mandatory;
  scrollbar-width:none; -ms-overflow-style:none; cursor:grab;
  scroll-behavior:smooth; align-items:stretch;
}
.car-track::-webkit-scrollbar { display:none; }
.car-track.dragging { cursor:grabbing; scroll-snap-type:none; scroll-behavior:auto; }
.car-slide { flex:0 0 100%; scroll-snap-align:center; display:flex; align-items:center; padding:0 17px; }
/* 轮播内的卡片交由 slide 控制左右间距 */
.car-slide > .promo, .car-slide > .ext-entry { margin:0; width:100%; }
.car-dots { display:flex; justify-content:center; align-items:center; gap:6px; margin-top:10px; }
.dot { width:6px; height:6px; border-radius:3px; background:#d5dae0; transition:width .22s, background .22s; cursor:pointer; flex-shrink:0; }
.dot.on { width:18px; background:#0a84ff; }
/* 单页时隐藏指示点 */
.car-dots.single { display:none; }

/* ═══ 一屏方案页：紧凑组件 ═══ */
/* 紧凑借据行 */
.lrow { display:flex; align-items:center; gap:10px; padding:10px 11px; background:#fafbfc; border:1.6px solid #e8ebef; border-radius:11px; margin-bottom:8px; cursor:pointer; transition:.16s; }
.lrow:hover { border-color:#bcdcff; }
.lrow.on { border-color:#0a84ff; background:#f0f7ff; }
.lrow .cb2 { width:19px; height:19px; border-radius:50%; border:1.9px solid #d5dae0; background:#fff; flex-shrink:0; position:relative; }
.lrow.on .cb2 { background:#0a84ff; border-color:#0a84ff; }
.lrow.on .cb2::after { content:'✓'; position:absolute; inset:0; display:flex; align-items:center; justify-content:center; color:#fff; font-size:11px; font-weight:800; }
.lrow .mid { flex:1; min-width:0; }
.lrow .l1 { font-size:12.5px; font-weight:800; display:flex; align-items:center; gap:5px; flex-wrap:wrap; }
.lrow .l2 { font-size:10.5px; color:#8a939e; margin-top:3px; display:flex; align-items:center; gap:5px; }
.lrow .l2 .o { text-decoration:line-through; }
.lrow .l2 .n { color:#0a84ff; font-weight:700; }
.lrow .amt { font-size:13px; font-weight:800; color:#2c333d; white-space:nowrap; }

/* 方案总览：核心数字 */
.hero { background:linear-gradient(160deg,#f0f7ff,#fafcff); border:1.6px solid #d6e9ff; border-radius:14px; padding:15px; }
.hero-lb { font-size:11px; color:#5a7ca8; }
.hero-date { font-size:25px; font-weight:800; color:#0a6ede; letter-spacing:-.6px; margin-top:3px; }
.hero-sub { font-size:10.5px; color:#7c9bc4; margin-top:3px; }
.hero-hr { height:1px; background:#d6e9ff; margin:12px 0; }
.hero-total { display:flex; justify-content:space-between; align-items:flex-end; }
.hero-total .k { font-size:12.5px; color:#5a7ca8; font-weight:600; }
.hero-total .v { font-size:27px; font-weight:800; color:#ff6a13; letter-spacing:-.8px; line-height:1; }
.detail-link { display:flex; align-items:center; justify-content:center; gap:5px; margin-top:12px; padding:9px; background:#fff; border:1.4px solid #bcdcff; border-radius:9px; font-size:12px; color:#0a6ede; font-weight:700; cursor:pointer; transition:.16s; }
.detail-link:hover { background:#e5f2ff; border-color:#0a84ff; }

/* 底部协议+按钮紧凑区 */
.ab-agree { display:flex; gap:8px; align-items:flex-start; font-size:10.5px; color:#6d7580; line-height:1.45; margin-bottom:10px; }
.ab-agree input { margin-top:1px; width:14px; height:14px; accent-color:#0a84ff; flex-shrink:0; }
.ab-agree a { color:#0a84ff; text-decoration:none; font-weight:600; }

/* ═══ 天数加减器 Stepper ═══ */
.stepper-wrap { display:flex; align-items:center; justify-content:center; gap:0; background:#fafbfc; border:1.6px solid #e8ebef; border-radius:11px; padding:4px 6px; }
.step-btn { width:42px; height:42px; border:none; background:transparent; font-size:22px; font-weight:400; color:#0a84ff; cursor:pointer; border-radius:8px; display:flex; align-items:center; justify-content:center; transition:.14s; user-select:none; flex-shrink:0; }
.step-btn:hover { background:#e5f2ff; }
.step-btn:active { background:#bcdcff; }
.step-inp { width:54px; height:42px; border:none; background:transparent; font-size:22px; font-weight:800; color:#2c333d; text-align:center; outline:none; padding:0; -moz-appearance:textfield; flex-shrink:0; }
.step-inp::-webkit-outer-spin-button, .step-inp::-webkit-inner-spin-button { -webkit-appearance:none; }
.step-unit { font-size:13px; color:#8a939e; font-weight:600; margin-right:6px; }

/* ═══ 底部上滑弹窗 Bottom Sheet ═══ */
.sheet-mask { position:absolute; inset:0; background:rgba(0,0,0,.42); opacity:0; pointer-events:none; transition:opacity .26s; z-index:20; }
.sheet-mask.on { opacity:1; pointer-events:auto; }
.sheet { position:absolute; left:0; right:0; bottom:0; background:#fff; border-radius:20px 20px 0 0; z-index:21; transform:translateY(102%); transition:transform .3s cubic-bezier(.32,.72,0,1); max-height:74%; display:flex; flex-direction:column; box-shadow:0 -6px 24px rgba(0,0,0,.14); }
.sheet.on { transform:translateY(0); }
.sheet-grab { width:36px; height:4px; background:#dde2e9; border-radius:2px; margin:9px auto 0; flex-shrink:0; }
.sheet-h { padding:12px 17px 11px; border-bottom:1px solid #f0f2f5; font-size:15px; font-weight:800; flex-shrink:0; display:flex; align-items:center; justify-content:space-between; }
.sheet-x { width:24px; height:24px; border-radius:50%; background:#f2f4f7; color:#8a939e; display:flex; align-items:center; justify-content:center; font-size:14px; cursor:pointer; flex-shrink:0; }
.sheet-b { overflow-y:auto; padding:13px 17px 0; flex:1; }
.sheet-b::-webkit-scrollbar { width:0; }
.sheet-f { padding:12px 17px 24px; flex-shrink:0; }
.sheet-f button { width:100%; height:46px; border-radius:23px; border:none; background:#0a84ff; color:#fff; font-size:15px; font-weight:700; cursor:pointer; }

/* 弹窗内明细块 */
.dblk { background:#fafbfc; border-radius:11px; padding:12px; margin-bottom:9px; }
.dblk-h { font-size:12.5px; font-weight:800; margin-bottom:8px; display:flex; align-items:center; justify-content:space-between; }
.period-change { padding:7px 8px; background:#fff; border:1px solid #eef0f3; border-radius:7px; margin-bottom:6px; }
.period-main { display:flex; align-items:center; gap:7px; }
.period-badge { min-width:31px; height:18px; display:inline-flex; align-items:center; justify-content:center; border-radius:4px; padding:0 5px; background:#eef2f7; color:#5a7ca8; font-size:10px; font-weight:700; flex-shrink:0; }
.period-before { color:#8a939e; font-size:11.5px; text-decoration:line-through; white-space:nowrap; }
.period-arrow { color:#0a84ff; font-size:12px; font-weight:700; }
.period-after { color:#0a84ff; font-size:11.5px; font-weight:800; white-space:nowrap; }
.period-meta { display:flex; align-items:center; gap:6px; margin:5px 0 0 38px; }
.period-fee { color:#ff6a13; font-size:10.5px; font-weight:700; }
.period-hint { font-size:10px; color:#8a939e; margin:0 0 7px; }
.dsum { background:#fff8e8; border:1px solid #ffe4ab; border-radius:10px; padding:11px 12px; margin-bottom:11px; }
.dnote { font-size:10.5px; color:#8a939e; line-height:1.6; padding:2px 0 12px; }

/* ═══ 展期方案页支付时限简提示 ═══ */
.deadline-note { margin:0 17px 10px; padding:8px 10px; border-radius:8px; background:#fff8e8; color:#8a5a00; font-size:10.5px; line-height:1.45; text-align:center; }

/* ═══ 支付方式选择弹窗 ═══ */
.pay-sheet { position:absolute; left:0; right:0; bottom:0; background:#fff; border-radius:20px 20px 0 0; z-index:21; transform:translateY(102%); transition:transform .3s cubic-bezier(.32,.72,0,1); max-height:78%; display:flex; flex-direction:column; box-shadow:0 -6px 24px rgba(0,0,0,.14); }
.pay-sheet.on { transform:translateY(0); }
.pay-sheet-mask { position:absolute; inset:0; background:rgba(0,0,0,.42); opacity:0; pointer-events:none; transition:opacity .26s; z-index:20; }
.pay-sheet-mask.on { opacity:1; pointer-events:auto; }
.pay-sheet-h { padding:15px 17px 12px; font-size:20px; font-weight:800; display:flex; align-items:center; justify-content:space-between; flex-shrink:0; }
.pay-sheet-x { width:27px; height:27px; border-radius:50%; background:#f2f4f7; color:#69727d; display:flex; align-items:center; justify-content:center; font-size:16px; cursor:pointer; }
.pay-sheet-b { overflow-y:auto; padding:0 17px; flex:1; }
.pay-sheet-b::-webkit-scrollbar { width:0; }
.pay-method { position:relative; display:flex; align-items:center; gap:12px; padding:17px 13px; background:#f4f5f7; border-radius:18px; margin:0 0 12px; cursor:pointer; transition:.16s; border:1.5px solid transparent; }
.pay-method.selected { background:#e9f2ff; border-color:#bcdcff; }
.pay-method:hover { background:#e9f2ff; }
.pay-options .safety { font-size:11px; color:#8a939e; line-height:1.5; padding:4px 0 0; }
.pay-method .recommend { position:absolute; left:0; top:-1px; transform:translateY(-50%); background:#ff8500; color:#fff; font-size:10px; padding:4px 8px; border-radius:4px; font-weight:700; }
.pay-method .pm-icon { width:42px; height:42px; border-radius:11px; background:#fff; display:flex; align-items:center; justify-content:center; font-size:21px; flex-shrink:0; }
.pay-method .pm-info { flex:1; min-width:0; }
.pay-method .pm-name { font-size:16px; font-weight:800; color:#1e2530; }
.pay-method .pm-desc { font-size:12px; color:#8a939e; margin-top:4px; }
.pay-method .pm-fee { font-size:12px; color:#5c6673; margin-top:10px; }
.pay-method .pm-fee b { color:#ff8500; font-size:16px; }
.pay-method .pm-arrow { color:#46515e; font-size:24px; font-weight:300; }
.pay-sheet-foot { padding:7px 17px 27px; flex-shrink:0; }
.pay-sheet-foot .safety { font-size:11px; color:#8a939e; line-height:1.5; text-align:left; }

/* ═══ 离线部分支付处理中 Banner ═══ */
.partial-banner { margin:12px 17px 0; background:linear-gradient(118deg,#fff4e8,#fff9ed); border:1px solid #ffd8a8; border-radius:14px; padding:11px 12px; display:flex; align-items:center; gap:9px; cursor:pointer; box-shadow:0 3px 10px rgba(255,133,0,.08); }
.partial-banner .pb-icon { width:34px; height:34px; border-radius:10px; background:#ff8500; color:#fff; display:flex; align-items:center; justify-content:center; font-size:17px; flex-shrink:0; }
.partial-banner .pb-info { flex:1; min-width:0; }
.partial-banner .pb-title { color:#a84b00; font-size:13px; font-weight:800; }
.partial-banner .pb-detail { color:#8a5a00; font-size:10.5px; margin-top:4px; line-height:1.4; }
.partial-banner .pb-time { display:flex; align-items:center; gap:2px; margin-top:5px; }
.partial-banner .pb-time b { background:#ff8500; color:#fff; border-radius:3px; min-width:18px; padding:2px 3px; text-align:center; font-size:10px; }
.partial-banner .pb-time i { color:#d46b00; font-style:normal; font-size:10px; font-weight:700; }
.partial-banner .pb-arrow { color:#ff8500; font-size:21px; }

/* ═══ 支付页部分支付状态 ═══ */
.partial-payment { background:#fff4e8; border:1px solid #ffd8a8; border-radius:14px; padding:14px; margin:0 17px 12px; }
.partial-payment .pp-title { display:flex; align-items:center; justify-content:space-between; color:#a84b00; font-size:14px; font-weight:800; }
.partial-payment .pp-status { background:#ff8500; color:#fff; padding:3px 7px; border-radius:4px; font-size:10px; }
.partial-payment .pp-total { display:flex; align-items:baseline; justify-content:space-between; margin-top:10px; }
.partial-payment .pp-total .label { font-size:11px; color:#8a5a00; }
.partial-payment .pp-total .amount { font-size:22px; color:#2c333d; font-weight:900; }
.partial-payment .pp-progress-track { height:8px; background:#ffe0ba; border-radius:5px; overflow:hidden; margin:10px 0 12px; }
.partial-payment .pp-progress-fill { height:100%; width:60%; background:linear-gradient(90deg,#ff9b45,#ff8500); border-radius:5px; }
.partial-payment .pp-grid { display:grid; grid-template-columns:1fr 1fr; gap:8px; }
.partial-payment .pp-item { background:#fff; border-radius:8px; padding:9px; }
.partial-payment .pp-label { color:#8a939e; font-size:10.5px; }
.partial-payment .pp-value { color:#2c333d; font-size:17px; font-weight:800; margin-top:3px; }
.partial-payment .pp-value.orange { color:#ff8500; }
.partial-payment .pp-deadline { display:flex; align-items:center; justify-content:space-between; margin-top:11px; padding-top:9px; border-top:1px solid #ffe0ba; color:#8a5a00; font-size:10.5px; }
.partial-payment .pp-time { font-size:14px; font-weight:800; color:#ff8500; }
.partial-payment .pp-note { color:#8a5a00; font-size:10.5px; margin-top:7px; line-height:1.4; }
.payment-select-hint { margin:0 17px 12px; background:#f4f6f9; border-radius:13px; padding:14px; display:flex; align-items:center; justify-content:space-between; color:#69727d; font-size:12px; }
.payment-select-hint b { color:#0a84ff; font-size:13px; }
.pay-bar .l { flex:1; }
.pay-bar .lb { font-size:11px; color:#8a939e; }
.pay-bar .n { font-size:24px; font-weight:800; letter-spacing:-.7px; }
.pay-bar .b { height:46px; padding:0 38px; background:#ff6a13; color:#fff; border:none; border-radius:23px; font-size:15.5px; font-weight:700; cursor:pointer; box-shadow:0 4px 14px rgba(255,106,19,.3); white-space:nowrap; }

/* ═══ 通用组件 ═══ */
.card { background:#fff; margin:11px 17px; border-radius:14px; padding:15px; box-shadow:0 1px 4px rgba(0,0,0,.045); }
.card-t { font-size:14.5px; font-weight:800; margin-bottom:12px; letter-spacing:-.2px; }
.row { display:flex; justify-content:space-between; align-items:center; padding:5px 0; gap:10px; }
.row .k { font-size:12px; color:#8a939e; }
.row .v { font-size:12px; color:#2c333d; font-weight:600; text-align:right; }
.row .v.blue { color:#0a84ff; font-weight:800; }
.row .v.or { color:#ff6a13; font-weight:800; }
.row .v.big { font-size:15.5px; }
.hr { height:1px; background:#f0f2f5; margin:10px 0; }
.loan { background:#fafbfc; border:1.8px solid #e8ebef; border-radius:12px; padding:12px; margin-bottom:9px; cursor:pointer; transition:.18s; position:relative; }
.loan:hover { border-color:#bcdcff; }
.loan.on { border-color:#0a84ff; background:#f0f7ff; }
.loan .cb { position:absolute; right:12px; top:12px; width:20px; height:20px; border-radius:50%; border:1.9px solid #d5dae0; background:#fff; }
.loan.on .cb { background:#0a84ff; border-color:#0a84ff; }
.loan.on .cb::after { content:'✓'; position:absolute; inset:0; display:flex; align-items:center; justify-content:center; color:#fff; font-size:11px; font-weight:800; }
.loan-no { font-size:13px; font-weight:800; margin-bottom:8px; padding-right:28px; display:flex; align-items:center; gap:5px; flex-wrap:wrap; }
.tg { font-size:9px; padding:2px 5px; border-radius:4px; font-weight:700; white-space:nowrap; }
.tg.dpd { background:#ffeceb; color:#ff3b30; }
.tg.max { background:#e5f2ff; color:#0a84ff; }
.tg.ok { background:#e8f9ed; color:#1da750; }
.days { display:flex; gap:9px; margin-bottom:11px; }
.day { flex:1; height:42px; border-radius:10px; border:1.8px solid #e8ebef; background:#fff; font-size:13px; font-weight:700; color:#2c333d; cursor:pointer; transition:.18s; padding:0 2px; }
.day:hover:not(:disabled) { border-color:#0a84ff; color:#0a84ff; }
.day.on { border-color:#0a84ff; background:#e5f2ff; color:#0a6ede; }
.day:disabled { background:#f7f8fa; color:#ccd2d9; border-color:#f0f2f5; cursor:not-allowed; }
.inp-row { display:flex; gap:9px; align-items:center; }
.inp { flex:1; height:42px; border-radius:10px; border:1.8px solid #e8ebef; padding:0 12px; font-size:13.5px; font-weight:600; outline:none; }
.inp:focus { border-color:#0a84ff; }
.sfx { font-size:13px; color:#6d7580; font-weight:600; white-space:nowrap; }
.limit { font-size:11px; color:#e2590c; background:#fff5ed; border:1px solid #ffdcc2; padding:8px 10px; border-radius:9px; margin-top:9px; line-height:1.45; }
.calc { background:#fafbfc; border-radius:11px; padding:12px; margin-bottom:8px; }
.calc-no { font-size:12.5px; font-weight:800; margin-bottom:7px; }
.arrow-d { display:flex; align-items:center; gap:7px; margin:4px 0; flex-wrap:wrap; }
.arrow-d .od { font-size:12px; color:#8a939e; text-decoration:line-through; }
.arrow-d .ic { color:#0a84ff; font-size:12.5px; }
.arrow-d .nd { font-size:13px; color:#0a84ff; font-weight:800; }
.total { display:flex; justify-content:space-between; align-items:center; gap:10px; }
.total .k { font-size:14px; font-weight:800; }
.total .v { font-size:25px; font-weight:800; color:#ff6a13; letter-spacing:-.8px; }
.cd { text-align:center; font-size:11px; color:#8a939e; margin-top:10px; }
.cd b { color:#ff3b30; font-weight:800; }
.note { font-size:10px; color:#a8b0b9; text-align:center; margin-top:8px; line-height:1.5; }
.agree { display:flex; gap:8px; align-items:flex-start; margin-top:12px; font-size:11px; color:#6d7580; line-height:1.5; }
.agree input { margin-top:2px; width:14px; height:14px; accent-color:#0a84ff; flex-shrink:0; }
.agree a { color:#0a84ff; text-decoration:none; font-weight:600; }
.steps { display:flex; align-items:center; justify-content:center; padding:11px 10px; background:#fff; border-bottom:1px solid #f0f2f5; flex-shrink:0; }
.st { display:flex; align-items:center; font-size:9.5px; color:#c0c7cf; font-weight:600; white-space:nowrap; }
.st .d { width:18px; height:18px; border-radius:50%; border:1.6px solid #dde2e9; display:flex; align-items:center; justify-content:center; font-size:9px; margin-right:4px; flex-shrink:0; }
.st.on { color:#0a84ff; } .st.on .d { border-color:#0a84ff; background:#0a84ff; color:#fff; }
.st.dn { color:#1da750; } .st.dn .d { border-color:#1da750; background:#1da750; color:#fff; }
.ln { width:14px; height:1.6px; background:#e8ebef; margin:0 5px; flex-shrink:0; }
.pm { display:flex; align-items:center; gap:11px; padding:13px 12px; background:#fafbfc; border:1.8px solid #e8ebef; border-radius:12px; margin-bottom:8px; cursor:pointer; transition:.18s; }
.pm.on { border-color:#0a84ff; background:#f0f7ff; }
.pm .ic { width:38px; height:38px; border-radius:10px; background:#fff; border:1px solid #eef0f3; display:flex; align-items:center; justify-content:center; font-size:18px; flex-shrink:0; }
.pm .in { flex:1; min-width:0; }
.pm .n { font-size:13.5px; font-weight:700; }
.pm .d { font-size:10px; color:#8a939e; margin-top:2px; }
.pm .r { width:19px; height:19px; border-radius:50%; border:1.9px solid #d5dae0; flex-shrink:0; }
.pm.on .r { border-color:#0a84ff; background:#0a84ff; box-shadow:inset 0 0 0 3.5px #fff; }
.res-ic { text-align:center; margin:34px 0 16px; }
.res-ic .c { width:74px; height:74px; border-radius:50%; display:inline-flex; align-items:center; justify-content:center; font-size:36px; }
.res-ic .c.ok { background:#e8f9ed; color:#1da750; }
.res-ic .c.pr { background:#e5f2ff; color:#0a84ff; }
.res-ic .c.no { background:#ffeceb; color:#ff3b30; }
.res-ic .c.ex { background:#f4f6f9; color:#9aa3ad; }
.res-t { text-align:center; font-size:19px; font-weight:800; letter-spacing:-.3px; padding:0 20px; }
.res-s { text-align:center; font-size:12px; color:#8a939e; margin-top:6px; padding:0 28px; line-height:1.5; }
.switcher { display:flex; gap:6px; margin:15px 17px 0; flex-wrap:wrap; justify-content:center; }
.switcher button { font-size:10px; padding:5px 11px; border-radius:13px; cursor:pointer; font-weight:700; border:1.4px solid; background:#fff; }
.sw-ok { border-color:#1da750; color:#1da750; }
.sw-pr { border-color:#0a84ff; color:#0a84ff; }
.sw-no { border-color:#ff3b30; color:#ff3b30; }
.sw-ex { border-color:#9aa3ad; color:#9aa3ad; }

/* ═══ 右侧说明面板 ═══ */
.panel { flex:1; min-width:300px; }
.pcard { background:#fff; border-radius:13px; padding:18px; box-shadow:0 1px 5px rgba(0,0,0,.06); margin-bottom:14px; }
.pcard h3 { font-size:14px; font-weight:800; margin-bottom:11px; padding-bottom:9px; border-bottom:1.5px solid #f0f2f5; display:flex; align-items:center; gap:7px; }
.pcard h3::before { content:''; width:3.5px; height:14px; background:#0a84ff; border-radius:2px; flex-shrink:0; }
.pcard ul { list-style:none; }
.pcard li { font-size:12px; color:#525b66; line-height:1.8; padding-left:15px; position:relative; }
.pcard li::before { content:''; position:absolute; left:0; top:9px; width:5px; height:5px; border-radius:50%; background:#bcdcff; }
.pcard li strong { color:#2c333d; font-weight:700; }
.rt { display:inline-block; font-size:9.5px; padding:1.5px 6px; border-radius:4px; margin-left:4px; font-weight:700; }
.rt.r { background:#e5f2ff; color:#0a84ff; }
.rt.w { background:#fff5ed; color:#e2590c; }
.rt.g { background:#e8f9ed; color:#1da750; }
.i18n { background:#fff; border-radius:13px; padding:18px; box-shadow:0 1px 5px rgba(0,0,0,.06); }
.i18n h3 { font-size:14px; font-weight:800; margin-bottom:12px; padding-bottom:9px; border-bottom:1.5px solid #f0f2f5; }
.i18n table { width:100%; border-collapse:collapse; }
.i18n th { background:#f7f9fb; font-size:11px; font-weight:700; color:#69727d; padding:8px; text-align:left; border-bottom:1.5px solid #eef0f3; }
.i18n th:nth-child(1){width:22%} .i18n th:nth-child(2){width:37%}
.i18n td { font-size:11px; padding:7px 8px; border-bottom:1px solid #f4f6f9; color:#3d4550; line-height:1.55; vertical-align:top; }
.i18n td:nth-child(1) { color:#8a939e; font-size:10px; }
.i18n td:nth-child(2) { font-weight:600; color:#1a1a1a; }
.i18n td:nth-child(3) { color:#0a6ede; }
.i18n tr:hover td { background:#fafbfc; }
.i18n .grp td { background:#f0f7ff !important; font-weight:800; color:#0a6ede; font-size:10.5px; }

@media (max-width:1500px){ .stage-inner { flex-wrap:wrap; } .panel { min-width:100%; } }
</style>
</head>
<body>

<div class="topbar">
  <h1>📱 展期功能 APP 原型图 · 中西对照版</h1>
  <div class="meta">v3.0 · Aria · 2026-09-21 · 左侧中文版 / 右侧西语版，界面结构完全一致</div>
</div>

<div class="tabs" id="tabs">
  <div class="tab active" data-p="h1">首页（常态）<span class="badge app">APP</span></div>
  <div class="tab" data-p="h1p">首页（支付中）<span class="badge app">APP</span></div>
  <div class="tab" data-p="h2">还款页（常态）<span class="badge app">APP</span></div>
  <div class="tab" data-p="h2p">还款页（支付中）<span class="badge app">APP</span></div>
  <div class="tab" data-p="h2b">还款页（仅展期常态）<span class="badge app">APP</span></div>
  <div class="tab" data-p="h3">我的账户<span class="badge app">APP</span></div>
  <div class="tab" data-p="h4">Historial Préstamos<span class="badge app">APP</span></div>
  <div class="tab" data-p="h5b">借据详情（展期支付中）<span class="badge app">APP</span></div>
  <div class="tab" data-p="h5c">借据详情（展期完成）<span class="badge app">APP</span></div>
  <div class="tab" data-p="h5d">借据详情（无展期记录）<span class="badge app">APP</span></div>
  <div class="tab" data-p="s1">S1 方案与试算（一屏）<span class="badge app">APP</span></div>
  <div class="tab" data-p="s1b">S1 明细弹窗<span class="badge app">APP</span></div>
  <div class="tab" data-p="s2">S2 支付（常态）<span class="badge app">APP</span></div>
  <div class="tab" data-p="s2p">S2 支付（部分支付中）<span class="badge app">APP</span></div>
</div>

<!-- ════════════ 模板：我的账户 ════════════ -->
<template id="tpl-h3">
  <div class="iphone"><div class="screen">
    <div class="statusbar"><span class="t">9:41</span><div class="r"><span class="sig"><i></i><i></i><i></i><i></i></span><span>📶</span><span class="batt"><i></i></span></div></div>
    <div class="body account-body">
      <div class="account-head">
        <div class="account-avatar">👩</div>
        <div class="account-phone">49******2909</div>
        <div class="account-greet"><t zh="恭喜您！👋" es="¡MUCHO GUSTO! 👋"></t></div>
      </div>
      <div class="account-tabs">
        <div class="account-tab active"><div><t zh="历史记录" es="Historial"></t></div><div class="num"><t zh="借款" es="Préstamos"></t></div></div>
        <div class="account-tab"><div><t zh="优惠券" es="Cupones"></t></div><div class="num">14</div></div>
      </div>
      <div class="account-limit">
        <div><div class="label"><t zh="剩余额度" es="Límite restante"></t></div><div class="amount">MXN$5,000</div></div>
        <div class="arrow">→</div>
      </div>
      <div class="account-section">
        <div class="account-section-title"><t zh="我的" es="Mi"></t></div>
        <div class="account-grid">
          <div class="account-item js-go" data-go="h4"><div class="icon">▧</div><div><t zh="还款历史" es="Hist. pagos"></t></div></div>
          <div class="account-item"><div class="icon">▤</div><div><t zh="银行卡" es="Tarjetas"></t></div></div>
          <div class="account-item"><div class="icon">▱</div><div><t zh="钱包" es="Billetera"></t></div></div>
          <div class="account-item"><div class="icon">▣</div><div><t zh="个人资料" es="Perfil"></t></div></div>
          <div class="account-item"><div class="icon">♔</div><div><t zh="赚取奖励" es="Gana dinero"></t></div></div>
          <div class="account-item"><div class="icon">☆</div><div>Holacoin</div></div>
          <div class="account-item"><div class="icon">◉</div><div><t zh="社交资料" es="Perfil social"></t></div></div>
          <div class="account-item"><div class="icon">?</div><div>FAQ</div></div>
          <div class="account-item"><div class="icon">▧</div><div>Feedback</div></div>
        </div>
      </div>
      <div class="account-section">
        <div class="account-section-title"><t zh="其他" es="Otros"></t></div>
        <div class="account-menu">
          <div class="account-menu-row"><span>▯ &nbsp; <t zh="更换手机号" es="Cambiar número"></t></span><span class="arrow">›</span></div>
          <div class="account-menu-row"><span>♧ &nbsp; <t zh="联系我们" es="Contáctanos"></t></span><span class="arrow">›</span></div>
          <div class="account-menu-row"><span>◫ &nbsp; <t zh="关于我们" es="Nosotros"></t></span><span class="arrow">›</span></div>
          <div class="account-menu-row"><span>♙ &nbsp; <t zh="法律条款" es="Términos legales"></t></span><span class="arrow">›</span></div>
        </div>
      </div>
      <div class="account-footer">HolaFina 1.2.6<br><u><t zh="隐私声明" es="Aviso de Privacidad"></t></u></div>
    </div>
    <div class="tabbar">
      <div class="it js-go" data-go="h1"><div class="ic">⌂</div><div class="lb"><t zh="首页" es="HolaFina"></t></div></div>
      <div class="it js-go" data-go="h2"><div class="ic">$</div><div class="lb"><t zh="还款" es="Pago"></t></div></div>
      <div class="it on"><div class="ic">☺</div><div class="lb"><t zh="我的" es="Perfil"></t></div></div>
    </div>
    <div class="homebar"></div>
  </div></div>
</template>

<!-- ════════════ 模板：全部借据历史 ════════════ -->
<template id="tpl-h4">
  <div class="iphone"><div class="screen">
    <div class="statusbar"><span class="t">9:41</span><div class="r"><span class="sig"><i></i><i></i><i></i><i></i></span><span>📶</span><span class="batt"><i></i></span></div></div>
    <div class="history-nav"><span class="back js-go" data-go="h3">‹</span><span class="title"><t zh="借款历史" es="Historial Préstamos"></t></span><span class="head-icon">♧</span></div>
    <div class="body history-body">
      <div class="history-card js-go" data-go="h5b">
        <div class="top"><span class="label"><t zh="待还金额" es="Monto pendiente"></t></span><span class="period-link">3 <t zh="期还款" es="pagos"></t> ›</span></div>
        <div class="loan-no">202404301234</div>
        <div class="money">MXN$15,500 <span class="old">$2,300</span><span class="info">i</span></div>
        <div class="date"><t zh="申请时间 31/04/2024" es="Hora de solicitud 31/04/2024"></t></div>
      </div>
      <div class="history-card js-go" data-go="h5b">
        <div class="top"><span class="label"><t zh="待还金额" es="Monto pendiente"></t></span><span class="period-link">2 <t zh="期还款" es="pagos"></t> ›</span></div>
        <div class="loan-no">202404305678</div>
        <div class="money">MXN$15,500</div>
        <div class="date"><t zh="申请时间 31/04/2024" es="Hora de solicitud 31/04/2024"></t></div>
      </div>
      <div class="history-card js-go" data-go="h5d">
        <div class="top"><span class="label"><t zh="待还金额" es="Monto pendiente"></t></span><span class="period-link">1 <t zh="期还款" es="pago"></t> ›</span></div>
        <div class="loan-no">202405011122</div>
        <div class="money">MXN$15,500</div>
        <div class="date"><t zh="申请时间 31/04/2024" es="Hora de solicitud 31/04/2024"></t></div>
      </div>
      <div class="history-card js-go" data-go="h5c">
        <div class="top"><span class="label"><t zh="待还金额" es="Monto pendiente"></t></span><span class="period-link">2 <t zh="期还款" es="pagos"></t> ›</span></div>
        <div class="loan-no">202405021234</div>
        <div class="money">MXN$15,500</div>
        <div class="date"><t zh="申请时间 31/04/2024" es="Hora de solicitud 31/04/2024"></t></div>
      </div>
    </div>
  </div></div>
</template>

<!-- ════════════ 模板：借据详情（展期状态） ════════════ -->
<template id="tpl-h5">
  <div class="iphone"><div class="screen">
    <div class="statusbar"><span class="t">9:41</span><div class="r"><span class="sig"><i></i><i></i><i></i><i></i></span><span>📶</span><span class="batt"><i></i></span></div></div>
    <div class="history-nav"><span class="back js-go" data-go="h4">‹</span><span class="title"><t zh="借据详情" es="Detalle del préstamo"></t></span><span class="head-icon">♧</span></div>
    <div class="body history-body">
      <div class="card loan-summary" style="margin:0 0 12px;">
        <div class="card-t"><t zh="借据信息" es="Información del préstamo"></t></div>
        <div class="row"><span class="k"><t zh="借据编号" es="No. de préstamo"></t></span><span class="v">202609121234</span></div>
        <div class="row"><span class="k"><t zh="总待还金额" es="Monto total pendiente"></t></span><span class="v blue">MXN$8,800.00</span></div>
        <div class="row"><span class="k"><t zh="当前总待还" es="Pendiente actual"></t></span><span class="v blue">MXN$5,000.00</span></div>
        <div class="row"><span class="k"><t zh="当前状态" es="Estado actual"></t></span><span class="v"><span class="tg dpd"><t zh="逾期" es="Vencido"></t></span></span></div>
        <div class="row"><span class="k"><t zh="计划期数" es="Cuotas del plan"></t></span><span class="v">4/4</span></div>
        <div class="row"><span class="k"><t zh="放款成功时间" es="Fecha de desembolso"></t></span><span class="v">2026-05-30 10:15:22</span></div>
        <div class="row"><span class="k"><t zh="放款金额" es="Monto desembolsado"></t></span><span class="v">MXN$8,000.00</span></div>
        <div class="row"><span class="k"><t zh="放款银行卡后四位" es="Últimos 4 dígitos de la tarjeta"></t></span><span class="v">1234</span></div>
      </div>

      <div class="card loan-plan" data-state="no_extension,payment_pending" style="margin:0 0 12px;">
        <div class="card-t"><t zh="最新还款计划" es="Plan de pago actual"></t></div>
        <div class="plan-subtitle"><t zh="展期尚未生效，展示当前最新计划；已还和待还期次均保留。" es="La extensión aún no está activa; se muestra el plan actual con cuotas pagadas y pendientes."></t></div>
        <div class="loan-plan-row"><div class="plan-top"><span>1/4</span><span class="plan-date">01/06/2026 — 15/06/2026</span></div><div class="plan-bottom"><span><t zh="总待还款金额" es="Total a pagar"></t> <b>$1,500.00</b></span><span><t zh="已还金额" es="Pagado"></t> <b class="paid">$1,500.00</b></span></div></div>
        <div class="loan-plan-row"><div class="plan-top"><span>2/4</span><span class="plan-date">16/06/2026 — 30/06/2026</span></div><div class="plan-bottom"><span><t zh="总待还款金额" es="Total a pagar"></t> <b>$2,300.00</b></span><span><t zh="已还金额" es="Pagado"></t> <b class="paid">$0.00</b></span></div></div>
        <div class="loan-plan-row"><div class="plan-top"><span>3/4</span><span class="plan-date">01/07/2026 — 15/07/2026</span></div><div class="plan-bottom"><span><t zh="总待还款金额" es="Total a pagar"></t> <b>$800.00</b></span><span><t zh="已还金额" es="Pagado"></t> <b class="paid">$0.00</b></span></div></div>
        <div class="loan-plan-row"><div class="plan-top"><span>4/4</span><span class="plan-date">16/07/2026 — 30/07/2026</span></div><div class="plan-bottom"><span><t zh="总待还款金额" es="Total a pagar"></t> <b>$1,900.00</b></span><span><t zh="已还金额" es="Pagado"></t> <b class="paid">$0.00</b></span></div></div>
      </div>

      <div class="card loan-plan" data-state="effective" style="margin:0 0 12px;">
        <div class="card-t"><t zh="最新还款计划" es="Plan de pago actualizado"></t></div>
        <div class="plan-subtitle"><t zh="已完成展期后仅展示更新后的最新计划；每期时长仍保持 15 天。" es="Después de completar la extensión, solo se muestra el plan actualizado; cada cuota mantiene 15 días."></t></div>
        <div class="loan-plan-row"><div class="plan-top"><span>1/4</span><span class="plan-date">01/06/2026 — 18/06/2026</span></div><div class="plan-bottom"><span><t zh="总待还款金额" es="Total a pagar"></t> <b>$1,500.00</b></span><span><t zh="已还金额" es="Pagado"></t> <b class="paid">$1,500.00</b></span></div></div>
        <div class="loan-plan-row"><div class="plan-top"><span>2/4</span><span class="plan-date">19/06/2026 — 03/07/2026</span></div><div class="plan-bottom"><span><t zh="总待还款金额" es="Total a pagar"></t> <b>$2,300.00</b></span><span><t zh="已还金额" es="Pagado"></t> <b class="paid">$0.00</b></span></div></div>
        <div class="loan-plan-row"><div class="plan-top"><span>3/4</span><span class="plan-date">04/07/2026 — 18/07/2026</span></div><div class="plan-bottom"><span><t zh="总待还款金额" es="Total a pagar"></t> <b>$800.00</b></span><span><t zh="已还金额" es="Pagado"></t> <b class="paid">$0.00</b></span></div></div>
        <div class="loan-plan-row"><div class="plan-top"><span>4/4</span><span class="plan-date">19/07/2026 — 02/08/2026</span></div><div class="plan-bottom"><span><t zh="总待还款金额" es="Total a pagar"></t> <b>$1,900.00</b></span><span><t zh="已还金额" es="Pagado"></t> <b class="paid">$0.00</b></span></div></div>
      </div>

      <div class="account-section extension-records" data-state="payment_pending,effective" style="margin:0;">
        <div class="account-section-title"><t zh="展期记录" es="Historial de extensiones"></t></div>
        <div class="account-menu">
          <div class="account-menu-row js-go" data-state="payment_pending" data-go="s2p">
            <span><b>2026-09-21</b><br><small>3 <t zh="天" es="días"></t> · $167.50</small></span>
            <span style="display:flex;align-items:center;gap:7px;"><span class="tg dpd"><t zh="支付中" es="Pago en proceso"></t></span><span class="arrow">›</span></span>
          </div>
          <div class="account-menu-row" data-state="effective">
            <span><b>2026-09-21</b><br><small>3 <t zh="天" es="días"></t> · $167.50</small></span>
            <span class="tg ok"><t zh="已完成" es="Completada"></t></span>
          </div>
          <div class="account-menu-row">
            <span><b>2026-08-15</b><br><small>2 <t zh="天" es="días"></t> · $100.00</small></span>
            <span class="tg ok"><t zh="已完成" es="Completada"></t></span>
          </div>
        </div>
      </div>
    </div>
    <div class="actionbar" style="padding-top:10px;">
      <button class="btn-lg orange js-go" data-go="h2"><t zh="去还款" es="Ir a pagar"></t></button>
    </div>
  </div></div>
</template>

<!-- ════════════ 模板：首页 ════════════ -->
<template id="tpl-h1">
  <div class="iphone"><div class="screen">
    <div class="statusbar"><span class="t">9:41</span>
      <div class="r"><span class="sig"><i></i><i></i><i></i><i></i></span><span>📶</span><span class="batt"><i></i></span></div>
    </div>
    <div class="body">
      <div class="hf-head">
        <div class="hf-brand">
          <div>
            <div class="hf-logo"><span class="a">Hola</span><span class="b">Fina</span></div>
            <div class="hf-swoosh"></div>
            <div class="hf-slogan"><span style="color:#0a84ff;">🛡</span><t zh="安全借款服务" es="Servicio seguro de préstamo"></t></div>
          </div>
          <div class="hf-icons">
            <div class="hf-ic">🎧</div>
            <div class="hf-ic">🔔<span class="hf-dot">15</span></div>
          </div>
        </div>
      </div>

      <div class="promo" data-state="normal" data-offer="restructure">
        <div class="promo-top">
          <span class="promo-q"><t zh="全额还款有压力？" es="¿Difícil pagar todo?"></t></span>
          <span class="timer"><b>23</b><i>:</i><b>59</b><i>:</i><b>59</b></span>
        </div>
        <div class="promo-sub"><t zh="新方案：首付更低，余款分期" es="Nuevo plan: pago inicial más bajo, el resto en cuotas"></t></div>
        <button class="promo-btn"><t zh="查看详情" es="Ver Detalles"></t></button>
      </div>

      <div class="partial-banner js-go" data-state="partial" data-go="s2p">
        <div class="pb-icon">⏳</div>
        <div class="pb-info">
          <div class="pb-title"><t zh="展期支付处理中" es="Pago de extensión en proceso"></t></div>
          <div class="pb-detail"><t zh="已支付 $100.00 · 剩余待支付 $67.50" es="Pagado $100.00 · Restante $67.50"></t></div>
          <div class="pb-time"><b>18</b><i>:</i><b>42</b><i>:</i><b>10</b><span style="font-size:10px;color:#8a5a00;margin-left:3px;"><t zh="剩余" es="restante"></t></span></div>
        </div>
        <div class="pb-arrow">›</div>
      </div>

      <div class="pend">
        <div class="pend-h"><t zh="近期待还款（MXN$）" es="Pagos pendientes recientes (MXN$)"></t></div>
        <div class="pend-amt"><span class="n">37,000</span><span class="ar">›</span></div>
        <div class="pend-due"><t zh="到期日 10/07/2026" es="Vencimiento 10/07/2026"></t> <span class="late"><t zh="（逾期 4 天）" es="(4 días de mora)"></t></span></div>
      </div>

      <div class="waiver">
        <div class="ic">%</div>
        <div class="tx"><t zh="为您部分减免利息和手续费" es="Te reducimos parcialmente intereses y comisiones"></t></div>
        <div class="lk"><t zh="详情 ›" es="Detalles ›"></t></div>
      </div>

      <!-- ★ 展期入口 -->
      <div class="ext-entry js-go" data-state="normal" data-go="s1">
        <div class="ext-ic">📅</div>
        <div class="ext-tx">
          <div class="ext-h"><t zh="延长还款日" es="Extender fecha de pago"></t> <span class="ext-cd"><b>3</b><i>d</i><b>23</b><i>:</i><b>59</b><i>:</i><b>45</b></span></div>
          <div class="ext-d"><t zh="3 笔借据可展期 · 最高 30 天" es="3 préstamos elegibles · Hasta 30 días"></t></div>
        </div>
        <div class="ext-ar">›</div>
      </div>

      <div class="dual">
        <button class="w"><t zh="全部待还" es="Todo por pagar"></t></button>
        <button class="o"><t zh="立即还款" es="Pagar ahora"></t></button>
      </div>
      <div class="pend-help"><t zh="还款未到账？ ›" es="¿El pago no llegó? ›"></t></div>

      <div class="sec-t"><t zh="借款" es="Préstamos"></t></div>
      <div class="credit">
        <div class="credit-r">
          <div>
            <div class="lb"><t zh="可用额度" es="Límite disponible"></t></div>
            <div class="n">$5,000</div>
          </div>
          <button class="b"><t zh="再借一笔" es="Otro préstamo"></t></button>
        </div>
      </div>
      <div class="credit-tip"><t zh="恭喜！每次按时使用，额度都会提升，期限非常灵活。" es="¡Felicidades! Su límite aumenta cada vez que lo usa con plazos muy flexibles."></t></div>

      <div class="sec-t"><t zh="更多" es="Más"></t></div>
      <div class="safe">
        <div class="tx">
          <div class="h"><t zh="注意资金安全" es="Cuidado con sus fondos"></t></div>
          <div class="d"><t zh="识别官方渠道，避免" es="Identifica canales oficiales, evita"></t> <span style="color:#ff3b30;font-weight:600;"><t zh="可疑链接" es="enlaces sospechosos"></t></span>。</div>
        </div>
        <div class="em">👮</div>
      </div>

      <div class="sec-t"><t zh="我的权益" es="Mis ventajas"></t></div>
      <div class="adv">
        <div class="it"><div class="c">📱</div><div class="l"><t zh="APP 申请" es="Solicitud en la app"></t></div></div>
        <div class="it"><div class="c">⚡</div><div class="l"><t zh="快速审核" es="Revisión rápida"></t></div></div>
        <div class="it"><div class="c">💲</div><div class="l"><t zh="还款便捷" es="Pago conveniente"></t></div></div>
      </div>

      <div class="fmark"><div class="l">HolaFina</div><div class="s"><t zh="安全快速信贷" es="Crédito Seguro Rápido"></t></div></div>
    </div>
    <div class="tabbar">
      <div class="it on"><div class="ic">🏠</div><div class="lb"><t zh="首页" es="HolaFina"></t></div></div>
      <div class="it js-go" data-go="h2"><div class="ic">💲</div><div class="lb"><t zh="还款" es="Pago"></t></div></div>
      <div class="it js-go" data-go="h3"><div class="ic">☺</div><div class="lb"><t zh="我的" es="Perfil"></t></div></div>
    </div>
    <div class="homebar"></div>
  </div></div>
</template>

<!-- ════════════ 模板：还款页 ════════════ -->
<template id="tpl-h2">
  <div class="iphone"><div class="screen">
    <div class="statusbar"><span class="t">9:41</span>
      <div class="r"><span class="sig"><i></i><i></i><i></i><i></i></span><span>📶</span><span class="batt"><i></i></span></div>
    </div>
    <div class="rp-nav">
      <span class="nav-pad"></span>
      <div class="rp-tabs">
        <span class="rp-tab on"><t zh="待还" es="Pendientes"></t></span>
        <span class="rp-tab"><t zh="已还" es="Pagados"></t></span>
      </div>
      <span class="qm">?</span>
    </div>
    <!-- ★ 固定区：Banner 轮播（3秒自动轮播，可手动切换），不随页面滚动 -->
    <div class="rp-sticky">
      <div class="car-track js-car" data-autoplay="true">
        <!-- 第 1 页：分期促销 -->
        <div class="car-slide">
          <div class="promo" data-state="normal" data-offer="restructure">
            <div class="promo-top">
              <span class="promo-q"><t zh="全额还款有压力？" es="¿Difícil pagar todo?"></t></span>
              <span class="timer"><b>23</b><i>:</i><b>59</b><i>:</i><b>59</b></span>
            </div>
            <div class="promo-sub"><t zh="新方案：首付更低，余款分期" es="Nuevo plan: pago inicial más bajo, el resto en cuotas"></t></div>
            <button class="promo-btn"><t zh="查看详情" es="Ver Detalles"></t></button>
          </div>
        </div>

        <!-- 第 2 页：展期入口 -->
        <div class="car-slide">
          <div class="ext-entry js-go" data-state="normal" data-go="s1">
            <div class="ext-ic">📅</div>
            <div class="ext-tx">
              <div class="ext-h"><t zh="延长还款日" es="Extender fecha de pago"></t> <span class="ext-cd"><b>3</b><i>d</i><b>23</b><i>:</i><b>59</b><i>:</i><b>45</b></span></div>
              <div class="ext-d"><t zh="3 笔借据可展期 · 最高 30 天" es="3 préstamos elegibles · Hasta 30 días"></t></div>
            </div>
            <div class="ext-ar">›</div>
          </div>
        </div>
      </div>
      <div class="car-dots js-dots" data-state="normal"></div>
    </div>

    <!-- 离线部分支付状态 Banner：固定在还款页顶部 -->
    <div class="partial-banner js-go" data-state="partial" data-go="s2p">
      <div class="pb-icon">⏳</div>
      <div class="pb-info">
        <div class="pb-title"><t zh="展期支付处理中" es="Pago de extensión en proceso"></t></div>
        <div class="pb-detail"><t zh="已支付 $100.00 · 剩余待支付 $67.50" es="Pagado $100.00 · Restante $67.50"></t></div>
        <div class="pb-time"><b>18</b><i>:</i><b>42</b><i>:</i><b>10</b><span style="font-size:10px;color:#8a5a00;margin-left:3px;"><t zh="剩余" es="restante"></t></span></div>
      </div>
      <div class="pb-arrow">›</div>
    </div>

    <div class="body">
      <div class="plan-head">
        <span class="t"><t zh="还款计划" es="Plan de pago"></t></span>
        <span class="pre"><t zh="提前还款 ›" es="Pago anticipado ›"></t></span>
      </div>
      <div class="disc-pill">🎁 <t zh="限时折扣" es="Descuento limitado"></t></div>

      <!-- ═══ 按月分组 · 多借据多期次 ═══ -->
      <div class="mon"><span class="bar"></span><span class="tx"><t zh="2026 年 9 月" es="Sep de 2026"></t></span></div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609121234 · 1/4</span><t zh="到期日 12/09/2026" es="vence el 12/09/2026"></t> <span class="late"><t zh="逾期 9 天" es="9 días de atraso"></t></span></div>
          <div class="inst-a">MXN$1,500 <span class="ar">›</span></div>
          <div class="inst-was"><t zh="原价：$1,800" es="Antes: $1,800"></t></div>
        </div>
        <div class="rad half"></div>
      </div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609121234 · 2/4</span><t zh="到期日 28/09/2026" es="vence el 28/09/2026"></t> <span class="today"><t zh="今日还款" es="Pago hoy"></t></span></div>
          <div class="inst-a">MXN$2,300 <span class="ar">›</span></div>
        </div>
        <div class="rad on"></div>
      </div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609155678 · 1/3</span><t zh="到期日 30/09/2026" es="vence el 30/09/2026"></t> <span class="left"><t zh="还剩 9 天" es="Faltan 9 días"></t></span></div>
          <div class="inst-a">MXN$3,500 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="mon"><span class="bar"></span><span class="tx"><t zh="2026 年 10 月" es="Oct de 2026"></t></span></div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609121234 · 3/4</span><t zh="到期日 05/10/2026" es="vence el 05/10/2026"></t> <span class="left"><t zh="还剩 14 天" es="Faltan 14 días"></t></span></div>
          <div class="inst-a">MXN$800 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609121234 · 4/4</span><t zh="到期日 20/10/2026" es="vence el 20/10/2026"></t> <span class="left"><t zh="还剩 29 天" es="Faltan 29 días"></t></span></div>
          <div class="inst-a">MXN$1,900 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609155678 · 2/3</span><t zh="到期日 15/10/2026" es="vence el 15/10/2026"></t> <span class="left"><t zh="还剩 24 天" es="Faltan 24 días"></t></span></div>
          <div class="inst-a">MXN$3,500 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="mon"><span class="bar"></span><span class="tx"><t zh="2026 年 11 月" es="Nov de 2026"></t></span></div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609155678 · 3/3</span><t zh="到期日 15/11/2026" es="vence el 15/11/2026"></t> <span class="left"><t zh="还剩 55 天" es="Faltan 55 días"></t></span></div>
          <div class="inst-a">MXN$3,500 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="refl"><t zh="还款将在 30 分钟内到账。" es="Tu pago se reflejará en 30 min."></t> <span class="lk"><t zh="还款未到账？" es="¿Pago no reflejado?"></t></span></div>
      <div class="save-bar"><t zh="一次性结清逾期，节省利息" es="Liquida tu atraso en un solo pago y ahorra intereses"></t></div>
    </div>
    <div class="pay-bar tabbar-above">
      <div class="l">
        <div class="lb"><t zh="还款金额" es="Monto de pago"></t></div>
        <div class="n">$3,800</div>
      </div>
      <button class="b"><t zh="还款" es="Pagar"></t></button>
    </div>
    <div class="tabbar">
      <div class="it js-go" data-go="h1"><div class="ic">🏠</div><div class="lb"><t zh="首页" es="HolaFina"></t></div></div>
      <div class="it on"><div class="ic">💲</div><div class="lb"><t zh="还款" es="Pago"></t></div></div>
      <div class="it js-go" data-go="h3"><div class="ic">☺</div><div class="lb"><t zh="我的" es="Perfil"></t></div></div>
    </div>
    <div class="homebar"></div>
  </div></div>
</template>

<!-- ════════════ 模板：还款页（仅展期 banner） ════════════ -->
<template id="tpl-h2b">
  <div class="iphone"><div class="screen">
    <div class="statusbar"><span class="t">9:41</span>
      <div class="r"><span class="sig"><i></i><i></i><i></i><i></i></span><span>📶</span><span class="batt"><i></i></span></div>
    </div>
    <div class="rp-nav">
      <span class="nav-pad"></span>
      <div class="rp-tabs">
        <span class="rp-tab on"><t zh="待还" es="Pendientes"></t></span>
        <span class="rp-tab"><t zh="已还" es="Pagados"></t></span>
      </div>
      <span class="qm">?</span>
    </div>

    <!-- ★ 固定区：轮播仅一页（促销 Banner 不展示），指示点自动隐藏 -->
    <div class="rp-sticky">
      <div class="car-track js-car">
        <div class="car-slide">
          <div class="ext-entry js-go" data-state="normal" data-go="s1">
            <div class="ext-ic">📅</div>
            <div class="ext-tx">
              <div class="ext-h"><t zh="延长还款日" es="Extender fecha de pago"></t> <span class="ext-cd"><b>3</b><i>d</i><b>23</b><i>:</i><b>59</b><i>:</i><b>45</b></span></div>
              <div class="ext-d"><t zh="3 笔借据可展期 · 最高 30 天" es="3 préstamos elegibles · Hasta 30 días"></t></div>
            </div>
            <div class="ext-ar">›</div>
          </div>
        </div>
      </div>
      <div class="car-dots js-dots" data-state="normal"></div>
    </div>

    <!-- 离线部分支付状态 Banner：固定在还款页顶部 -->
    <div class="partial-banner js-go" data-state="partial" data-go="s2p">
      <div class="pb-icon">⏳</div>
      <div class="pb-info">
        <div class="pb-title"><t zh="展期支付处理中" es="Pago de extensión en proceso"></t></div>
        <div class="pb-detail"><t zh="已支付 $100.00 · 剩余待支付 $67.50" es="Pagado $100.00 · Restante $67.50"></t></div>
        <div class="pb-time"><b>18</b><i>:</i><b>42</b><i>:</i><b>10</b><span style="font-size:10px;color:#8a5a00;margin-left:3px;"><t zh="剩余" es="restante"></t></span></div>
      </div>
      <div class="pb-arrow">›</div>
    </div>

    <div class="body">
      <div class="plan-head">
        <span class="t"><t zh="还款计划" es="Plan de pago"></t></span>
        <span class="pre"><t zh="提前还款 ›" es="Pago anticipado ›"></t></span>
      </div>
      <div class="disc-pill">🎁 <t zh="限时折扣" es="Descuento limitado"></t></div>

      <!-- ═══ 按月分组 · 多借据多期次 ═══ -->
      <div class="mon"><span class="bar"></span><span class="tx"><t zh="2026 年 9 月" es="Sep de 2026"></t></span></div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609121234 · 1/4</span><t zh="到期日 12/09/2026" es="vence el 12/09/2026"></t> <span class="late"><t zh="逾期 9 天" es="9 días de atraso"></t></span></div>
          <div class="inst-a">MXN$1,500 <span class="ar">›</span></div>
          <div class="inst-was"><t zh="原价：$1,800" es="Antes: $1,800"></t></div>
        </div>
        <div class="rad half"></div>
      </div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609121234 · 2/4</span><t zh="到期日 28/09/2026" es="vence el 28/09/2026"></t> <span class="today"><t zh="今日还款" es="Pago hoy"></t></span></div>
          <div class="inst-a">MXN$2,300 <span class="ar">›</span></div>
        </div>
        <div class="rad on"></div>
      </div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609155678 · 1/3</span><t zh="到期日 30/09/2026" es="vence el 30/09/2026"></t> <span class="left"><t zh="还剩 9 天" es="Faltan 9 días"></t></span></div>
          <div class="inst-a">MXN$3,500 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="mon"><span class="bar"></span><span class="tx"><t zh="2026 年 10 月" es="Oct de 2026"></t></span></div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609121234 · 3/4</span><t zh="到期日 05/10/2026" es="vence el 05/10/2026"></t> <span class="left"><t zh="还剩 14 天" es="Faltan 14 días"></t></span></div>
          <div class="inst-a">MXN$800 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609121234 · 4/4</span><t zh="到期日 20/10/2026" es="vence el 20/10/2026"></t> <span class="left"><t zh="还剩 29 天" es="Faltan 29 días"></t></span></div>
          <div class="inst-a">MXN$1,900 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609155678 · 2/3</span><t zh="到期日 15/10/2026" es="vence el 15/10/2026"></t> <span class="left"><t zh="还剩 24 天" es="Faltan 24 días"></t></span></div>
          <div class="inst-a">MXN$3,500 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="mon"><span class="bar"></span><span class="tx"><t zh="2026 年 11 月" es="Nov de 2026"></t></span></div>

      <div class="inst">
        <div class="inst-l">
          <div class="inst-d"><span class="inst-term2">202609155678 · 3/3</span><t zh="到期日 15/11/2026" es="vence el 15/11/2026"></t> <span class="left"><t zh="还剩 55 天" es="Faltan 55 días"></t></span></div>
          <div class="inst-a">MXN$3,500 <span class="ar">›</span></div>
        </div>
        <div class="rad"></div>
      </div>

      <div class="refl"><t zh="还款将在 30 分钟内到账。" es="Tu pago se reflejará en 30 min."></t> <span class="lk"><t zh="还款未到账？" es="¿Pago no reflejado?"></t></span></div>
      <div class="save-bar"><t zh="一次性结清逾期，节省利息" es="Liquida tu atraso en un solo pago y ahorra intereses"></t></div>
    </div>
    <div class="pay-bar tabbar-above">
      <div class="l">
        <div class="lb"><t zh="还款金额" es="Monto de pago"></t></div>
        <div class="n">$3,800</div>
      </div>
      <button class="b"><t zh="还款" es="Pagar"></t></button>
    </div>
    <div class="tabbar">
      <div class="it js-go" data-go="h1"><div class="ic">🏠</div><div class="lb"><t zh="首页" es="HolaFina"></t></div></div>
      <div class="it on"><div class="ic">💲</div><div class="lb"><t zh="还款" es="Pago"></t></div></div>
      <div class="it js-go" data-go="h3"><div class="ic">☺</div><div class="lb"><t zh="我的" es="Perfil"></t></div></div>
    </div>
    <div class="homebar"></div>
  </div></div>
</template>




<!-- ════════════ 模板：S1 方案与试算（一屏） ════════════ -->
<template id="tpl-s1">
  <div class="iphone"><div class="screen">
    <div class="statusbar"><span class="t">9:42</span>
      <div class="r"><span class="sig"><i></i><i></i><i></i><i></i></span><span>📶</span><span class="batt"><i></i></span></div>
    </div>
    <div class="rp-nav">
      <span class="bk js-go" data-go="h2">‹</span>
      <div class="rp-tabs"><span class="rp-tab on"><t zh="延长还款日" es="Extender pago"></t></span></div>
      <span class="qm">?</span>
    </div>
    <div class="steps">
      <div class="st on"><div class="d">1</div><t zh="确认方案" es="Plan"></t></div><div class="ln"></div>
      <div class="st"><div class="d">2</div><t zh="支付" es="Pagar"></t></div>
    </div>
    <div class="body">
      <!-- ① 可展期借据 -->
      <div class="card">
        <div class="card-t"><t zh="可展期借据" es="Préstamos elegibles"></t></div>

        <div class="lrow on js-loan">
          <div class="cb2"></div>
          <div class="mid">
            <div class="l1"><span style="color:#5a7ca8;font-size:11px;font-weight:600;">202609121234</span> <span class="tg dpd"><t zh="逾期 9 天" es="Vencido 9 días"></t></span></div>
            <div class="l2"><t zh="到期日 12/09/2026" es="vence el 12/09/2026"></t></div>
          </div>
          <div class="amt">$1,500.00</div>
        </div>

        <div class="lrow on js-loan">
          <div class="cb2"></div>
          <div class="mid">
            <div class="l1"><span style="color:#5a7ca8;font-size:11px;font-weight:600;">202609155678</span> <span class="tg" style="background:#fff7e6;color:#e2590c;"><t zh="到期日" es="Hoy"></t></span></div>
            <div class="l2"><t zh="到期日 21/09/2026" es="vence el 21/09/2026"></t></div>
          </div>
          <div class="amt">$3,500.00</div>
        </div>

        <div class="lrow js-loan">
          <div class="cb2"></div>
          <div class="mid">
            <div class="l1"><span style="color:#5a7ca8;font-size:11px;font-weight:600;">202609189012</span> <span class="tg ok"><t zh="还剩 14 天" es="Faltan 14 días"></t></span></div>
            <div class="l2"><t zh="到期日 05/10/2026" es="vence el 05/10/2026"></t></div>
          </div>
          <div class="amt">$800.00</div>
        </div>
      </div>

      <!-- ② 天数：加减器 + 手填，默认 1 天，步进 1 天，上限由策略统一输出 -->
      <div class="card">
        <div class="card-t" style="display:flex;align-items:center;justify-content:space-between;">
          <span><t zh="展期天数" es="Días de extensión"></t></span>
          <span class="js-max-lbl" style="font-size:10.5px;color:#8a939e;font-weight:500;"><t zh="最多 15 天" es="Máx. 15 días"></t></span>
        </div>
        <div class="stepper-wrap">
          <button class="step-btn js-step" data-d="-1">−</button>
          <input class="step-inp js-din" type="text" value="1" inputmode="numeric" data-max="15">
          <span class="step-unit"><t zh="天" es="días"></t></span>
          <button class="step-btn js-step" data-d="+1">+</button>
        </div>
        <div class="limit js-lim">⚠️ <t zh="本次最多可展期 15 天（策略输出）" es="Máximo 15 días para esta extensión (según política)"></t></div>
      </div>

      <!-- ③ 核心结果：新还款日 + 合计，明细进弹窗 -->
      <div class="card" style="padding:0;background:transparent;box-shadow:none;margin-top:0;">
        <div class="hero">
          <div class="hero-lb"><t zh="展期后最近还款日" es="Próxima fecha de pago"></t></div>
          <div class="hero-date">13/09/2026</div>
          <div class="hero-sub"><t zh="2 笔借据均顺延 1 天" es="2 préstamos, +1 día cada uno"></t></div>
          <div class="hero-hr"></div>
          <div class="hero-total">
            <div>
              <div class="k"><t zh="合计支付" es="Total a pagar"></t></div>
              <div style="font-size:10px;color:#7c9bc4;margin-top:2px;"><t zh="展期费 $100.00 + 逾期费 $67.50" es="Cargo $100.00 + Mora $67.50"></t></div>
            </div>
            <div class="v">$167.50</div>
          </div>
          <div class="dnote" style="margin:9px 0 0;padding:8px 10px;background:#fff8eb;border:1px solid #ffe2b7;border-radius:8px;color:#8a5a00;line-height:1.55;font-size:10.5px;"><t zh="展期费固定不变。若借据已逾期，逾期费用会在支付完成前按日增长，最终待支付金额以支付时系统更新结果为准。展期成功后，支付金额为展期服务费，不抵扣借据应还款；展期未成功，已支付金额将用于偿还当前借据。" es="El cargo por extensión es fijo. Si tu préstamo está vencido, los cargos por mora pueden aumentar cada día hasta completar el pago; el monto final se actualizará al momento de pagar. Si la extensión se activa, el pago no reducirá el monto pendiente de tu préstamo. Si no se activa, el monto pagado se aplicará al pago de tu préstamo actual."></t></div>
          <div class="detail-link js-sheet-open">
            <span><t zh="查看费用与还款日说明" es="Ver costos y cambios de fecha"></t></span>
            <span>›</span>
          </div>
        </div>
      </div>

      <div class="deadline-note"><t zh="方案确认后请在 24 小时内完成支付，超时将自动取消。" es="Completa el pago dentro de 24 horas después de confirmar; de lo contrario, se cancelará automáticamente."></t></div>
      <div class="cd"><t zh="方案将在" es="La oferta expira en"></t> <b>14:59</b> <t zh="后失效" es=""></t></div>
      <div class="note" style="padding-bottom:14px;"><t zh="* 日期和金额均由服务端计算" es="* Las fechas y montos son calculados por el servidor"></t></div>
    </div>

    <!-- 底部：协议 + 单一 CTA 直达支付 -->
    <div class="actionbar">
      <label class="ab-agree">
        <input type="checkbox" checked>
        <span><t zh="我已阅读并同意" es="He leído y acepto los"></t> <a href="#"><t zh="《展期条款》" es="Términos de Extensión"></t></a> <t zh="和" es="y el"></t> <a href="#"><t zh="《隐私政策》" es="Aviso de Privacidad"></t></a></span>
      </label>
      <button class="btn-lg orange js-go" data-go="s2"><t zh="确认并支付 $167.50" es="Confirmar y pagar $167.50"></t></button>
    </div>
    <div class="homebar"></div>

    <!-- 次要信息：底部上滑弹窗 -->
    <div class="sheet-mask js-sheet-close"></div>
    <div class="sheet js-sheet">
      <div class="sheet-grab"></div>
      <div class="sheet-h">
        <span><t zh="逐笔明细" es="Detalle por préstamo"></t></span>
        <span class="sheet-x js-sheet-close">✕</span>
      </div>
      <div class="sheet-b">
        <div class="dsum">
          <div class="row" style="padding:3px 0;"><span class="k"><t zh="展期天数" es="Días de extensión"></t></span><span class="v"><t zh="1 天" es="1 día"></t></span></div>
          <div class="row" style="padding:3px 0;"><span class="k"><t zh="展期借据数" es="Préstamos"></t></span><span class="v">2</span></div>
          <div class="row" style="padding:3px 0;"><span class="k"><t zh="展期费用" es="Cargo de extensión"></t></span><span class="v or">$100.00</span></div>
          <div class="row" style="padding:3px 0;"><span class="k"><t zh="逾期费用汇总" es="Total de mora"></t></span><span class="v or">$67.50</span></div>
          <div class="hr" style="margin:8px 0;"></div>
          <div class="row" style="padding:3px 0;"><span class="k" style="font-weight:700;"><t zh="合计待支付" es="Total a pagar"></t></span><span class="v or" style="font-size:15px;">$167.50</span></div>
        </div>

        <div style="font-size:13px;font-weight:800;color:#2c333d;margin:14px 0 8px;"><t zh="还款日变化" es="Cambios en fechas de pago"></t></div>
        <div class="dnote" style="padding:0 0 8px;"><t zh="以下展示所有已选借据的剩余未还期次还款日变化；已还期次不展示。" es="A continuación se muestran los cambios de fecha de todas las cuotas pendientes de los préstamos seleccionados. Las cuotas pagadas no se muestran."></t></div>

        <div class="dblk">
          <div class="dblk-h"><span>202609121234</span></div>
          <div class="period-change">
            <div class="period-main"><span class="period-badge">2/4</span><span class="period-before">28/09/2026</span><span class="period-arrow">→</span><span class="period-after">29/09/2026</span></div>
            <div class="period-meta"><span class="tg dpd"><t zh="逾期 9 天" es="9 días de atraso"></t></span><span class="period-fee"><t zh="逾期费用 $67.50" es="Mora $67.50"></t></span></div>
          </div>
          <div class="period-change">
            <div class="period-main"><span class="period-badge">3/4</span><span class="period-before">05/10/2026</span><span class="period-arrow">→</span><span class="period-after">06/10/2026</span></div>
            <div class="period-meta"><span class="tg ok"><t zh="还剩 14 天" es="Faltan 14 días"></t></span></div>
          </div>
          <div class="period-change">
            <div class="period-main"><span class="period-badge">4/4</span><span class="period-before">20/10/2026</span><span class="period-arrow">→</span><span class="period-after">21/10/2026</span></div>
            <div class="period-meta"><span class="tg ok"><t zh="还剩 29 天" es="Faltan 29 días"></t></span></div>
          </div>
        </div>

        <div class="dblk">
          <div class="dblk-h"><span>202609155678</span></div>
          <div class="period-change">
            <div class="period-main"><span class="period-badge">1/3</span><span class="period-before">21/09/2026</span><span class="period-arrow">→</span><span class="period-after">22/09/2026</span></div>
            <div class="period-meta"><span class="tg" style="background:#fff7e6;color:#e2590c;"><t zh="到期日" es="Hoy"></t></span></div>
          </div>
          <div class="period-change">
            <div class="period-main"><span class="period-badge">2/3</span><span class="period-before">15/10/2026</span><span class="period-arrow">→</span><span class="period-after">16/10/2026</span></div>
            <div class="period-meta"><span class="tg ok"><t zh="还剩 24 天" es="Faltan 24 días"></t></span></div>
          </div>
          <div class="period-change">
            <div class="period-main"><span class="period-badge">3/3</span><span class="period-before">15/11/2026</span><span class="period-arrow">→</span><span class="period-after">16/11/2026</span></div>
            <div class="period-meta"><span class="tg ok"><t zh="还剩 55 天" es="Faltan 55 días"></t></span></div>
          </div>
        </div>
      </div>
      <div class="sheet-f">
        <button class="js-sheet-close"><t zh="我知道了" es="Entendido"></t></button>
      </div>
    </div>
  </div></div>
</template>

<!-- ════════════ 模板：S2 支付 ════════════ -->
<template id="tpl-s2">
  <div class="iphone"><div class="screen">
    <div class="statusbar"><span class="t">9:45</span>
      <div class="r"><span class="sig"><i></i><i></i><i></i><i></i></span><span>📶</span><span class="batt"><i></i></span></div>
    </div>
    <div class="rp-nav">
      <span class="bk js-go" data-go="s1">‹</span>
      <div class="rp-tabs"><span class="rp-tab on"><t zh="支付展期费用" es="Pagar extensión"></t></span></div>
      <span class="qm">?</span>
    </div>
    <div class="steps">
      <div class="st dn"><div class="d">✓</div><t zh="确认方案" es="Plan"></t></div><div class="ln"></div>
      <div class="st on"><div class="d">2</div><t zh="支付" es="Pagar"></t></div>
    </div>
    <div class="body">
      <div class="card" data-state="normal" style="text-align:center;padding:20px 15px;">
        <div style="font-size:11.5px;color:#8a939e;"><t zh="应付金额" es="Monto a pagar"></t></div>
        <div style="font-size:34px;font-weight:800;color:#ff6a13;margin-top:6px;letter-spacing:-1.2px;">$167.50</div>
        <div style="font-size:11.5px;color:#8a939e;margin-top:2px;">MXN</div>
        <div class="hr"></div>
        <div style="font-size:11px;color:#8a939e;"><t zh="请在 24 小时内完成支付（截止 22/09/2026 09:42）" es="Paga dentro de 24 horas (hasta el 22/09/2026 09:42)"></t></div>
      </div>

      <div class="partial-payment" data-state="partial">
        <div class="pp-title"><span><t zh="展期支付处理中" es="Pago de extensión en proceso"></t></span><span class="pp-status"><t zh="部分支付" es="Pago parcial"></t></span></div>
        <div class="pp-total"><span class="label"><t zh="支付订单总额" es="Total de la orden"></t></span><span class="amount">$167.50</span></div>
        <div class="pp-progress-track"><div class="pp-progress-fill"></div></div>
        <div class="dnote" style="padding:0 0 8px;color:#8a5a00;"><t zh="已完成 60% 支付；已收金额在有效期内暂记为展期费用支付中，完成全额支付后展期和还款计划才会生效。" es="Se ha completado el 60% del pago; el monto recibido queda temporalmente como pago de extensión hasta completar el total y activar la extensión y el plan."></t></div>
        <div class="pp-grid">
          <div class="pp-item"><div class="pp-label"><t zh="已支付金额" es="Monto pagado"></t></div><div class="pp-value">$100.00</div></div>
          <div class="pp-item"><div class="pp-label"><t zh="剩余待支付" es="Monto restante"></t></div><div class="pp-value orange">$67.50</div></div>
        </div>
        <div class="pp-deadline"><span><t zh="剩余支付时间" es="Tiempo restante"></t></span><span class="pp-time">18:42:10</span></div>
      </div>

      <div class="dnote" style="margin:10px 0;padding:9px 10px;background:#fff8eb;border:1px solid #ffe2b7;border-radius:8px;color:#8a5a00;line-height:1.55;font-size:10.5px;"><t zh="展期费固定不变。若支付跨天，逾期费用可能增长，请以支付前系统刷新后的待支付金额为准。展期成功后，本次支付金额为展期服务费，不抵扣借据应还款；展期未成功，已支付金额将自动用于偿还当前借据。" es="El cargo por extensión es fijo. Si el pago cruza un nuevo día, los cargos por mora pueden aumentar; consulta el monto actualizado por el sistema antes de pagar. Si la extensión se activa, este pago no reducirá el monto pendiente de tu préstamo. Si no se activa, el monto pagado se aplicará automáticamente al pago de tu préstamo actual."></t></div>

      <div class="card pay-options">
        <div class="card-t"><t zh="支付方式" es="Método de pago"></t></div>
        <div class="pay-method selected js-pay-method">
          <span class="recommend"><t zh="推荐" es="Recomendado"></t></span>
          <div class="pm-icon">🏦</div>
          <div class="pm-info">
            <div class="pm-name"><t zh="银行转账" es="Transf. bancaria"></t></div>
            <div class="pm-desc"><t zh="几分钟到账" es="Acreditación en minutos"></t></div>
            <div class="pm-fee"><t zh="手续费" es="Comisión"></t> <b>0</b> MXN</div>
          </div>
          <div class="pm-arrow">›</div>
        </div>
        <div class="pay-method js-pay-method">
          <div class="pm-icon">🏪</div>
          <div class="pm-info">
            <div class="pm-name"><t zh="现金支付" es="Pago en efectivo"></t></div>
            <div class="pm-desc"><t zh="约半小时到账" es="Acreditación en media hora"></t></div>
            <div class="pm-fee"><t zh="手续费" es="Comisión"></t> <b>10</b> MXN</div>
          </div>
          <div class="pm-arrow">›</div>
        </div>
        <div class="safety"><t zh="无论选择哪种支付方式，请妥善保存支付凭证。" es="Sin importar la forma de pago que elijas, guarda bien el recibo."></t></div>
      </div>
      <div class="note" style="padding:0 17px 13px;"><t zh="支付金额须与确认方案完全一致" es="El monto debe coincidir exactamente con la oferta confirmada"></t></div>
    </div>
    <div class="actionbar" data-state="normal">
      <button class="btn-lg orange js-go" data-go="h5c"><t zh="支付 $167.50" es="Pagar $167.50"></t></button>
    </div>
    <div class="homebar"></div>
  </div></div>
</template>


<!-- ════════════ 舞台：首页 ════════════ -->
<div class="stage active" id="s-h1">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-h1"></div>
  <div class="panel">
    <div class="pcard">
      <h3>首页展期入口</h3>
      <ul>
        <li><strong>位置</strong>：减免提示条下方、还款双按钮上方</li>
        <li><strong>形式</strong>：独立卡片，蓝色描边 + 渐变图标，与促销 Banner 区分层级</li>
        <li><strong>蓝色 Banner</strong>：代表资产重组方案；常态下可与展期入口同时展示，但两种方案互斥<span class="rt r">互斥</span></li>
        <li><strong>选择后失效</strong>：用户确认展期或资产重组其中一个方案后，另一个方案立即失效</li>
        <li><strong>倒计时</strong>：标题右侧展示策略有效期倒计时（天:时:分:秒），替代原 NUEVO 标签，营造紧迫感</li>
        <li>摘要仅展示借据数、最高天数、有效期，<strong>不展示费用和目标日期</strong><span class="rt w">重要</span></li>
        <li>资格获取失败时整卡不展示，静默降级</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>西语适配注意点</h3>
      <ul>
        <li>西语文案普遍比中文长 <strong>40%~80%</strong>，卡片需支持两行摘要</li>
        <li>「Extender fecha de pago」比「延长还款日」长约一倍，标题行需预留换行空间</li>
        <li>按钮文案「Todo por pagar」较长，双按钮区已缩小字号并允许内边距压缩<span class="rt w">已适配</span></li>
        <li>金额格式统一 <strong>MXN$1,500.00</strong>，千分位逗号、小数点两位</li>
        <li>日期格式统一 <strong>DD/MM/YYYY</strong>，符合墨西哥习惯</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>为什么放在这个位置</h3>
      <ul>
        <li>用户看到待还金额和逾期天数后，正处于「需要解决方案」状态</li>
        <li>减免提示已给出一个方案，展期作为第二个方案紧随其后</li>
        <li>位于「立即还款」上方，不抢占主还款转化，但保证曝光</li>
        <li>建议监控入口 CTR 与主还款按钮点击率的相互影响<span class="rt g">数据</span></li>
      </ul>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：首页（支付中） ════════════ -->
<div class="stage" id="s-h1p">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-h1" data-state="partial"></div>
  <div class="panel">
    <div class="pcard">
      <h3>首页支付处理中（独立状态）</h3>
      <ul>
        <li>该状态与首页常态为两个独立原型，不与可发起展期状态混合</li>
        <li>展示支付处理中 Banner：已支付金额、剩余待支付金额、剩余支付时间</li>
        <li>支付处理中状态下不展示展期入口，用户不能再次发起展期</li>
        <li>点击 Banner 仅进入对应的部分支付订单页 S2，不进入 S1 方案页</li>
      </ul>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：还款页 ════════════ -->
<div class="stage" id="s-h2">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-h2"></div>
  <div class="panel">
    <div class="pcard">
      <h3>页面层级：一级页面<span class="rt w">已修正</span></h3>
      <ul>
        <li>还款页是<strong>一级页面</strong>，通过底部 TabBar 的「还款 / Pago」进入</li>
        <li><strong>无左上角返回按钮</strong>，左侧仅保留等宽占位以保证页签视觉居中</li>
        <li><strong>底部保留 TabBar</strong>，与首页同一套，当前项「还款 / Pago」高亮</li>
        <li>层级结构：TabBar 三个一级页面（首页 / 还款 / 我的）平级互切</li>
        <li>页内「待还 / 已还」为二级页签，不改变页面层级</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>Banner 轮播<span class="rt w">已改为轮播</span></h3>
      <ul>
        <li>促销 Banner 与展期入口<strong>合并为一个轮播位</strong>，共占一个位置</li>
        <li><strong>支持手动左右滑动</strong>：触屏滑动、触控板横滑、鼠标按住拖拽均可</li>
        <li>松手后自动吸附到最近一页，不会停在半页状态</li>
        <li>下方指示点显示当前页，<strong>点击指示点可直接跳页</strong></li>
        <li>仅一页时指示点自动隐藏<span class="rt g">已适配</span></li>
        <li>拖拽超过 5px 判定为滑动，<strong>抑制本次点击</strong>，避免误触卡片跳转<span class="rt r">细节</span></li>
        <li>两台设备轮播独立，可分别滑动对比</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>轮播带来的空间收益<span class="rt g">已优化</span></h3>
      <ul>
        <li>改轮播前：两 banner 上下堆叠，固定区约 <strong>230px</strong></li>
        <li>改轮播后：仅占最高一页高度 + 指示点，约 <strong>161px</strong></li>
        <li><strong>为还款计划释放约 69px</strong>，首屏由 3 条增至约 4 条分期</li>
        <li>固定元素合计从 58% 屏高降至 <strong>49%</strong>，内容区由 42% 回到 <strong>51%</strong></li>
        <li>轮播仅一页时固定区进一步降至 95px，内容区 59%，可见约 5 条</li>
        <li>新增 banner 位时不再继续挤压内容区，只增加轮播页数<span class="rt g">可扩展</span></li>
      </ul>
    </div>
    <div class="pcard">
      <h3>轮播规则待确认<span class="rt w">待确认</span></h3>
      <ul>
        <li><strong>自动轮播</strong>：还款页常态每 3 秒自动切换一页</li>
        <li><strong>手动操作</strong>：用户触屏滑动、触控板横滑、鼠标拖拽或点击指示点后，自动轮播停止</li>
        <li><strong>是否循环</strong>？原型为不循环（首页左滑、末页右滑无响应）</li>
        <li><strong>默认页</strong>：当前默认展示促销（第 1 页）。若展期转化更高可考虑调整</li>
        <li><strong>排序规则</strong>：建议由服务端下发 banner 列表及顺序，前端不硬编码</li>
        <li>埋点需区分 <strong>banner 位置、曝光页、滑动次数</strong>，以评估各 banner 实际曝光率<span class="rt g">数据</span></li>
      </ul>
    </div>
    <div class="pcard">
      <h3>固定区与层叠顺序</h3>
      <ul>
        <li>轮播区常驻顶部，<strong>不随内容滚动</strong></li>
        <li>固定区底部带一道浅阴影，暗示下方内容可滚动</li>
        <li><strong>自上而下</strong>：状态栏 → 导航栏 → Banner 轮播 → 滚动内容 → 支付栏 → TabBar → Home Indicator</li>
        <li>支付栏与 TabBar 均常驻底部，滚动时不跟随</li>
        <li>支付栏底部留白已取消，改由 TabBar 承担安全区间距<span class="rt g">已适配</span></li>
      </ul>
    </div>
    <div class="pcard">
      <h3>还款页展期入口</h3>
      <ul>
        <li><strong>位置</strong>：促销 Banner 下方、还款计划标题上方</li>
        <li><strong>样式</strong>：与首页入口完全一致，保持用户认知统一<span class="rt r">一致性</span></li>
        <li>用户浏览还款计划时若发现无力还款，可直接切换到展期方案</li>
        <li>点击后进入 P2（二级页面，有返回按钮）</li>
        <li>实现时 P2 的返回应回到<strong>来源页</strong>（首页或还款页），原型统一演示为返回首页</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>双入口协同规则</h3>
      <ul>
        <li>两个入口共用同一份资格查询结果，同一会话不重复请求<span class="rt g">性能</span></li>
        <li>埋点区分来源：<strong>entry_source = home / repay_list</strong></li>
        <li>建议分渠道对比 CTR，判断哪个位置转化更高</li>
        <li>若资格在页面停留期间失效，进入 P2 时由服务端重新校验并提示</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>西语适配注意点</h3>
      <ul>
        <li>还款页日期表述用小写动词开头「vence el 12/09/2026」，符合原设计</li>
        <li>逾期/今日/剩余三种状态文案长度差异大，右侧勾选圈固定不挤压</li>
        <li>底部「Monto de pago」+ 金额 + 按钮三段式，按钮宽度已做收窄适配</li>
        <li>月份分组用缩写「Sep de 2026 / Oct de 2026」，节省横向空间</li>
      </ul>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：还款页（支付中） ════════════ -->
<div class="stage" id="s-h2p">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-h2" data-state="partial"></div>
  <div class="panel">
    <div class="pcard">
      <h3>还款页支付处理中（独立状态）</h3>
      <ul>
        <li>该状态与还款页常态为独立原型，不同时展示“展期入口”</li>
        <li>支付中状态不展示轮播底部指示小图标，避免用户误以为还可以切换其他方案</li>
        <li>顶部仅展示支付处理中 Banner：已支付金额、剩余待支付金额、剩余支付时间</li>
        <li>点击 Banner 进入部分支付订单 S2；不进入展期方案页</li>
        <li>当前展期订单未全额支付或超时前，用户不能再次发起新的展期</li>
      </ul>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：还款页（仅展期 banner） ════════════ -->
<div class="stage" id="s-h2b">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-h2b"></div>
  <div class="panel">
    <div class="pcard">
      <h3>场景说明：轮播仅一页</h3>
      <ul>
        <li>促销 Banner 与展期入口<strong>展示逻辑相互独立</strong></li>
        <li>本图演示促销 Banner 不展示、<strong>轮播仅剩展期入口一页</strong>的状态</li>
        <li><strong>指示点自动隐藏</strong>，不出现只有一个点的尴尬状态<span class="rt r">细节</span></li>
        <li>单页时不可滑动，但仍沿用轮播容器结构，无需单独布局</li>
        <li>入口样式、文案、跳转与两页状态完全一致</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>促销 Banner 不展示的典型原因</h3>
      <ul>
        <li>分期营销活动已结束或未到投放时段</li>
        <li>用户不符合分期方案的准入条件</li>
        <li>用户已参与过本期活动或已拒绝过该方案</li>
        <li>运营侧手动关闭该位置投放</li>
        <li>促销配置接口异常，降级为不展示</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>四种组合状态<span class="rt r">需研发覆盖</span></h3>
      <ul>
        <li><strong>两页轮播</strong>：促销第 1 页、展期第 2 页，显示指示点（见上一个页签）</li>
        <li><strong>仅展期一页</strong>：不显示指示点、不可滑动，即本图</li>
        <li><strong>仅促销一页</strong>：同理，不显示指示点、不可滑动</li>
        <li><strong>均无</strong>：轮播容器与固定区整体<strong>不渲染</strong>，还款计划紧贴导航栏</li>
        <li>固定区为空时不得残留空白带或分隔阴影<span class="rt w">重要</span></li>
        <li>建议按服务端下发的 banner 列表长度动态决定，前端不写死两页<span class="rt r">实现</span></li>
      </ul>
    </div>
    <div class="pcard">
      <h3>顺序与优先级</h3>
      <ul>
        <li>两者同时存在时，<strong>促销 Banner 在上、展期入口在下</strong></li>
        <li>促销为限时活动、带倒计时，时效性更强故置顶</li>
        <li>展期作为兜底方案紧随其后，形成「分期 → 展期」的方案梯度</li>
        <li>若后续需要调整优先级，建议用 A/B 测试验证对还款转化的影响<span class="rt g">数据</span></li>
      </ul>
    </div>
  </div>
</div>
</div>




<!-- ════════════ 舞台：我的账户 ════════════ -->
<div class="stage" id="s-h3">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-h3"></div>
  <div class="panel">
    <div class="pcard">
      <h3>我的账户</h3>
      <ul>
        <li>按参考图展示用户头像、手机号、问候语、借款/优惠券信息和剩余额度</li>
        <li>“Hist. pagos / 还款历史”是用户所有借据入口，点击进入 Historial Préstamos</li>
        <li>账户页底部 TabBar 的“我的 / Perfil”高亮</li>
      </ul>
    </div>
    <div class="i18n">
      <h3>🌐 账户页关键文案</h3>
      <table><thead><tr><th>位置</th><th>中文</th><th>西语</th></tr></thead><tbody>
        <tr><td>页面身份</td><td>我的账户</td><td>Perfil</td></tr>
        <tr><td>历史入口</td><td>还款历史</td><td>Hist. pagos</td></tr>
        <tr><td>借款历史页</td><td>借款历史</td><td>Historial Préstamos</td></tr>
        <tr><td>剩余额度</td><td>剩余额度</td><td>Límite restante</td></tr>
      </tbody></table>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：全部借据历史 ════════════ -->
<div class="stage" id="s-h4">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-h4"></div>
  <div class="panel">
    <div class="pcard">
      <h3>全部借据历史</h3>
      <ul>
        <li>用户点击账户页“Hist. pagos”进入本页面</li>
        <li>页面展示当前用户全部借据卡片，包括待还金额、期数、申请时间和借据编号</li>
        <li>借据编号格式为借款日期（YYYYMMDD）+ loanNo 后四位，方便用户区分不同借据</li>
        <li>借据编号不替代期数信息，期数仍通过“X pagos / X 期还款”展示</li>
      </ul>
    </div>
    <div class="i18n">
      <h3>🌐 借据历史字段对照</h3>
      <table><thead><tr><th>字段</th><th>中文</th><th>西语</th></tr></thead><tbody>
        <tr><td>待还金额</td><td>待还金额</td><td>Monto pendiente</td></tr>
        <tr><td>期数</td><td>3 期还款</td><td>3 pagos</td></tr>
        <tr><td>借据编号</td><td>借据编号</td><td>No. de préstamo</td></tr>
        <tr><td>申请时间</td><td>申请时间</td><td>Hora de solicitud</td></tr>
      </tbody></table>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：借据详情（展期支付中） ════════════ -->
<div class="stage" id="s-h5b"><div class="stage-inner"><div class="pair" data-tpl="tpl-h5" data-state="payment_pending"></div><div class="panel"><div class="pcard"><h3>借据详情（展期记录支付中）</h3><ul><li>借据详情主体是完整的最新还款计划，所有已还和待还期次均展示。</li><li>“展期记录”当前状态为支付中，可点击该记录进入支付展期费用页面。</li><li>未完成全额支付前，最新还款计划不变。</li></ul></div></div></div></div>

<!-- ════════════ 舞台：借据详情（展期已完成） ════════════ -->
<div class="stage" id="s-h5c"><div class="stage-inner"><div class="pair" data-tpl="tpl-h5" data-state="effective"></div><div class="panel"><div class="pcard"><h3>借据详情（展期记录已完成）</h3><ul><li>借据详情主体是最新还款计划，展示全部已还和待还期次。</li><li>展期记录仅标记“已完成”；展期结果通过最新还款计划的日期变化体现。</li><li>期次时长保持15天：第一期结束日顺延后，下一期从次日开始计算。</li></ul></div></div></div></div>

<!-- ════════════ 舞台：借据详情（无展期记录） ════════════ -->
<div class="stage" id="s-h5d"><div class="stage-inner"><div class="pair" data-tpl="tpl-h5" data-state="no_extension"></div><div class="panel"><div class="pcard"><h3>借据详情（无展期记录）</h3><ul><li>借据详情主体是完整的最新还款计划，所有已还和待还期次均展示。</li><li>该借据没有任何展期记录，因此整个“展期记录”模块不展示。</li><li>用户可使用底部“去还款”按钮进入还款页。</li></ul></div></div></div></div>

<!-- ════════════ 舞台：S1 方案与试算 ════════════ -->
<div class="stage" id="s-s1">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-s1"></div>
  <div class="panel">
    <div class="pcard">
      <h3>流程精简：4 步 → 2 步<span class="rt g">已优化</span></h3>
      <ul>
        <li><strong>原流程</strong>：选借据 → 选天数试算 → 方案确认 → 支付（4 个页面）</li>
        <li><strong>新流程</strong>：方案与试算（1 屏）→ 支付（共 2 步）</li>
        <li>选择、试算、确认三件事合并到同一屏，<strong>不再有中间页跳转</strong></li>
        <li>底部单一 CTA「确认并支付 $XXX」直达支付，省掉一次确认页</li>
        <li>次要信息移入底部弹窗，首屏只留决策必需的两个数字</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>点击次数对比</h3>
      <ul>
        <li><strong>原流程</strong>：勾选借据 → 下一步 → 选天数 → 确认方案 → 勾协议 → 确认并支付 → 支付 = 约 <strong>7 次</strong></li>
        <li><strong>新流程</strong>：（借据默认全选、天数默认 15 天已试算）→ 勾协议 → 确认并支付 → 支付 = 约 <strong>3 次</strong></li>
        <li>减少约 <strong>4 次点击</strong>、<strong>2 次页面跳转</strong></li>
        <li>用户进入即可看到完整方案，<strong>不改默认值时零选择成本</strong><span class="rt g">关键</span></li>
      </ul>
    </div>
    <div class="pcard">
      <h3>默认值与交互<span class="rt r">需确认</span></h3>
      <ul>
        <li><strong>借据默认全选</strong>，但不在界面上标注"默认全选"字样</li>
        <li><strong>天数默认 1 天</strong>，用加减器（ − / + 按钮）步进调整，步进为 1 天</li>
        <li>支持手动输入天数，仅接受正整数</li>
        <li>去掉快捷天数按钮（7/15/30），减少选择干扰</li>
        <li>天数区域右上角直接展示<strong>「最多 X 天」</strong>，X 由策略输出<span class="rt r">策略</span></li>
        <li>用户改动借据或天数 → 旧试算立即失效 → 自动重新试算<span class="rt r">R13</span></li>
        <li>加减器不允许低于 1 天、不允许超过批次上限</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>借据展示调整</h3>
      <ul>
        <li>标题改为<strong>「可展期借据」</strong>，语义更准确</li>
        <li>去掉借据编号（脱敏编号对用户无意义），改为<strong>原始借款金额 + 借款日期</strong></li>
        <li>每行右侧展示该笔借据的<strong>最多可展期天数</strong>（策略输出）</li>
        <li>每行左侧保留「原还款日 → 新还款日」的日期变化</li>
        <li>逾期标签保留，帮助用户识别紧急程度</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>信息分层：首屏 vs 弹窗</h3>
      <ul>
        <li><strong>首屏必须可见</strong>：新还款日、合计支付金额（展期费+逾期费）、方案有效期倒计时</li>
        <li><strong>方案页简提示</strong>：展示“确认后 24 小时内完成支付，超时自动取消”，不放入费用与还款日说明弹窗</li>
        <li><strong>S2支付页正文承载</strong>：展期天数、借据数、展期费用、逾期费用（有才展示）、合计，以及按借据分组展示所有剩余未还期次的展期前/后还款日变化</li>
        <li><strong>不展示计算公式</strong>：用户侧不展示本金、日息、乘法过程，仅展示最终金额<span class="rt r">已确认</span></li>
        <li>逾期费用为 0 时该行<strong>不展示</strong>，避免出现"逾期费 $0"的困惑<span class="rt w">条件展示</span></li>
        <li>展期成立后须在 <strong>24 小时</strong>内完成支付，超时自动取消<span class="rt r">时限</span></li>
      </ul>
    </div>
    <div class="pcard">
      <h3>可交互验证</h3>
      <ul>
        <li>点击借据行可勾选/取消，批次上限与超限天数按钮实时联动<span class="rt g">可交互</span></li>
        <li>点击「查看逐笔明细与费用说明」打开底部弹窗</li>
        <li>点击快捷天数可切换，输入框同步</li>
        <li>两台设备独立交互，可分别操作对比</li>
      </ul>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：S1 明细弹窗 ════════════ -->
<div class="stage" id="s-s1b">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-s1" data-sheet="open"></div>
  <div class="panel">
    <div class="pcard">
      <h3>明细弹窗（Bottom Sheet）</h3>
      <ul>
        <li>本页展示弹窗<strong>打开状态</strong>，与上一页签为同一页面的两个状态</li>
        <li>由「查看逐笔明细与费用说明」触发，底部上滑出现</li>
        <li>最大高度 74% 屏高，内容超出时弹窗内部滚动，背景页不滚动</li>
        <li><strong>三种关闭方式</strong>：点击遮罩、右上角 ✕、底部「我知道了」</li>
        <li>顶部留有下拉手柄样式，提示可下滑关闭（实现时建议支持手势）</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>弹窗内容结构</h3>
      <ul>
        <li><strong>顶部汇总</strong>：展期天数、借据数量、合计支付（黄底强调）</li>
        <li><strong>逐笔明细</strong>：每笔独立块，含原/新还款日、待还金额、展期费、逾期利息、小计</li>
        <li><strong>费用说明</strong>：用自然语言写清计算方式，标注无隐藏费用<span class="rt w">合规</span></li>
        <li>逾期借据带「逾期 X 天」标签，与首屏保持一致</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>为什么用弹窗而非新页面</h3>
      <ul>
        <li>弹窗<strong>不脱离当前上下文</strong>，关闭即回到方案页，无需重新加载</li>
        <li>避免「进详情页 → 返回」造成的方向感丢失</li>
        <li>不产生新的路由层级，返回键行为更可预期</li>
        <li>用户多为查看确认而非操作，弹窗足够承载<span class="rt g">体验</span></li>
      </ul>
    </div>
    <div class="pcard">
      <h3>弹窗打开时的约束</h3>
      <ul>
        <li>背景页内容禁止滚动，防止穿透</li>
        <li>报价倒计时<strong>继续走</strong>，不因弹窗暂停</li>
        <li>弹窗打开期间若报价过期，关闭后需提示并刷新方案<span class="rt r">R14</span></li>
        <li>弹窗内为纯展示，<strong>不提供任何修改入口</strong>，避免与首屏状态冲突</li>
      </ul>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：S2 ════════════ -->
<div class="stage" id="s-s2">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-s2"></div>
  <div class="panel">
    <div class="pcard">
      <h3>S2 支付方式直接展示</h3>
      <ul>
        <li>默认展示离线支付“部分支付处理中”状态：已支付金额、剩余待支付金额、剩余支付时间</li>
        <li>未完成全额支付前，展期方案和新还款计划不生效<span class="rt w">关键</span></li>
        <li>支付页直接展示两种支付方式，不再使用支付方式底部弹窗</li>
        <li><strong>银行转账</strong>：推荐，几分钟到账，手续费 0 MXN</li>
        <li><strong>现金支付</strong>：约半小时到账，手续费 10 MXN</li>
        <li>支付方式卡片使用大圆角浅灰背景、到账时间、手续费和右箭头，参考 HolaFina 现有支付页风格</li>
        <li>默认选中推荐的银行转账，点击其他方式切换选中态</li>
        <li>底部「支付 $167.50」按钮在支付、账务和计划更新全部成功后，直接进入借据详情并展示最新还款计划</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>支付后路径</h3>
      <ul>
        <li><strong>成功生效</strong> → 回调重校验 → 更新最新还款计划 → 直接进入借据详情</li>
        <li><strong>已扣款但计划未更新</strong> → 保持支付中状态并执行自动补偿，不展示独立结果页<span class="rt w">关键</span></li>
        <li><strong>未成功或超时</strong> → 已支付金额按正常还款入账，关闭展期状态；APP 不展示展期结果或失败页</li>
        <li><strong>用户取消</strong> → 停留 S2，订单保留至超时</li>
        <li>回调幂等：同一支付流水不重复更新计划<span class="rt r">R16</span></li>
      </ul>
    </div>
    <div class="i18n">
      <h3>🌐 S2 支付方式对照</h3>
      <table>
        <thead><tr><th>位置</th><th>中文</th><th>西语</th></tr></thead>
        <tbody>
          <tr><td>页面标题</td><td>支付展期费用</td><td>Pagar extensión</td></tr>
          <tr><td>金额标签</td><td>应付金额</td><td>Monto a pagar</td></tr>
          <tr><td>支付时限</td><td>请在 24 小时内完成支付</td><td>Paga dentro de 24 horas</td></tr>
          <tr><td>支付方式入口</td><td>点击支付后选择</td><td>Elegir al pagar</td></tr>
          <tr><td>弹窗标题</td><td>选择支付方式</td><td>Elige método de pago</td></tr>
          <tr><td>推荐方式</td><td>推荐 · 银行转账</td><td>Recomendado · Transf. bancaria</td></tr>
          <tr><td>到账时间</td><td>几分钟到账</td><td>Acreditación en minutos</td></tr>
          <tr><td>推荐手续费</td><td>手续费 0 MXN</td><td>Comisión 0 MXN</td></tr>
          <tr><td>现金方式</td><td>现金支付</td><td>Pago en efectivo</td></tr>
          <tr><td>现金到账</td><td>约半小时到账</td><td>Acreditación en media hora</td></tr>
          <tr><td>现金手续费</td><td>手续费 10 MXN</td><td>Comisión 10 MXN</td></tr>
          <tr><td>安全提示</td><td>请妥善保存支付凭证</td><td>Guarda bien el recibo</td></tr>
          <tr><td>金额说明</td><td>支付金额须与确认方案完全一致</td><td>El monto debe coincidir exactamente con la oferta confirmada</td></tr>
          <tr><td>支付失败</td><td>支付未成功，请重试或更换支付方式</td><td>Pago no exitoso, intenta de nuevo o cambia el método de pago</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
</div>

<!-- ════════════ 舞台：S2 支付中 ════════════ -->
<div class="stage" id="s-s2p">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-s2" data-state="partial"></div>
  <div class="panel">
    <div class="pcard">
      <h3>S2 部分支付处理中（独立状态）</h3>
      <ul>
        <li>该页面只对应已有的展期支付订单，不是新的展期申请</li>
        <li>展示支付处理中、已支付金额、剩余待支付金额、剩余支付时间</li>
        <li>用户可以继续支付当前订单剩余金额，但不能再次发起展期</li>
        <li>未全额支付前不更新还款计划、不展示展期成功</li>
      </ul>
    </div>
  </div>
</div>
</div>

<style>.csw{width:720px;min-width:720px}</style>

<!-- ════════════ 模板：C1 发起展期 ════════════ -->
<template id="tpl-c1">
  <div class="csw">
    <div class="csh"><t zh="催收系统 — 发起展期" es="Sistema de Cobranza — Solicitar extensión"></t></div>
    <div class="csb">
      <div class="csc">
        <h4><t zh="用户信息" es="Información del cliente"></t></h4>
        <div class="csg">
          <div class="csf"><label><t zh="用户ID" es="ID de cliente"></t></label><div class="v">U20260001</div></div>
          <div class="csf"><label><t zh="姓名" es="Nombre"></t></label><div class="v">María García López</div></div>
          <div class="csf"><label><t zh="联系电话" es="Teléfono"></t></label><div class="v">+52 55 ****7890</div></div>
          <div class="csf"><label><t zh="展期资格" es="Elegibilidad"></t></label><div class="v"><span class="stag ap"><t zh="可展期" es="Elegible"></t></span></div></div>
          <div class="csf"><label><t zh="策略版本" es="Versión de política"></t></label><div class="v">v2026.09.15</div></div>
          <div class="csf"><label><t zh="资格有效期" es="Válido hasta"></t></label><div class="v">2026-09-25 23:59</div></div>
        </div>
      </div>

      <div class="csc">
        <h4><t zh="可展期借据（勾选后发起）" es="Préstamos elegibles (selecciona para continuar)"></t></h4>
        <table class="cst">
          <thead><tr>
            <th style="width:24px;"><input type="checkbox" checked></th>
            <th><t zh="借据编号" es="No. de préstamo"></t></th>
            <th><t zh="原还款日" es="Vencimiento"></t></th>
            <th><t zh="待还金额" es="Monto pendiente"></t></th>
            <th>DPD</th>
            <th><t zh="剩余本金" es="Capital"></t></th>
            <th><t zh="展期日息" es="Tasa diaria"></t></th>
          </tr></thead>
          <tbody>
            <tr><td><input type="checkbox" checked></td><td>LN20260001-1234</td><td>2026-09-12</td><td>$1,500.00</td><td style="color:#ff3b30;font-weight:600;">9</td><td>$1,500</td><td><t zh="日息 2%" es="Tasa 2%"></t></td></tr>
            <tr><td><input type="checkbox" checked></td><td>LN20260001-5678</td><td>2026-09-28</td><td>$2,300.00</td><td>—</td><td>$3,500</td><td><t zh="日息 2%" es="Tasa 2%"></t></td></tr>
            <tr><td><input type="checkbox"></td><td>LN20260001-9012</td><td>2026-10-05</td><td>$800.00</td><td>—</td><td>$800</td><td><t zh="日息 2%" es="Tasa 2%"></t></td></tr>
          </tbody>
        </table>
        <div style="margin-top:10px;font-size:11.5px;color:#e2590c;background:#fff5ed;border:1px solid #ffdcc2;padding:8px 10px;border-radius:7px;">⚠️ <t zh="已选 2 笔 · 总剩余本金 $5,000 · 日息 2% · 最长 15 天" es="2 seleccionados · Capital $5,000 · Tasa 2% · Máx. 15 días"></t></div>
      </div>

      <div class="csc">
        <h4><t zh="展期天数 & 服务端试算" es="Días de extensión & cálculo del servidor"></t></h4>
        <div style="display:flex;gap:10px;align-items:center;margin-bottom:13px;flex-wrap:wrap;">
          <label style="font-size:12px;color:#69727d;"><t zh="展期天数：" es="Días:"></t></label>
          <input type="number" value="15" style="width:88px;height:31px;border:1px solid #dde2e9;border-radius:6px;padding:0 8px;font-size:12px;font-weight:600;">
          <span style="font-size:11.5px;color:#8a939e;"><t zh="天（策略上限 15 天）" es="días (máx. 15 según política)"></t></span>
          <button class="csbtn p"><t zh="请求试算" es="Calcular"></t></button>
        </div>
        <table class="cst">
          <thead><tr>
            <th><t zh="借据编号" es="No. de préstamo"></t></th>
            <th><t zh="原还款日" es="Fecha original"></t></th>
            <th><t zh="新还款日" es="Nueva fecha"></t></th>
            <th><t zh="展期费" es="Cargo"></t></th>
            <th><t zh="逾期费" es="Mora"></t></th>
            <th><t zh="待支付" es="A pagar"></t></th>
          </tr></thead>
          <tbody>
            <tr><td>LN20260001-1234</td><td>2026-09-12</td><td style="color:#0a84ff;font-weight:700;">2026-09-13</td><td>$30.00</td><td>$67.50</td><td style="font-weight:700;">$97.50</td></tr>
            <tr><td>LN20260001-5678</td><td>2026-09-28</td><td style="color:#0a84ff;font-weight:700;">2026-09-22</td><td>$70.00</td><td>—</td><td style="font-weight:700;">$70.00</td></tr>
          </tbody>
          <tfoot><tr><td colspan="5" style="text-align:right;"><t zh="合计应付：" es="Total a pagar:"></t></td><td style="font-size:14px;color:#ff6a13;font-weight:800;">$167.50</td></tr></tfoot>
        </table>
        <div style="font-size:10.5px;color:#a8b0b9;margin-top:8px;font-style:italic;"><t zh="* 费用由服务端计算 · 展期成立后 24 小时内需完成支付 · 报价 Q20260921-001" es="* Montos calculados por el servidor · Pago requerido en 24 horas · Oferta Q20260921-001"></t></div>
      </div>

      <div class="csc">
        <h4><t zh="沟通记录（必填）" es="Registro de contacto (obligatorio)"></t></h4>
        <div class="csg c2">
          <div class="csf"><label><t zh="沟通结果 *" es="Resultado del contacto *"></t></label>
            <select class="cssel">
              <option class="js-txt" data-zh="用户同意" data-es="Acepta"></option>
              <option class="js-txt" data-zh="用户考虑中" data-es="Lo está considerando"></option>
              <option class="js-txt" data-zh="用户拒绝" data-es="Rechaza"></option>
            </select>
          </div>
          <div class="csf"><label><t zh="用户意愿 *" es="Iniciativa *"></t></label>
            <select class="cssel">
              <option class="js-txt" data-zh="主动要求" data-es="Solicitud propia"></option>
              <option class="js-txt" data-zh="催员建议后同意" data-es="Acepta tras sugerencia"></option>
              <option class="js-txt" data-zh="其他" data-es="Otro"></option>
            </select>
          </div>
        </div>
        <div style="margin-top:11px;">
          <label style="font-size:11px;color:#8a939e;display:block;margin-bottom:4px;"><t zh="备注（选填，最多 500 字）" es="Notas (opcional, máx. 500 caracteres)"></t></label>
          <textarea class="csta js-val" data-zh="用户来电表示近期资金周转困难，希望延长 15 天还款期限，承诺届时一定还款。" data-es="El cliente llamó indicando dificultades de liquidez, solicita extender 15 días y se compromete a pagar en la nueva fecha."></textarea>
        </div>
      </div>

      <div style="text-align:right;padding-bottom:16px;">
        <button class="csbtn g" style="margin-right:10px;"><t zh="取消" es="Cancelar"></t></button>
        <button class="csbtn p"><t zh="提交展期申请" es="Enviar solicitud"></t></button>
      </div>
    </div>
  </div>
</template>

<!-- ════════════ 模板：C2 展期审批 ════════════ -->
<template id="tpl-c2">
  <div class="csw">
    <div class="csh"><t zh="催收系统 — 展期审批" es="Sistema de Cobranza — Aprobación de extensión"></t></div>
    <div class="csb">
      <div class="csc">
        <h4><t zh="待审批列表" es="Solicitudes pendientes"></t></h4>
        <table class="cst">
          <thead><tr>
            <th><t zh="申请编号" es="No. solicitud"></t></th>
            <th><t zh="用户" es="Cliente"></t></th>
            <th><t zh="借据数" es="Préstamos"></t></th>
            <th><t zh="天数" es="Días"></t></th>
            <th><t zh="金额" es="Monto"></t></th>
            <th><t zh="发起人" es="Solicitante"></t></th>
            <th><t zh="状态" es="Estado"></t></th>
            <th><t zh="操作" es="Acción"></t></th>
          </tr></thead>
          <tbody>
            <tr style="background:#fff8e8;"><td>EXT20260921001</td><td>María García</td><td>2</td><td>15</td><td style="font-weight:700;">$167.50</td><td>张三</td><td><span class="stag pd"><t zh="待审批" es="Pendiente"></t></span></td><td><span style="color:#0a84ff;cursor:pointer;font-weight:600;"><t zh="审批" es="Revisar"></t></span></td></tr>
            <tr><td>EXT20260920003</td><td>José Hernández</td><td>1</td><td>7</td><td style="font-weight:700;">$80.00</td><td>李四</td><td><span class="stag ap"><t zh="已通过" es="Aprobada"></t></span></td><td><span style="color:#8a939e;cursor:pointer;"><t zh="查看" es="Ver"></t></span></td></tr>
            <tr><td>EXT20260919002</td><td>Ana Martínez</td><td>3</td><td>30</td><td style="font-weight:700;">$600.00</td><td>张三</td><td><span class="stag rj"><t zh="已拒绝" es="Rechazada"></t></span></td><td><span style="color:#8a939e;cursor:pointer;"><t zh="查看" es="Ver"></t></span></td></tr>
          </tbody>
        </table>
      </div>

      <div class="csc" style="border:2px solid #0a84ff;">
        <h4><t zh="审批详情 — EXT20260921001" es="Detalle de aprobación — EXT20260921001"></t></h4>
        <div class="csg" style="margin-bottom:13px;">
          <div class="csf"><label><t zh="用户ID" es="ID de cliente"></t></label><div class="v">U20260001</div></div>
          <div class="csf"><label><t zh="姓名" es="Nombre"></t></label><div class="v">María García López</div></div>
          <div class="csf"><label><t zh="发起渠道" es="Canal"></t></label><div class="v"><t zh="催收端 · 催员张三" es="Cobranza · Agente 张三"></t></div></div>
          <div class="csf"><label><t zh="展期天数" es="Días de extensión"></t></label><div class="v" style="color:#0a84ff;font-size:14px;font-weight:800;"><t zh="15 天" es="15 días"></t></div></div>
          <div class="csf"><label><t zh="合计金额" es="Monto total"></t></label><div class="v" style="color:#ff6a13;font-size:14px;font-weight:800;">$167.50</div></div>
          <div class="csf"><label><t zh="报价有效期" es="Oferta válida hasta"></t></label><div class="v">2026-09-21 10:30</div></div>
        </div>

        <div style="font-size:12px;font-weight:700;margin-bottom:8px;"><t zh="借据明细" es="Detalle de préstamos"></t></div>
        <table class="cst" style="margin-bottom:13px;">
          <thead><tr>
            <th><t zh="借据编号" es="No. de préstamo"></t></th>
            <th><t zh="原还款日" es="Fecha original"></t></th>
            <th><t zh="新还款日" es="Nueva fecha"></t></th>
            <th>DPD</th>
            <th><t zh="展期费" es="Cargo"></t></th>
            <th><t zh="逾期费" es="Mora"></t></th>
            <th><t zh="待支付" es="A pagar"></t></th>
          </tr></thead>
          <tbody>
            <tr><td>LN20260001-1234</td><td>2026-09-12</td><td style="color:#0a84ff;font-weight:700;">2026-09-13</td><td style="color:#ff3b30;font-weight:600;">9</td><td>$30.00</td><td>$67.50</td><td style="font-weight:700;">$97.50</td></tr>
            <tr><td>LN20260001-5678</td><td>2026-09-28</td><td style="color:#0a84ff;font-weight:700;">2026-09-22</td><td>—</td><td>$70.00</td><td>—</td><td style="font-weight:700;">$70.00</td></tr>
          </tbody>
        </table>

        <div style="font-size:12px;font-weight:700;margin-bottom:8px;"><t zh="沟通记录" es="Registro de contacto"></t></div>
        <div class="csg c2" style="margin-bottom:11px;">
          <div class="csf"><label><t zh="沟通结果" es="Resultado"></t></label><div class="v"><t zh="用户同意" es="Acepta"></t></div></div>
          <div class="csf"><label><t zh="用户意愿" es="Iniciativa"></t></label><div class="v"><t zh="主动要求" es="Solicitud propia"></t></div></div>
        </div>
        <div class="csf" style="margin-bottom:13px;"><label><t zh="催员备注" es="Notas del agente"></t></label><div class="v" style="margin-top:4px;line-height:1.6;font-weight:400;"><t zh="用户来电表示近期资金周转困难，希望延长 15 天还款期限，承诺届时一定还款。" es="El cliente llamó indicando dificultades de liquidez, solicita extender 15 días y se compromete a pagar en la nueva fecha."></t></div></div>

        <div style="font-size:12px;font-weight:700;margin-bottom:8px;"><t zh="版本信息（审计追溯）" es="Versiones (auditoría)"></t></div>
        <div class="csg" style="margin-bottom:13px;">
          <div class="csf"><label><t zh="策略版本" es="Política"></t></label><div class="v">v2026.09.15</div></div>
          <div class="csf"><label><t zh="展期日息" es="Tasa diaria"></t></label><div class="v">2% (0.02)</div></div>
          <div class="csf"><label><t zh="报价版本" es="Oferta"></t></label><div class="v">Q20260921-001</div></div>
        </div>

        <div style="border-top:1px solid #f0f2f5;padding-top:13px;display:flex;gap:11px;align-items:flex-end;">
          <div style="flex:1;">
            <label style="font-size:11px;color:#8a939e;display:block;margin-bottom:4px;"><t zh="审批意见（拒绝时必填）" es="Comentario (obligatorio al rechazar)"></t></label>
            <textarea class="csta"></textarea>
          </div>
          <div style="display:flex;gap:8px;">
            <button class="csbtn d"><t zh="拒绝" es="Rechazar"></t></button>
            <button class="csbtn s"><t zh="通过" es="Aprobar"></t></button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<!-- ════════════ 模板：C3 展期详情 ════════════ -->
<template id="tpl-c3">
  <div class="csw">
    <div class="csh"><t zh="催收系统 — 展期详情" es="Sistema de Cobranza — Detalle de extensión"></t></div>
    <div class="csb">
      <div class="csc">
        <h4><t zh="基本信息" es="Información general"></t></h4>
        <div class="csg">
          <div class="csf"><label><t zh="申请编号" es="No. solicitud"></t></label><div class="v">EXT20260921001</div></div>
          <div class="csf"><label><t zh="当前状态" es="Estado actual"></t></label><div class="v"><span class="stag sc"><t zh="展期成功" es="Extensión exitosa"></t></span></div></div>
          <div class="csf"><label><t zh="发起渠道" es="Canal"></t></label><div class="v"><t zh="催收端" es="Cobranza"></t></div></div>
          <div class="csf"><label><t zh="用户" es="Cliente"></t></label><div class="v">María García (U20260001)</div></div>
          <div class="csf"><label><t zh="展期天数" es="Días"></t></label><div class="v" style="color:#0a84ff;font-weight:800;"><t zh="15 天" es="15 días"></t></div></div>
          <div class="csf"><label><t zh="合计支付" es="Total pagado"></t></label><div class="v" style="color:#ff6a13;font-weight:800;">$167.50 MXN</div></div>
        </div>
      </div>

      <div class="csc">
        <h4><t zh="借据信息" es="Detalle de préstamos"></t></h4>
        <table class="cst">
          <thead><tr>
            <th><t zh="借据编号" es="No. de préstamo"></t></th>
            <th><t zh="原还款日" es="Fecha original"></t></th>
            <th><t zh="新还款日" es="Nueva fecha"></t></th>
            <th><t zh="展期费" es="Cargo"></t></th>
            <th><t zh="逾期费" es="Mora"></t></th>
            <th><t zh="待支付" es="A pagar"></t></th>
            <th><t zh="计划更新" es="Plan"></t></th>
          </tr></thead>
          <tbody>
            <tr><td>LN20260001-1234</td><td>2026-09-12</td><td style="color:#0a84ff;font-weight:700;">2026-09-13</td><td>$30.00</td><td>$67.50</td><td style="font-weight:700;">$97.50</td><td><span class="stag ap"><t zh="成功" es="OK"></t></span></td></tr>
            <tr><td>LN20260001-5678</td><td>2026-09-28</td><td style="color:#0a84ff;font-weight:700;">2026-09-22</td><td>$70.00</td><td>—</td><td style="font-weight:700;">$70.00</td><td><span class="stag ap"><t zh="成功" es="OK"></t></span></td></tr>
          </tbody>
          <tfoot><tr><td colspan="5" style="text-align:right;"><t zh="合计：" es="Total:"></t></td><td style="color:#ff6a13;font-weight:800;">$167.50</td><td></td></tr></tfoot>
        </table>
      </div>

      <div class="csc">
        <h4><t zh="版本信息（审计追溯）" es="Versiones (auditoría)"></t></h4>
        <div class="csg">
          <div class="csf"><label><t zh="策略版本" es="Política"></t></label><div class="v">v2026.09.15</div></div>
          <div class="csf"><label><t zh="展期日息" es="Tasa diaria"></t></label><div class="v">2% (0.02)</div></div>
          <div class="csf"><label><t zh="报价版本" es="Oferta"></t></label><div class="v">Q20260921-001</div></div>
          <div class="csf"><label><t zh="原计划版本" es="Plan anterior"></t></label><div class="v">PLAN-2026-V3</div></div>
          <div class="csf"><label><t zh="新计划版本" es="Plan nuevo"></t></label><div class="v">PLAN-2026-V4</div></div>
          <div class="csf"><label><t zh="支付流水号" es="No. de pago"></t></label><div class="v">PAY20260921001</div></div>
        </div>
      </div>

      <div class="csc">
        <h4><t zh="操作时间线（全链路留痕）" es="Línea de tiempo (trazabilidad completa)"></t></h4>
        <div class="tl">
          <div class="tli"><div class="tm">2026-09-21 09:28</div><div class="tx"><t zh="催员张三获取展期资格 · 策略返回 3 笔可展期借据" es="El agente 张三 consultó la elegibilidad · 3 préstamos elegibles"></t></div></div>
          <div class="tli"><div class="tm">2026-09-21 09:30</div><div class="tx"><t zh="提交展期申请 · 选择 2 笔 · 展期 15 天 · 报价 Q20260921-001 · 进入审批" es="Solicitud enviada · 2 préstamos · 15 días · Oferta Q20260921-001 · En aprobación"></t></div></div>
          <div class="tli"><div class="tm">2026-09-21 09:35</div><div class="tx"><t zh="主管王五审批通过 · 状态变更为待用户确认" es="Supervisor 王五 aprobó · Estado: pendiente de confirmación del cliente"></t></div></div>
          <div class="tli"><div class="tm">2026-09-21 09:40</div><div class="tx"><t zh="推送用户确认通知（Push + 短信）" es="Notificación enviada al cliente (Push + SMS)"></t></div></div>
          <div class="tli"><div class="tm">2026-09-21 09:42</div><div class="tx"><t zh="用户在 APP 确认方案 · 勾选展期协议 v1.0" es="El cliente confirmó en la app · Aceptó los términos v1.0"></t></div></div>
          <div class="tli"><div class="tm">2026-09-21 09:44</div><div class="tx"><t zh="创建支付订单前重校验通过 · 报价、资格、版本、金额一致" es="Revalidación previa al pago OK · Oferta, elegibilidad, versiones y monto coinciden"></t></div></div>
          <div class="tli"><div class="tm">2026-09-21 09:45</div><div class="tx"><t zh="用户支付 $167.50 · 方式 SPEI · 流水 PAY20260921001" es="Pago de $167.50 · SPEI · Folio PAY20260921001"></t></div></div>
          <div class="tli"><div class="tm">2026-09-21 09:45</div><div class="tx"><t zh="回调幂等校验通过 · 2 笔借据计划在同一事务中更新成功" es="Callback idempotente OK · 2 planes actualizados en la misma transacción"></t></div></div>
          <div class="tli"><div class="tm">2026-09-21 09:46</div><div class="tx"><t zh="展期成功 · 通知用户新还款日（Push + 短信）" es="Extensión exitosa · Cliente notificado de su nueva fecha (Push + SMS)"></t></div></div>
        </div>
      </div>

      <div class="csc">
        <h4><t zh="沟通与审批记录" es="Contacto y aprobación"></t></h4>
        <div class="csg c2" style="margin-bottom:11px;">
          <div class="csf"><label><t zh="沟通结果" es="Resultado"></t></label><div class="v"><t zh="用户同意" es="Acepta"></t></div></div>
          <div class="csf"><label><t zh="用户意愿" es="Iniciativa"></t></label><div class="v"><t zh="主动要求" es="Solicitud propia"></t></div></div>
          <div class="csf"><label><t zh="发起人" es="Solicitante"></t></label><div class="v"><t zh="张三（催收一组）" es="张三 (Equipo 1)"></t></div></div>
          <div class="csf"><label><t zh="审批人" es="Aprobador"></t></label><div class="v"><t zh="王五（催收主管）" es="王五 (Supervisor)"></t></div></div>
        </div>
        <div class="csf"><label><t zh="审批意见" es="Comentario de aprobación"></t></label><div class="v" style="margin-top:4px;font-weight:400;"><t zh="金额合理，同意展期。" es="Monto razonable, extensión aprobada."></t></div></div>
      </div>
    </div>
  </div>
</template>

<!-- ════════════ 舞台：C1 / C2 / C3 ════════════ -->
<div class="stage" id="s-c1">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-c1"></div>
  <div class="panel">
    <div class="pcard">
      <h3>C1 催收端发起展期</h3>
      <ul>
        <li>催员在债务详情页点击「发起展期」，系统<strong>实时</strong>获取资格</li>
        <li>与 APP 使用同一资格、天数、定价、日期和费用试算口径<span class="rt r">一致性</span></li>
        <li>催收端展示完整借据编号（APP 端脱敏）</li>
        <li>沟通结果和用户意愿为必填，用于审批参考和审计</li>
        <li>不可展期时展示不可发起原因并关闭弹窗</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>为什么催收端也要西语版</h3>
      <ul>
        <li>墨西哥本地催员使用西语界面，<strong>右侧即为实际部署版本</strong></li>
        <li>左侧中文版供国内产品和研发团队评审、验收使用</li>
        <li>两版字段完全一致，仅界面语言不同<span class="rt g">对照</span></li>
        <li>催员姓名、团队等内部信息保留原文，不做翻译</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>提交后状态流转</h3>
      <ul>
        <li>需要审批 → <strong>approval_pending</strong></li>
        <li>无需审批 → <strong>pending_user_confirm</strong></li>
        <li>审批通过后仍需用户确认并支付，<strong>不直接修改还款计划</strong><span class="rt w">关键</span></li>
      </ul>
    </div>
  </div>
</div>
</div>

<div class="stage" id="s-c2">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-c2"></div>
  <div class="panel">
    <div class="pcard">
      <h3>C2 展期审批</h3>
      <ul>
        <li>审批列表展示全部申请，待审批记录淡黄底高亮</li>
        <li>点击「审批」展开详情面板，信息一站式呈现</li>
        <li>详情含：用户信息、借据明细、沟通记录、版本信息</li>
        <li>报价有效期提醒审批时效，过期需重新试算<span class="rt w">注意</span></li>
      </ul>
    </div>
    <div class="pcard">
      <h3>审批操作规则</h3>
      <ul>
        <li><strong>通过</strong>：意见选填 → pending_user_confirm</li>
        <li><strong>拒绝</strong>：原因<strong>必填</strong> → rejected<span class="rt r">规则</span></li>
        <li>通过后<strong>不直接修改还款计划</strong><span class="rt w">关键</span></li>
        <li>审批人、意见、时间全部留痕</li>
      </ul>
    </div>
    <div class="i18n">
      <h3>🌐 状态与通知对照</h3>
      <table>
        <thead><tr><th>状态码</th><th>中文</th><th>西语</th></tr></thead>
        <tbody>
          <tr><td>eligible</td><td>满足资格</td><td>Elegible</td></tr>
          <tr><td>approval_pending</td><td>待审批</td><td>Pendiente de aprobación</td></tr>
          <tr><td>pending_user_confirm</td><td>待用户确认</td><td>Pendiente de tu confirmación</td></tr>
          <tr><td>pending_payment</td><td>待支付</td><td>Pendiente de pago</td></tr>
          <tr><td>processing</td><td>处理中</td><td>En proceso</td></tr>
          <tr><td>success</td><td>展期成功</td><td>Extensión exitosa</td></tr>
          <tr><td>rejected</td><td>已拒绝</td><td>Rechazada</td></tr>
          <tr><td>expired</td><td>已过期</td><td>Expirada</td></tr>
          <tr><td>failed</td><td>失败</td><td>Fallida</td></tr>
          <tr class="grp"><td colspan="3">用户通知文案</td></tr>
          <tr><td>N1 待确认</td><td>您有一笔展期方案待确认，请在 APP 中查看</td><td>Tienes un plan de extensión pendiente de confirmar, revísalo en la app</td></tr>
          <tr><td>N2 审批通过</td><td>您的展期申请已通过，请确认并支付</td><td>Tu solicitud de extensión fue aprobada, confirma y realiza el pago</td></tr>
          <tr><td>N3 审批拒绝</td><td>您的展期申请未通过，可查看原因</td><td>Tu solicitud de extensión no fue aprobada, consulta el motivo</td></tr>
          <tr><td>N4 待支付</td><td>您有一笔展期订单待支付，请在有效期内完成</td><td>Tienes una orden de extensión pendiente, complétala antes de que expire</td></tr>
          <tr><td>N7 成功</td><td>展期成功！您的新还款日为 27/09/2026</td><td>¡Extensión exitosa! Tu nueva fecha de pago es el 27/09/2026</td></tr>
          <tr><td>N8 失败退款</td><td>展期处理失败，退款将在 3 个工作日内返还</td><td>La extensión falló, el reembolso se procesará en 3 días hábiles</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
</div>

<div class="stage" id="s-c3">
<div class="stage-inner">
  <div class="pair" data-tpl="tpl-c3"></div>
  <div class="panel">
    <div class="pcard">
      <h3>C3 展期详情</h3>
      <ul>
        <li>在债务详情页的「展期记录」入口查看</li>
        <li>展示全链路信息，状态和金额与 APP 端一致<span class="rt r">R17</span></li>
        <li>借据表格额外展示每笔的「计划更新」结果</li>
        <li>版本信息用于回溯策略和定价一致性</li>
      </ul>
    </div>
    <div class="pcard">
      <h3>审计留痕要求</h3>
      <ul>
        <li>资格请求时间、策略结果、版本、借据快照</li>
        <li>用户或催员选择的借据及天数</li>
        <li>原计划版本、试算结果、报价版本和有效期</li>
        <li>用户确认记录、协议版本、渠道及设备信息</li>
        <li>审批记录、意见、操作人</li>
        <li>支付订单、流水、回调次数、幂等结果</li>
        <li>计划变更前后快照、费用入账、补偿记录<span class="rt g">审计</span></li>
      </ul>
    </div>
    <div class="i18n">
      <h3>🌐 异常场景提示对照</h3>
      <table>
        <thead><tr><th>场景</th><th>中文</th><th>西语</th></tr></thead>
        <tbody>
          <tr><td>资格查询失败</td><td>暂时无法获取展期资格，请稍后重试</td><td>No se puede obtener la elegibilidad, intenta más tarde</td></tr>
          <tr><td>无可展期借据</td><td>当前没有可展期的借据</td><td>No hay préstamos elegibles para extensión</td></tr>
          <tr><td>天数为空</td><td>请输入展期天数</td><td>Ingresa los días de extensión</td></tr>
          <tr><td>格式错误</td><td>展期天数必须为正整数</td><td>Los días deben ser un número entero positivo</td></tr>
          <tr><td>超过上限</td><td>本次最多可展期 X 天</td><td>Máximo X días para esta extensión</td></tr>
          <tr><td>天数不足</td><td>展期后还款日必须晚于当前日期</td><td>La nueva fecha debe ser posterior a hoy</td></tr>
          <tr><td>试算失败</td><td>暂时无法计算展期方案，请稍后重试</td><td>No se pudo calcular la extensión, intenta más tarde</td></tr>
          <tr><td>报价过期</td><td>展期方案已过期，请重新确认</td><td>La oferta ha expirado, confirma nuevamente</td></tr>
          <tr><td>状态变化</td><td>借据状态已变化，请重新获取方案</td><td>El estado del préstamo cambió, obtén un nuevo plan</td></tr>
          <tr><td>重复提交</td><td>请勿重复提交</td><td>No envíes solicitudes duplicadas</td></tr>
          <tr><td>支付失败</td><td>支付未成功，请重试或更换支付方式</td><td>Pago no exitoso, intenta de nuevo o cambia el método de pago</td></tr>
          <tr><td>已扣款未生效</td><td>支付已收到，展期正在处理中</td><td>Pago recibido, la extensión está en proceso</td></tr>
          <tr><td>批量部分更新</td><td>展期正在处理中，请勿重复支付</td><td>Extensión en proceso, no realices pagos duplicados</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
</div>

<script>
/* ═══ 双语渲染：同一模板渲染两次 ═══ */
var LANGS=[{k:'zh',lb:'🇨🇳 中文版'},{k:'es',lb:'🇲🇽 Español（实际上线版）'}];
document.querySelectorAll('.pair').forEach(function(pair){
  var tpl=document.getElementById(pair.dataset.tpl);
  if(!tpl) return;
  LANGS.forEach(function(L){
    var wrap=document.createElement('div');
    wrap.className='ph-wrap';
    var lbl=document.createElement('div');
    lbl.className='ph-lbl '+L.k;
    lbl.textContent=L.lb;
    wrap.appendChild(lbl);
    var node=tpl.content.cloneNode(true);
    // 按状态渲染：normal 默认常态，partial 仅渲染支付处理中状态
    var viewState=pair.dataset.state||'normal';
    node.querySelectorAll('[data-state]').forEach(function(el){
      var allowedStates=String(el.dataset.state || '').split(',').map(function(state){ return state.trim(); });
      if(allowedStates.indexOf(viewState) === -1) el.remove();
    });
    // 支付中状态不自动轮播，避免用户误以为可以切换其他方案
    if(viewState!=='normal'){
      node.querySelectorAll('[data-autoplay]').forEach(function(el){ el.removeAttribute('data-autoplay'); });
    }
    // 普通文本节点
    node.querySelectorAll('t').forEach(function(t){
      var txt=t.getAttribute(L.k);
      t.textContent = (txt===null?'':txt);
    });
    // 表单控件的值（textarea / input）——不能用 <t> 包裹
    node.querySelectorAll('.js-val').forEach(function(el){
      el.value = el.dataset[L.k] || '';
    });
    // option 等仅接受纯文本的元素
    node.querySelectorAll('.js-txt').forEach(function(el){
      el.textContent = el.dataset[L.k] || '';
    });
    // 标记语言作用域
    node.querySelectorAll('.screen,.csw').forEach(function(s){ s.dataset.lang=L.k; });
    // 该舞台要求弹窗默认展开（用于演示打开态）
    if(pair.dataset.sheet==='open'){
      node.querySelectorAll('.js-sheet,.sheet-mask').forEach(function(x){ x.classList.add('on'); });
    }
    wrap.appendChild(node);
    pair.appendChild(wrap);
  });
});

/* ═══ Banner 轮播：指示点 + 手动拖拽滑动 ═══ */
document.querySelectorAll('.js-car').forEach(function(track){
  var slides=track.querySelectorAll('.car-slide');
  var dots=track.parentElement.querySelector('.js-dots');
  if(!dots) return;

  var autoplay=track.dataset.autoplay==='true' && slides.length>1;
  var autoplayTimer=null;
  function stopAutoplay(){
    if(autoplayTimer){ clearInterval(autoplayTimer); autoplayTimer=null; }
  }
  function startAutoplay(){
    if(!autoplay || autoplayTimer) return;
    autoplayTimer=setInterval(function(){
      if(track.classList.contains('dragging')) return;
      var current=Math.round(track.scrollLeft/track.clientWidth);
      var next=current+1;
      if(next>=slides.length) next=0;
      track.scrollTo({left:track.clientWidth*next,behavior:'smooth'});
    },3000);
  }
  startAutoplay();

  // 生成指示点；仅一页时隐藏
  if(slides.length<2){ dots.classList.add('single'); }
  for(var i=0;i<slides.length;i++){
    var dt=document.createElement('div');
    dt.className='dot'+(i===0?' on':'');
    dt.dataset.i=i;
    dt.addEventListener('click',function(e){
      e.stopPropagation();
      stopAutoplay();
      track.scrollTo({left:track.clientWidth*(+this.dataset.i),behavior:'smooth'});
    });
    dots.appendChild(dt);
  }

  // 滚动时同步指示点
  var raf=null;
  track.addEventListener('scroll',function(){
    if(raf) return;
    raf=requestAnimationFrame(function(){
      raf=null;
      var idx=Math.round(track.scrollLeft/track.clientWidth);
      dots.querySelectorAll('.dot').forEach(function(d,j){
        d.classList.toggle('on',j===idx);
      });
    });
  });

  // 鼠标拖拽滑动（触屏/触控板由浏览器原生处理）
  var down=false, sx=0, sl=0, moved=0;
  track.addEventListener('pointerdown',function(e){
    stopAutoplay();
    if(e.pointerType==='touch') return;      // 触屏交给原生滚动
    down=true; moved=0;
    sx=e.clientX; sl=track.scrollLeft;
    track.classList.add('dragging');
  });
  track.addEventListener('pointermove',function(e){
    if(!down) return;
    var dx=e.clientX-sx;
    moved=Math.max(moved,Math.abs(dx));
    track.scrollLeft=sl-dx;
  });
  function release(){
    if(!down) return;
    down=false;
    track.classList.remove('dragging');
    // 松手后吸附到最近一页
    var idx=Math.round(track.scrollLeft/track.clientWidth);
    idx=Math.max(0,Math.min(slides.length-1,idx));
    track.scrollTo({left:track.clientWidth*idx,behavior:'smooth'});
    // 发生过拖拽则抑制本次点击，避免误触卡片跳转
    if(moved>5){
      track.dataset.drag='1';
      setTimeout(function(){ delete track.dataset.drag; },0);
    }
  }
  track.addEventListener('pointerup',release);
  track.addEventListener('pointerleave',release);
  track.addEventListener('pointercancel',release);
  // 拖拽中禁止原生图片/文本拖动
  track.addEventListener('dragstart',function(e){ e.preventDefault(); });
});

/* ═══ 页面切换 ═══ */
function go(id){
  document.querySelectorAll('.stage').forEach(function(s){s.classList.remove('active');});
  document.querySelectorAll('.tab').forEach(function(t){t.classList.remove('active');});
  var st=document.getElementById('s-'+id);
  if(st) st.classList.add('active');
  var tb=document.querySelector('[data-p="'+id+'"]');
  if(tb) tb.classList.add('active');
  window.scrollTo(0,0);
}
document.querySelectorAll('.tab').forEach(function(t){
  t.addEventListener('click',function(){go(this.dataset.p);});
});

/* ═══ 委托事件：跳转 / 借据勾选 / 天数 / 结果切换 ═══ */
var TXT={
  lim:{zh:function(n){return '⚠️ 本次最多可展期 '+n+' 天';},
       es:function(n){return '⚠️ Máximo '+n+' días para esta extensión';}},
  limNone:{zh:'⚠️ 请至少选择一笔借据', es:'⚠️ Selecciona al menos un préstamo'},
  limS:{zh:function(n){return '最多 '+n+' 天';}, es:function(n){return 'Máx. '+n+' días';}},
  limSNone:{zh:'—', es:'—'}
};

document.addEventListener('click',function(e){
  // 轮播拖拽刚结束：抑制本次点击，避免误触卡片跳转
  var inCar=e.target.closest('.js-car');
  if(inCar && inCar.dataset.drag) return;

  // 跳转
  var g=e.target.closest('.js-go');
  if(g){ go(g.dataset.go); return; }

  // 借据勾选
  var ln=e.target.closest('.js-loan');
  if(ln){
    ln.classList.toggle('on');
    return;
  }

  // 天数加减器
  var sb=e.target.closest('.js-step');
  if(sb){
    var sc=sb.closest('.screen');
    var inp=sc.querySelector('.js-din');
    if(!inp) return;
    var cur=parseInt(inp.value)||0;
    var delta=parseInt(sb.dataset.d)||0;
    var mx=parseInt(inp.dataset.max)||15;
    var nv=Math.max(1,Math.min(mx,cur+delta));
    inp.value=nv;
    return;
  }

  // 打开明细弹窗
  var so=e.target.closest('.js-sheet-open');
  if(so){
    var sc0=so.closest('.screen');
    sc0.querySelector('.js-sheet').classList.add('on');
    sc0.querySelector('.sheet-mask').classList.add('on');
    return;
  }

  // 关闭明细弹窗（遮罩 / ✕ / 我知道了）
  var scl=e.target.closest('.js-sheet-close');
  if(scl){
    var sc1=scl.closest('.screen');
    sc1.querySelector('.js-sheet').classList.remove('on');
    sc1.querySelector('.sheet-mask').classList.remove('on');
    return;
  }

  // 直接选择支付方式
  var pm=e.target.closest('.js-pay-method');
  if(pm){
    var payGroup=pm.closest('.pay-options');
    if(payGroup){
      payGroup.querySelectorAll('.js-pay-method').forEach(function(item){ item.classList.remove('selected'); });
      pm.classList.add('selected');
    }
    return;
  }

  // 结果状态切换
  var sw=e.target.closest('.js-sw');
  if(sw){
    var s2=sw.closest('.screen');
    s2.querySelectorAll('.js-res').forEach(function(r){
      r.style.display = (r.dataset.r===sw.dataset.r)?'block':'none';
    });
    return;
  }
});
</script>
</body>
</html>
