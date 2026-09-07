<div align="center">

# Krzysztof Leszczyński

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains%20Mono&weight=600&size=22&duration=3500&pause=900&color=1C9D6A&center=true&vCenter=true&width=720&height=70&lines=Automatyzuj%C4%99%20to%2C%20co%20kto%C5%9B%20dzi%C5%9B%20przepisuje%20r%C4%99cznie%3BWordPress%20%E2%80%A2%20WooCommerce%20%E2%80%A2%20Python%20%E2%80%A2%20integracje%3BOd%20formularza%20do%20oferty%20PDF%20%E2%80%94%20bez%20kopiuj-wklej" alt="Automatyzuję to, co ktoś dziś przepisuje ręcznie" />

![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### 👇 Nie wierz na słowo — kliknij i zobacz, jak to działa

[![Demo: automatyzacja ofertowania](https://img.shields.io/badge/▶_DEMO-Automatyzacja_ofertowania-1C9D6A?style=for-the-badge)](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/krzysiek2115op/mp-offer-automation-suite/main/tools/strona-pokazowa/blueprint.json)
[![Demo: katalog z importera](https://img.shields.io/badge/▶_DEMO-Katalog_z_importera-1C9D6A?style=for-the-badge)](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/krzysiek2115op/iaai-importer-demo/main/blueprint.json)

*Oba uruchamiają kompletnego WordPressa **w Twojej przeglądarce**. Nic nie instalujesz, nic nie konfigurujesz.*

</div>

---

## 🎯 Czym się zajmuję

> Najprościej: **jeśli ktoś u Was codziennie przepisuje te same dane z miejsca w miejsce — buduję program, który robi to za niego.**
> Nie musisz się znać na technologii. Wystarczy, że opiszesz, co dziś klikacie ręcznie.

<table>
<tr>
<td width="33%" valign="top">

### 🔁 Koniec z przepisywaniem ręcznie

Ktoś u Was przenosi dane z formularza do maila, z maila do Excela, a z Excela do systemu?

Buduję program, który robi to sam: **zapytanie od klienta zamienia się w gotową ofertę PDF** i zadanie dla handlowca. Bez jednego „kopiuj-wklej".

**Co z tego masz:** oferta wychodzi w kilka minut zamiast w pół dnia, a nikt nie zapomina o kliencie.

</td>
<td width="33%" valign="top">

### 🔌 Dane z zewnątrz, zawsze aktualne

Potrzebujesz na stronie danych, które żyją gdzie indziej — cennika dostawcy, katalogu aukcji, stanów magazynowych?

Robię most: **dane same się pobierają i same wyświetlają** u Ciebie na stronie. Też w nocy i w weekend.

**Co z tego masz:** strona jest aktualna bez Twojego udziału i bez ręcznego wgrywania plików.

</td>
<td width="33%" valign="top">

### 🤖 AI i agenty w mojej pracy

Z narzędziami AI pracuję codziennie — pomagają pisać kod, wyłapywać w nim błędy i przygotowywać dokumentację dla Ciebie.

To nie jest gadżet. To powód, dla którego **ten sam zakres robię szybciej i taniej**, niż gdybym pisał wszystko od zera.

**Co z tego masz:** krótszy termin i niższa cena — przy tej samej kontroli, bo każdą linię i tak sprawdzam ja.

</td>
</tr>
</table>

**Robię też strony i sklepy WordPress** — autorskie motywy bez sterty wtyczek, widok mobilny, SEO lokalne. Bez abonamentów, które za rok przestaną działać.

<sub>Nie wiesz, do której szufladki pasuje Twój przypadek? Napisz zwykłym językiem, co Was męczy — od tego jest pierwsza rozmowa.</sub>

---

## 🚀 Projekty

### 1. MP Offer Automation Suite — od zapytania do podpisanej oferty

[![Repo](https://img.shields.io/badge/kod_źródłowy-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/krzysiek2115op/mp-offer-automation-suite)
![Ostatni commit](https://img.shields.io/github/last-commit/krzysiek2115op/mp-offer-automation-suite?style=flat-square&label=ostatni%20commit&color=1C9D6A)
![Rozmiar](https://img.shields.io/github/languages/code-size/krzysiek2115op/mp-offer-automation-suite?style=flat-square&label=rozmiar%20kodu&color=777BB4)
![Wydania](https://img.shields.io/github/v/release/krzysiek2115op/mp-offer-automation-suite?style=flat-square&label=wydanie&color=21759B)

Pakiet **3 wtyczek** prowadzący zapytanie ofertowe od formularza na stronie do oferty PDF i zadania u handlowca.

![Panel procesów sprzedażowych: lista spraw z klientem, statusem, przypisanym handlowcem i terminem SLA](assets/procesy-sprzedazowe.png)

> **Kluczowa decyzja:** wtyczki **nie znają swoich klas ani tabel** — rozmawiają wyłącznie zdarzeniami WordPressa. Klient może wdrożyć jedną i ocenić efekt, zanim zdecyduje o reszcie. Podpięcie nowego kroku do procesu to nowa wtyczka słuchająca haka, bez dotykania istniejącego kodu.

**33 944 linii kodu produkcyjnego** i **32 767 linii testów** · **72 wydania** · CI na PHP 7.4 + 8.3 · harness procesu ze **110 niezmiennikami**

`PHP` `WordPress` `WooCommerce` `MySQL` `dompdf` `PHPCS/WPCS` `GitHub Actions`

---

### 2. Copart / IAAI Importer — cudze dane na stronie klienta

[![Repo](https://img.shields.io/badge/kod_źródłowy-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/krzysiek2115op/copart-iaai-importer)
![Ostatni commit](https://img.shields.io/github/last-commit/krzysiek2115op/copart-iaai-importer?style=flat-square&label=ostatni%20commit&color=1C9D6A)
![Rozmiar](https://img.shields.io/github/languages/code-size/krzysiek2115op/copart-iaai-importer?style=flat-square&label=rozmiar%20kodu&color=3776AB)

Scraper w Pythonie chodzi na VPS z timera systemd i zasila własną bazę. Wtyczka WordPress czyta ją **read-only** i renderuje katalog z filtrami.

![Katalog pojazdów z filtrami marki, rocznika i typu uszkodzenia oraz kartami ofert](assets/katalog-aut.png)

> **Zdjęcia są hotlinkowane ze źródła** — hosting klienta zajmuje **0 MB**, czy w katalogu jest 50 czy 5000 pozycji. Gdyby scraper działał jako wtyczka, każde pobranie obciążałoby serwer klienta, a błąd mógłby położyć stronę. Rozdzielone — strona serwuje ostatnie dobre dane, nawet gdy pobieranie się wywali.

**Komplet dokumentacji dla osoby nietechnicznej:** 9 dokumentów krok po kroku + 10 plików PDF.

`Python` `PHP` `WordPress` `MySQL` `systemd` `pytest`

---

### 3. Automatic AI — sklep z kursami online

[![Zobacz na żywo](https://img.shields.io/badge/zobacz_na_żywo-1C9D6A?style=flat-square&logo=googlechrome&logoColor=white)](https://matthewplugins.github.io/szkolenia-podglad/szkolenia)
![Prywatne](https://img.shields.io/badge/kod_źródłowy-prywatny-6B7280?style=flat-square)

Katalog kursów, strony sprzedażowe i **automatyczne otwieranie dostępu po opłaceniu zamówienia**.

![Landing katalogu szkoleń Automatic AI z liczbami oferty i mockupem platformy](assets/automatic-ai.png)

> **Świadoma decyzja: nie pisać własnej kasy ani własnego systemu kursów.** WooCommerce robi płatności bezpieczniej i utrzymuje je ktoś inny. Moją pracą jest szew między systemami — najtańsza część, a jednocześnie ta, której nie da się kupić gotowej.

Osobna wtyczka monitorująca pilnuje, czy ścieżka płatność → dostęp nadal działa. **Automatyzacja bez monitoringu to maszyna bez kontrolki** — działa, dopóki nie przestanie, i nikt nie wie kiedy.

`2 kursy` · `12 modułów` · `73 lekcje` · `20 godzin materiału`

`Next.js 16` `React 19` `TypeScript` `Tailwind` `PHP` `WordPress` `WooCommerce`

---

### 4. Czarodziejski Dworek — strona przedszkola w dwóch wariantach

[![Strona na żywo](https://img.shields.io/badge/strona_na_żywo-1C9D6A?style=flat-square&logo=googlechrome&logoColor=white)](https://krzysiek2115op.github.io/czarodziejski-dworek/)
[![Repo](https://img.shields.io/badge/kod_źródłowy-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/krzysiek2115op/czarodziejski-dworek)

Ta sama strona w dwóch wariantach: statyczny HTML i **autorski motyw WordPress bez ani jednej wtyczki**.

> **Dlaczego bez wtyczek:** każda wtyczka to zależność, która może przestać być rozwijana albo przejść na abonament. Przy kliencie bez działu IT to realne ryzyko — za dwa lata strona przestaje działać, bo wtyczka do galerii zniknęła.

Formularze przez zewnętrzną usługę: bez bazy, bez abonamentu, klucz w panelu zamiast w kodzie. Efekt uboczny — strona **nie przechowuje danych osobowych z formularza**, więc zakres obowiązków wokół RODO jest istotnie mniejszy.

`HTML5` `CSS3` `vanilla JS` `PHP` `schema.org` `WCAG` `CSP`

---

## 🧰 Tech stack

**Backend**

![PHP](https://img.shields.io/badge/PHP_7.4–8.3-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python_3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL_/_MariaDB-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**WordPress**

![WordPress](https://img.shields.io/badge/wtyczki_i_motywy_od_zera-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white)
![WP-CLI](https://img.shields.io/badge/WP--CLI-0073AA?style=for-the-badge&logo=wordpress&logoColor=white)

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Automatyzacja i jakość**

![Linux](https://img.shields.io/badge/systemd_/_cron-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_/_podman-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Testy](https://img.shields.io/badge/PHPCS_·_pytest_·_ESLint-4B5563?style=for-the-badge)

**AI — moje codzienne narzędzia pracy**

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-181717?style=for-the-badge&logo=githubcopilot&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-0F172A?style=for-the-badge&logo=cursor&logoColor=white)
![Windsurf](https://img.shields.io/badge/Windsurf-09B6A2?style=for-the-badge&logo=windsurf&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=for-the-badge)

![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logo=deepseek&logoColor=white)
![Grok](https://img.shields.io/badge/Grok-000000?style=for-the-badge&logo=x&logoColor=white)
![Perplexity](https://img.shields.io/badge/Perplexity-1FB8CD?style=for-the-badge&logo=perplexity&logoColor=white)

<sub>AI przyspiesza pisanie i sprawdzanie kodu — <b>nie zastępuje przeglądu</b>. Każda dostawa przechodzi przeze mnie i przez osobny przebieg kontrolny opisany niżej.</sub>

---

## 📊 W liczbach

Wolę pokazać, ile kodu przeszło przez ręce, niż ile ktoś przybił gwiazdek.

| | |
|---|---|
| 🔨 **~1 230 commitów własnych** w 12 repozytoriach | 507 w publicznych (licznik GitHuba) + 724 w prywatnych, których ten licznik nie widzi |
| 📦 **33 944 linii kodu produkcyjnego** w flagowym projekcie | 160 plików, 72 wydania |
| 🧪 **32 767 linii testów** — niemal tyle, co kodu | plus **110 niezmienników procesu** w CI |
| 📚 **9 dokumentów + 10 PDF** dla klienta nietechnicznego | dokumentacja to część dostawy, nie dodatek |
| ▶️ **2 klikalne demo** | klient ocenia produkt, zanim zapłaci |

<div align="center">

![Commity — pakiet ofertowy](https://img.shields.io/github/commit-activity/t/krzysiek2115op/mp-offer-automation-suite?style=for-the-badge&label=commity%20%C2%B7%20pakiet%20ofertowy&color=21759B)
![Commity — importer aukcji](https://img.shields.io/github/commit-activity/t/krzysiek2115op/copart-iaai-importer?style=for-the-badge&label=commity%20%C2%B7%20importer%20aukcji&color=3776AB)
![Commity — platforma szkoleniowa](https://img.shields.io/badge/commity%20%C2%B7%20platforma%20szkoleniowa-666-6B7280?style=for-the-badge)

<sub>Dwa pierwsze liczniki pobiera GitHub na żywo — to całość commitów w tych repozytoriach i wszystkie są moje. Trzeci dotyczy repozytorium prywatnego (668 commitów, z tego 666 moich), więc podaję liczbę wprost.</sub>

</div>

---

## 🤝 Jak pracuję

To, co odróżnia moją ofertę od „wyślę Ci ZIP-a i powodzenia":

| | |
|---|---|
| 🎬 **Najpierw demo, potem decyzja** | Dwa moje projekty mają klikalne demo. Zobaczysz, jak działa, zanim cokolwiek zapłacisz. |
| 🧩 **Modułowo, nie wszystko naraz** | Wdrażamy jeden element, oceniasz efekt, dopiero potem resztę. Nic nie zmusza Cię do całości. |
| 📖 **Dokumentacja dla Ciebie, nie dla programisty** | Instrukcja krok po kroku, żeby system działał bez mojego udziału. |
| 🔍 **Osobny przebieg kontrolny** | Komplet zielonych testów nie znaczy, że kod jest poprawny — znaczy, że przechodzi te testy, które ktoś pomyślał się napisać. Audyt mojego flagowego projektu znalazł **8 błędów krytycznych w kodzie, który przechodził wszystkie testy**. Od tego czasu zakładam osobną kontrolę w każdej dostawie. |
| 🚫 **Bez abonamentów, których nie potrzebujesz** | Jeśli da się zrobić bez płatnej wtyczki — robię bez. |

---

## 📫 Kontakt

**Napisz albo zadzwoń.** Powiedz, co robisz dziś ręcznie i jak często — odpowiem, czy da się to zautomatyzować, ile to zajmie i ile będzie kosztowało. Bez zobowiązań i bez żargonu.

<div align="center">

## 📧 krzysztof2006oskar@wp.pl

## 📱 531 820 534

[![Napisz maila](https://img.shields.io/badge/✉_NAPISZ_MAILA-krzysztof2006oskar@wp.pl-1C9D6A?style=for-the-badge)](mailto:krzysztof2006oskar@wp.pl?subject=Pytanie%20o%20automatyzacj%C4%99)
[![Zadzwoń](https://img.shields.io/badge/📞_ZADZWOŃ-531_820_534-1C9D6A?style=for-the-badge)](tel:+48531820534)

[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/krzysztof.leszczynski.148/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/krzysiek2115op)

<sub>Odpowiadam w ciągu jednego dnia roboczego. Wolisz najpierw napisać niż dzwonić? Mail jest w porządku — opisz proces, resztę dopytam sam.</sub>

</div>

---

<details>
<summary><b>🇬🇧 English summary</b></summary>

<br>

I automate repetitive business processes in WordPress and WooCommerce — the ones where someone still copies data by hand between a form, an inbox and a system.

- **Custom WordPress/WooCommerce plugins** — quote-to-offer pipelines, lead qualification, PDF generation, sales workflow
- **Data integrations and scrapers** — Python on a VPS feeding a private database, read-only WordPress plugin on the front
- **E-commerce integrations** — WooCommerce wired to whatever has to happen after payment
- **AI-assisted delivery** — I work with AI coding assistants daily (Claude Code, Copilot, Cursor, Windsurf, Codex) and with ChatGPT, Gemini, Claude, DeepSeek, Grok and Perplexity for research. Same scope, shorter timeline, lower price — every line still reviewed by me
- **Websites and custom themes** — no plugin bloat, local SEO, accessibility, mobile-first

**Try before you decide** — both flagship projects ship a clickable demo that boots a full WordPress install in your browser:

[![Demo 1](https://img.shields.io/badge/▶_DEMO-Quote_to_offer_automation-1C9D6A?style=for-the-badge)](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/krzysiek2115op/mp-offer-automation-suite/main/tools/strona-pokazowa/blueprint.json)
[![Demo 2](https://img.shields.io/badge/▶_DEMO-Auction_catalogue-1C9D6A?style=for-the-badge)](https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/krzysiek2115op/iaai-importer-demo/main/blueprint.json)

Featured work: [MP Offer Automation Suite](https://github.com/krzysiek2115op/mp-offer-automation-suite) (33,944 lines of production PHP plus 32,767 lines of tests, 72 releases, CI on PHP 7.4 + 8.3, a process harness of 110 invariants) · [Copart/IAAI Importer](https://github.com/krzysiek2115op/copart-iaai-importer) (Python scraper on a VPS, read-only WordPress plugin, images hotlinked so the client's hosting uses 0 MB) · [Automatic AI course shop](https://matthewplugins.github.io/szkolenia-podglad/szkolenia) (WooCommerce wired to an LMS — payment unlocks access automatically)

**How I work:** demo before you decide · modular delivery, one piece at a time · documentation written for the person operating the system, not for a developer · AI speeds up writing and checking the code, it does not replace review · a separate verification pass on every delivery, because a green test suite only proves the code passes the tests someone thought to write.

**Contact:** [krzysztof2006oskar@wp.pl](mailto:krzysztof2006oskar@wp.pl) · +48 531 820 534 · [Facebook](https://www.facebook.com/krzysztof.leszczynski.148/) — tell me what you do by hand today and how often, and I will tell you whether it is worth automating, how long it takes and what it costs.

</details>

<div align="center">

<sub>Masz proces, który zjada Wam czas? Napisz — powiem wprost, czy warto go automatyzować.</sub>

</div>
