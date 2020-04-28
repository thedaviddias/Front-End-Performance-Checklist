<h1 align="center">
<br>
  <a href="https://github.com/thedaviddias/Front-End-Performance-Checklist"><img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170"></a>
  <br>
    <br>
  Checklista wydajności Frontendu
  <br>
</h1>

<h4 align="center">🎮 Jedyna checklista wydajności Frontend, która działa szybciej, niż inne.</h4>
<p align="center">Jedna prosta zasada: "Projektuj i koduj z wydajnością na uwadze"</p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://discord.gg/btHQRkm">
    <img src="https://img.shields.io/badge/chat-on_discord-4837E2.svg?style=flat-square" alt="Discord">
  </a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="Licence MIT">
  </a>
</p>

<p align="center">
  <a href="#how-to-use">Jak korzystać</a> • <a href="#contributing">Współtworzenie</a> • <a href="http://feedback.frontendchecklist.io/">Plan</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Product Hunt</a>
</p>

<p align="center">
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/ParkSB/Front-End-Performance-Checklist">🇰🇷</a>
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
  <a href="https://github.com/mbiesiad/Front-End-Performance-Checklist">🇵🇱</a>
</p>

<p align="center">
    <span>Inne checklisty:</span>
    <br>
  🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Front-End Checklist</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Front-End Design Checklist</a>
</p>

## Spis treści

