# Questionario Skill Pattinaggio

Repo statica pubblicabile con GitHub Pages.

Contiene solo:

- `skill-questionario.html`
- `skill-tuning.html`
- `skilltree-catalog.js`
- `index.html`

I dati non vengono salvati in questa repo. Revisioni e tuning vengono letti/scritti su Supabase dopo login autorizzato.

## Sicurezza

- Nessuna chiave segreta nel frontend.
- La publishable key Supabase e pubblica per definizione.
- Il database e protetto da RLS: `anon` non ha accesso alle tabelle, `skill_definizioni` e limitata al super maestro.
