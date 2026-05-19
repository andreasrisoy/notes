---
title: risoy.io // Notes
layout: page
---

<div class="custom-home">
    <header>
        <h1 class="matrix-title">risoy.io // Notes</h1>
        <p class="tagline">99% ustrukturerte tanker, 1% nyttig dokumentasjon.</p>
        <p class="description">Velkommen til min digitale hage. Dette er et personlig, søkbart oppslagsverk for tekniske prosedyrer, homelab-konfigurasjoner og faglige jukselapper.</p>
    </header>

    <div class="terminal-container">
        <div class="terminal-header">💡 Hage-status</div>
        <div class="terminal-output">
            • <b>Infrastruktur:</b> Quartz 4.0 via GitHub Actions<br>
            • <b>Modus:</b> Minimalistisk digital hage<br>
            • <b>Søk:</b> Bruk søkefeltet øverst til høyre (eller trykk <kbd>Ctrl</kbd> + <kbd>K</kbd>) for å endevende notatene.
        </div>
    </div>

    <div class="section-divider">🌱 Aktive tråder i hagen</div>
    
    <div class="garden-links">
        <p>
            📂 <b>Homelab & Serverdrift:</b> <a href="./unraid">Unraid-oppsett</a> | <a href="./docker">Docker-containere</a><br>
            🔐 <b>Sikkerhet & Identitet:</b> <a href="./gpg-yubikey">GPG + YubiKey-guider</a> | <a href="./dns-records">DNS Over-engineering</a><br>
            👨‍⚕️ <b>Faglige notater:</b> <a href="./medisin">Kliniske retningslinjer</a>
        </p>
    </div>
</div>

<style>
    /* Overstyrer Quartz-stilen på forsiden for å matche hovedsiden din */
    .custom-home {
        max-width: 600px;
        margin: 2rem auto;
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }
    .matrix-title {
        font-size: 1.8rem;
        font-weight: 600;
        margin: 0;
        color: #f3f4f6;
        letter-spacing: -0.5px;
    }
    .tagline {
        color: #3b82f6;
        font-size: 0.85rem;
        margin-top: 0.4rem;
        font-weight: 500;
    }
    .description {
        color: #9ca3af;
        font-size: 0.85rem;
        margin-top: 0.5rem;
        margin-bottom: 2rem;
        line-height: 1.5;
    }
    .section-divider {
        font-size: 0.9rem;
        color: #3b82f6;
        text-transform: uppercase;
        letter-spacing: 1px;
        margin-top: 2rem;
        margin-bottom: 1rem;
        border-bottom: 1px solid #1f2937;
        padding-bottom: 5px;
        font-weight: 600;
    }
    .terminal-container {
        background: #070a10;
        border: 1px solid #1f2937;
        border-radius: 8px;
        padding: 1rem;
        margin-bottom: 1.5rem;
    }
    .terminal-header {
        font-size: 0.7rem;
        color: #3b82f6;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        margin-bottom: 0.5rem;
        font-weight: bold;
    }
    .terminal-output {
        color: #9ca3af;
        font-family: "SF Mono", "SFProMono-Regular", Consolas, monospace;
        font-size: 0.8rem;
        line-height: 1.6;
    }
    .terminal-output b { color: #f3f4f6; }
    .garden-links p {
        line-height: 1.8;
        font-size: 0.9rem;
    }
    .garden-links a {
        color: #f3f4f6;
        text-decoration: none;
        border-bottom: 1px solid #1f2937;
        transition: border-color 0.2s, color 0.2s;
    }
    .garden-links a:hover {
        color: #3b82f6;
        border-color: #3b82f6;
    }
    kbd {
        background: #1f2937;
        border: 1px solid #374151;
        border-radius: 3px;
        padding: 1px 4px;
        font-size: 0.75rem;
        color: #f3f4f6;
    }
</style>
