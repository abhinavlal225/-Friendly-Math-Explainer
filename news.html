<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Lumière — Real Estate Image Enhancer</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400;1,500&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
/* ═══════════════════════════════════════════
   DESIGN TOKENS — Luxury Editorial Light
═══════════════════════════════════════════ */
:root {
  --white:      #ffffff;
  --paper:      #faf9f7;
  --paper2:     #f4f2ef;
  --paper3:     #ede9e3;
  --border:     #e4dfd8;
  --border2:    #d4cec6;
  --ink:        #1a1714;
  --ink2:       #2c2926;
  --ink3:       #46423d;
  --mute:       #8a847c;
  --mute2:      #b4afa8;
  --bronze:     #a07848;
  --bronze-l:   #c49a60;
  --bronze-d:   #7a5830;
  --gold:       #d4a843;
  --sage:       #6b8c6b;
  --sage-l:     #8aab8a;
  --blush:      #c4886a;
  --radius:     10px;
  --radius-lg:  16px;
  --shadow-sm:  0 1px 3px rgba(26,23,20,0.07), 0 1px 2px rgba(26,23,20,0.05);
  --shadow:     0 4px 16px rgba(26,23,20,0.08), 0 2px 6px rgba(26,23,20,0.05);
  --shadow-lg:  0 12px 48px rgba(26,23,20,0.12), 0 4px 16px rgba(26,23,20,0.07);
  --ease:       cubic-bezier(0.4, 0, 0.2, 1);
}

/* ═══════════════════════════════════════════
   RESET & BASE
═══════════════════════════════════════════ */
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
html { font-size: 16px; height: 100%; scroll-behavior: smooth; }
body {
  font-family: 'DM Sans', sans-serif;
  background: var(--paper);
  color: var(--ink);
  min-height: 100vh;
  -webkit-font-smoothing: antialiased;
}
::-webkit-scrollbar { width: 5px; }
::-webkit-scrollbar-track { background: var(--paper2); }
::-webkit-scrollbar-thumb { background: var(--border2); border-radius: 3px; }
img { max-width: 100%; display: block; }
button { font-family: 'DM Sans', sans-serif; }

/* ═══════════════════════════════════════════
   TOPBAR
═══════════════════════════════════════════ */
.topbar {
  display: flex; align-items: center; justify-content: space-between;
  padding: 0 2.5rem; height: 66px;
  background: var(--white);
  border-bottom: 1px solid var(--border);
  position: sticky; top: 0; z-index: 200;
  box-shadow: var(--shadow-sm);
}

.brand { display: flex; align-items: center; gap: 0.875rem; }
.brand-mark {
  width: 34px; height: 34px;
  background: linear-gradient(135deg, var(--bronze) 0%, var(--gold) 100%);
  border-radius: 8px;
  display: flex; align-items: center; justify-content: center;
  font-size: 1rem; color: white;
  box-shadow: 0 2px 8px rgba(160,120,72,0.35);
}
.brand-name {
  font-family: 'Playfair Display', serif;
  font-size: 1.3rem; font-weight: 500;
  color: var(--ink);
  letter-spacing: 0.03em;
}
.brand-name span {
  font-style: italic;
  color: var(--bronze);
}
.brand-tagline {
  font-size: 0.6rem; font-weight: 500;
  color: var(--mute2); letter-spacing: 0.16em;
  text-transform: uppercase; margin-top: 1px; display: block;
}

.nav-pills { display: flex; align-items: center; gap: 0.5rem; }
.nav-pill {
  padding: 0.38rem 1rem; border-radius: 20px;
  font-size: 0.72rem; font-weight: 500;
  cursor: pointer; transition: all 0.2s var(--ease);
  border: 1px solid transparent; background: transparent; color: var(--mute);
}
.nav-pill:hover { color: var(--ink); }
.nav-pill.active {
  background: var(--ink); color: var(--white);
  box-shadow: 0 2px 8px rgba(26,23,20,0.2);
}

.topbar-actions { display: flex; align-items: center; gap: 0.6rem; }
.btn {
  padding: 0.45rem 1.15rem; border-radius: 6px;
  font-size: 0.75rem; font-weight: 600;
  cursor: pointer; transition: all 0.2s var(--ease);
  border: 1px solid var(--border2); background: transparent; color: var(--ink3);
}
.btn:hover { border-color: var(--bronze); color: var(--bronze); }
.btn-primary {
  background: var(--ink); color: var(--white); border-color: var(--ink);
}
.btn-primary:hover { background: var(--ink2); border-color: var(--ink2); box-shadow: 0 4px 16px rgba(26,23,20,0.25); color: var(--white); }
.btn-gold {
  background: linear-gradient(135deg, var(--bronze), var(--gold));
  color: var(--white); border: none;
  box-shadow: 0 2px 12px rgba(160,120,72,0.3);
}
.btn-gold:hover { box-shadow: 0 4px 20px rgba(160,120,72,0.45); transform: translateY(-1px); color: var(--white); }
.btn:disabled { opacity: 0.32; cursor: not-allowed; transform: none !important; box-shadow: none !important; }

/* ═══════════════════════════════════════════
   APP LAYOUT
═══════════════════════════════════════════ */
.app { display: grid; grid-template-columns: 320px 1fr; min-height: calc(100vh - 66px); }

/* ═══════════════════════════════════════════
   LEFT SIDEBAR
═══════════════════════════════════════════ */
.sidebar {
  background: var(--white);
  border-right: 1px solid var(--border);
  padding: 1.5rem;
  display: flex; flex-direction: column; gap: 1.25rem;
  overflow-y: auto;
}

/* Panel section */
.panel {
  border: 1px solid var(--border);
  border-radius: var(--radius);
  overflow: hidden;
  background: var(--white);
  box-shadow: var(--shadow-sm);
  animation: panelIn 0.5s var(--ease) both;
}
.panel:nth-child(1) { animation-delay: 0.04s; }
.panel:nth-child(2) { animation-delay: 0.09s; }
.panel:nth-child(3) { animation-delay: 0.14s; }
.panel:nth-child(4) { animation-delay: 0.19s; }
@keyframes panelIn {
  from { opacity: 0; transform: translateY(10px); }
  to   { opacity: 1; transform: translateY(0); }
}

.panel-head {
  padding: 0.75rem 1rem;
  border-bottom: 1px solid var(--border);
  display: flex; align-items: center; gap: 0.5rem;
  background: var(--paper);
}
.panel-icon { font-size: 0.85rem; }
.panel-head h3 {
  font-size: 0.65rem; font-weight: 600;
  letter-spacing: 0.14em; text-transform: uppercase;
  color: var(--bronze);
}
.panel-body { padding: 1rem; display: flex; flex-direction: column; gap: 0.875rem; }

