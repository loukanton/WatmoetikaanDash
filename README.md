# Wat moet ik aan? - Parameters & Admin Portal

Een Admin Portal om alle kledingadviez-parameters aan te passen en naar GitHub te pushen.

## 📁 Bestanden

- **`parameters.json`** – Alle temperatuurdrempels, seizoenen, jas-logica, schoenen
- **`admin-portal.html`** – Admin UI (open in browser)

## 🚀 Hoe te gebruiken

1. Open `admin-portal.html` in je browser
2. Pas parameters aan (sliders, inputs, etc.)
3. Klik "Opslaan naar GitHub"
4. Parameters zijn nu in `parameters.json` opgeslagen

## 📋 Parameter Structuur

```json
{
  "seizoenen": {
    "lente": { drempels per seizoen },
    "zomer": { ... },
    "herfst": { ... },
    "winter": { ... }
  },
  "drempels": { twee-stage, muts, wanten, etc. },
  "jas_logica": { geen_jas, vest, tussenjas, winterjas, regenjas },
  "schoenen_logica": { sneakers, slippers, regenlaarzen, warme_schoenen },
  "accessories": { muts, wanten, sjaal, pet }
}
```

## 🔗 Deploy op Netlify

1. Push deze repo naar GitHub
2. Ga naar [Netlify](https://netlify.com)
3. Klik "New site from Git" → Selecteer deze repo
4. Deploy!

Dan is je Admin Portal live op `https://your-site.netlify.app/admin-portal.html`

## 💡 Tips

- **Seizoenen aanpassen**: Pas start/end datums aan
- **Drempels wijzigen**: Gebruik sliders of type direct in
- **Jas/Schoenen logica**: Edit emoji, label, temperatuur ranges
- **Alle wijzigingen gaan naar GitHub**: Handmatig pushen niet nodig!

---

Gemaakt met ❤️ voor Louk
