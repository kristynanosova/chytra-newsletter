# 📬 Newsletter Chytrá organizace

Šablona pro měsíční email newsletter. Navržena tak, aby šlo vše editovat **přímo na GitHubu** bez nutnosti instalovat cokoliv.

---

## 🌐 Živý náhled (GitHub Pages)

Po nastavení GitHub Pages bude šablona dostupná na adrese:

```
https://[tvoje-jmeno].github.io/chytra-newsletter/
```

> Každá změna, kterou uložíš na GitHubu, se automaticky projeví v náhledu do ~1 minuty.

---

## ✏️ Jak editovat newsletter každý měsíc

### Krok 1 — Otevři soubor na GitHubu
1. Přejdi do tohoto repozitáře na **github.com**
2. Klikni na soubor **`newsletter.html`**
3. Klikni na ikonu **tužky** (Edit this file) vpravo nahoře

### Krok 2 — Najdi sekci, kterou chceš upravit
Šablona obsahuje komentáře, které ti ukáží, kde co editovat:
```html
<!-- ✏️ EDITUJ: Slovo od Kristýny -->
```
Hledej tuhle značku pomocí **Ctrl+F** (nebo Cmd+F na Macu).

### Krok 3 — Ulož změny
1. Dole na stránce klikni na **"Commit changes"**
2. Napiš krátký popis změny, např. `Newsletter říjen 2026`
3. Klikni **"Commit changes"** (zeleně)

### Krok 4 — Zkopíruj do Mailchimp / Ecomail
1. Otevři živý náhled (viz výše)
2. V Mailchimpu / Ecomailu vyber **"Code your own"** nebo **"Paste HTML"**
3. Zkopíruj celý obsah souboru `newsletter.html` a vlož ho

---

## 📁 Struktura souborů

```
chytra-newsletter/
├── newsletter.html      ← Hlavní šablona (EDITUJ TENTO SOUBOR)
├── index.html           ← GitHub Pages náhled (neupravuj)
└── README.md            ← Tento návod
```

---

## 🎨 Barvy a styl

| Prvek | Barva | Hex kód |
|:---|:---|:---|
| Tmavé pozadí (header, novinky) | Tmavá modrá | `#192231` |
| Akcentová barva (tlačítka, štítky) | Žlutá | `#FDD801` |
| Sekundární akcent (citáty, zákulisí) | Fialová | `#9E76F0` |
| Světlé pozadí | Světle šedá | `#EAEAEA` |

---

## 📋 Sekce šablony — co kde editovat

| Sekce | Co editovat | Kde hledat |
|:---|:---|:---|
| **Záhlaví** | Měsíc a číslo vydání | `<!-- ✏️ EDITUJ: Číslo a měsíc newsletteru -->` |
| **Slovo od Kristýny** | Osobní úvod (3–5 vět) | `<!-- ✏️ EDITUJ: Osobní úvod -->` |
| **Téma čísla** | Hlavní článek (300–500 slov) | `<!-- ✏️ EDITUJ: Nadpis hlavního článku -->` |
| **Novinky v systému** | Až 3 novinky (ikona, název, popis) | `<!-- ✏️ EDITUJ: Každá novinka -->` |
| **Ze zákulisí** | Text + fotka z kanceláře | `<!-- ✏️ EDITUJ: Text zákulisního příběhu -->` |
| **Hlas klienta** | Citát + jméno + organizace | `<!-- ✏️ EDITUJ: Citát klienta -->` |
| **Tip měsíce** | 3–5 tipů (číslo + text) | `<!-- ✏️ EDITUJ: Body tipu -->` |
| **CTA tlačítko** | Odkaz na demo | `<!-- ✏️ EDITUJ: href — vlož správný odkaz -->` |
| **Zápatí** | Kontakty, LinkedIn | `<!-- ✏️ EDITUJ: Kontakty -->` |

---

## 📸 Jak přidat fotku ze zákulisí

V šabloně najdi tuto sekci:
```html
<!-- ✏️ EDITUJ: Fotka ze zákulisí -->
```

**Možnost A — fotka z internetu (nebo GitHub):**
```html
<img src="https://tvoje-url.com/foto.jpg" width="520" style="border-radius:10px; max-width:100%;" alt="Tým Chytrá" />
```

**Možnost B — fotka nahraná do tohoto repozitáře:**
1. Na GitHubu klikni **"Add file" → "Upload files"**
2. Nahraj fotku (např. `foto-rijen.jpg`)
3. Použij relativní cestu: `src="foto-rijen.jpg"`

---

## ⚙️ Nastavení GitHub Pages (jednorázové)

1. V repozitáři klikni na **Settings** (nastavení)
2. V levém menu vyber **Pages**
3. V sekci "Branch" vyber **main** a složku **/ (root)**
4. Klikni **Save**
5. Za ~2 minuty bude tvůj náhled dostupný na vygenerované URL

---

## 📧 Integrace s Mailchimp / Ecomail

### Mailchimp
1. Nová kampaň → **Regular Email**
2. V kroku "Design" vyber **"Code your own"**
3. Vlož celý obsah `newsletter.html`
4. Odkaz pro odhlášení (`*|UNSUB|*`) se doplní automaticky

### Ecomail (česká alternativa)
1. Nová kampaň → **HTML šablona**
2. Vlož kód z `newsletter.html`
3. Ecomail automaticky nahradí `*|UNSUB|*` odkazem pro odhlášení

---

## 🗓️ Harmonogram

| Týden | Co dělat |
|:---|:---|
| **Týden 3 předchozího měsíce** | Vymyslet téma čísla, udělat fotku ze zákulisí |
| **Týden 4 předchozího měsíce** | Napsat texty, vložit do šablony |
| **1. čtvrtek v měsíci, 9:00** | Odeslat newsletter |

---

*Chytrá organizace · [www.chytraorganizace.cz](https://www.chytraorganizace.cz) · +420 778 707 176*