/* ── UPLOAD ── */
.upload-zone {
  border: 1.5px dashed var(--border2);
  border-radius: var(--radius);
  padding: 1.75rem 1rem;
  text-align: center;
  cursor: pointer;
  transition: all 0.25s var(--ease);
  background: var(--paper);
  display: flex; flex-direction: column; align-items: center; gap: 0.75rem;
  position: relative; overflow: hidden;
}
.upload-zone::before {
  content: '';
  position: absolute; inset: 0;
  background: linear-gradient(135deg, transparent 40%, rgba(160,120,72,0.04));
  pointer-events: none;
}
.upload-zone:hover, .upload-zone.over {
  border-color: var(--bronze);
  background: rgba(160,120,72,0.04);
}
.upload-zone.over { transform: scale(1.01); }
.upload-icon-wrap {
  width: 52px; height: 52px; border-radius: 50%;
  background: var(--paper2); border: 1px solid var(--border);
  display: flex; align-items: center; justify-content: center;
  font-size: 1.4rem; transition: all 0.25s;
}
.upload-zone:hover .upload-icon-wrap { background: rgba(160,120,72,0.1); border-color: var(--bronze-l); transform: scale(1.05); }
.upload-title {
  font-family: 'Playfair Display', serif;
  font-size: 0.95rem; font-weight: 500; color: var(--ink2);
}
.upload-sub { font-size: 0.7rem; color: var(--mute); line-height: 1.5; }
.upload-sub em { color: var(--bronze); font-style: normal; cursor: pointer; font-weight: 600; }
.upload-sub em:hover { text-decoration: underline; }
.upload-formats { font-size: 0.58rem; color: var(--mute2); letter-spacing: 0.1em; text-transform: uppercase; }
#fileInput { display: none; }

/* Thumbnail strip */
.thumb-strip { display: flex; gap: 0.5rem; flex-wrap: wrap; }
.thumb-item {
  position: relative; width: 72px; height: 54px; border-radius: 5px;
  overflow: hidden; border: 1px solid var(--border);
  cursor: pointer; transition: all 0.18s;
  flex-shrink: 0;
}
.thumb-item:hover { border-color: var(--bronze); transform: scale(1.05); }
.thumb-item.active { border: 2px solid var(--bronze); box-shadow: 0 0 0 2px rgba(160,120,72,0.2); }
.thumb-item img { width: 100%; height: 100%; object-fit: cover; }
.thumb-remove {
  position: absolute; top: 2px; right: 2px;
  width: 16px; height: 16px; background: rgba(26,23,20,0.7);
  border-radius: 50%; color: white; font-size: 0.5rem;
  display: flex; align-items: center; justify-content: center;
  cursor: pointer; opacity: 0; transition: opacity 0.15s;
  border: none;
}
.thumb-item:hover .thumb-remove { opacity: 1; }
.thumb-add {
  width: 72px; height: 54px; border-radius: 5px;
  border: 1.5px dashed var(--border2); background: var(--paper2);
  display: flex; align-items: center; justify-content: center;
  color: var(--mute); font-size: 1.2rem; cursor: pointer;
  transition: all 0.18s; flex-shrink: 0;
}
.thumb-add:hover { border-color: var(--bronze); color: var(--bronze); background: rgba(160,120,72,0.05); }

/* ── ENHANCEMENT TOGGLES ── */
.enhance-list { display: flex; flex-direction: column; gap: 0.5rem; }
.enhance-row {
  display: flex; align-items: center; justify-content: space-between;
  padding: 0.65rem 0.875rem;
  border: 1px solid var(--border); border-radius: 7px;
  background: var(--paper); transition: all 0.18s;
  cursor: pointer;
}
.enhance-row:hover { border-color: var(--bronze-l); background: rgba(160,120,72,0.03); }
.enhance-row.active { border-color: var(--bronze); background: rgba(160,120,72,0.06); }
.enhance-left { display: flex; align-items: center; gap: 0.6rem; }
.enhance-icon {
  width: 30px; height: 30px; border-radius: 7px;
  display: flex; align-items: center; justify-content: center;
  font-size: 0.85rem; background: var(--paper3);
  transition: all 0.18s;
}
.enhance-row.active .enhance-icon { background: rgba(160,120,72,0.15); }
.enhance-label { font-size: 0.78rem; font-weight: 500; color: var(--ink3); }
.enhance-desc { font-size: 0.62rem; color: var(--mute); margin-top: 1px; }

/* Toggle switch */
.toggle { position: relative; width: 36px; height: 20px; flex-shrink: 0; }
.toggle input { opacity: 0; width: 0; height: 0; position: absolute; }
.toggle-track {
  position: absolute; inset: 0; border-radius: 10px;
  background: var(--border2); cursor: pointer; transition: all 0.2s;
}
.toggle input:checked + .toggle-track { background: var(--bronze); }
.toggle-track::after {
  content: ''; position: absolute;
  width: 14px; height: 14px; background: white; border-radius: 50%;
  top: 3px; left: 3px; transition: transform 0.2s;
  box-shadow: 0 1px 3px rgba(0,0,0,0.2);
}
.toggle input:checked + .toggle-track::after { transform: translateX(16px); }

/* ── ROOM DETECTION ── */
.room-badge {
  display: inline-flex; align-items: center; gap: 0.4rem;
  padding: 0.3rem 0.75rem; border-radius: 20px;
  background: var(--paper2); border: 1px solid var(--border);
  font-size: 0.68rem; font-weight: 500; color: var(--ink3);
}
.room-dot { width: 7px; height: 7px; border-radius: 50%; background: var(--sage); flex-shrink: 0; }

/* ── STAGING STYLE ── */
.style-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 0.5rem; }
.style-btn {
  padding: 0.55rem; border: 1px solid var(--border); border-radius: 7px;
  background: var(--paper); cursor: pointer; text-align: center;
  transition: all 0.18s; font-family: 'DM Sans', sans-serif;
}
.style-btn:hover { border-color: var(--bronze-l); background: rgba(160,120,72,0.04); }
.style-btn.active { border-color: var(--bronze); background: rgba(160,120,72,0.08); }
.style-btn .st-icon { font-size: 1.1rem; }
.style-btn .st-name { font-size: 0.64rem; font-weight: 600; color: var(--ink3); letter-spacing: 0.05em; text-transform: uppercase; margin-top: 3px; }
.style-btn.active .st-name { color: var(--bronze); }

/* ── ENHANCE BUTTON ── */
.enhance-btn {
  width: 100%; padding: 0.875rem;
  background: var(--ink); color: var(--white);
  border: none; border-radius: var(--radius);
  font-family: 'DM Sans', sans-serif;
  font-size: 0.82rem; font-weight: 600;
  letter-spacing: 0.06em; cursor: pointer;
  transition: all 0.22s var(--ease);
  box-shadow: 0 4px 20px rgba(26,23,20,0.2);
  display: flex; align-items: center; justify-content: center; gap: 0.5rem;
}
.enhance-btn:hover:not(:disabled) {
  background: var(--ink2); transform: translateY(-1px);
  box-shadow: 0 8px 28px rgba(26,23,20,0.28);
}
.enhance-btn:disabled { opacity: 0.3; cursor: not-allowed; transform: none; box-shadow: none; }

/* ═══════════════════════════════════════════
   MAIN STAGE
═══════════════════════════════════════════ */
.stage {
  background: var(--paper2);
  display: flex; flex-direction: column;
  overflow: hidden; position: relative;
}

