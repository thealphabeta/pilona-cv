# Projekt: pilona-cv (Terminal CV)

## Zusammenfassung
Erstellung einer unkonventionellen, interaktiven Bewerbung im Terminal-Stil basierend auf dem Hugo Static Site Generator und dem Theme `hugo-theme-terminalcv`. Die Website wird automatisiert über GitHub Actions auf GitHub Pages gehostet.

- **Technologie:** Hugo (Static Site Generator)
- **Design:** Terminal / CLI Ästhetik (hugo-theme-terminalcv)
- **Hosting:** GitHub Pages
- **Ziel:** Eine differenzierende, technische Präsentation der Vita.

---

## Ablaufplan (Phasen)

### Phase 1: Projekt-Setup (Basis)
1. **Hugo Projekt initialisieren:** `hugo new site . --force`
2. **Git Repository einrichten:** `git init`
3. **Theme hinzufügen:** Als Submodul einbinden (`git submodule add https://github.com/coolapso/hugo-theme-terminalcv themes/terminalcv`)
4. **Grundkonfiguration:** `hugo.toml` (oder `config.toml`) mit Theme-Vorgaben füllen.

### Phase 2: Inhaltsgestaltung (Content)
1. **Stammdaten pflegen:** Name, Kontakt, Social Media in der Konfiguration hinterlegen.
2. **Lebenslauf-Sektionen:** Erstellung der Markdown-Dateien für:
   - Erfahrung (Experience)
   - Ausbildung (Education)
   - Skills / Technologien
   - Projekte (Optional)
3. **Über mich:** Personalisierung der Startseite (Terminal-Begrüßungstext).

### Phase 3: Individualisierung & Design
1. **Farbschema:** Anpassung der Terminal-Farben (z.B. Retro-Grün oder Amber).
2. **Interaktive Elemente:** Testen der "Befehle" im Theme (z.B. `help`, `whoami`).
3. **Favicon & SEO:** Hinzufügen eines passenden Terminal-Icons.

### Phase 4: Deployment (GitHub Pages)
1. **GitHub Repository erstellen:** Repository `pilona-cv` auf GitHub anlegen.
2. **GitHub Actions Workflow:** `.github/workflows/hugo.yaml` für automatisches Build & Deploy erstellen.
3. **Domain-Check:** Aktivierung von HTTPS und (optional) Verknüpfung einer Custom Domain.

### Phase 5: Testing & Release
1. **Mobile Check:** Sicherstellen, dass das Terminal-Layout auf Smartphones lesbar bleibt.
2. **Link-Check:** Validierung aller externen Verweise (LinkedIn, GitHub, E-Mail).
3. **Live-Gang:** Finale Veröffentlichung.

---

## Nächste Schritte
1. Initialisierung des Hugo-Skeletts.
2. Einbindung des Themes.
3. Erster lokaler Testlauf via `hugo server`.
