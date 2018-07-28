<h1 align="center">
<br>
  <img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170">
  <br>
    <br>
  Front-End Performance Checklist
  <br>
</h1>

<h4 align="center">🎮 The only Front-End Performance Checklist that runs faster than the others.</h4>
<p align="center">One simple rule: "Design and code with performance in mind"</p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://gitter.im/Front-End-Checklist/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link">
    <img src="https://img.shields.io/badge/chat-on_gitter-008080.svg?style=flat-square" alt="Gitter">
  </a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="Licence MIT">
  </a>
</p>

<p align="center">
  <a href="#how-to-use">How To Use</a> • <a href="#contributing">Contributing</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Product Hunt</a>
</p>
<p align="center">
    <span>Other Checklists:</span>
    <br>
  🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Front-End Checklist</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Front-End Design Checklist</a>
</p>

## Table of Contents

1. **[HTML](#html)**
2. **[CSS](#css)**
3. **[Fonts](#fonts)**
4. **[Images](#images)**
5. **[JavaScript](#javascript)**
6. **[Server](#server) (in progress)**
7. **[JS Frameworks](#js-frameworks) (in progress)**

## Introduction

Performance is a huge subject, but it's not always a "back-end" or an "admin" subject: it's a Front-End responsibility too. The Front-End Performance Checklist is an exhaustive list of elements you should check or at least be aware of, as a Front-End developer and apply to your project (personal and professional).

### How to use?

For each rule, you will have a paragraph explaining *why* this rule is important and *how* you can fix it. For more deep information, you should find links that will point to 🛠 tools, 📖 articles or 📹 medias that can complete the checklist.

All items in the **Front-End Performance Checklist** are essentials to achieve the highest performance score but you would find an indicator to help you to eventually prioritised some rules amount others. There are 3 levels of priority:

* ![Low][low] means that the item has a **low** priority.
* ![Medium][medium] means that the item has a **medium** priority. You shouldn't avoid tackling that item.
* ![High][high] means that the item has a **high** priority. You can't avoid following that rule and implement the corrections recommended.

### Performance tools

List of the tools you can use to test or monitor your website or application:
 
 * 🛠 [WebPagetest - Website Performance and Optimization Test](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Website Speed Test and Website Analysis](https://www.dareboost.com/) (use the coupon WPCDD20 for -20%)
 * 🛠 [GTmetrix | Website Speed and Performance Optimization](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Pingdom Website Speed Test](https://tools.pingdom.com)
 * 📖 [Pagespeed - The tool and optimization guide](https://varvy.com/pagespeed/)
 * 📖 [Make the Web Faster | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Welcome to the wonderful world of Web Performance](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Check Web Performance &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Website and Server Uptime Monitoring - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Monitor front-end performance](https://speedcurve.com)
 * 🛠 [PWMetrics - CLI tool and lib to gather performance metrics](https://github.com/paulirish/pwmetrics)
 
### References

 * 📹 [The Cost Of JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4)
 * 📖 [Get Started With Analyzing Runtime Performance  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [State of the Web | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Page Weight Doesn't Matter](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
---

## HTML

![html]

- [ ] **Minified HTML:** ![medium] The HTML code is minified, comments, white spaces and new lines are removed from production files.

    *Why:*
    > Removing all unnecessary spaces, comments and break will reduce the size of your HTML and speed up your site's page load times and obviously lighten the download for your user.

    *How:*
    > ⁃ Most of the frameworks have plugins to facilitate the minification of the webpages. You can use a bunch of NPM modules that can do the job for you automatically.

    * 🛠 [HTML minifier | Minify Code](http://minifycode.com/html-minifier/)
    * 🛠 [Online HTML Compressor](http://refresh-sf.com)
    * 📖 [Experimenting with HTML minifier — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)

- [ ] **Remove unnecessary comments:** ![low] Ensure that comments are removed from your pages.

    *Why:*
    > Comments are not really useful for the user then should be removed from production files. One case where you want to keep comments could be if you need to keep the origin for a library.

    *How:*
    > ⁃ Most of the time, comments can be removed using an HTML minify plugin.

 * 🛠 [remove-html-comments - npm](https://www.npmjs.com/package/remove-html-comments)

- [ ] **Remove unnecessary attributes:** ![low] Type attributes like `type="text/javascript"` or `type="text/css"` anymore and should be removed.

    ```html
    <!-- Before HTML5 -->
    <script type="text/javascript">
        // Javascript code
    </script>

    <!-- Today -->
    <script>
        // Javascript code
    </script>
    ```

    *Why:*
    > Type attributes are not necessary as HTML5 implies text/css and text/javascript as defaults. Unused code should be removed when not used by your website or app as they add more weight to your pages.

    *How:*
    > ⁃ Ensure that all your `<link>` and `<script>` tags don't have any type attribute.

    * 📖 [The Script Tag | CSS-Tricks](https://css-tricks.com/the-script-tag/)
   
- [ ] **Place CSS tags always before JavaScript tags:** ![high] Ensure that your CSS is always loaded before having JavaScript code.

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

    *Why:*
    > Having your CSS tags before any JavaScript enables better, parallel download which speed up browser rendering time.

    *How:*
    > ⁃ Ensure that `<link>`  and `<style>` in your `<head>` are always before your `<script>`.

    * 📖 [Ordering your styles and scripts for pagespeed](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **Minimize the number of iframes:** ![high] Use iframes only if you don't have any other technical possibility. Try to avoid as much as you can iframes.

**[⬆ back to top](#table-of-contents)**

## CSS

![css]

- [ ] **Minification:** ![high] All CSS files are minified, comments, white spaces and new lines are removed from production files.

    *Why:*
    > When CSS files are minified, the content is loaded faster and less data is sent to the client. It's important to always minify CSS files in production. It is beneficial for the user as it is for any business who wants to lower bandwidth costs and lower resource usage.

    *How:*
    > ⁃ Use tools to minify your files automatically before or during your build or your deployment.

    * 🛠 [cssnano: A modular minifier based on the PostCSS ecosystem. - cssnano](https://cssnano.co/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)


- [ ] **Concatenation:** ![medium] CSS files are concatenated in a single file *(Not always valid for HTTP/2)*.

    ```html

    <!-- Not recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Recommended -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *Why:*
    > If you are still using HTTP/1, you may need to still concatenate your files, it's less true if your server use HTTP/2 (tests should be made).

    *How:*
    > ⁃ Use online tool or any plugin before or during your build or your deployment to concatenate your files.
    ⁃ Ensure, of course, that concatenation does not break your project.

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **Non-blocking:** ![high] CSS files need to be non-blocking to prevent the DOM from taking time to load.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *Why:*
    > CSS files can block the page load and delay the rendering of your page. Using `preload` can actually load the CSS files before the browser starts showing the content of the page.

    *How:*
    > ⁃ You need to add the `rel` attribute with the `preload` value and add `as="style"` on the `<link>` element.

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Example of preload CSS using loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Preloading content with rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: What Is It Good For? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **Length of CSS classes:** ![low] The length of your classes can have an (slight) impact on your HTML and CSS files (eventually).

    *Why:*
    > Even performance impacts can be disputable, taking a decision on a naming strategy regarding your project can have a substantial impact on the maintainability of your stylesheets. If you are using BEM, in some cases, you can end up with classes having more characters than needed. It's always important to choose wisely your names and namespaces.

    *How:*
    > ⁃ Setting a limit in terms of number of characters could be interesting for some people, but ensuring that you broke down your website in components can help to reduce the amount of classes (and declarations) and the length of your classes.

    * 🛠 [long vs short class · jsPerf](https://jsperf.com/long-vs-short-class)

- [ ] **Unused CSS:** ![medium] Remove unused CSS selectors.

    *Why:*
    > Removing unused CSS selectors can reduce the size of your files and then speed up the load of your assets.

    *How:*
    > ⁃ ⚠️ Always check if the framework CSS you want to use don't already has a reset / normalize code included. Sometimes you may not need everything that is inside your reset / normalize file.

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS Critical:** ![high] The CSS critical (or "above the fold") collects all the CSS used to render the visible portion of the page. It is embedded before your principal CSS call and between `<style></style>` in a single line (minified if possible).

    *Why:*
    > Inlining critical CSS help to speed up the rendering of the web pages reducing the number of requests to the server.

    *How:*
    > ⁃ Generate the CSS critical with online tools or using a plugin like the one that Addy Osmani developed.

    * 📖 [Understanding Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inlining critical CSS for better web performance | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
     * 🛠 [Critical Path CSS Generator - Prioritize above the fold content :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)

- [ ] **Embedded or inline CSS:** ![high] Avoid using embed or inline CSS inside your `<body>` *(Not valid for HTTP/2)*

    *Why:*
    > One of the first reason it's because it's a good practice to **separate content from design**. It also helps you have a more maintainable code and keep your site accessible. But regarding performance, it's simply because it decreases the file-size of your HTML pages and the load time.

    *How:*
    > ⁃ Always use external stylesheets or embed CSS in your `<head>` (and follow the others CSS performance rules)

    * 📖 [Observe CSS Best Practices: Avoid CSS Inline Styles](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Analyse stylesheets complexity:** ![high] Analyzing your stylesheets can help you to flag issues, redundancies and duplicate CSS selectors.

    *Why:*
    > Sometimes you may have redundancies or validation errors in your CSS, analysing your CSS files and removed these complexities can help you to speed up your CSS files (because your browser will read them faster)

    *How:*
    > ⁃ Your CSS should be organized, using a CSS preprocessor can help you with that. Some online tools listed above can also help you analysing and correct your code.

    * 🛠 [TestMyCSS | Optimize and Check CSS Performance](http://www.testmycss.com/)
    * 📖 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: CSS selectors complexity and performance analyzer](https://github.com/macbre/analyze-css)

**[⬆ back to top](#table-of-contents)**

## Fonts

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **Webfont formats:** ![medium] You are using WOFF2 on your web project or application.

    *Why:*
    > According to Google, the WOFF 2.0 Web Font compression format offers 30% average gain over WOFF 1.0. It's then good to use WOFF 2.0, WOFF 1.0 as a fallback and TTF.

    *How:*
    > ⁃ Check before buying your new font that the provider gives you the WOFF2 format. If you are using a free font, you can always use Font Squirrel to generate all the formats you need.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Use `preconnect` to load your fonts faster:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Why:*
    > When you arrived on a website, your device needs to find out where your site lives and which server it needs to connect with. Your browser had to contact a DNS server and wait for the lookup complete before fetching the resource (fonts, CSS files...). Prefetches and preconnects allow the browser

    *How:*
    > ⁃ Before prefetching your webfonts, use webpagetest to evaluate your website.
    ⁃ Look for teal colored DNS lookups and note the host that are being requested.
    ⁃ Prefetch your webfonts in your `<head>` and add eventually these hostnames that you should prefetch too.

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)

- [ ] **Webfont size:** ![medium] Webfont sizes don't exceed 300kb (all variants included)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)
 
- [ ] **Prevent Flash of Invisible Text:** ![medium] Avoid transparent text until the Webfont is loaded

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ back to top](#table-of-contents)**

## Images

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Images optimization:** ![high] Your images are optimized, compressed without direct impact to the end user.

    *Why:*
    > Optimized images load faster in your browser and consume less data.

    *How:*
    > ⁃ Try using CSS3 effects when it's possible (instead of a small image)
    ⁃ When it's possible, use fonts instead of text encoded in your images
    ⁃ Use SVG
    ⁃ Use a tool and specify a level compression under 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)


* [ ] **Images format:** ![high] Choose your image format appropriately.

    *Why:*
    > To ensure that your images don't slow your website, choose the format that will

    *How:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) to identify which images can eventually use **next-gen formats** (like JPEG 2000m JPEG XR or WebP)
    ⁃ Compare different formats, sometimes using PNG8 is better than PNG16, sometimes it's not.

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
     * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
     * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Use vector image vs raster/bitmap:** ![medium] Prefer using vector image rather than bitmap images (when possible).

    *Why:*
    > Vector images (SVG) tend to be smaller than images and SVG's are responsive and scale perfectly. These images can be animated and modified by CSS.

* [ ] **Images dimensions:** ![medium] Set `width` and `height` attributes on `<img>` if the final rendered image size is known.

    *Why:*
    > If height and width are set, the space required for the image is reserved when the page is loaded. However, without these attributes, the browser does not know the size of the image, and cannot reserve the appropriate space to it. The effect will be that the page layout will change during loading (while the images load).

* [ ] **Avoid using Base64 images:** ![medium] You could eventually convert tiny images to base64 but it's actually not the best practice.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading:** ![medium] Images are lazyloaded (A noscript fallback is always provided).

    *Why:*
    > It will improve the response time of the current page and then avoid loading unnecessary images that the user may not need.

    *How:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) to identify how many **images are offscreen**.
    ⁃ Use a JavaScript plugin like to lazyload your images.

    * 🛠 [verlok/lazyload: Github](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: Github](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Responsive images:** ![medium] Ensure to serve images that are close to your display size.

    *Why:*
    > Small devices don't need images bigger than their viewport. It's recommended to have multiple versions of one image on different sizes.

    *How:*
    > ⁃ Create different image sizes for the devices you want to target.
    ⁃ Use `srcset` and `picture` to deliver multiple variants of each image.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ back to top](#table-of-contents)**

## JavaScript

![javascript]

- [ ] **JS Minification:** ![high] All JavaScript files are minified, comments, white spaces and new lines are removed from production files *(still valid if using HTTP/2)*.

    *Why:*
    > Removing all unnecessary spaces, comments and break will reduce the size of your JavaScript files and speed up your site's page load times and obviously lighten the download for your user.

    *How:*
    > ⁃ Use the tools suggested below to minify your files automatically before or during your build or your deployment.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **No JavaScript inside:** ![medium] *(Only valid for website)* Avoid having multiple JavaScript codes embedded in the middle of your body. Regroup your JavaScript code inside external files or eventually in the `<head>` or at the end of your page (before `</body>`).

    *Why:*
    > Placing JavaScript embedded code directly in your `<body>` can slow down your page because it loads while the DOM is being built. The best option is to use external files with `async` or `defer` to avoid blocking the DOM. Another option is to place some scripts inside your `<head>`. Most of the time analytics code or small script that need to load before the DOM gets to main processing.

    *How:*
    > ⁃ Ensure that all your files are loaded using `async` or `defer` and decide wisely the code that you will need to inject in your `<head>`.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **Non-blocking JavaScript:** ![high] JavaScript files are loaded asynchronously using `async` or deferred using `defer` attribute.

    ```html
    <!-- Defer Attribute -->
    <script defer src="foo.js">

    <!-- Async Attribute -->
    <script async src="foo.js">
    ```

    *Why:*
    > JavaScript blocks the normal parsing of the HTML document, so when the parser reaches a `<script>` tag (particularly is inside the `<head>`), it stops to fetch and run it. Adding `async` or `defer` are highly recommended if your scripts are placed in the top of your page but less valuable if just before your `</body>` tag. But it's a good practice to always use these attributes to avoid any performance issue.

    *How:*
    > ⁃ Add `async` (if the script don't rely on other scripts) or `defer` (if the script relies upon or relied upon by an async script) as an attribute to your script tag.
    ⁃ If you have small scripts, maybe use inline script place above async scripts.

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)

* [ ] **Optimized and updated JS libraries:** ![medium] All JavaScript libraries used in your project are necessary (prefer Vanilla Javascript for simple functionalities), updated to their latest version and don't overwhelm your JavaScript with unnecessary methods.

    *Why:*
    > Most of the time, new versions come with optimization and security fix. You should use the most optimized code to speed up your project and ensure that you'll not slow down your website or app without outdated plugin.

    *How:*
    > ⁃ If your project use NPM packages, [npm-check](https://www.npmjs.com/package/npm-check) is a pretty interesting library to upgrade / update your libraries.

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **Check dependencies size limit:** ![low] Ensure to use wisely external libraries, most of the time, you can use a lighter library for a same functionality.

    *Why:*
    > You may be tempted to use one of the 745 000 packages you can find on [npm](https://www.npmjs.com/), but you need to choose the best package for your needs. For example, MomentJS is an awesome library but with a lot of methods you may never use, that's why Day.js was created. It's just 2kB vs 16.4kB gz for Moment.

    *How:*
    > ⁃ Always compare and choose the best and lighter library for your needs. You can also use tools like [npm trends](http://www.npmtrends.com/) to compare NPM package downloads counts or [Bundlephobia](https://bundlephobia.com/) to know the size of your dependencies.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript Profiling:** ![medium] Check for performance problems in your JavaScript files (and CSS too).

    *Why:*
    > JavaScript complexity can slow down runtime performance. Identifying these possible issues are essential to offer the smoothest user experience.

    *How:*
    > ⁃ Use the Timeline tool in the Chrome Developer Tool to evaluate scripts events and found the one that may take too much time.

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)

**[⬆ back to top](#table-of-contents)**

## Server

![server-side]

- [ ] **Page weight < 1500 KB (ideally < 500 KB):** ![high] Reduce the size of your page + resources as much as you can.

    *Why:*
    > Ideally you should try to target < 500 KB but the state of web shows that the median of Kilobytes is around 1500 KB (even on mobile). Depending on your target users, connection, devices, it's important to reduce as much as possible your total Kilobytes to have the best user experience possible.

    *How:*
    > ⁃ All the rules inside the Front-End Performance Checklist will help you to reduce as much as possible your resources and your code.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Page load times < 3 seconds:** ![high] Reduce as much as possible your page load times to quickly deliver your content to your users.

    *Why:*
    > Faster your website or app is, less you have probability of bounce increases, in other terms you have less chances to lose your user or future client. Enough researches on the subject prove that point.
    
    *How:*
    >  ⁃ Use online tools like [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) or [WebPageTest](https://www.webpagetest.org/) to analyze what could be slowing you down and use the Front-End Performance Checklist to improve your load times.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Time To First Byte < 1.3 seconds:** ![high] Reduce as much as you can the time your browser waits before receiving data.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **Cookie size:** ![medium] If you are using cookies be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.

    *Why:*
    > cookies are exchanged in the HTTP headers between web servers and browsers. It's important to keep the size of cookies as low as possible to minimize the impact on the user's response time.

    *How:*
    > ⁃ Eliminate unnecessary cookies

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Minimizing HTTP requests:** ![high] Always ensure that every file requested are essential for your website or application.

- [ ] **Use a CDN to deliver your assets:** ![medium] Use a CDN to deliver faster your content over the world.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Serve files from the same protocol:** ![high] Avoid having your website using HTTPS and serve files coming from source using HTTP.

- [ ] **Serve reachable files:** ![high] Avoid requesting unreachable files (404).

- [ ] **Set HTTP cache headers properly:** ![high] Set HTTP headers to avoid expensive number of roundtrips between your browser and the server.

- [ ] **GZIP / Brotli compression is enabled:** ![high]

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ back to top](#table-of-contents)**

---
## Performances and JS Frameworks

### Vue

### React

 * 📖 [Optimizing Performance - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [React image manipulation | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Debugging React performance with React 16 and Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)

---

## Translations

The Front-End Performance Checklist wants to also be available in other languages! Don't hesitate to submit your contribution!

* 🇵🇹 Portuguese: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 Chinese: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)

## Contributing

**Open an issue or a pull request to suggest changes or additions.**

## Support

If you have any question or suggestion, don't hesitate to use Gitter or Twitter:

* [Chat on Gitter](https://gitter.im/Front-End-Checklist/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Author

**Build with ❤️ by [David Dias](https://github.com/thedaviddias) at [@influitive](https://influitive.com/) 🇨🇦**

## Contributors

This project exists thanks to all the people who contribute. [[Contribute]](.github/CONTRIBUTING.md).

## License

[MIT](LICENCE.md)

All icons are provided by [Icons8](https://icons8.com/)

**[⬆ back to top](#table-of-contents)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: https://front-end-checklist.now.sh/low.svg
[medium]: https://front-end-checklist.now.sh/medium.svg
[high]: https://front-end-checklist.now.sh/high.svg