/* ── STAGE HEADER ── */
.stage-header {
  background: var(--white); border-bottom: 1px solid var(--border);
  padding: 0.875rem 2rem;
  display: flex; align-items: center; justify-content: space-between;
  flex-shrink: 0;
}
.view-toggle {
  display: flex; background: var(--paper2); border: 1px solid var(--border);
  border-radius: 20px; overflow: hidden; padding: 2px;
}
.view-toggle button {
  background: transparent; border: none; padding: 0.3rem 0.875rem;
  font-family: 'DM Sans', sans-serif; font-size: 0.68rem; font-weight: 600;
  letter-spacing: 0.08em; text-transform: uppercase; color: var(--mute);
  cursor: pointer; border-radius: 16px; transition: all 0.18s;
}
.view-toggle button.active { background: var(--white); color: var(--ink); box-shadow: var(--shadow-sm); }

.stage-actions { display: flex; gap: 0.5rem; align-items: center; }
.stage-stat {
  padding: 0.3rem 0.875rem; border-radius: 20px;
  background: var(--paper2); border: 1px solid var(--border);
  font-size: 0.65rem; font-weight: 500; color: var(--mute);
  display: flex; align-items: center; gap: 0.35rem;
}
.stage-stat-dot { width: 6px; height: 6px; border-radius: 50%; background: var(--sage); animation: statPulse 2s ease-in-out infinite; }
@keyframes statPulse { 0%,100% { opacity:1; } 50% { opacity:0.3; } }
.stage-stat-dot.idle { background: var(--mute2); animation: none; }

/* ── CANVAS WORKSPACE ── */
.workspace {
  flex: 1; display: flex; align-items: center; justify-content: center;
  padding: 2rem; overflow: hidden; position: relative;
}

/* Empty state */
.empty-workspace {
  display: flex; flex-direction: column; align-items: center; justify-content: center;
  gap: 1.25rem; text-align: center; color: var(--mute2);
  height: 100%;
}
.empty-icon {
  width: 80px; height: 80px; border-radius: 50%;
  background: var(--white); border: 1px solid var(--border);
  display: flex; align-items: center; justify-content: center;
  font-size: 2.2rem; box-shadow: var(--shadow-sm);
}
.empty-title {
  font-family: 'Playfair Display', serif;
  font-size: 1.2rem; font-weight: 500; color: var(--ink3);
}
.empty-sub { font-size: 0.78rem; color: var(--mute); max-width: 240px; line-height: 1.6; }

/* ── COMPARE VIEW ── */
.compare-container {
  position: relative; border-radius: var(--radius-lg); overflow: hidden;
  box-shadow: var(--shadow-lg);
  max-width: 100%; max-height: 100%;
  display: none; cursor: col-resize; user-select: none;
  border: 1px solid var(--border);
}
.compare-container.visible { display: block; animation: fadeUp 0.4s var(--ease) both; }
@keyframes fadeUp { from { opacity:0; transform:translateY(12px); } to { opacity:1; transform:translateY(0); } }

#imgOriginal { display: block; max-width: 100%; max-height: calc(100vh - 220px); object-fit: contain; }
#imgEnhanced {
  position: absolute; top: 0; left: 0; width: 100%; height: 100%;
  object-fit: cover; clip-path: inset(0 50% 0 0);
}
.split-divider {
  position: absolute; top: 0; bottom: 0; left: 50%;
  width: 2px; background: white; transform: translateX(-50%);
  pointer-events: none; z-index: 10;
  box-shadow: 0 0 8px rgba(0,0,0,0.3);
}
.split-handle {
  position: absolute; top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  width: 44px; height: 44px; background: white; border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  box-shadow: 0 4px 20px rgba(0,0,0,0.25);
  pointer-events: none; z-index: 11; font-size: 1rem;
}
.corner-label {
  position: absolute; padding: 0.25rem 0.75rem; border-radius: 20px;
  font-size: 0.6rem; font-weight: 700; letter-spacing: 0.12em; text-transform: uppercase;
  backdrop-filter: blur(12px); pointer-events: none; z-index: 12;
}
.label-before { top: 1rem; left: 1rem; background: rgba(26,23,20,0.6); color: rgba(255,255,255,0.85); }
.label-after  { top: 1rem; right: 1rem; background: rgba(160,120,72,0.85); color: white; }

/* ── PROCESSING OVERLAY ── */
.proc-overlay {
  position: absolute; inset: 0; z-index: 100;
  background: rgba(250,249,247,0.92); backdrop-filter: blur(12px);
  display: none; flex-direction: column; align-items: center; justify-content: center;
  gap: 1.5rem; border-radius: var(--radius-lg);
}
.proc-overlay.on { display: flex; }

/* Elegant spinner — concentric rings */
.spinner-wrap { position: relative; width: 72px; height: 72px; }
.spin-ring {
  position: absolute; border-radius: 50%; border: 1.5px solid transparent;
  animation: spinRing linear infinite;
}
.spin-ring:nth-child(1) { inset:0; border-top-color: var(--bronze); animation-duration:1.2s; }
.spin-ring:nth-child(2) { inset:8px; border-top-color: var(--bronze-l); animation-duration:1.8s; animation-direction:reverse; }
.spin-ring:nth-child(3) { inset:16px; border-top-color: var(--gold); animation-duration:2.4s; }
.spin-center { position:absolute; inset:28px; background:var(--bronze); border-radius:50%; animation:spinPulse 2s ease-in-out infinite; }
@keyframes spinRing { to { transform: rotate(360deg); } }
@keyframes spinPulse { 0%,100%{transform:scale(1);opacity:1;} 50%{transform:scale(1.3);opacity:0.6;} }

.proc-title {
  font-family: 'Playfair Display', serif;
  font-size: 1.1rem; font-weight: 500; color: var(--ink2);
  letter-spacing: 0.02em;
}
.proc-subtitle { font-size: 0.72rem; color: var(--mute); }

.prog-bar-wrap { width: 220px; }
.prog-track {
  height: 3px; background: var(--border2); border-radius: 2px; overflow: hidden;
  margin-bottom: 0.4rem;
}
.prog-fill {
  height: 100%;
  background: linear-gradient(90deg, var(--bronze-d), var(--bronze), var(--gold));
  border-radius: 2px; width: 0%; transition: width 0.5s var(--ease);
}
.prog-meta { display: flex; justify-content: space-between; }
.prog-pct { font-family: 'Playfair Display', serif; font-size: 0.85rem; color: var(--bronze); font-weight: 500; }
.prog-step { font-size: 0.65rem; color: var(--mute); }

/* ── ENHANCEMENT RESULTS PANEL ── */
.results-panel {
  background: var(--white); border-top: 1px solid var(--border);
  padding: 1rem 2rem; flex-shrink: 0;
  display: none; align-items: center; justify-content: space-between; gap: 1rem;
}
.results-panel.show { display: flex; animation: slideUp 0.35s var(--ease) both; }
@keyframes slideUp { from{opacity:0;transform:translateY(10px);} to{opacity:1;transform:translateY(0);} }

.result-stats { display: flex; gap: 1.5rem; }
.r-stat { text-align: center; }
.r-val {
  font-family: 'Playfair Display', serif;
  font-size: 1.3rem; font-weight: 600; color: var(--bronze);
  display: block; letter-spacing: -0.01em;
}
.r-lbl { font-size: 0.6rem; color: var(--mute); letter-spacing: 0.1em; text-transform: uppercase; }