1. **[HTML](#html)**
2. **[CSS](#css)**
3. **[Czcionki](#czcionki)**
4. **[Obrazy](#obrazy)**
5. **[JavaScript](#javascript)**
6. **[Serwer](#serwer) (w trakcie)**
7. **[Frameworki JS](#wydajno%C5%9B%C4%87-i-frameworki-js) (w trakcie)**

## Wprowadzenie

Wydajność jest sporym tematem, ale nie zawsze jest to tylko temat "backendu" lub "admina": to także odpowiedzialność frontendu. Lista kontrolna wydajności frontendu to wyczerpująca lista elementów, które powinieneś sprawdzić, a przynajmniej być jej świadomym, jako programista frontend i stosować to w swoim projekcie (osobistym i zawodowym).

### Jak korzystać?

Dla każdej zasady będzie akapit wyjaśniający *dlaczego* ta zasada jest ważna i *jak* możesz to naprawić. Aby uzyskać więcej szczegółowych informacji, należy znaleźć linki, które będą wskazywać 🛠 narzędzia, 📖 artykuły lub 📹 media które mogą wypełnić listę kontrolną.

Wszystkie elementy w **Checklista wyjdajności Frontend** są niezbędne, aby osiągnąć najwyższy wynik wydajności, ale można znaleźć też wskaźnik, który pomoże w ustaleniu priorytetów niektórych zasad w stosunku do innych. Istnieją 3 poziomy priorytetu:

* ![Low][low] oznacza, że element ma **niski** priorytet.
* ![Medium][medium] oznacza, że element ma **średni** priorytet. Nie powinieneś unikać zajmowania się tą kwestią.
* ![High][high] oznacza, że element ma **wysoki** priorytet. Nie można uniknąć przestrzegania tej zasady i wprowadzenia zalecanych poprawek.

### Narzędzia wydajności

Lista narzędzi, których możesz użyć do testowania lub monitorowania swojej witryny lub aplikacji:

 * 🛠 [WebPagetest - Website Performance and Optimization Test](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Website Speed Test and Website Analysis](https://www.dareboost.com/) (użyj kuponu WPCDD20 dla -20%)
 * 🛠 [Treo: Page Speed Monitoring](https://treo.sh/?ref=perfchecklist)
 * 🛠 [GTmetrix | Website Speed and Performance Optimization](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Web.dev](https://web.dev/measure)
 * 🛠 [Pingdom Website Speed Test](https://tools.pingdom.com)
 * 📖 [Make the Web Faster | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Welcome to the wonderful world of Web Performance](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Check Web Performance &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Website and Server Uptime Monitoring - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Link do darmowej rejestracji](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Monitor front-end performance](https://speedcurve.com)
 * 🛠 [PWMetrics - CLI tool and lib to gather performance metrics](https://github.com/paulirish/pwmetrics)
 * 🛠 [Varvy - Page speed optimization]( https://varvy.com/pagespeed/)
 * 🛠 [Lighthouse - Google]( https://developers.google.com/web/tools/lighthouse/#devtools)
 * 🛠 [Checkbot browser extension - Checks for web performance best practices](https://www.checkbot.io/)
 * 🛠 [Yellow Lab Tools | Online test to help speeding up heavy web pages](https://yellowlab.tools/)
 * 🛠 [Speedrank - Web Performance Monitoring](https://speedrank.app/)
 * 🛠 [DebugBear - Monitor website performance and Lighthouse scores](https://www.debugbear.com/)
 * 🛠 [packtracker.io - Check your webpack bundle size on every pull request.](https://packtracker.io/)
 * 🛠 [Exthouse - Analyze the impact of a browser extension on web performance](https://github.com/treosh/exthouse)

### Odnośniki

 * 📹 [The Cost Of JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4) ([wersja tekstowa](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4))
 * [AddyOsmani.com - Start Performance Budgeting](https://addyosmani.com/blog/performance-budgets/)
 * 📖 [Get Started With Analyzing Runtime Performance  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [State of the Web | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Page Weight Doesn't Matter](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
 * 📖 [Front-End Performance Checklist 2018 [PDF, Apple Pages]](https://www.smashingmagazine.com/2018/01/front-end-performance-checklist-2018-pdf-pages/)
 * 📖 [Designing for Performance Weighing Aesthetics and Speed - By Lara Callender Hogan [eBook, Print]](http://designingforperformance.com/index.html)
 * 📖 [Varvy - Web performance glossary](https://varvy.com/performance/)
 * 📖 [fabkrum/web-performance-resources: Up to date collection of valuable web performance resources](https://github.com/fabkrum/web-performance-resources)
 * 📖 [Checkbot - Web Speed Best Practices](https://www.checkbot.io/guide/speed/)
 * 🛠 [Progressive Tooling - A list of community-built, third-party tools that can be used to improve page performance](https://progressivetooling.com/)

---

## HTML

![html]

- [ ] **Zminifikowany HTML:** ![medium] Kod HTML jest minifikowany, komentarze, białe znaki i nowe wiersze są usuwane z plików produkcyjnych.

    *Czemu:*
    > Usunięcie wszystkich niepotrzebnych spacji, komentarzy i atrybutów zmniejszy rozmiar kodu HTML i przyspieszy czas wczytywania strony w witrynie oraz oczywiście zmniejszy pobieranie pliku dla użytkownika.

    *Jak:*
    > Większość frameworków ma wtyczki ułatwiające minifikację stron internetowych. Możesz użyć zestawu modułów NPM, które mogą wykonać zadanie automatycznie.

    * 🛠 [HTML minifier | Minify Code](http://minifycode.com/html-minifier/)
    * 🛠 [Online HTML Compressor](http://refresh-sf.com)
    * 📖 [Experimenting with HTML minifier — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)
   
- [ ] **Umieść tagi CSS zawsze przed tagami JavaScript:** ![high] Upewnij się, że twój CSS jest zawsze ładowany przed kodem JavaScript.

    ```html
    <!-- Not recommended -->
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    <link rel="stylesheet" href="foo.css"/>

    <!-- Recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    ```

    *Czemu:*
    > Posiadanie tagów CSS przed JavaScriptem umożliwia lepsze równoległe pobieranie, co przyspiesza czas renderowania w przeglądarce.

    *Jak:*
    > ⁃ Upewnij się, że `<link>` i `<style>` w twoim `<head>` są zawsze przed twoim `<script>`.

    * 📖 [Ordering your styles and scripts for pagespeed](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **Zminimalizuj liczbę iframes:** ![high] Używaj iframe tylko wtedy, gdy nie masz innych technicznych możliwości. Staraj się unikać iframe tak bardzo, jak potrafisz.

- [ ] **Optymalizacja wstępnego ładowania z pobieraniem wstępnym, dns-prefetch i prerender:** ![low] Popularne przeglądarki mogą korzystać z dyrektywy tagu `<link>` i atrybutu "rel" z niektórymi słowami kluczowymi, aby wstępnie załadować określone adresy URL.

    *Czemu:*
    > Pobieranie wstępne umożliwia przeglądarce ciche pobieranie niezbędnych zasobów potrzebnych do wyświetlenia treści, do których użytkownik może uzyskać dostęp w najbliższej przyszłości. Przeglądarka jest w stanie przechowywać te zasoby w pamięci podręcznej i przyspieszyć ładowanie stron internetowych, gdy używają różnych domen do zasobów strony. Po zakończeniu ładowania strony internetowej i upłynięciu czasu bezczynności przeglądarka rozpoczyna pobieranie innych zasobów. Gdy użytkownik przejdzie do określonego linku (już wstępnie pobranego), treść zostanie natychmiast wyświetlona.

    *Jak:*
    > ⁃ Upewnij się, że `<link>` w twojej sekcji `<head>`.

    * 📖 [What Is Prefetching and Why Use It](https://www.keycdn.com/support/prefetching)
    * 📖 [Prefetching, preloading, prebrowsing](https://css-tricks.com/prefetching-preloading-prebrowsing/)
    * 📖 [What is Preload, Prefetch, and Preconnect](https://www.keycdn.com/blog/resource-hints)

**[⬆ powrót do góry](#spis-treści)**

## CSS

![css]

- [ ] **Minifikacja:** ![high] Wszystkie pliki CSS są minifikowane, komentarze, białe znaki i nowe wiersze są usuwane z plików produkcyjnych.

    *Czemu:*
    > Po zminifikowaniu plików CSS zawartość ładuje się szybciej i do klienta wysyłanych jest mniej danych. Ważne jest, aby zawsze minifikować pliki CSS podczas produkcji. Jest to korzystne dla użytkownika, podobnie jak dla każdej firmy, która chce obniżyć koszty przepustowości i zmniejszyć zużycie zasobów.

    *Jak:*
    > ⁃ Użyj narzędzi, aby zminifikować pliki automatycznie przed kompilacją lub wdrożeniem lub w jej trakcie.

    * 🛠 [cssnano: A modular minifier based on the PostCSS ecosystem. - cssnano](https://cssnano.co/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)


- [ ] **Konkatenacja:** ![medium] Pliki CSS są łączone w jednym pliku *(nie zawsze dotyczy HTTP/2)*.

    ```html

    <!-- Niezalecane -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Zalecane -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *Czemu:*
    > Jeśli nadal używasz protokołu HTTP/1, może być konieczne połączenie plików, mniej prawdopodobne jest, jeśli serwer używa protokołu HTTP/2 (należy wykonać testy).

    *Jak:*
    > ⁃ Użyj narzędzia online lub dowolnej wtyczki przed kompilacją plików lub podczas kompilacji lub wdrożenia, aby połączyć twoje pliki. <br>
    ⁃ Upewnij się oczywiście, że konkatenacja nie psuje twojego projektu.

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **Nieblokujące:** ![high] Pliki CSS muszą być nieblokujące, aby nie dopuścić do poświęcenia czasu przez DOM.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *Czemu:*
    > Pliki CSS mogą blokować ładowanie strony i opóźniać jej renderowanie. Za pomocą `preload` można załadować aktualne pliki CSS, zanim przeglądarka zacznie wyświetlać zawartość strony.

    *Jak:*
    > ⁃ Musisz dodać atrybut `rel` z wartością `preload` i dodać `as="style"` w elemencie `<link>`.

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Example of preload CSS using loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Preloading content with rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: What Is It Good For? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **Nieużywany CSS:** ![medium] Usuń nieużywane selektory CSS.

    *Czemu:*
    > Usunięcie nieużywanych selektorów CSS może zmniejszyć rozmiar plików, a następnie przyspieszyć ładowanie zasobów.

    *Jak:*
    > ⁃ ⚠️ Zawsze sprawdź, czy we frameworku CSS, którego chcesz użyć, nie ma jeszcze kodu resetowania / normalizacji. Czasami możesz nie potrzebować wszystkiego, co znajduje się w pliku resetowania / normalizacji.

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS Critical:** ![high] CSS critical (lub "above the fold") zbiera wszystkie CSS użyte do renderowania widocznej części strony. Jest osadzony przed głównym wywołaniem CSS i między `<style></style>` w pojedynczej linii (minifikowane, gdy możliwe).

    *Czemu:*
    > Wprowadzenie critical CSS pomaga przyspieszyć renderowanie stron internetowych, zmniejszając liczbę żądań do serwera.

    *Jak:*
    > Wygeneruj CSS critical za pomocą narzędzi online lub używając wtyczki takiej jak ta, którą opracował Addy Osmani.

    * 📖 [Understanding Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inlining critical CSS for better web performance | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
     * 🛠 [Critical Path CSS Generator - Prioritize above the fold content :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
     * 📖 [Reduce the size of the above-the-fold content](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **Osadzony lub wbudowany CSS:** ![high] Unikaj używania wbudowanego lub osadzonego CSS wewnątrz swojego `<body>` *(Nie dotyczy HTTP/2)*

    *Czemu:*
    > Jednym z pierwszych powodów jest to, że jest to dobra praktyka, aby **oddzielić treść od projektu**. Pomaga także w utrzymaniu kodu, który jest łatwiejszy w utrzymaniu i zapewnia dostęp do witryny. Ale jeśli chodzi o wydajność, to po prostu dlatego, że zmniejsza rozmiar pliku stron HTML i czas ładowania.

    *Jak:*
    > Zawsze używaj zewnętrznych arkuszy stylów lub osadzaj CSS w swoim `<head>` (i postępuj zgodnie z innymi zasadami wydajności CSS)

    * 📖 [Observe CSS Best Practices: Avoid CSS Inline Styles](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Analizuj złożoność arkuszy stylów:** ![high] Analiza arkuszy stylów może pomóc w oznaczaniu problemów, redundancji i duplikowaniu selektorów CSS.

    *Czemu:*
    > Czasami możesz mieć nadmiarowości lub błędy sprawdzania poprawności w swoim CSS, analiza plików CSS i usunięcie tych złożoności może pomóc ci przyspieszyć pliki CSS (ponieważ twoja przeglądarka będzie je szybciej czytać)

    *Jak:*
    > Twój CSS powinien być zorganizowany, używanie preprocesora CSS może ci w tym pomóc. Niektóre narzędzia online wymienione poniżej mogą również pomóc w analizie i poprawieniu kodu.

    * 🛠 [TestMyCSS | Optimize and Check CSS Performance](http://www.testmycss.com/)
    * 🛠 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: CSS selectors complexity and performance analyzer](https://github.com/macbre/analyze-css)
    * 🛠 [Project Wallace](https://www.projectwallace.com/) jest jak CSS Stats ale przechowuje statystyki, abyś mógł śledzić zmiany

**[⬆ powrót do góry](#spis-treści)**

## Czcionki

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **Webfont formats:** ![medium] Używasz WOFF2 w swoim projekcie lub aplikacji webowej.

    *Czemu:*
    > Według Google, WOFF 2.0 Web Font format kompresji oferuje 30% średni zysk w porównaniu z WOFF 1.0. W takim przypadku dobrze jest użyć WOFF 2.0, WOFF 1.0 jako rezerwowego i TTF.

    *Jak:*
    > Przed zakupem nowej czcionki sprawdź, czy dostawca podaje ci format WOFF2. Jeśli używasz darmowej czcionki, zawsze możesz użyć Font Squirrel, aby wygenerować wszystkie potrzebne formaty.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Używaj `preconnect` aby ładować twoje czcionki szybciej:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Czemu:*
    > Po wejściu na stronę internetową urządzenie musi dowiedzieć się, gdzie znajduje się twoja witryna i z którym serwerem musi się połączyć. Twoja przeglądarka musiała skontaktować się z serwerem DNS i poczekać na zakończenie wyszukiwania przed pobraniem zasobu (czcionek, plików CSS...). Prefiksy i połączenia wstępne pozwalają przeglądarce wyszukać informacje DNS i rozpocząć nawiązywanie połączenia TCP z serwerem obsługującym plik czcionek. Zapewnia to wzrost wydajności, ponieważ zanim przeglądarka zacznie analizować plik css z informacjami o czcionce i odkryje, że musi zażądać pliku czcionki z serwera, będzie już wstępnie rozpoznawać informacje DNS i mieć otwarte połączenie do serwera gotowego w puli połączeń.

    *Jak:*
    > ⁃ Przed prefetchingiem twoich webfonts, użyj webpagetest, aby ocenić swoją stronę<br>
    ⁃ Poszukaj zapytań DNS w kolorze morskim i zwróć uwagę na żądany host <br>
    ⁃ Pobierz wstępnie twoje webfonts w `<head>` i ostatecznie dodaj te nazwy hostów, które powinieneś również pobrać

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader gives you added control when using linked fonts via @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Rozmiar webfont:** ![medium] Rozmiary webfont nie przekraczają 300kb (zawarte wszystkie warianty)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Zapobiegaj Flashowi lub niewidocznemu tekstowi:** ![medium] Unikaj przezroczystego tekstu, dopóki Webfont jest ładowany

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ powrót do góry](#spis-treści)**

## Obrazy

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Optymalizacja obrazów:** ![high] Twoje obrazy są zoptymalizowane, skompresowane bez bezpośredniego wpływu na użytkownika końcowego.

    *Czemu:*
    > Zoptymalizowane obrazy ładują się szybciej w przeglądarce i zużywają mniej danych.

    *Jak:*
    > ⁃ Spróbuj użyć efektów CSS3, gdy jest to możliwe (zamiast małego obrazu) <br>
    ⁃ Jeśli to możliwe, używaj czcionek zamiast tekstu zakodowanego na obrazach <br>
    ⁃ Użyj SVG <br>
    ⁃ Użyj narzędzia i określ poziom kompresji poniżej 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Essential Image Optimization - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)
    * 🛠 [ImageEngine - Image Webpage Loading Test](https://demo.imgeng.in)
    * 🛠 [SVGOMG - Optimize SVG vector graphics files](https://jakearchibald.github.io/svgomg/)


* [ ] **Format obrazów:** ![high] Wybierz odpowiedni format obrazu.

    *Czemu:*
    > Aby mieć pewność, że twoje obrazy nie spowalniają twojej witryny, wybierz format, który będzie odpowiadał twojemu obrazowi. Jeśli jest to zdjęcie, JPEG jest w większości przypadków bardziej odpowiedni, niż PNG lub GIF. Ale nie zapomnij spojrzeć na formaty nex-gen, które mogą zmniejszyć rozmiar twoich plików. Każdy format obrazu ma zalety i wady, ważne jest, aby je znać, aby umożliwić jak najlepszy wybór.

    *Jak:*
    > ⁃ Użyj [Lighthouse](https://developers.google.com/web/tools/lighthouse/) w celu ustalenia, które obrazy mogą ostatecznie wykorzystać **formaty następnej generacji** (np. JPEG 2000m JPEG XR lub WebP) <br>
    ⁃ Porównaj różne formaty, czasem użycie PNG8 jest lepsze niż PNG16, a czasem nie.

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Użyj obrazu wektorowego vs rastra/bitmapy:** ![medium] Preferuj używanie obrazu wektorowego zamiast obrazów bitmapowych (jeśli to możliwe).

    *Czemu:*
    > Obrazy wektorowe (SVG) są zwykle mniejsze niż obrazy, a pliki SVG są responsywne i idealnie skalowane. Te obrazy mogą być animowane i modyfikowane przez CSS.

* [ ] **Wymiary obrazów:** ![medium] Ustaw atrybuty `width` i `height` na `<img>` jeśli znany jest ostateczny rozmiar renderowanego obrazu.

    *Czemu:*
    > Jeśli ustawiona jest wysokość i szerokość, wymagana przestrzeń dla obrazu jest rezerwowana podczas ładowania strony. Jednak bez tych atrybutów przeglądarka nie zna rozmiaru obrazu i nie może zarezerwować dla niego odpowiedniej przestrzeni. Efektem będzie zmiana układu strony podczas ładowania (podczas ładowania obrazów).

* [ ] **Unikaj używania obrazów Base64:** ![medium] Możesz w końcu przekonwertować małe obrazy na base64, ale tak naprawdę nie jest to najlepsza praktyka.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading:** ![medium] Obrazy poza ekranem są ładowane leniwie (zawsze dostępna jest rezerwowa kopia noscript).

    *Czemu:*
    > Poprawi to czas odpowiedzi bieżącej strony, a następnie pozwoli uniknąć ładowania niepotrzebnych obrazów, których użytkownik może nie potrzebować.

    *Jak:*
    > ⁃ Użyj [Lighthouse](https://developers.google.com/web/tools/lighthouse/) aby określić, ile **obrazów jest poza ekranem**.<br>
    ⁃ Użyj wtyczki JavaScript takiej jak poniżej, aby lazyloadować swoje obrazy. Pamiętaj, aby kierować reklamy tylko na obrazy poza ekranem. <br>
    ⁃ Upewnij się także, że alternatywne 'leniwe ładowane' obrazy są wyświetlane po najechaniu myszką lub po wykonaniu innych czynności przez użytkownika.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Responsywne obrazy:** ![medium] Pamiętaj, aby wyświetlać obrazy zbliżone do twojego rozmiaru wyświetlacza.

    *Czemu:*
    > Niewielkie urządzenia nie potrzebują obrazów większych niż ich okno poglądu. Zalecane jest posiadanie wielu wersji jednego obrazu w różnych rozmiarach.

    *Jak:*
    > ⁃ Utwórz różne rozmiary obrazów dla urządzeń, na które chcesz kierować reklamy. <br>
    ⁃ Użyj `srcset` i `picture` aby dostarczyć wiele wariantów każdego obrazu.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ powrót do góry](#spis-treści)**

## JavaScript

![javascript]

- [ ] **Minifikacja JS:** ![high] Wszystkie pliki JavaScript są pomniejszone, komentarze, białe znaki i nowe wiersze są usuwane z plików produkcyjnych *(nadal ważne, używając HTTP/2)*.

    *Czemu:*
    > Usunięcie wszystkich niepotrzebnych spacji, komentarzy i podziałów zmniejszy rozmiar plików JavaScript i przyspieszy czas wczytywania strony w twojej witrynie i oczywiście zmniejszy pobieranie pliku dla użytkownika.

    *Jak:*
    > ⁃ Skorzystaj z sugerowanych poniżej narzędzi, aby automatycznie zminimalizować pliki przed kompilacją lub wdrożeniem lub w jej trakcie.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **Brak JavaScript w środku:** ![medium] *(Dotyczy tylko witryny internetowej)* Unikaj osadzania wielu kodów JavaScript w środku ciała (body). Zgrupuj kod JavaScript w plikach zewnętrznych lub ewentualnie w `<head>` lub na końcu strony (przed `</body>`).

    *Czemu:*
    > Umieszczanie kodu JavaScript osadzonego bezpośrednio w twoim `<body>` może spowolnić twoją stronę, ponieważ ładuje się podczas budowania DOM. Najlepszą opcją jest użycie plików zewnętrznych z `async` lub `defer` aby uniknąć blokowania DOM. Inną opcją jest umieszczenie niektórych skryptów w twoim `<head>`. Przez większość czasu kod analityczny lub mały skrypt, który należy załadować, zanim DOM przejdzie do głównego przetwarzania.

    *Jak:*
    > Upewnij się, że wszystkie twoje pliki są ładowane przy użyciu `async` lub `defer` i mądrze zdecyduj, jaki kod będziesz musiał wprowadzić w `<head>`.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Nieblokujący JavaScript:** ![high] Pliki JavaScript są ładowane asynchronicznie za pomocą `async` lub odroczone za pomocą atrybutu `defer`.

    ```html
    <!-- Atrybut Defer -->
    <script defer src="foo.js"></script>

    <!-- Atrybut Async  -->
    <script async src="foo.js"></script>
    ```

    *Czemu:*
    > JavaScript blokuje normalne parsowanie dokumentu HTML, więc gdy parser osiągnie znacznik `<script>` (szczególnie znajduje się w `<head>`), przestaje go pobierać i uruchamiać. Dodanie `async` lub `defer` jest wysoce zalecane, jeśli twoje skrypty są umieszczone na górze strony, ale mniej wartościowe, jeśli są tuż przed tagiem `</body>`. Ale dobrą praktyką jest zawsze używanie tych atrybutów, aby uniknąć problemów z wydajnością.

    *Jak:*
    > ⁃ Dodaj `async` (jeśli skrypt nie opiera się na innych skryptach) lub `defer` (jeśli skrypt opiera się na skrypcie asynchronicznym lub na nim polegał) jako atrybut tagu skryptu. <br>
    ⁃ Jeśli masz małe skrypty, możesz użyć wbudowanego skryptu zamiast skryptów asynchronicznych.

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Defer loading JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Zoptymalizowane i zaktualizowane biblioteki JS:** ![medium] Wszystkie biblioteki JavaScript używane w twoim projekcie są konieczne (preferowana Vanilla JavaScript dla prostych funkcjonalności), zaktualizowane do najnowszej wersji i nie przytłaczają JavaScript niepotrzebnymi metodami.

    *Czemu:*
    > W większości przypadków nowe wersje są dostarczane z optymalizacją i poprawką bezpieczeństwa. Powinieneś użyć najbardziej zoptymalizowanego kodu, aby przyspieszyć swój projekt i upewnić się, że nie spowolnisz swojej witryny lub aplikacji bez przestarzałej wtyczki.

    *Jak:*
    > Jeśli twój projekt używa pakietów NPM, [npm-check](https://www.npmjs.com/package/npm-check) jest całkiem interesującą biblioteką do upgrade'u / aktualizacji bibliotek.
    > [Greenkeeper](https://greenkeeper.io/) może automatycznie szukać zależności i sugerować aktualizację za każdym razem, gdy wychodzi nowa wersja.

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **Sprawdź limit wielkości zależności:** ![low] Upewnij się, że korzystasz mądrze z zewnętrznych bibliotek, przez większość czasu możesz używać lżejszej biblioteki dla tej samej funkcjonalności.

    *Czemu:*
    > Możesz mieć ochotę skorzystać z jednego z 745 000 pakietów, które możesz znaleźć z [npm](https://www.npmjs.com/), ale musisz wybrać najlepszy pakiet dla swoich potrzeb. Na przykład MomentJS jest niesamowitą biblioteką, ale z wieloma metodami, których nigdy możesz nie użyć, właśnie dlatego utworzono Day.js. To tylko 2kB vs 16,4kB gz dla Moment.

    *Jak:*
    > Zawsze porównuj i wybieraj najlepszą i lżejszą bibliotekę dla swoich potrzeb. Możesz także użyć narzędzi takich jak [npm trends](http://www.npmtrends.com/) aby porównać liczbę pobrań pakietów NPM lub [Bundlephobia](https://bundlephobia.com/) aby poznać rozmiar swoich zależności.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 🛠 [js-dependency-viewer - npm](https://www.npmjs.com/package/js-dependency-viewer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript Profiling:** ![medium] Sprawdź problemy z wydajnością w swoich plikach JavaScript (i CSS).

    *Czemu:*
    > Złożoność JavaScript może spowolnić działanie środowiska wykonawczego. Zidentyfikowanie tych możliwych problemów jest niezbędne, aby zapewnić jak najbardziej płynną obsługę.

    *Jak:*
    > Użyj narzędzia Timeline Tool w Chrome Developer Tool, aby ocenić zdarzenia związane ze skryptami i znaleźć takie, które mogą zająć zbyt dużo czasu.

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 Tips To Improve Javascript Performance](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Zastosowanie Service Workers:** ![medium] Korzystasz z Service Workers w swoim PWA do buforowania danych lub wykonywania możliwych ciężkich zadań bez wpływu na komfort użytkowania aplikacji.
   
    * 📖 [Service Workers: an Introduction  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Measuring the Real-world Performance Impact of Service Workers  |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [What Are Service Workers and How They Help Improve Performance](https://www.keycdn.com/blog/service-workers/)
    * 📹 [How does a service worker work? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ powrót do góry](#spis-treści)**

## Serwer

![server-side]

- [ ] **Twoja strona korzysta z HTTPS:** ![high]

    *Czemu:*
    > HTTPS jest przeznaczony nie tylko dla witryn e-commerce, ale dla wszystkich witryn, które wymieniają dane. Dane udostępniane przez użytkownika lub dane udostępniane podmiotowi zewnętrznemu. Współczesne przeglądarki ograniczają funkcjonalność witryn, które nie są bezpieczne. Na przykład: geolokalizacja, powiadomienia wypychane i pracownicy usług nie działają, jeśli Twoja instancja nie używa HTTPS. A dzisiaj łatwiej jest skonfigurować projekt z certyfikatem SSL niż wcześniej (i za darmo dzięki [Let's Encrypt](https://letsencrypt.org/)).

 * 📖 [Why Use HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Enabling HTTPS Without Sacrificing Your Web Performance - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [How HTTPS Affects Website Performance](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP versus HTTPS versus HTTP2 - The real story | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Test them both yourself](https://www.httpvshttps.com/)

- [ ] **Waga strony < 1500 KB (idealnie < 500 KB):** ![high] Zmniejsz rozmiar strony + zasoby tak bardzo, jak to możliwe.

    *Czemu:*
    > Najlepiej jest spróbować kierować reklamy na <500 KB, ale stan sieci pokazuje, że mediana kilobajtów wynosi około 1500 KB (nawet na urządzeniach mobilnych). W zależności od docelowych użytkowników, połączenia sieciowego i urządzeń ważne jest, aby maksymalnie zmniejszyć całkowitą liczbę kilobajtów, aby zapewnić jak najlepszą obsługę.

    *Jak:*
    > ⁃ Wszystkie zasady znajdujące się na liście kontrolnej wydajności frontendu pomogą ci maksymalnie ograniczyć zasoby i kod.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Czasy ładowania strony < 3 sekund:** ![high] Skróć maksymalnie czas ładowania strony, aby szybko dostarczać treści użytkownikom

    *Czemu:*
    > Im szybsza jest twoja strona internetowa lub aplikacja, tym mniejsze prawdopodobieństwo wzrostu odrzuceń, innymi słowy masz mniejsze szanse na utratę użytkownika lub przyszłego klienta. Dowodem na to są wystarczające badania na ten temat.

    *Jak:*
    > Użyj narzędzi online, takich jak [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) lub [WebPageTest](https://www.webpagetest.org/) aby przeanalizować, co może cię spowalniać, i skorzystaj z Listy kontrolnej wydajności frontendu, aby skrócić czas ładowania.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Time To First Byte < 1.3 sekund:** ![high] Skróć maksymalnie, ile możesz, czas oczekiwania przeglądarki przed otrzymaniem danych.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 📖 [Time to First Byte (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **Rozmiar cookie:** ![medium] Jeśli używasz plików cookie, upewnij się, że każdy plik cookie nie przekracza 4096 bajtów, a nazwa domeny nie zawiera więcej, niż 20 plików cookie.

    *Czemu:*
    > Pliki cookie są wymieniane w nagłówkach HTTP między serwerami internetowymi, a przeglądarkami. Ważne jest, aby rozmiar plików cookie był jak najniższy, aby zminimalizować wpływ na czas reakcji użytkownika.

    *Jak:*
    > Wyeliminuj niepotrzebne pliki cookie.

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Minimalizowanie żądań HTTP:** ![high] Zawsze upewnij się, że każdy zażądany plik jest niezbędny dla twojej witryny lub aplikacji.
 * 📖 [Combine external CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Combine external JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Użyj CDN, aby dostarczyć swoje assety:** ![medium] Skorzystaj z CDN, aby szybciej dostarczać treści na cały świat.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Serwuj pliki z tego samego protokołu:** ![high] Unikaj wyświetlania w witrynie plików pochodzących ze źródła za pomocą protokołu HTTP w witrynie, która używa na przykład HTTPS. Jeśli witryna korzysta z HTTPS, pliki zewnętrzne powinny pochodzić z tego samego protokołu.

- [ ] **Podaj pliki osiągalne:** ![high] Unikaj żądania plików nieosiągalnych (404).
 * 📖 [How to avoid bad requests](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **Ustaw poprawnie nagłówki pamięci podręcznej HTTP:** ![high] Ustaw nagłówki HTTP, aby uniknąć kosztownej liczby zwrotów między przeglądarką, a serwerem.
 * 📖 [Using cache-control for browser caching](https://varvy.com/pagespeed/cache-control.html)

- [ ] **Kompresja GZIP / Brotli jest włączona:** ![high] Użyj metody kompresji, takiej jak Gzip lub Brotli, aby zmniejszyć rozmiar plików JavaScript. Dzięki plikowi o mniejszych rozmiarach użytkownicy będą mogli szybciej pobierać zasób, co poprawi wydajność.

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ powrót do góry](#spis-treści)**

---
## Wydajność i frameworki JS

### Angular
 * 📖 [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)

### React

 * 📖 [Optimizing Performance - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [React image manipulation | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Debugging React performance with React 16 and Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)
  * 📖 [Build Performant - React](https://web.dev/react/)

### Vue
 * 📖 [Vue - Useful Links|Style Guide and Performance](https://learn-vuejs.github.io/vue-patterns/useful-links/)

## Wydajność oraz CMS

### WordPress

* 🛠 [Test Your Website Speed | WordPress Hosting by @WPEngine](https://wpengine.com/speed-tool/)

#### Artykuły

 * 📖 [19 Tips to Speed Up WordPress Performance (Updated)](https://www.wpbeginner.com/wordpress-performance-speed/)
 * 📖 [Speed Up Your WordPress - How to Save Images Optimized for Web](https://www.wpbeginner.com/beginners-guide/speed-wordpress-save-images-optimized-web/)

#### Zalecane wtyczki

* 🛠 [Caching Plugin for WordPress - Speed up your website with WP Rocket](https://wp-rocket.me/)
* 🛠 [WP-Sweep | WordPress.org](https://wordpress.org/plugins/wp-sweep/)
* 🛠 [Imagify Image Optimizer | WordPress.org](https://wordpress.org/plugins/imagify/)

---

## Tłumaczenia

Checklista wydajności frontend chce być dostępna również w innych językach! Nie wahaj się przesłać swojego wkładu!

* 🇵🇹 portugalski: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 chiński: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)
* 🇷🇺 rosyjski: [lex111/Front-End-Performance-Checklist](https://github.com/lex111/Front-End-Performance-Checklist)
* 🇫🇷 francuski: [WilliamDASILVA/Front-End-Performance-Checklist](https://github.com/WilliamDASILVA/Front-End-Performance-Checklist)
* 🇰🇷 koreański: [ParkSB/Front-End-Performance-Checklist](https://github.com/ParkSB/Front-End-Performance-Checklist)
* 🇪🇸 hiszpański: [dagerzuga/Front-End-Performance-Checklist](https://github.com/dagerzuga/Front-End-Performance-Checklist)
* 🇻🇮 wietnamski: [huynhan147/Front-End-Performance-Checklist](https://github.com/huynhan147/FrontEnd-Performance-Checklist)

## Współtworzenie

**Otwórz issue lub stwórz pull request, aby zasugerować zmiany lub uzupełnienia.**

## Wsparcie

Jeśli masz jakieś pytania lub sugestie, nie wahaj się skorzystać z Discord lub Twittera:

* [Chat na Discord](https://discord.gg/btHQRkm)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Autor

**Stworzone** z ❤️ od [David Dias](https://github.com/thedaviddias)

## Współtwórcy

Ten projekt istnieje dzięki wszystkim ludziom, którzy wnoszą swój wkład. [[Współtworzenie]](.github/CONTRIBUTING.md).
<a href="https://github.com/thedaviddias/Front-End-Performance-Checklist/graphs/contributors">
    <img src="https://opencollective.com/front-end-checklist/contributors.svg?width=890" />
</a>


## Backers

Podziękowania dla wszystkich naszych backers! 🙏 [[Zostań backer](https://opencollective.com/front-end-checklist#backer)]

<a href="https://opencollective.com/front-end-checklist#backers" target="_blank"><img src="https://opencollective.com/front-end-checklist/backers.svg?width=890"></a>


## Sponsorzy

Wesprzyj ten projekt, zostając sponsorem. Twoje logo pojawi się tutaj wraz z linkiem do Twojej witryny. [[Zostań sponsorem](https://opencollective.com/front-end-checklist#sponsor)]

<a href="https://opencollective.com/front-end-checklist/sponsor/0/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/1/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/2/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/3/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/4/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/5/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/6/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/7/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/8/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/9/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/9/avatar.svg"></a>

## Licencja

[MIT](LICENSE)

Wszystkie ikony są dostarczane przez [Icons8](https://icons8.com/)

**[⬆ powrót do góry](#spis-treści)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: images/priority/low.svg
[medium]: images/priority/medium.svg
[high]: images/priority/high.svg
