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

`PHP` `WordPress` `WooCommerce` `MySQL` `dompdf` `GitHub Actions`

---

**[Copart/IAAI Importer](https://github.com/krzysiek2115op/copart-iaai-importer)** — aktualna oferta z aukcji samochodowych na stronie dealera, bez ręcznego wprowadzania pojazdów.

Scraper w Pythonie chodzi na VPS z timera systemd: crawl → normalizacja → deduplikacja → audyt → zapis do bazy. Wtyczka WordPress czyta tę bazę **read-only** i renderuje podstronę z filtrami i paginacją. Zdjęcia hotlinkowane, więc na dysku klienta zajmuje to **0 MB**.

▶️ **[Klikalne demo](https://github.com/krzysiek2115op/iaai-importer-demo)** — uruchamia się w przeglądarce, bez instalacji.

`Python` `PHP` `WordPress` `MySQL` `systemd` `pytest`

---

**[Strona przedszkola](https://krzysiek2115op.github.io/-Nowa-strona-Czarodziejski-Dworek-/)** — ta sama strona w dwóch wariantach: statyczny HTML i autorski motyw WordPress **bez ani jednej wtyczki**.

Formularze przez Web3Forms: bez bazy, bez abonamentu, klucz wklejany przez właściciela w panelu. SEO lokalne, schema.org, CSP, WCAG, mobile-first.

`HTML` `CSS` `vanilla JS` `PHP` `WordPress`

---

**[AI PR Guardian](https://github.com/krzysiek2115op/AI-PR-GUARDIAN-)** — bramka jakości dla Pull Requestów oparta o subagenta „strażnik regresji" i obowiązkowego krytyka, który próbuje obalić jego tezę.

Powstała, gdy okazało się, że 4 z 13 znanych klas błędów w projekcie nie miały żadnej ochrony automatycznej, mimo 25 strażników i 75 testów.

`JavaScript` `GitHub Actions` `Anthropic API` `zero dependencies`

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

Featured: [MP Offer Automation Suite](https://github.com/krzysiek2115op/mp-offer-automation-suite) (~23k lines of PHP, 14 releases, CI on PHP 7.4 + 8.3) · [Copart/IAAI Importer](https://github.com/krzysiek2115op/copart-iaai-importer) ([live demo](https://github.com/krzysiek2115op/iaai-importer-demo), runs in your browser)

</details>

---

📫 **Zlecenia i współpraca** — napisz przez [GitHub](https://github.com/krzysiek2115op)