.result-enhancements { display: flex; gap: 0.4rem; flex-wrap: wrap; }
.r-tag {
  padding: 0.22rem 0.65rem; border-radius: 20px;
  font-size: 0.62rem; font-weight: 600; letter-spacing: 0.06em;
  background: rgba(160,120,72,0.1); color: var(--bronze); border: 1px solid rgba(160,120,72,0.2);
}

.export-actions { display: flex; gap: 0.5rem; }

/* ── TOAST ── */
.toast {
  position: fixed; bottom: 2rem; left: 50%;
  transform: translateX(-50%) translateY(60px);
  background: var(--ink); color: white; border-radius: 30px;
  padding: 0.65rem 1.5rem; font-size: 0.78rem; font-weight: 500;
  box-shadow: var(--shadow-lg);
  transition: transform 0.38s cubic-bezier(0.34,1.56,0.64,1);
  z-index: 999; white-space: nowrap;
}
.toast.up { transform: translateX(-50%) translateY(0); }

/* ── ZOOM OVERLAY ── */
.zoom-overlay {
  position: fixed; inset: 0; z-index: 500;
  background: rgba(26,23,20,0.88); backdrop-filter: blur(8px);
  display: none; align-items: center; justify-content: center;
}
.zoom-overlay.show { display: flex; }
.zoom-img { max-width: 90vw; max-height: 90vh; border-radius: var(--radius); box-shadow: var(--shadow-lg); }
.zoom-close {
  position: absolute; top: 1.5rem; right: 1.5rem;
  width: 40px; height: 40px; background: rgba(255,255,255,0.1);
  border: 1px solid rgba(255,255,255,0.2); border-radius: 50%;
  color: white; font-size: 1.2rem; cursor: pointer;
  display: flex; align-items: center; justify-content: center;
  transition: all 0.2s;
}
.zoom-close:hover { background: rgba(255,255,255,0.2); }

/* ── HIDDEN PROCESSING CANVAS ── */
#workCanvas { display: none; }

/* ═══════════════════════════════════════════
   RESPONSIVE
═══════════════════════════════════════════ */
@media (max-width: 860px) {
  .app { grid-template-columns: 1fr; }
  .sidebar { border-right: none; border-bottom: 1px solid var(--border); max-height: 55vh; }
  .workspace { padding: 1rem; }
  .stage-header { padding: 0.75rem 1rem; }
  .topbar { padding: 0 1rem; }
  .brand-tagline, .nav-pills { display: none; }
}
</style>
</head>
<body>

<!-- ════════ TOPBAR ════════ -->
<header class="topbar">
  <div class="brand">
    <div class="brand-mark">✦</div>
    <div>
      <div class="brand-name">Lumi<span>ère</span></div>
      <span class="brand-tagline">Real Estate Image Enhancer</span>
    </div>
  </div>
  <div class="nav-pills">
    <button class="nav-pill active">Enhance</button>
    <button class="nav-pill">Batch</button>
    <button class="nav-pill">History</button>
  </div>
  <div class="topbar-actions">
    <button class="btn" id="resetBtn">Reset</button>
    <button class="btn btn-gold" id="exportBtn" disabled>↓ Export</button>
  </div>
</header>

<div class="app">

  <!-- ════════ SIDEBAR ════════ -->
  <aside class="sidebar">

    <!-- 1. IMAGE UPLOAD -->
    <div class="panel">
      <div class="panel-head"><span class="panel-icon">🏠</span><h3>Property Images</h3></div>
      <div class="panel-body">
        <div class="upload-zone" id="uploadZone">
          <div class="upload-icon-wrap">🖼️</div>
          <div class="upload-title">Upload Property Images</div>
          <div class="upload-sub">Drag & drop or <em id="browseLink">select files</em></div>
          <div class="upload-formats">JPG · PNG · WebP</div>
          <input type="file" id="fileInput" accept="image/*" multiple>
        </div>
        <div class="thumb-strip" id="thumbStrip" style="display:none">
          <!-- thumbnails inserted here -->
          <div class="thumb-add" id="thumbAdd" title="Add more">+</div>
        </div>
        <div class="room-badge" id="roomBadge" style="display:none">
          <div class="room-dot"></div>
          <span id="roomLabel">Detecting room…</span>
        </div>
      </div>
    </div>

    <!-- 2. ENHANCEMENT OPTIONS -->
    <div class="panel">
      <div class="panel-head"><span class="panel-icon">⚡</span><h3>Enhancement Options</h3></div>
      <div class="panel-body" style="padding:0.75rem;">
        <div class="enhance-list">
          <div class="enhance-row active" data-key="lighting" onclick="toggleEnhance(this)">
            <div class="enhance-left">
              <div class="enhance-icon">☀️</div>
              <div>
                <div class="enhance-label">Lighting Correction</div>
                <div class="enhance-desc">Auto brightness & white balance</div>
              </div>
            </div>
            <label class="toggle" onclick="event.stopPropagation()">
              <input type="checkbox" id="tog_lighting" checked>
              <div class="toggle-track"></div>
            </label>
          </div>
          <div class="enhance-row active" data-key="color" onclick="toggleEnhance(this)">
            <div class="enhance-left">
              <div class="enhance-icon">🎨</div>
              <div>
                <div class="enhance-label">Color Enhancement</div>
                <div class="enhance-desc">Vibrancy & sharpness boost</div>
              </div>
            </div>
            <label class="toggle" onclick="event.stopPropagation()">
              <input type="checkbox" id="tog_color" checked>
              <div class="toggle-track"></div>
            </label>
          </div>
          <div class="enhance-row active" data-key="noise" onclick="toggleEnhance(this)">
            <div class="enhance-left">
              <div class="enhance-icon">✨</div>
              <div>
                <div class="enhance-label">Noise Reduction</div>
                <div class="enhance-desc">Smooth grain & artifacts</div>
              </div>
            </div>
            <label class="toggle" onclick="event.stopPropagation()">
              <input type="checkbox" id="tog_noise" checked>
              <div class="toggle-track"></div>
            </label>
          </div>
          <div class="enhance-row" data-key="removal" onclick="toggleEnhance(this)">
            <div class="enhance-left">
              <div class="enhance-icon">🪄</div>
              <div>
                <div class="enhance-label">Object Removal</div>
                <div class="enhance-desc">Remove clutter & distractions</div>
              </div>
            </div>
            <label class="toggle" onclick="event.stopPropagation()">
              <input type="checkbox" id="tog_removal">
              <div class="toggle-track"></div>
            </label>
          </div>
          <div class="enhance-row" data-key="sky" onclick="toggleEnhance(this)">
            <div class="enhance-left">
              <div class="enhance-icon">🌤️</div>
              <div>
                <div class="enhance-label">Sky Replacement</div>
                <div class="enhance-desc">Exterior images only</div>
              </div>
            </div>
            <label class="toggle" onclick="event.stopPropagation()">
              <input type="checkbox" id="tog_sky">
              <div class="toggle-track"></div>
            </label>
          </div>
          <div class="enhance-row" data-key="staging" onclick="toggleEnhance(this)">
            <div class="enhance-left">
              <div class="enhance-icon">🛋️</div>
              <div>
                <div class="enhance-label">Virtual Staging</div>
                <div class="enhance-desc">Add furniture to empty rooms</div>
              </div>
            </div>
            <label class="toggle" onclick="event.stopPropagation()">
              <input type="checkbox" id="tog_staging">
              <div class="toggle-track"></div>
            </label>
          </div>
        </div>
      </div>
    </div>

    <!-- 3. STAGING STYLE (visible when staging enabled) -->
    <div class="panel" id="stagingPanel" style="display:none">
      <div class="panel-head"><span class="panel-icon">🏛️</span><h3>Staging Style</h3></div>
      <div class="panel-body" style="padding:0.75rem;">
        <div class="style-grid">
          <button class="style-btn active" data-style="modern">
            <div class="st-icon">🖤</div>
            <div class="st-name">Modern</div>
          </button>
          <button class="style-btn" data-style="luxury">
            <div class="st-icon">✨</div>
            <div class="st-name">Luxury</div>
          </button>
          <button class="style-btn" data-style="scandi">
            <div class="st-icon">🌿</div>
            <div class="st-name">Scandi</div>
          </button>
          <button class="style-btn" data-style="minimal">
            <div class="st-icon">○</div>
            <div class="st-name">Minimal</div>
          </button>
        </div>
      </div>
    </div>

    <!-- ENHANCE BUTTON -->
    <button class="enhance-btn" id="enhanceBtn" disabled>
      <span>✦</span> Enhance Image
    </button>

  </aside>

  <!-- ════════ STAGE ════════ -->
  <main class="stage">

    <!-- Stage header -->
    <div class="stage-header">
      <div class="view-toggle">
        <button class="active" id="btnCompare" onclick="setView('compare')">Compare</button>
        <button id="btnBefore" onclick="setView('before')">Before</button>
        <button id="btnAfter"  onclick="setView('after')">After</button>
      </div>
      <div class="stage-actions">
        <div class="stage-stat">
          <div class="stage-stat-dot idle" id="statusDot"></div>
          <span id="statusTxt">Ready</span>
        </div>
        <button class="btn" id="zoomBtn" disabled onclick="openZoom()">⊕ Zoom</button>
      </div>
    </div>

    <!-- Workspace -->
    <div class="workspace" id="workspace">
      <canvas id="workCanvas"></canvas>

      <!-- Empty state -->
      <div class="empty-workspace" id="emptyState">
        <div class="empty-icon">🏡</div>
        <div class="empty-title">Your Canvas Awaits</div>
        <div class="empty-sub">Upload a property image to preview and apply AI enhancements.</div>
      </div>

      <!-- Compare container -->
      <div class="compare-container" id="compareContainer">
        <img id="imgOriginal" src="" alt="Original">
        <img id="imgEnhanced" src="" alt="Enhanced">
        <div class="split-divider" id="splitDiv"></div>
        <div class="split-handle" id="splitHandle">⟺</div>
        <div class="corner-label label-before">Before</div>
        <div class="corner-label label-after">After</div>

        <!-- Processing overlay (inside compare container) -->
        <div class="proc-overlay" id="procOverlay">
          <div class="spinner-wrap">
            <div class="spin-ring"></div>
            <div class="spin-ring"></div>
            <div class="spin-ring"></div>
            <div class="spin-center"></div>
          </div>
          <div>
            <div class="proc-title">Enhancing Your Property</div>
            <div class="proc-subtitle" id="procSub">Initialising AI pipeline…</div>
          </div>
          <div class="prog-bar-wrap">
            <div class="prog-track"><div class="prog-fill" id="progFill"></div></div>
            <div class="prog-meta">
              <span class="prog-pct" id="progPct">0%</span>
              <span class="prog-step" id="progStep">Starting</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Results panel -->
    <div class="results-panel" id="resultsPanel">
      <div class="result-stats">
        <div class="r-stat"><span class="r-val" id="rScore">—</span><span class="r-lbl">Appeal Score</span></div>
        <div class="r-stat"><span class="r-val" id="rBright">—</span><span class="r-lbl">Brightness</span></div>
        <div class="r-stat"><span class="r-val" id="rSharp">—</span><span class="r-lbl">Sharpness</span></div>
      </div>
      <div class="result-enhancements" id="rTags"></div>
      <div class="export-actions">
        <button class="btn" onclick="downloadComparison()">↓ Comparison</button>
        <button class="btn btn-primary" onclick="downloadEnhanced()">↓ Enhanced</button>
      </div>
    </div>

  </main>
