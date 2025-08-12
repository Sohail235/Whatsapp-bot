<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Whatsapp-bot — Neon UI README</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0b0f14;
      --panel:#071018;
      --neon-1:#7C5CFF; /* purple */
      --neon-2:#00E6A8; /* teal */
      --muted:#9aa6b2;
      --glass: rgba(255,255,255,0.04);
    }
    *{box-sizing:border-box}
    body{font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial; margin:0; background: radial-gradient(1200px 600px at 10% 10%, rgba(124,92,255,0.08), transparent), radial-gradient(800px 400px at 90% 90%, rgba(0,230,168,0.04), transparent), var(--bg); color:#e6eef6; -webkit-font-smoothing:antialiased}
    .wrap{max-width:980px;margin:48px auto;padding:28px;border-radius:18px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow: 0 10px 30px rgba(2,6,23,0.7);border:1px solid rgba(255,255,255,0.02)}
    header{display:flex;align-items:center;gap:18px}
    .logo{height:76px;width:76px;border-radius:14px;background:linear-gradient(135deg,var(--neon-1),var(--neon-2));display:flex;align-items:center;justify-content:center;box-shadow:0 8px 30px rgba(124,92,255,0.12), inset 0 -6px 20px rgba(0,0,0,0.25);border:1px solid rgba(255,255,255,0.06);font-weight:800;font-size:22px}
    h1{font-size:20px;margin:0}
    p.lead{color:var(--muted);margin:6px 0 20px}
    .badges{display:flex;gap:8px;flex-wrap:wrap;margin-top:6px}
    .badge{background:var(--glass);padding:6px 10px;border-radius:999px;font-size:12px;color:var(--muted);border:1px solid rgba(255,255,255,0.02)}.grid{display:grid;grid-template-columns:1fr 320px;gap:24px}
.card{background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.02)}
.section-title{display:flex;align-items:center;gap:10px}
.pill{padding:6px 10px;border-radius:999px;background:linear-gradient(90deg, rgba(124,92,255,0.12), rgba(0,230,168,0.08));color:var(--neon-1);font-weight:700}

pre{background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:14px;border-radius:10px;overflow:auto;border:1px solid rgba(255,255,255,0.02);font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, "Roboto Mono", "Courier New", monospace;font-size:13px;color:#dbeefe}
code{color:#cfeef2}

.features{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:12px;margin-top:12px}
.feature{background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.00));padding:12px;border-radius:8px;border:1px solid rgba(255,255,255,0.02)}
.feature h4{margin:0 0 6px;font-size:14px}
.muted{color:var(--muted);font-size:13px}

.right .meta{display:flex;flex-direction:column;gap:10px}
.meta .item{display:flex;justify-content:space-between;align-items:center;padding:10px;border-radius:10px;background:linear-gradient(180deg, rgba(255,255,255,0.012), transparent);border:1px solid rgba(255,255,255,0.02)}
.cta{display:flex;gap:10px;margin-top:6px}
.btn{padding:10px 14px;border-radius:10px;border:none;cursor:pointer;font-weight:700}
.btn-primary{background:linear-gradient(90deg,var(--neon-1),var(--neon-2));box-shadow:0 8px 30px rgba(124,92,255,0.12);color:#051019}
.btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--neon-2)}

footer{margin-top:20px;color:var(--muted);font-size:13px;text-align:center}

@media (max-width:900px){.grid{grid-template-columns:1fr}.logo{height:60px;width:60px}.wrap{margin:20px}}

  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">SK</div>
      <div>
        <h1>Whatsapp-bot <span style="color:var(--muted);font-weight:600">— feature-packed WhatsApp automation</span></h1>
        <p class="lead">A fast, modular WhatsApp bot built with <strong>Node.js</strong> and <strong>Baileys</strong>. Scales from small groups to large communities — with group control, auto-reactions, media tools, moderation, and more.</p>
        <div class="badges">
          <div class="badge">Node.js</div>
          <div class="badge">Baileys</div>
          <div class="badge">Termux friendly</div>
          <div class="badge">Modular commands</div>
        </div>
      </div>
    </header><div style="height:18px"></div>

