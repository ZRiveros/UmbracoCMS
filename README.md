# 🌐 Umbraco Onatrix

Detta projekt är en statisk webbplats byggd i **Umbraco CMS (v16.3.1)** med **Razor Views** och **Block List Editor** för innehållshantering.  
Syftet med projektet är att återskapa designen för företaget **Onatrix** enligt tillhandahållen designfil.

Projektet är utvecklat enligt kraven för **G-nivå** och fokuserar på korrekt uppbyggnad, struktur och innehåll — ej på responsivitet eller avancerad funktionalitet.

---

## 🧩 Funktionalitet och struktur

- Webbplatsen följer designfilens samtliga **sidor, sektioner och innehållsstruktur**.
- **Block List Editor** och **Element Types** används för att bygga upp sidorna modulärt.
- **Posters** hanteras som **child pages** under relevant sida.
- **Formulär** (t.ex. "Request a call back") finns visuellt enligt design, men är **inte funktionella**.
- **Navigeringen** är dynamisk och hämtas automatiskt från innehållsträdet i Umbraco.
- **Globala delar** såsom logotyp, kontaktinformation och sociala länkar är hårdkodade (ingen Site Settings används).
- Ingen paginering eller slider är implementerad.
- Sökfunktionen i headern är ej fungerande (endast visuell).

---

## 🛠️ Teknisk översikt

| Teknologi | Användning |
|------------|-------------|
| **Umbraco CMS 16.3.1** | Backend och innehållshantering |
| **ASP.NET Core / Razor (.cshtml)** | Dynamisk rendering av innehåll |
| **HTML5 / CSS3** | Struktur och styling |
| **Font Awesome** | Ikoner |
| **Visual Studio 2022** | Utvecklingsmiljö |
| **GitHub** | Versionshantering |

---

## ⚙️ Installation och körning

1. Klona repot:
   ```bash
   git clone https://github.com/ZRiveros/UmbracoOnatrix.git