</div>

<!-- ZOOM OVERLAY -->
<div class="zoom-overlay" id="zoomOverlay" onclick="closeZoom()">
  <button class="zoom-close" onclick="closeZoom()">✕</button>
  <img class="zoom-img" id="zoomImg" src="" alt="">
</div>

<!-- TOAST -->
<div class="toast" id="toast"></div>

<script>
/* ══════════════════════════════════════════════
   STATE
══════════════════════════════════════════════ */
const S = {
  images:      [],   // { file, url, name }
  activeIdx:   -1,
  originalURL: null,
  enhancedURL: null,
  enhancedCanvas: null,
  view:        'compare',
  splitPct:    50,
  dragging:    false,
  roomType:    null,
  stagingStyle:'modern',
  enhancements:{
    lighting: true,
    color:    true,
    noise:    true,
    removal:  false,
    sky:      false,
    staging:  false,
  },
};

/* Enhancement processing params by option */
const ENHANCE_PARAMS = {
  lighting: {
    brightness: 1.12, contrast: 1.10,
    whiteBalance: { r: 1.04, g: 1.0, b: 0.97 },
  },
  color: {
    saturation: 1.25, sharpness: 1.15, vibrance: 1.2,
  },
  noise: {
    blur: 0.6,
  },
  removal: { darken: 0.0 }, // simulated
  sky:     { skyTint: true },
  staging: { overlay: true },
};

/* Room type detection heuristics (simulated) */
const ROOM_TYPES = [
  'Living Room', 'Master Bedroom', 'Kitchen', 'Bathroom',
  'Dining Room', 'Home Office', 'Exterior / Garden', 'Basement',
];

/* Staging style overlays */
const STAGING_OVERLAYS = {
  modern:  { r:0,   g:0,   b:0,   a:0.03 },
  luxury:  { r:40,  g:30,  b:0,   a:0.04 },
  scandi:  { r:230, g:220, b:210, a:0.05 },
  minimal: { r:245, g:245, b:240, a:0.04 },
};

/* ══════════════════════════════════════════════
   DOM REFS
══════════════════════════════════════════════ */
const uploadZone     = document.getElementById('uploadZone');
const fileInput      = document.getElementById('fileInput');
const thumbStrip     = document.getElementById('thumbStrip');
const thumbAdd       = document.getElementById('thumbAdd');
const roomBadge      = document.getElementById('roomBadge');
const roomLabel      = document.getElementById('roomLabel');
const compareBox     = document.getElementById('compareContainer');
const imgOriginal    = document.getElementById('imgOriginal');
const imgEnhanced    = document.getElementById('imgEnhanced');
const splitDiv       = document.getElementById('splitDiv');
const splitHandle    = document.getElementById('splitHandle');
const procOverlay    = document.getElementById('procOverlay');
const progFill       = document.getElementById('progFill');
const progPct        = document.getElementById('progPct');
const progStep       = document.getElementById('progStep');
const procSub        = document.getElementById('procSub');
const workCanvas     = document.getElementById('workCanvas');
const emptyState     = document.getElementById('emptyState');
const resultsPanel   = document.getElementById('resultsPanel');
const enhanceBtn     = document.getElementById('enhanceBtn');
const exportBtn      = document.getElementById('exportBtn');
const statusDot      = document.getElementById('statusDot');
const statusTxt      = document.getElementById('statusTxt');
const stagingPanel   = document.getElementById('stagingPanel');
const ctx            = workCanvas.getContext('2d', { willReadFrequently: true });

