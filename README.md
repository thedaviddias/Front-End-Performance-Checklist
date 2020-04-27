<h1 align="center">
<br>
  <a href="https://github.com/thedaviddias/Front-End-Performance-Checklist"><img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170"></a>
  <br>
    <br>
  Checklista wyjdajności Frontendu
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
3. **[Fonts](#fonts)**
4. **[Images](#images)**
5. **[JavaScript](#javascript)**
6. **[Server](#server) (w trakcie)**
7. **[JS Frameworks](#wydajności-i-frameworki-js) (w trakcie)**

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
     * 📖 [Reduce the size of the above-the-fold content
](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

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
    * 🛠 [Project Wallace](https://www.projectwallace.com/) is like CSS Stats but stores stats over time so you can track your changes

**[⬆ powrót do góry](#spis-treści)**

## Fonts

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **Webfont formats:** ![medium] You are using WOFF2 on your web project or application.

    *Czemu:*
    > According to Google, the WOFF 2.0 Web Font compression format offers 30% average gain over WOFF 1.0. It's then good to use WOFF 2.0, WOFF 1.0 as a fallback and TTF.

    *Jak:*
    > Check before buying your new font that the provider gives you the WOFF2 format. If you are using a free font, you can always use Font Squirrel to generate all the formats you need.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Use `preconnect` to load your fonts faster:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Czemu:*
    > When you arrived on a website, your device needs to find out where your site lives and which server it needs to connect with. Your browser had to contact a DNS server and wait for the lookup complete before fetching the resource (fonts, CSS files...). Prefetches and preconnects allow the browser to lookup the DNS information and start establishing a TCP connection to the server hosting the font file. This provides a performance boost because by the time the browser gets around to parsing the css file with the font information and discovering it needs to request a font file from the server, it will already have pre-resolved the DNS information and have an open connection to the server ready in its connection pool.

    *Jak:*
    > ⁃ Before prefetching your webfonts, use webpagetest to evaluate your website <br>
    ⁃ Look for teal colored DNS lookups and note the host that are being requested <br>
    ⁃ Prefetch your webfonts in your `<head>` and add eventually these hostnames that you should prefetch too

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader gives you added control when using linked fonts via @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Webfont size:** ![medium] Webfont sizes don't exceed 300kb (all variants included)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Prevent Flash or Invisible Text:** ![medium] Avoid transparent text until the Webfont is loaded

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ powrót do góry](#spis-treści)**

## Images

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Images optimization:** ![high] Your images are optimized, compressed without direct impact to the end user.

    *Why:*
    > Optimized images load faster in your browser and consume less data.

    *Jak:*
    > ⁃ Try using CSS3 effects when it's possible (instead of a small image) <br>
    ⁃ When it's possible, use fonts instead of text encoded in your images <br>
    ⁃ Use SVG <br>
    ⁃ Use a tool and specify a level compression under 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Essential Image Optimization - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)
    * 🛠 [ImageEngine - Image Webpage Loading Test](https://demo.imgeng.in)
    * 🛠 [SVGOMG - Optimize SVG vector graphics files](https://jakearchibald.github.io/svgomg/)


* [ ] **Images format:** ![high] Choose your image format appropriately.

    *Czemu:*
    > To ensure that your images don't slow your website, choose the format that will correspond to your image. If it's a photo, JPEG is most of the time more appropriate than PNG or GIF. But don't forget to look a the nex-gen formats which can reduce the size of your files. Each image format has pros and cons, it's important to know these to make the best choice possible.

    *Jak:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) to identify which images can eventually use **next-gen formats** (like JPEG 2000m JPEG XR or WebP) <br>
    ⁃ Compare different formats, sometimes using PNG8 is better than PNG16, sometimes it's not.

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Use vector image vs raster/bitmap:** ![medium] Prefer using vector image rather than bitmap images (when possible).

    *Czemu:*
    > Vector images (SVG) tend to be smaller than images and SVG's are responsive and scale perfectly. These images can be animated and modified by CSS.

* [ ] **Images dimensions:** ![medium] Set `width` and `height` attributes on `<img>` if the final rendered image size is known.

    *Czemu:*
    > If height and width are set, the space required for the image is reserved when the page is loaded. However, without these attributes, the browser does not know the size of the image, and cannot reserve the appropriate space to it. The effect will be that the page layout will change during loading (while the images load).

* [ ] **Avoid using Base64 images:** ![medium] You could eventually convert tiny images to base64 but it's actually not the best practice.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading:** ![medium] Offscreen images are loaded lazily (A noscript fallback is always provided).

    *Czemu:*
    > It will improve the response time of the current page and then avoid loading unnecessary images that the user may not need.

    *Jak:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) to identify how many **images are offscreen**. <br>
    ⁃ Use a JavaScript plugin like the following to lazyload your images. Make sure you target offscreen images only. <br>
    ⁃ Also make sure to lazyload alternative images shown at mouseover or upon other user actions.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Responsive images:** ![medium] Ensure to serve images that are close to your display size.

    *Czemu:*
    > Small devices don't need images bigger than their viewport. It's recommended to have multiple versions of one image on different sizes.

    *Jak:*
    > ⁃ Create different image sizes for the devices you want to target. <br>
    ⁃ Use `srcset` and `picture` to deliver multiple variants of each image.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ powrót do góry](#spis-treści)**

## JavaScript

![javascript]

- [ ] **JS Minification:** ![high] All JavaScript files are minified, comments, white spaces and new lines are removed from production files *(still valid if using HTTP/2)*.

    *Czemu:*
    > Removing all unnecessary spaces, comments and break will reduce the size of your JavaScript files and speed up your site's page load times and obviously lighten the download for your user.

    *Jak:*
    > ⁃ Use the tools suggested below to minify your files automatically before or during your build or your deployment.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **No JavaScript inside:** ![medium] *(Only valid for website)* Avoid having multiple JavaScript codes embedded in the middle of your body. Regroup your JavaScript code inside external files or eventually in the `<head>` or at the end of your page (before `</body>`).

    *Czemu:*
    > Placing JavaScript embedded code directly in your `<body>` can slow down your page because it loads while the DOM is being built. The best option is to use external files with `async` or `defer` to avoid blocking the DOM. Another option is to place some scripts inside your `<head>`. Most of the time analytics code or small script that need to load before the DOM gets to main processing.

    *Jak:*
    > Ensure that all your files are loaded using `async` or `defer` and decide wisely the code that you will need to inject in your `<head>`.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Non-blocking JavaScript:** ![high] JavaScript files are loaded asynchronously using `async` or deferred using `defer` attribute.

    ```html
    <!-- Defer Attribute -->
    <script defer src="foo.js"></script>

    <!-- Async Attribute -->
    <script async src="foo.js"></script>
    ```

    *Czemu:*
    > JavaScript blocks the normal parsing of the HTML document, so when the parser reaches a `<script>` tag (particularly is inside the `<head>`), it stops to fetch and run it. Adding `async` or `defer` are highly recommended if your scripts are placed in the top of your page but less valuable if just before your `</body>` tag. But it's a good practice to always use these attributes to avoid any performance issue.

    *Jak:*
    > ⁃ Add `async` (if the script don't rely on other scripts) or `defer` (if the script relies upon or relied upon by an async script) as an attribute to your script tag. <br>
    ⁃ If you have small scripts, maybe use inline script place above async scripts.

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Defer loading JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Optimized and updated JS libraries:** ![medium] All JavaScript libraries used in your project are necessary (prefer Vanilla JavaScript for simple functionalities), updated to their latest version and don't overwhelm your JavaScript with unnecessary methods.

    *Czemu:*
    > Most of the time, new versions come with optimization and security fix. You should use the most optimized code to speed up your project and ensure that you'll not slow down your website or app without outdated plugin.

    *Jak:*
    > If your project use NPM packages, [npm-check](https://www.npmjs.com/package/npm-check) is a pretty interesting library to upgrade / update your libraries.
    > [Greenkeeper](https://greenkeeper.io/) can automatically look for your dependencies and suggest an update every time a new version is out.

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **Check dependencies size limit:** ![low] Ensure to use wisely external libraries, most of the time, you can use a lighter library for a same functionality.

    *Czemu:*
    > You may be tempted to use one of the 745 000 packages you can find on [npm](https://www.npmjs.com/), but you need to choose the best package for your needs. For example, MomentJS is an awesome library but with a lot of methods you may never use, that's why Day.js was created. It's just 2kB vs 16.4kB gz for Moment.

    *Jak:*
    > Always compare and choose the best and lighter library for your needs. You can also use tools like [npm trends](http://www.npmtrends.com/) to compare NPM package downloads counts or [Bundlephobia](https://bundlephobia.com/) to know the size of your dependencies.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 🛠 [js-dependency-viewer - npm](https://www.npmjs.com/package/js-dependency-viewer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript Profiling:** ![medium] Check for performance problems in your JavaScript files (and CSS too).

    *Czemu:*
    > JavaScript complexity can slow down runtime performance. Identifying these possible issues are essential to offer the smoothest user experience.

    *Jak:*
    > Use the Timeline tool in the Chrome Developer Tool to evaluate scripts events and found the one that may take too much time.

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 Tips To Improve Javascript Performance](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Use of Service Workers:** ![medium] You are using Service Workers in your PWA to cache data or execute possible heavy tasks without impacting the user experience of your application.
   
    * 📖 [Service Workers: an Introduction  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Measuring the Real-world Performance Impact of Service Workers  |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [What Are Service Workers and How They Help Improve Performance](https://www.keycdn.com/blog/service-workers/)
    * 📹 [How does a service worker work? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ powrót do góry](#spis-treści)**

## Server

![server-side]

- [ ] **Your website is using HTTPS:** ![high]

    *Czemu:*
    > HTTPS is not only for ecommerce websites, but for all websites that are exchanging data. Data shared by a user or data shared to an external entity. Modern browsers today limit functionalities for sites that are not secure. For example: geolocation, push notifications and service workers don't work if your instance is not using HTTPS. And today is much more easy to setup a project with an SSL certificate than it was before (and for free, thanks to [Let's Encrypt](https://letsencrypt.org/)).

 * 📖 [Why Use HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Enabling HTTPS Without Sacrificing Your Web Performance - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [How HTTPS Affects Website Performance](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP versus HTTPS versus HTTP2 - The real story | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Test them both yourself](https://www.httpvshttps.com/)

- [ ] **Page weight < 1500 KB (ideally < 500 KB):** ![high] Reduce the size of your page + resources as much as you can.

    *Czemu:*
    > Ideally you should try to target < 500 KB but the state of web shows that the median of Kilobytes is around 1500 KB (even on mobile). Depending on your target users, network connection, devices, it's important to reduce as much as possible your total Kilobytes to have the best user experience possible.

    *Jak:*
    > ⁃ All the rules inside the Front-End Performance Checklist will help you to reduce as much as possible your resources and your code.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Page load times < 3 seconds:** ![high] Reduce as much as possible your page load times to quickly deliver your content to your users.

    *Czemu:*
    > Faster your website or app is, less you have probability of bounce increases, in other terms you have less chances to lose your user or future client. Enough researches on the subject prove that point.

    *Jak:*
    > Use online tools like [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) or [WebPageTest](https://www.webpagetest.org/) to analyze what could be slowing you down and use the Front-End Performance Checklist to improve your load times.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Time To First Byte < 1.3 seconds:** ![high] Reduce as much as you can the time your browser waits before receiving data.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 📖 [Time to First Byte (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **Cookie size:** ![medium] If you are using cookies, be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.

    *Czemu:*
    > Cookies are exchanged in the HTTP headers between web servers and browsers. It's important to keep the size of cookies as low as possible to minimize the impact on the user's response time.

    *Jak:*
    > Eliminate unnecessary cookies.

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Minimizing HTTP requests:** ![high] Always ensure that every file requested are essential for your website or application.
 * 📖 [Combine external CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Combine external JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Use a CDN to deliver your assets:** ![medium] Use a CDN to deliver faster your content over the world.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Serve files from the same protocol:** ![high] Avoid having your website serving files coming from source using HTTP on your website which is using HTTPS for example. If your website is using HTTPS, external files should come from the same protocol.

- [ ] **Serve reachable files:** ![high] Avoid requesting unreachable files (404).
 * 📖 [How to avoid bad requests](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **Set HTTP cache headers properly:** ![high] Set HTTP headers to avoid expensive number of roundtrips between your browser and the server.
 * 📖 [Using cache-control for browser caching](https://varvy.com/pagespeed/cache-control.html)

- [ ] **GZIP / Brotli compression is enabled:** ![high] Use a compression method such as Gzip or Brotli to reduce the size of your JavaScript files. With a smaller sizes file, users will be able to download the asset faster, resulting in improved performance.

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

**Stworzone z ❤️ od [David Dias](https://github.com/thedaviddias)

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
