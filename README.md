# scoledo.de

Weiterleitung von **scoledo.de** auf **https://amafida.de/scoledo/** über GitHub Pages (kostenloses HTTPS-Zertifikat).

- `index.html` und `404.html` leiten jede Adresse sofort weiter (Meta-Refresh + JavaScript).
- `CNAME` = scoledo.de (Custom Domain von GitHub Pages).
- DNS bei United Domains: A-Records `scoledo.de` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; CNAME `www` → amafida.github.io. MX/TXT/autodiscover/autoconfig für E-Mail (hallo@scoledo.de) bleiben unverändert.

## Vorher (bis 23.11.2026)

United-Domains-Weiterleitung (301) auf https://www.amafida.de/scoledo – nur über http:// erreichbar, kein Zertifikat für https://scoledo.de. Alte DNS-Werte: A `@` und `*` → 89.31.143.90 (United-Domains-Weiterleitungsserver). Unverändert gelassen: A `autodiscover`, `*.autodiscover`, `autoconfig`, `*.autoconfig` → 89.31.143.90; MX 10 mx00.udag.de, 20 mx01.udag.de; TXT `v=spf1 include:_smtp.udag.de ~all`.

Zurück zur alten Lösung: im United-Domains-Portfolio unter scoledo.de → Website → Weiterleitung wieder aktivieren (setzt die A-Records zurück).