/* ══════════════════════════════════════════════
   UPLOAD
══════════════════════════════════════════════ */
uploadZone.addEventListener('click', () => fileInput.click());
document.getElementById('browseLink').addEventListener('click', e => { e.stopPropagation(); fileInput.click(); });
thumbAdd.addEventListener('click', () => fileInput.click());
uploadZone.addEventListener('dragover', e => { e.preventDefault(); uploadZone.classList.add('over'); });
uploadZone.addEventListener('dragleave', () => uploadZone.classList.remove('over'));
uploadZone.addEventListener('drop', e => {
  e.preventDefault(); uploadZone.classList.remove('over');
  const files = [...e.dataTransfer.files].filter(f => f.type.startsWith('image/'));
  if (files.length) addImages(files);
});
fileInput.addEventListener('change', () => {
  if (fileInput.files.length) addImages([...fileInput.files]);
});

function addImages(files) {
  files.forEach(file => {
    const url = URL.createObjectURL(file);
    S.images.push({ file, url, name: file.name });
  });
  renderThumbs();
  selectImage(S.images.length - 1);
  showToast(`✓ ${files.length} image${files.length > 1 ? 's' : ''} added`);
}

function renderThumbs() {
  // Remove existing thumbs (not the add button)
  thumbStrip.querySelectorAll('.thumb-item').forEach(t => t.remove());
  S.images.forEach((img, i) => {
    const div = document.createElement('div');
    div.className = 'thumb-item' + (i === S.activeIdx ? ' active' : '');
    div.innerHTML = `<img src="${img.url}" alt=""><button class="thumb-remove" onclick="removeImage(event,${i})">✕</button>`;
    div.addEventListener('click', () => selectImage(i));
    thumbStrip.insertBefore(div, thumbAdd);
  });
  thumbStrip.style.display = S.images.length ? 'flex' : 'none';
}

function removeImage(e, i) {
  e.stopPropagation();
  URL.revokeObjectURL(S.images[i].url);
  S.images.splice(i, 1);
  if (S.activeIdx >= S.images.length) S.activeIdx = S.images.length - 1;
  if (S.images.length === 0) { resetStage(); }
  else { renderThumbs(); selectImage(S.activeIdx); }
}

function selectImage(i) {
  S.activeIdx = i;
  S.originalURL = S.images[i].url;
  S.enhancedURL = null;
  renderThumbs();
  imgOriginal.src = S.originalURL;
  imgEnhanced.src = S.originalURL; // show original in both until enhanced
  imgOriginal.onload = () => {
    emptyState.style.display = 'none';
    compareBox.classList.add('visible');
    setSplit(50);
    setView('before');
    enhanceBtn.disabled = false;
    exportBtn.disabled = true;
    zoomBtnEl().disabled = false;
    detectRoom(S.originalURL);
    resultsPanel.classList.remove('show');
    setStatus('Image loaded — apply enhancements', false);
  };
}

function zoomBtnEl() { return document.getElementById('zoomBtn'); }

/* ══════════════════════════════════════════════
   ROOM DETECTION (simulated)
══════════════════════════════════════════════ */
function detectRoom(url) {
  roomBadge.style.display = 'inline-flex';
  roomLabel.textContent = 'Detecting room type…';
  setTimeout(() => {
    // Heuristic: use image filename for hints, else random
    const name = (S.images[S.activeIdx]?.name || '').toLowerCase();
    let room;
    if (name.includes('kitchen')) room = 'Kitchen';
    else if (name.includes('bed')) room = 'Master Bedroom';
    else if (name.includes('bath')) room = 'Bathroom';
    else if (name.includes('ext') || name.includes('garden') || name.includes('front')) room = 'Exterior / Garden';
    else if (name.includes('office')) room = 'Home Office';
    else room = ROOM_TYPES[Math.floor(Math.random() * ROOM_TYPES.length)];
    S.roomType = room;
    roomLabel.textContent = `Detected: ${room}`;
  }, 800);
}

/* ══════════════════════════════════════════════
   ENHANCEMENT TOGGLES
══════════════════════════════════════════════ */
function toggleEnhance(row) {
  const key = row.dataset.key;
  const chk = row.querySelector('input[type=checkbox]');
  chk.checked = !chk.checked;
  S.enhancements[key] = chk.checked;
  row.classList.toggle('active', chk.checked);
  // Show/hide staging style panel
  if (key === 'staging') stagingPanel.style.display = chk.checked ? 'block' : 'none';
}

// Wire checkboxes directly too
document.querySelectorAll('.enhance-row input[type=checkbox]').forEach(chk => {
  chk.addEventListener('change', () => {
    const key = chk.id.replace('tog_','');
    S.enhancements[key] = chk.checked;
    chk.closest('.enhance-row').classList.toggle('active', chk.checked);
    if (key === 'staging') stagingPanel.style.display = chk.checked ? 'block' : 'none';
  });
});

// Staging style buttons
document.querySelectorAll('.style-btn').forEach(b => {
  b.addEventListener('click', () => {
    document.querySelectorAll('.style-btn').forEach(x => x.classList.remove('active'));
    b.classList.add('active'); S.stagingStyle = b.dataset.style;
  });
});

/* ══════════════════════════════════════════════
   AI ENHANCEMENT ENGINE
══════════════════════════════════════════════ */
enhanceBtn.addEventListener('click', startEnhancement);

async function startEnhancement() {
  if (S.activeIdx < 0) return;
  procOverlay.classList.add('on');
  setStatus('Enhancing…', true);
  enhanceBtn.disabled = true;

  const steps = [
    { label: 'Loading full-resolution image',   sub: 'Decoding pixel data',        pct: 8  },
    { label: 'Analysing scene & room type',      sub: 'Computer vision detection',  pct: 18 },
    { label: 'Correcting exposure & lighting',   sub: 'Auto white balance applied', pct: 32 },
    { label: 'Enhancing color & vibrancy',       sub: 'Tone mapping in progress',   pct: 46 },
    { label: 'Reducing noise & grain',           sub: 'Smart smoothing algorithm',  pct: 58 },
    { label: 'Removing unwanted objects',        sub: 'Inpainting affected regions', pct: 68 },
    { label: 'Compositing sky replacement',      sub: 'Seamless blending pass',     pct: 78 },
    { label: 'Applying virtual staging',         sub: 'Furniture placement engine', pct: 88 },
    { label: 'Final quality pass',               sub: 'Sharpening & detail boost',  pct: 96 },
    { label: 'Packaging high-res output',        sub: 'Ready!',                     pct: 100},
  ];

  for (const step of steps) {
    procSub.textContent    = step.sub;
    progStep.textContent   = step.label;
    await animateProg(step.pct, 280 + Math.random() * 350);
  }

  // Run the actual canvas processing
  await processImage();

  procOverlay.classList.remove('on');
  enhanceBtn.disabled = false;
  exportBtn.disabled = false;
  setStatus('Enhancement complete', false);
  showToast('✓ Image enhanced — drag slider to compare');
  updateResults();
  setView('compare');
  setSplit(50);
}

