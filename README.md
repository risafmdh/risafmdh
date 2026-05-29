<div align="center">

<style>
@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-8px); }
}

@keyframes glow {
  0%, 100% { box-shadow: 0 0 20px rgba(56,189,248,0.2); }
  50% { box-shadow: 0 0 40px rgba(56,189,248,0.5); }
}

@keyframes gradientMove {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes fadeIn {
  from { opacity: 0; transform: scale(0.98); }
  to { opacity: 1; transform: scale(1); }
}

@keyframes pulse {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.6; }
}

.container {
  max-width: 720px;
  margin: auto;
  padding: 32px 20px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto;
  background: linear-gradient(160deg, #0a0a12, #12121f, #0d1117);
  border-radius: 28px;
  animation: fadeIn 1s ease-in-out;
}

.card {
  transition: 0.4s ease;
}

.card:hover {
  transform: translateY(-6px) scale(1.01);
  animation: glow 2s infinite;
}

.title {
  font-size: 42px;
  font-weight: 900;
  letter-spacing: 0.2em;
  background: linear-gradient(270deg, #fff, #38bdf8, #a78bfa, #fff);
  background-size: 600% 600%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradientMove 6s ease infinite;
}

.subtitle {
  color: #94a3b8;
  font-size: 13px;
  letter-spacing: 0.12em;
  animation: float 4s ease-in-out infinite;
}

.badge {
  display: inline-block;
  padding: 6px 14px;
  border-radius: 999px;
  background: rgba(52,211,153,0.12);
  border: 1px solid rgba(52,211,153,0.4);
  color: #6ee7b7;
  font-size: 11px;
  animation: pulse 2s infinite;
}

.glass {
  background: rgba(255,255,255,0.06);
  border: 1px solid rgba(255,255,255,0.12);
  border-radius: 20px;
  padding: 22px;
  backdrop-filter: blur(12px);
  transition: 0.3s ease;
}

.glass:hover {
  transform: scale(1.02);
}

.footer {
  margin-top: 20px;
  font-size: 12px;
  color: #94a3b8;
  opacity: 0.9;
}
</style>

<div class="container">

  <!-- Status -->
  <div class="badge">🟢 Available for opportunities</div>

  <!-- Title -->
  <h1 class="title">SOFTWARE ENGINEER</h1>

  <p class="subtitle">⚡ Futuristic Developer Portfolio</p>

  <!-- Bio -->
  <div class="glass card" style="margin-top: 20px;">
    <p style="color:#94a3b8; font-size:10px; letter-spacing:0.2em;">✨ BIO</p>
    <p style="font-size:20px; color:#fff;">
      Build • Learn • Create • Improve • Innovate
    </p>
  </div>

  <!-- Projects -->
  <div class="glass card" style="margin-top: 20px;">
    <p style="color:#94a3b8; font-size:11px; letter-spacing:0.2em;">📊 PROJECTS</p>

    <p>🌐 Web Apps — 12 projects <span style="color:#fcd34d;">Intermediate</span></p>
    <p>🎨 Frontend — 8 projects <span style="color:#86efac;">Advanced</span></p>
    <p>🚀 Full Stack — 5 projects <span style="color:#93c5fd;">Beginner</span></p>
  </div>

  <!-- Glow card -->
  <div class="glass card" style="margin-top: 20px; animation: glow 3s infinite;">
    💎 Crafting premium interfaces with scalable systems & modern UI design.
  </div>

  <!-- Footer -->
  <div class="footer">
    🔭 Open to collaborate • ☕ Coffee-powered code • 🛸 Building the future
  </div>

</div>

</div>
