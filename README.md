## Cześć, jestem Krzysztof 👋

**Automatyzuję powtarzalne procesy w WordPressie i WooCommerce** — te, w których ktoś dziś ręcznie przepisuje dane między formularzem, mailem i systemem.

Buduję wtyczki na zamówienie, integracje z zewnętrznymi źródłami danych i strony, które da się utrzymać bez abonamentów.

---

### Co robię

| | |
|---|---|
| 🔁 **Automatyzacja WP / WooCommerce** | Zapytanie → kwalifikacja leada → kalkulacja → oferta PDF → zadanie u handlowca. Bez ręcznego przepisywania. |
| 🔌 **Integracje i import danych** | Scraper w Pythonie na serwerze → własna baza → wtyczka WordPress wyświetla dane na stronie klienta. |
| 🌐 **Strony i motywy WordPress** | Autorskie motywy bez zbędnych wtyczek, SEO lokalne, dostępność, mobile-first. |

---

### Wybrane projekty

**[MP Offer Automation Suite](https://github.com/krzysiek2115op/mp-offer-automation-suite)** — pakiet 3 wtyczek WordPress/WooCommerce automatyzujący ścieżkę od zapytania do podpisanej oferty.

Wtyczki komunikują się **wyłącznie zdarzeniami WordPressa** — żadna nie zna klas ani tabel pozostałych, więc każdą można wdrożyć osobno. ~23 000 linii PHP, 14 wydań, CI z PHPCS/WPCS na PHP 7.4 i 8.3, harness procesu ze 110 niezmiennikami.

▶️ **[Klikalne demo](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/krzysiek2115op/mp-offer-automation-suite/main/tools/strona-pokazowa/blueprint.json)** — kompletny WordPress z trzema wtyczkami i pełnym przebiegiem procesu, uruchamia się w Twojej przeglądarce.

![Panel procesów sprzedażowych: lista spraw z klientem, statusem, przypisanym handlowcem i terminem SLA](assets/procesy-sprzedazowe.png)

*Panel procesów sprzedażowych — zrzut z działającego demo.*

`PHP` `WordPress` `WooCommerce` `MySQL` `dompdf` `GitHub Actions`

---

**[Copart/IAAI Importer](https://github.com/krzysiek2115op/copart-iaai-importer)** — aktualna oferta z aukcji samochodowych na stronie dealera, bez ręcznego wprowadzania pojazdów.

Scraper w Pythonie chodzi na VPS z timera systemd: crawl → normalizacja → deduplikacja → audyt → zapis do bazy. Wtyczka WordPress czyta tę bazę **read-only** i renderuje podstronę z filtrami i paginacją. Zdjęcia hotlinkowane, więc na dysku klienta zajmuje to **0 MB**.

▶️ **[Klikalne demo](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/krzysiek2115op/iaai-importer-demo/main/blueprint.json)** — uruchamia się w przeglądarce, bez instalacji.

![Katalog pojazdów z filtrami marki, rocznika i typu uszkodzenia oraz kartami ofert](assets/katalog-aut.png)

*Podstrona „Nasze auta" — filtry, karty pojazdów, oznaczenia źródła. Zdjęcia w demo to placeholdery; na wdrożeniu są hotlinkowane ze źródła.*

`Python` `PHP` `WordPress` `MySQL` `systemd` `pytest`

---

**[Czarodziejski Dworek — strona przedszkola](https://krzysiek2115op.github.io/-Nowa-strona-Czarodziejski-Dworek-/)** — ta sama strona w dwóch wariantach: statyczny HTML i autorski motyw WordPress **bez ani jednej wtyczki**.

Formularze przez Web3Forms: bez bazy, bez abonamentu, klucz wklejany przez właściciela w panelu. SEO lokalne, schema.org, CSP, WCAG, mobile-first.

`HTML` `CSS` `vanilla JS` `PHP` `WordPress`

---

**Automatic AI — sklep z kursami online** — katalog, strony sprzedażowe i automatyczne otwieranie dostępu po opłaceniu zamówienia.

Trzy wtyczki WordPress spinające WooCommerce z platformą kursową: klient płaci o drugiej w nocy i **od razu ma dostęp**, bez ręcznego odblokowywania. Świadoma decyzja: nie pisać własnej kasy ani własnego systemu kursów — moją pracą jest szew między nimi.

`2 kursy` · `12 modułów` · `73 lekcje` · `20 godzin materiału`

![Landing katalogu szkoleń Automatic AI z liczbami oferty i mockupem platformy](assets/automatic-ai.png)

▶️ **[Zobacz na żywo](https://matthewplugins.github.io/szkolenia-podglad/szkolenia)** — statyczny podgląd. Kod źródłowy prywatny, projekt prowadzony wspólnie.

`Next.js 16` `React 19` `TypeScript` `Tailwind` `PHP` `WordPress` `WooCommerce`

---

### Stack

**Backend** PHP 7.4–8.3 · Python 3.10+ · MySQL / MariaDB
**WordPress** wtyczki i motywy od zera, WooCommerce, WP-CLI, migracje schematu, WordPress Playground
**Frontend** HTML5 · CSS3 · vanilla JS · TypeScript · React 19 · Next.js 16 · Tailwind
**Automatyzacja** systemd timers · cron · GitHub Actions · Docker / podman
**Jakość** PHPCS/WPCS · ESLint · pytest · node:test · golden files · testy smoke

Piszę też dokumentację dla klienta nietechnicznego — instrukcje krok po kroku, nie tylko README dla programistów.

---

<details>
<summary><b>English summary</b></summary>

I automate repetitive business processes in WordPress and WooCommerce — the ones where someone still copies data by hand between a form, an inbox and a system.

- **Custom WordPress/WooCommerce plugins** — quote-to-offer pipelines, lead qualification, PDF generation, sales workflow
- **Data integrations and scrapers** — Python on a VPS feeding a private database, read-only WordPress plugin on the front
- **Websites and custom themes** — no plugin bloat, local SEO, accessibility, mobile-first
- **E-commerce integrations** — WooCommerce wired to whatever has to happen after payment

Featured: [MP Offer Automation Suite](https://github.com/krzysiek2115op/mp-offer-automation-suite) ([live demo](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/krzysiek2115op/mp-offer-automation-suite/main/tools/strona-pokazowa/blueprint.json), ~23k lines of PHP, 14 releases, CI on PHP 7.4 + 8.3) · [Copart/IAAI Importer](https://github.com/krzysiek2115op/copart-iaai-importer) ([live demo](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/krzysiek2115op/iaai-importer-demo/main/blueprint.json), runs in your browser) · [Automatic AI course shop](https://matthewplugins.github.io/szkolenia-podglad/szkolenia) (WooCommerce wired to an LMS — payment unlocks access automatically)

</details>

---

📫 **Zlecenia i współpraca** — napisz przez [GitHub](https://github.com/krzysiek2115op)