async function processImage() {
  const img = new Image();
  img.src = S.originalURL;
  await new Promise(res => { img.onload = res; });

  const W = img.naturalWidth;
  const H = img.naturalHeight;
  workCanvas.width  = W;
  workCanvas.height = H;
  ctx.drawImage(img, 0, 0);

  const imageData = ctx.getImageData(0, 0, W, H);
  const d = imageData.data;

  // Compute image stats for adaptive processing
  let sumR=0, sumG=0, sumB=0, count=0;
  for (let i=0; i<d.length; i+=16) { sumR+=d[i]; sumG+=d[i+1]; sumB+=d[i+2]; count++; }
  const avgR=sumR/count, avgG=sumG/count, avgB=sumB/count;
  const avgLum = 0.299*avgR + 0.587*avgG + 0.114*avgB;

  // Calculate adaptive brightness (darker images get more correction)
  const targetLum = 148;
  const adaptiveBright = S.enhancements.lighting
    ? Math.min(1.45, Math.max(0.85, targetLum / Math.max(avgLum, 30)))
    : 1.0;

  for (let i=0; i<d.length; i+=4) {
    let r = d[i], g = d[i+1], b = d[i+2];

    /* ── LIGHTING CORRECTION ── */
    if (S.enhancements.lighting) {
      // Adaptive exposure
      r *= adaptiveBright;
      g *= adaptiveBright;
      b *= adaptiveBright;
      // White balance
      r *= 1.04; b *= 0.97;
      // Soft contrast (S-curve approximation)
      r = sCurve(r); g = sCurve(g); b = sCurve(b);
    }

    /* ── COLOR ENHANCEMENT ── */
    if (S.enhancements.color) {
      // Convert to HSL, boost saturation, convert back
      const [h, sl, l] = rgbToHsl(r, g, b);
      const newS = Math.min(1, sl * 1.28);
      const [nr, ng, nb] = hslToRgb(h, newS, l);
      r = nr; g = ng; b = nb;
      // Vibrance (boost less-saturated pixels more)
      const sat = Math.max(r,g,b) - Math.min(r,g,b);
      const vibrF = 1 + (1 - sat/255) * 0.18;
      const lum2 = 0.299*r + 0.587*g + 0.114*b;
      r = lum2 + (r-lum2)*vibrF;
      g = lum2 + (g-lum2)*vibrF;
      b = lum2 + (b-lum2)*vibrF;
    }

    /* ── STAGING STYLE TINT ── */
    if (S.enhancements.staging) {
      const ov = STAGING_OVERLAYS[S.stagingStyle];
      r = r*(1-ov.a) + ov.r*ov.a;
      g = g*(1-ov.a) + ov.g*ov.a;
      b = b*(1-ov.a) + ov.b*ov.a;
      // Slightly warm everything for "staged" feel
      r *= 1.02; b *= 0.98;
    }

    /* ── OBJECT REMOVAL (sim: brighten corners slightly) ── */
    if (S.enhancements.removal) {
      const px = (i/4) % W;
      const py = Math.floor((i/4) / W);
      // Lighten lower 15% of image (floor area clutter)
      if (py > H*0.85) { r*=1.08; g*=1.08; b*=1.06; }
    }

    /* ── SKY REPLACEMENT TINT ── */
    if (S.enhancements.sky) {
      const py = Math.floor((i/4) / W);
      if (py < H * 0.35) {
        // Tint top portion with a sky-blue gradient
        const skyPct = 1 - py / (H * 0.35);
        r = r*(1-skyPct*0.4) + 135*skyPct*0.4;
        g = g*(1-skyPct*0.3) + 185*skyPct*0.3;
        b = b*(1-skyPct*0.2) + 235*skyPct*0.2;
      }
    }

    d[i]   = clamp(r);
    d[i+1] = clamp(g);
    d[i+2] = clamp(b);
  }

  // ── NOISE REDUCTION (box blur pass) ──
  if (S.enhancements.noise) {
    ctx.putImageData(imageData, 0, 0);
    ctx.filter = 'blur(0.4px)';
    ctx.drawImage(workCanvas, 0, 0);
    ctx.filter = 'none';
    // Re-read and sharpen slightly
    const bd = ctx.getImageData(0, 0, W, H).data;
    for (let i=0; i<imageData.data.length; i++) imageData.data[i] = bd[i];
  }

  ctx.putImageData(imageData, 0, 0);

  // ── SLIGHT UNSHARP MASK for final crispness ──
  if (S.enhancements.color) {
    const orig = ctx.getImageData(0, 0, W, H);
    ctx.filter = 'blur(1px)';
    ctx.drawImage(workCanvas, 0, 0);
    ctx.filter = 'none';
    const blurred = ctx.getImageData(0, 0, W, H);
    // Merge: sharp = original + (original - blurred) * amount
    const amount = 0.4;
    for (let i=0; i<orig.data.length; i+=4) {
      for (let c=0; c<3; c++) {
        orig.data[i+c] = clamp(orig.data[i+c] + (orig.data[i+c] - blurred.data[i+c]) * amount);
      }
    }
    ctx.putImageData(orig, 0, 0);
  }

  // Store result
  S.enhancedURL    = workCanvas.toDataURL('image/jpeg', 0.95);
  S.enhancedCanvas = workCanvas;
  imgEnhanced.src  = S.enhancedURL;

  return new Promise(res => { imgEnhanced.onload = res; setTimeout(res, 200); });
}

/* ── Image processing helpers ── */
function sCurve(v) {
  // Gentle S-curve for contrast: maps 0-255 → 0-255
  const x = v / 255;
  const s = x < 0.5
    ? 2 * x * x + x * 0.04
    : 1 - Math.pow(-2*x+2, 2) / 2;
  return (0.97 * s + 0.015) * 255;
}
function clamp(v) { return v<0?0:v>255?255:v|0; }
function rgbToHsl(r,g,b) {
  r/=255; g/=255; b/=255;
  const max=Math.max(r,g,b), min=Math.min(r,g,b);
  let h,s,l=(max+min)/2;
  if (max===min) { h=s=0; }
  else {
    const d=max-min;
    s = l>0.5 ? d/(2-max-min) : d/(max+min);
    switch(max){ case r: h=(g-b)/d+(g<b?6:0); break; case g: h=(b-r)/d+2; break; default: h=(r-g)/d+4; }
    h/=6;
  }
  return [h,s,l];
}
function hslToRgb(h,s,l) {
  let r,g,b;
  if (!s) { r=g=b=l; }
  else {
    const q=l<0.5?l*(1+s):l+s-l*s, p=2*l-q;
    const hue2rgb=(p,q,t)=>{if(t<0)t+=1;if(t>1)t-=1;if(t<1/6)return p+(q-p)*6*t;if(t<1/2)return q;if(t<2/3)return p+(q-p)*(2/3-t)*6;return p;};
    r=hue2rgb(p,q,h+1/3); g=hue2rgb(p,q,h); b=hue2rgb(p,q,h-1/3);
  }
  return [r*255, g*255, b*255];
}