<div class="grid">
  <main>
    <section class="card">
      <div class="section-title"><div class="pill">Features</div></div>
      <div class="features">
        <div class="feature">
          <h4>Group Management</h4>
          <div class="muted">Add/remove members, promote/demote, mute, set group link, auto-welcome & anti-spam.</div>
        </div>
        <div class="feature">
          <h4>Auto Reactions</h4>
          <div class="muted">React automatically using emoji rules and keyword triggers.</div>
        </div>
        <div class="feature">
          <h4>Media Tools</h4>
          <div class="muted">Download, convert to sticker, blur images, take screenshots and more.</div>
        </div>
        <div class="feature">
          <h4>Moderation</h4>
          <div class="muted">Anti-delete, anti-link, warnings, bans, and detailed logs.</div>
        </div>
      </div>

      <div style="height:14px"></div>

      <div class="section-title"><strong>Quick install</strong></div>
      <pre><code>pkg install nodejs git unzip

move your zip -> unzip -> enter folder

unzip devilmd.zip cd Whatsapp-bot npm install

create .env or config.js, then:

node main.js </code></pre>

<div style="height:12px"></div>

      <div class="section-title"><strong>Common commands</strong></div>
      <pre><code>// Example (bot owner commands)

.owner       — show owner info .kick @user  — remove user from group .promote     — make user admin .auto-react  — enable auto reaction mode .tagall      — mention everyone in group </code></pre>

<div style="height:12px"></div>

      <div class="section-title"><strong>Configuration</strong></div>
      <p class="muted">Edit <code>config.js</code> or environment variables (.env) to set owner number, bot name, and features. Store sessions inside <code>auth/</code>.</p>

      <div style="height:12px"></div>

      <div class="section-title"><strong>Security & Disclaimer</strong></div>
      <p class="muted">This project is provided for educational purposes. Do not use it for spam or to break WhatsApp's Terms of Service. Keep your tokens and credentials private.</p>
    </section>

    <section style="margin-top:16px" class="card">
      <div class="section-title"><strong>Project structure</strong></div>
      <pre><code>commands/          # all bot commands (kick.js, play.js, sticker.js ...)

lib/               # helpers & utilities data/              # json files for runtime state main.js / index.js  # entry points devilmd.zip        # original archive (you can remove) </code></pre>

<div style="height:12px"></div>

      <div class="section-title"><strong>Contributing</strong></div>
      <p class="muted">PRs welcome — open issues for bugs or feature requests. Follow the code style and add tests for new features where possible.</p>
    </section>
  </main>

  <aside class="right">
    <div class="card">
      <div class="meta">
        <div class="item"><strong>Repo</strong><span>https://github.com/Sohail235/Whatsapp-bot</span></div>
        <div class="item"><strong>License</strong><span>MIT</span></div>
        <div class="item"><strong>Author</strong><span>Sohail Khan (SK)</span></div>
        <div class="item"><strong>Node</strong><span>>=14</span></div>
      </div>

      <div class="cta">
        <button class="btn btn-primary" onclick="window.open('https://github.com/Sohail235/Whatsapp-bot','_blank')">Open Repo</button>
        <button class="btn btn-ghost" onclick="navigator.clipboard.writeText('git clone https://github.com/Sohail235/Whatsapp-bot.git')">Copy Git Clone</button>
      </div>
    </div>

    <div style="height:12px"></div>

    <div class="card">
      <div style="display:flex;align-items:center;justify-content:space-between"><strong>Preview</strong><span class="muted">(placeholders)</span></div>
      <div style="height:12px"></div>
      <div style="height:160px;border-radius:10px;background:linear-gradient(135deg, rgba(124,92,255,0.08), rgba(0,230,168,0.04));display:flex;align-items:center;justify-content:center;color:var(--muted);border:1px solid rgba(255,255,255,0.02)">Add screenshots or GIFs here</div>
    </div>

    <div style="height:12px"></div>

    <div class="card">
      <strong>Support</strong>
      <p class="muted" style="margin:8px 0 0">For help, open an issue on GitHub or contact <code>skthedevil@gmail.com</code>.</p>
    </div>
  </aside>
</div>

<footer>
  Made with ⚡ by <strong>Sohail Khan</strong> — <span class="muted">Keep credentials secret. Revoke tokens if exposed.</span>
</footer>

  </div>
</body>
</html>
