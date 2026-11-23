# scoledo.de

Weiterleitung von **scoledo.de** auf **https://amafida.de/scoledo/** über GitHub Pages (kostenloses HTTPS-Zertifikat).

- `index.html` und `404.html` leiten jede Adresse sofort weiter (Meta-Refresh + JavaScript).
- `CNAME` = scoledo.de (Custom Domain von GitHub Pages).
- DNS bei United Domains: A-Records `scoledo.de` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; CNAME `www` → amafida.github.io. MX/TXT/autodiscover/autoconfig für E-Mail (hallo@scoledo.de) bleiben unverändert.