/* ══════════════════════════════════════════════
   COMPARE SLIDER
══════════════════════════════════════════════ */
function setSplit(pct) {
  S.splitPct = pct;
  imgEnhanced.style.clipPath = `inset(0 ${100-pct}% 0 0)`;
  splitDiv.style.left    = pct + '%';
  splitHandle.style.left = pct + '%';
}

compareBox.addEventListener('mousedown', e => { if (S.view==='compare') { S.dragging=true; moveSplit(e.clientX); } });
document.addEventListener('mouseup', () => { S.dragging=false; });
document.addEventListener('mousemove', e => { if (S.dragging && S.view==='compare') moveSplit(e.clientX); });
compareBox.addEventListener('touchstart', e => { if (S.view==='compare') moveSplit(e.touches[0].clientX); }, {passive:true});
compareBox.addEventListener('touchmove', e => { if (S.view==='compare') moveSplit(e.touches[0].clientX); }, {passive:true});

function moveSplit(clientX) {
  const rect = compareBox.getBoundingClientRect();
  const pct  = Math.max(0, Math.min(100, (clientX-rect.left)/rect.width*100));
  setSplit(pct);
}

/* ══════════════════════════════════════════════
   VIEW MODES
══════════════════════════════════════════════ */
function setView(mode) {
  S.view = mode;
  ['compare','before','after'].forEach(m => {
    document.getElementById('btn'+m.charAt(0).toUpperCase()+m.slice(1)).classList.toggle('active', m===mode);
  });
  splitDiv.style.display    = mode==='compare' ? '' : 'none';
  splitHandle.style.display = mode==='compare' ? '' : 'none';

  if (mode==='compare') {
    imgEnhanced.style.display = '';
    setSplit(50);
  } else if (mode==='before') {
    imgEnhanced.style.display = 'none';
  } else {
    imgEnhanced.style.display = '';
    imgEnhanced.style.clipPath = 'inset(0 0% 0 0)';
  }
}

/* ══════════════════════════════════════════════
   RESULTS PANEL
══════════════════════════════════════════════ */
function updateResults() {
  const score = 72 + Math.round(Math.random() * 24);
  const bright = '+' + (8 + Math.round(Math.random()*18)) + '%';
  const sharp  = '+' + (12 + Math.round(Math.random()*22)) + '%';
  document.getElementById('rScore').textContent  = score + '/100';
  document.getElementById('rBright').textContent = bright;
  document.getElementById('rSharp').textContent  = sharp;

  const tags = document.getElementById('rTags');
  tags.innerHTML = '';
  const activeKeys = Object.entries(S.enhancements).filter(([,v])=>v).map(([k])=>k);
  const labels = { lighting:'Lighting Fixed', color:'Colors Enhanced', noise:'Noise Reduced',
                   removal:'Objects Removed', sky:'Sky Replaced', staging:`${S.stagingStyle} Staged` };
  activeKeys.forEach(k => {
    const t = document.createElement('span');
    t.className = 'r-tag'; t.textContent = labels[k] || k;
    tags.appendChild(t);
  });

  resultsPanel.classList.add('show');
}

/* ══════════════════════════════════════════════
   EXPORT
══════════════════════════════════════════════ */
document.getElementById('exportBtn').addEventListener('click', downloadEnhanced);

function downloadEnhanced() {
  if (!S.enhancedURL) return;
  const a = document.createElement('a');
  a.download = 'lumiere_enhanced_' + Date.now() + '.jpg';
  a.href = S.enhancedURL;
  a.click();
  showToast('✓ Enhanced image downloaded');
}

function downloadComparison() {
  if (!S.enhancedURL || !S.originalURL) return;
  // Create side-by-side comparison canvas
  const origImg = new Image();
  const enhImg  = new Image();
  origImg.src   = S.originalURL;
  origImg.onload = () => {
    enhImg.src = S.enhancedURL;
    enhImg.onload = () => {
      const W = origImg.naturalWidth * 2 + 20;
      const H = origImg.naturalHeight + 60;
      const c = document.createElement('canvas');
      c.width=W; c.height=H;
      const cx = c.getContext('2d');
      cx.fillStyle='#faf9f7';
      cx.fillRect(0,0,W,H);
      cx.drawImage(origImg,0,0);
      cx.drawImage(enhImg, origImg.naturalWidth+20, 0);
      cx.fillStyle='#1a1714'; cx.font='bold 24px Georgia';
      cx.fillText('Before', 12, H-16);
      cx.fillStyle='#a07848';
      cx.fillText('After  ✦ Lumière', origImg.naturalWidth+32, H-16);
      const url = c.toDataURL('image/jpeg',0.92);
      const a = document.createElement('a');
      a.download='lumiere_comparison_'+Date.now()+'.jpg';
      a.href=url; a.click();
      showToast('✓ Comparison downloaded');
    };
  };
}

/* ══════════════════════════════════════════════
   ZOOM
══════════════════════════════════════════════ */
function openZoom() {
  const src = S.enhancedURL || S.originalURL;
  if (!src) return;
  document.getElementById('zoomImg').src = src;
  document.getElementById('zoomOverlay').classList.add('show');
}
function closeZoom() { document.getElementById('zoomOverlay').classList.remove('show'); }
document.addEventListener('keydown', e => { if (e.key==='Escape') closeZoom(); });

/* ══════════════════════════════════════════════
   RESET
══════════════════════════════════════════════ */
document.getElementById('resetBtn').addEventListener('click', () => {
  S.images.forEach(i => URL.revokeObjectURL(i.url));
  S.images=[]; S.activeIdx=-1; S.originalURL=null; S.enhancedURL=null;
  resetStage();
  fileInput.value='';
  showToast('↺ Reset complete');
});
function resetStage() {
  imgOriginal.src=''; imgEnhanced.src='';
  compareBox.classList.remove('visible');
  emptyState.style.display='flex';
  resultsPanel.classList.remove('show');
  roomBadge.style.display='none';
  enhanceBtn.disabled=true; exportBtn.disabled=true; zoomBtnEl().disabled=true;
  setStatus('Ready', false);
  renderThumbs();
}

/* ══════════════════════════════════════════════
   STATUS & PROGRESS
══════════════════════════════════════════════ */
function setStatus(msg, active) {
  statusTxt.textContent=msg;
  statusDot.classList.toggle('idle', !active);
}
function animateProg(target, duration) {
  return new Promise(res => {
    const start=parseFloat(progFill.style.width)||0;
    const t0=performance.now();
    const step=now=>{
      const t=Math.min((now-t0)/duration,1);
      const v=start+(target-start)*easeOut(t);
      progFill.style.width=v+'%';
      progPct.textContent=Math.round(v)+'%';
      if(t<1) requestAnimationFrame(step); else res();
    };
    requestAnimationFrame(step);
  });
}
function easeOut(t){return 1-Math.pow(1-t,3);}

/* ══════════════════════════════════════════════
   TOAST
══════════════════════════════════════════════ */
let _tt;
function showToast(msg) {
  const t=document.getElementById('toast');
  t.textContent=msg; t.classList.add('up');
  clearTimeout(_tt); _tt=setTimeout(()=>t.classList.remove('up'),3000);
}

/* ══════════════════════════════════════════════
   INIT
══════════════════════════════════════════════ */
setTimeout(()=>showToast('✦ Welcome to Lumière — upload a property image to begin'),900);
</script>
</body>
</html>
