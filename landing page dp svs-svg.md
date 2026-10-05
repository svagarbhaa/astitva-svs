\<!DOCTYPE html\>

\<!--

  Astitva Series — Short Communications : Article Landing Page Template

  Version: 1.1.0  (2026-10-05)

  One file, no external dependencies. Bulk-generated across the corpus.


  DO NOT hand-edit series constants per page; edit the SERIES CONSTANTS block

  and regenerate. Missing tokens are left literal (\{\{TOKEN\}\}) so that CI can

  grep for them and fail the build.


  Build-time substitutions and escaping rules are documented in the generator

  contract accompanying this template. Read them before wiring the generator.

--\>

\<html lang="en"\>

\<head\>

\<meta charset="utf-8"\>

\<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover"\>

\<meta name="color-scheme" content="light dark"\>


\<!-- =====================================================================

     SERIES CONSTANTS (identical across all pages; update centrally)

     SERIES\_FULL=Astitva: Svādhyāya-Saṃhitā

     SERIES\_SHORT=Astitva Series — Short Communications

     PUBLISHER=Global Synergetic Foundation

     PUBLISHER\_SHORT=GSFN

     PUBLISHER\_LOCATION=New Delhi, India

     PUBLISHER\_URL=https://www.gsfn.org

     ORG\_ID=https://www.gsfn.org/\#organization

     ROR=https://ror.org/\[gsfn-ror\]

     ISNI\_ORG=\[0000 0000 0000 0000\]

     ISSN=2454-602X

     LICENSE=CC BY 4.0

     LICENSE\_URL=https://creativecommons.org/licenses/by/4.0/

     SERIES\_URL=https://www.gsfn.org/svadhyay-samhita.html

     SERIES\_NODE\_ID=https://www.gsfn.org/svadhyay-samhita.html\#series

     BASE\_URL=https://astitva.gsfn.org/svs/

     HUB\_URL=https://astitva.gsfn.org/

     ARCHIVE\_URL=https://astitva.gsfn.org/arch/

     OAI\_ENDPOINT=https://astitva.gsfn.org/oai

     FOUNDER\_URL=https://sati-shankar.gsfn.org/

     ===================================================================== --\>


\<title\>\{\{TITLE\}\} — \{\{SERIES\_SHORT\}\}\</title\>


\<meta name="description" content="\{\{ABSTRACT\}\}"\>

\<meta name="keywords" content="\{\{KEYWORDS\_CSV\}\}"\>

\<meta name="author" content="\{\{AUTHORS\_NAMES\_CSV\}\}"\>

\<meta name="robots" content="index, follow, max-image-preview:large, max-snippet:-1"\>

\<meta name="theme-color" content="\#fbfaf7" media="(prefers-color-scheme: light)"\>

\<meta name="theme-color" content="\#16150f" media="(prefers-color-scheme: dark)"\>

\<meta name="language" content="en"\>

\<meta name="geo.region" content="IN"\>


\<link rel="canonical" href="\{\{LANDING\_URL\}\}"\>

\<link rel="license" href="\{\{LICENSE\_URL\}\}"\>

\<link rel="icon" href="/favicon.ico" sizes="any"\>

\<link rel="icon" href="/favicon.svg" type="image/svg+xml"\>

\<link rel="apple-touch-icon" href="/apple-touch-icon.png"\>


\<!-- Machine-readable alternates: the digital handshake --\>

\<link rel="alternate" type="application/pdf"       href="\{\{PDF\_URL\}\}" title="PDF"\>

\<link rel="alternate" type="application/xml"       href="\{\{XML\_URL\}\}" title="JATS XML"\>

\<link rel="alternate" type="application/x-bibtex"  href="\{\{BIB\_URL\}\}" title="BibTeX"\>

\<link rel="alternate" type="application/x-research-info-systems" href="\{\{RIS\_URL\}\}" title="RIS"\>

\<link rel="alternate" type="application/vnd.citationstyles.csl+json" href="\{\{CSL\_URL\}\}" title="CSL-JSON"\>

\<link rel="alternate" type="application/oai-pmh+xml"

      href="\{\{OAI\_ENDPOINT\}\}?verb=GetRecord&amp;metadataPrefix=oai\_dc&amp;identifier=\{\{COMM\_ID\}\}"

      title="OAI-PMH record"\>


\<!-- Highwire Press (Google Scholar, Crossref, PubMed) --\>

\<meta name="citation\_title" content="\{\{TITLE\}\}"\>

\{\{AUTHORS\_HIGHWIRE\}\}

\<meta name="citation\_publication\_date" content="\{\{DATE\_PUBLISHED\}\}"\>

\<meta name="citation\_journal\_title" content="\{\{SERIES\_FULL\}\}"\>

\<meta name="citation\_series\_title" content="\{\{SERIES\_SHORT\}\}"\>

\<meta name="citation\_issn" content="\{\{ISSN\}\}"\>

\<meta name="citation\_volume" content="\{\{VOLUME\}\}"\>

\<meta name="citation\_issue" content="\{\{ISSUE\}\}"\>

\{\{IF\_PAGINATED\}\}\<meta name="citation\_firstpage" content="\{\{FIRSTPAGE\}\}"\>

\<meta name="citation\_lastpage" content="\{\{LASTPAGE\}\}"\>

\{\{/IF\_PAGINATED\}\}\<meta name="citation\_doi" content="\{\{DOI\}\}"\>

\<meta name="citation\_language" content="en"\>

\<meta name="citation\_abstract\_html\_url" content="\{\{LANDING\_URL\}\}"\>

\<meta name="citation\_fulltext\_html\_url" content="\{\{LANDING\_URL\}\}"\>

\<meta name="citation\_pdf\_url" content="\{\{PDF\_URL\}\}"\>

\<meta name="citation\_publisher" content="\{\{PUBLISHER\}\}"\>


\<!-- Dublin Core --\>

\<meta name="DC.title" content="\{\{TITLE\}\}"\>

\<meta name="DC.creator" content="\{\{AUTHORS\_NAMES\_CSV\}\}"\>

\<meta name="DC.date" content="\{\{DATE\_PUBLISHED\}\}"\>

\<meta name="DC.identifier" content="\{\{DOI\}\}"\>

\<meta name="DC.identifier" content="\{\{LANDING\_URL\}\}"\>

\<meta name="DC.publisher" content="\{\{PUBLISHER\}\}"\>

\<meta name="DC.language" content="en"\>

\<meta name="DC.rights" content="\{\{LICENSE\}\}"\>

\<meta name="DC.type" content="Text.ScholarlyArticle"\>

\<meta name="DC.subject" content="\{\{KEYWORDS\_CSV\}\}"\>


\<!-- Open Graph --\>

\<meta property="og:type" content="article"\>

\<meta property="og:title" content="\{\{TITLE\}\}"\>

\<meta property="og:description" content="\{\{ABSTRACT\}\}"\>

\<meta property="og:url" content="\{\{LANDING\_URL\}\}"\>

\<meta property="og:image" content="\{\{CARD\_URL\}\}"\>

\<meta property="og:image:width" content="1200"\>

\<meta property="og:image:height" content="630"\>

\<meta property="og:image:alt" content="\{\{TITLE\}\}"\>

\<meta property="og:site\_name" content="\{\{SERIES\_FULL\}\}"\>

\<meta property="og:locale" content="en\_US"\>

\<meta property="article:published\_time" content="\{\{DATE\_PUBLISHED\}\}"\>

\<meta property="article:modified\_time" content="\{\{DATE\_MODIFIED\}\}"\>

\<meta property="article:author" content="\{\{AUTHORS\_NAMES\_CSV\}\}"\>

\<meta property="article:section" content="Short Communications"\>

\<meta property="article:tag" content="\{\{KEYWORDS\_CSV\}\}"\>


\<!-- Twitter / X --\>

\<meta name="twitter:card" content="summary\_large\_image"\>

\<meta name="twitter:title" content="\{\{TITLE\}\}"\>

\<meta name="twitter:description" content="\{\{ABSTRACT\}\}"\>

\<meta name="twitter:image" content="\{\{CARD\_URL\}\}"\>

\<meta name="twitter:image:alt" content="\{\{TITLE\}\}"\>


\<!-- Schema.org: one @graph, four nodes, reused on every page --\>

\<script type="application/ld+json"\>

\{

  "@context": "https://schema.org",

  "@graph": \[

    \{

      "@type": "Organization",

      "@id": "\{\{ORG\_ID\}\}",

      "name": "\{\{PUBLISHER\}\}",

      "url": "\{\{PUBLISHER\_URL\}\}",

      "address": \{"@type": "PostalAddress", "addressLocality": "New Delhi", "addressCountry": "IN"\},

      "identifier": \[

        \{"@type": "PropertyValue", "propertyID": "ROR",  "value": "\{\{ROR\}\}"\},

        \{"@type": "PropertyValue", "propertyID": "ISNI", "value": "\{\{ISNI\_ORG\}\}"\},

        \{"@type": "PropertyValue", "propertyID": "ISSN", "value": "\{\{ISSN\}\}"\}

      \]

    \},

    \{

      "@type": "CreativeWorkSeries",

      "@id": "\{\{SERIES\_NODE\_ID\}\}",

      "name": "\{\{SERIES\_FULL\}\}",

      "alternateName": "\{\{SERIES\_SHORT\}\}",

      "url": "\{\{SERIES\_URL\}\}",

      "issn": "\{\{ISSN\}\}",

      "inLanguage": "en",

      "publisher": \{"@id": "\{\{ORG\_ID\}\}"\}

    \},

    \{

      "@type": "BreadcrumbList",

      "@id": "\{\{LANDING\_URL\}\}\#breadcrumb",

      "itemListElement": \[

        \{"@type": "ListItem", "position": 1, "name": "Astitva", "item": "\{\{HUB\_URL\}\}"\},

        \{"@type": "ListItem", "position": 2, "name": "Svādhyāya-Saṃhitā", "item": "\{\{ARCHIVE\_URL\}\}"\},

        \{"@type": "ListItem", "position": 3, "name": "\{\{SERIES\_SHORT\}\}", "item": "\{\{SERIES\_URL\}\}"\},

        \{"@type": "ListItem", "position": 4, "name": "\{\{COMM\_ID\}\}", "item": "\{\{LANDING\_URL\}\}"\}

      \]

    \},

    \{

      "@type": "ScholarlyArticle",

      "@id": "\{\{LANDING\_URL\}\}\#article",

      "headline": "\{\{TITLE\}\}",

      "alternativeHeadline": "\{\{SUBTITLE\}\}",

      "identifier": \[

        \{"@type": "PropertyValue", "propertyID": "DOI",     "value": "\{\{DOI\}\}"\},

        \{"@type": "PropertyValue", "propertyID": "ISSN",    "value": "\{\{ISSN\}\}"\},

        \{"@type": "PropertyValue", "propertyID": "comm\_id", "value": "\{\{COMM\_ID\}\}"\}

      \],

      "author": \{\{AUTHORS\_JSON\}\},

      "datePublished": "\{\{DATE\_PUBLISHED\}\}",

      "dateModified": "\{\{DATE\_MODIFIED\}\}",

      "version": "\{\{VERSION\}\}",

      "inLanguage": "en",

      "license": "\{\{LICENSE\_URL\}\}",

      "copyrightHolder": \{"@id": "\{\{ORG\_ID\}\}"\},

      "publisher": \{"@id": "\{\{ORG\_ID\}\}"\},

      "isPartOf": \{"@id": "\{\{SERIES\_NODE\_ID\}\}"\},

      "abstract": "\{\{ABSTRACT\}\}",

      "keywords": \{\{KEYWORDS\_JSON\}\},

      "mainEntityOfPage": "\{\{LANDING\_URL\}\}",

      "encoding": \[

        \{"@type": "MediaObject", "fileFormat": "application/pdf", "contentUrl": "\{\{PDF\_URL\}\}"\},

        \{"@type": "MediaObject", "fileFormat": "application/xml", "contentUrl": "\{\{XML\_URL\}\}"\}

      \]

    \}

  \]

\}

\</script\>


\<style\>

/\* ------------------------------------------------------------------

   Design tokens. One accent, one neutral ramp, system font stacks.

   ------------------------------------------------------------------ \*/

:root\{

  --bg:\#fbfaf7; --surface:\#ffffff; --text:\#16150f; --muted:\#5a574d;

  --rule:\#e6e2d8; --rule-strong:\#cfc9bb;

  --accent:\#4a3b8c; --accent-soft:\#ece9f6;

  --serif:"Iowan Old Style","Palatino Linotype",Palatino,"Book Antiqua",Georgia,"Noto Serif",serif;

  --sans:ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;

  --mono:ui-monospace,SFMono-Regular,"SF Mono",Menlo,Consolas,monospace;

  --measure:46rem; --radius:6px;

\}

@media (prefers-color-scheme: dark)\{

  :root\{

    --bg:\#16150f; --surface:\#1d1c15; --text:\#f2efe6; --muted:\#a8a397;

    --rule:\#2c2a22; --rule-strong:\#403d32;

    --accent:\#b8a9ff; --accent-soft:\#2a2440;

  \}

\}

\*,\*::before,\*::after\{box-sizing:border-box\}

html\{-webkit-text-size-adjust:100%;text-size-adjust:100%\}

body\{

  margin:0;background:var(--bg);color:var(--text);

  font-family:var(--serif);font-size:17px;line-height:1.6;

  font-kerning:normal;

  font-variant-ligatures:common-ligatures;

  font-variant-numeric:oldstyle-nums proportional-nums;

  text-rendering:optimizeLegibility;-webkit-font-smoothing:antialiased;

  padding:clamp(1.2rem,3vw,2.4rem) clamp(1rem,4vw,2rem) 3rem;

\}

@media (prefers-reduced-motion: reduce)\{

  \*\{animation:none!important;transition:none!important;scroll-behavior:auto!important\}

\}

a\{color:var(--accent);text-decoration:underline;text-underline-offset:.15em;text-decoration-thickness:.06em\}

a:hover\{text-decoration-thickness:.14em\}

:focus-visible\{outline:2px solid var(--accent);outline-offset:2px;border-radius:3px\}

:target\{background:var(--accent-soft);border-radius:3px;scroll-margin-top:1rem\}


.mono\{font-family:var(--mono);font-size:.9em\}

.skip\{position:absolute;left:-9999px;top:auto;width:1px;height:1px;overflow:hidden\}

.skip:focus\{position:static;width:auto;height:auto;padding:.5rem .75rem;background:var(--surface);border:1px solid var(--rule-strong);border-radius:var(--radius);font-family:var(--sans);font-size:.85rem\}


.shell\{max-width:var(--measure);margin:0 auto\}


/\* Topbar -------------------------------------------------------- \*/

.topbar\{

  display:flex;flex-wrap:wrap;gap:.4rem .9rem;justify-content:space-between;align-items:baseline;

  font-family:var(--sans);font-size:.78rem;color:var(--muted);

  padding-bottom:.9rem;margin-bottom:1.4rem;border-bottom:1px solid var(--rule)

\}

.topbar a\{color:var(--muted);text-decoration:none\}

.topbar a:hover\{color:var(--text);text-decoration:underline\}

.topbar .series a\{letter-spacing:.02em\}

.topbar nav\{display:flex;flex-wrap:wrap;gap:.35rem .8rem\}

.topbar nav span\[aria-hidden\]\{color:var(--rule-strong)\}


/\* Header -------------------------------------------------------- \*/

header.doc\{margin-bottom:2rem\}

.crumb\{

  font-family:var(--sans);font-size:.75rem;letter-spacing:.06em;

  color:var(--muted);margin:0 0 .7rem

\}

.crumb ol\{list-style:none;padding:0;margin:0;display:flex;flex-wrap:wrap;gap:.3rem .5rem\}

.crumb li\{display:inline-flex;align-items:baseline;gap:.4rem\}

.crumb li + li::before\{content:"›";color:var(--rule-strong);margin-right:.15rem\}

.crumb a\{color:var(--muted);text-decoration:none\}

.crumb a:hover\{color:var(--text);text-decoration:underline\}

.crumb \[aria-current="page"\]\{color:var(--text)\}


h1.title\{

  font-size:clamp(1.5rem,1.1rem + 1.6vw,2rem);

  font-weight:500;letter-spacing:-.012em;line-height:1.2;margin:0 0 .4rem

\}

p.subtitle\{font-style:italic;color:var(--muted);font-size:1.02rem;margin:0 0 1rem\}

ul.authors\{list-style:none;padding:0;margin:0;display:flex;flex-wrap:wrap;gap:.35rem .9rem;font-size:.95rem\}

ul.authors li\{display:inline-flex;align-items:baseline;gap:.35rem;flex-wrap:wrap\}

ul.authors .name\{font-variant-caps:small-caps;letter-spacing:.02em\}

ul.authors .orcid\{

  font-family:var(--sans);font-size:.68rem;letter-spacing:.06em;

  color:var(--muted);text-decoration:none;border:1px solid var(--rule);

  padding:.05rem .35rem;border-radius:999px;line-height:1.3

\}

ul.authors .orcid:hover\{color:var(--accent);border-color:var(--accent)\}

ul.authors .affil\{color:var(--muted);font-size:.85rem;font-style:italic\}


/\* Notice (optional, e.g., newer version available) -------------- \*/

.notice\{

  border:1px solid var(--rule-strong);border-radius:var(--radius);

  background:var(--accent-soft);color:var(--text);

  padding:.65rem .85rem;margin:0 0 1.4rem;font-size:.92rem

\}

.notice a\{font-weight:500\}


/\* Abstract ------------------------------------------------------ \*/

.abstract\{

  background:var(--surface);border:1px solid var(--rule);border-left:3px solid var(--accent);

  border-radius:var(--radius);padding:1rem 1.15rem;margin:0 0 1.6rem

\}

.abstract h2\{

  font-family:var(--sans);font-size:.72rem;letter-spacing:.14em;text-transform:uppercase;

  color:var(--muted);font-weight:600;margin:0 0 .5rem

\}

.abstract p\{margin:0;color:var(--text)\}

.abstract p + p\{margin-top:.6rem\}


/\* Actions ------------------------------------------------------- \*/

.actions\{display:flex;flex-wrap:wrap;gap:.5rem;margin:0 0 1.8rem\}

.btn\{

  display:inline-flex;align-items:center;gap:.45rem;

  font-family:var(--sans);font-size:.82rem;letter-spacing:.01em;

  padding:.5rem .8rem;border-radius:var(--radius);

  border:1px solid var(--rule-strong);background:var(--surface);color:var(--text);

  text-decoration:none;cursor:pointer;line-height:1

\}

.btn:hover\{border-color:var(--accent);color:var(--accent)\}

.btn.primary\{background:var(--accent);border-color:var(--accent);color:var(--bg)\}

.btn.primary:hover\{filter:brightness(1.06);color:var(--bg)\}

.btn svg\{width:14px;height:14px;flex:none\}


/\* Record (metadata) -------------------------------------------- \*/

section.meta\{margin:0 0 1.8rem\}

section.meta h2\{

  font-family:var(--sans);font-size:.72rem;letter-spacing:.14em;text-transform:uppercase;

  color:var(--muted);font-weight:600;margin:0 0 .6rem

\}

dl.record\{

  display:grid;grid-template-columns:10.5rem 1fr;

  gap:.45rem 1.1rem;margin:0;font-family:var(--sans);font-size:.9rem

\}

dl.record dt\{color:var(--muted);font-weight:500;font-size:.8rem;letter-spacing:.03em;padding-top:.1rem\}

dl.record dd\{margin:0;min-width:0\}

ul.tags\{display:flex;flex-wrap:wrap;gap:.35rem;margin:0;padding:0\}

ul.tags li\{

  list-style:none;font-size:.75rem;letter-spacing:.02em;

  padding:.15rem .5rem;border-radius:999px;

  background:var(--accent-soft);color:var(--accent);font-family:var(--sans)

\}

@media (max-width:520px)\{

  dl.record\{grid-template-columns:1fr;gap:.15rem 0\}

  dl.record dt\{margin-top:.5rem\}

\}


/\* Cite ---------------------------------------------------------- \*/

.cite\{

  background:var(--surface);border:1px solid var(--rule);border-radius:var(--radius);

  padding:1rem 1.15rem;margin:0 0 1.8rem

\}

.cite h2\{

  font-family:var(--sans);font-size:.72rem;letter-spacing:.14em;text-transform:uppercase;

  color:var(--muted);font-weight:600;margin:0 0 .55rem

\}

.cite p\{margin:0;font-size:.92rem;line-height:1.55\}

.cite .row\{display:flex;flex-wrap:wrap;gap:.5rem 1rem;align-items:center;margin-top:.75rem\}

.cite .row a\{font-family:var(--sans);font-size:.8rem\}

.cite .copied\{

  font-family:var(--sans);font-size:.78rem;color:var(--accent);

  min-height:1em

\}


/\* Footer -------------------------------------------------------- \*/

footer.doc\{

  margin-top:2.4rem;padding-top:1rem;border-top:1px solid var(--rule);

  font-family:var(--sans);font-size:.78rem;color:var(--muted);line-height:1.55

\}

footer.doc a\{color:var(--muted)\}

footer.doc a:hover\{color:var(--text)\}

footer.doc .row\{display:flex;flex-wrap:wrap;gap:.4rem .9rem;justify-content:space-between\}

footer.doc .id\{font-family:var(--mono);font-size:.75rem\}


/\* Print: a printed page carries its own handshake --------------- \*/

@media print\{

  :root\{

    --bg:\#fff; --surface:\#fff; --text:\#000; --muted:\#444;

    --rule:\#bbb; --rule-strong:\#888; --accent:\#000; --accent-soft:\#eee;

    --measure:none

  \}

  body\{padding:0;font-size:11pt;max-width:none\}

  .topbar,.skip,.actions,.cite .row,ul.authors .orcid\{display:none!important\}

  a\{color:\#000;text-decoration:none\}

  a\[href^="https://doi.org/"\]::after,

  footer.doc a\[href^="https://astitva"\]::after,

  footer.doc a\[href^="https://www.gsfn"\]::after\{

    content:" \<" attr(href) "\>";font-size:.85em;color:\#444;word-break:break-all

  \}

  .abstract\{border-left:2px solid \#000\}

  footer.doc::after\{

    content:"Cite as: \{\{CITATION\_TEXT\}\} — DOI: \{\{DOI\}\} — License: \{\{LICENSE\}\} — ISSN: \{\{ISSN\}\}";

    display:block;margin-top:.75rem;padding-top:.5rem;border-top:1px solid \#000;font-size:.9em

  \}

\}

\</style\>

\<noscript\>\<style\>\[data-copy\]\{display:none\}\</style\>\</noscript\>

\</head\>

\<body\>


\<a class="skip" href="\#main"\>Skip to content\</a\>


\<div class="shell"\>


  \<!-- Top bar: institution, hub, archive, founder --\>

  \<div class="topbar"\>

    \<div class="series"\>

      \<a href="\{\{SERIES\_URL\}\}"\>\{\{SERIES\_FULL\}\}\</a\>

    \</div\>

    \<nav aria-label="Portal navigation"\>

      \<a href="\{\{PUBLISHER\_URL\}\}"\>Institution\</a\>

      \<span aria-hidden="true"\>·\</span\>

      \<a href="\{\{HUB\_URL\}\}"\>Astitva\</a\>

      \<span aria-hidden="true"\>·\</span\>

      \<a href="\{\{ARCHIVE\_URL\}\}"\>Archive\</a\>

      \<span aria-hidden="true"\>·\</span\>

      \<a href="\{\{FOUNDER\_URL\}\}"\>Founder\</a\>

    \</nav\>

  \</div\>


  \<header class="doc"\>

    \<nav class="crumb" aria-label="Breadcrumb"\>

      \<ol\>

        \<li\>\<a href="\{\{HUB\_URL\}\}"\>Astitva\</a\>\</li\>

        \<li\>\<a href="\{\{ARCHIVE\_URL\}\}"\>Svādhyāya-Saṃhitā\</a\>\</li\>

        \<li\>\<a href="\{\{SERIES\_URL\}\}"\>\{\{SERIES\_SHORT\}\}\</a\>\</li\>

        \<li\>\<span aria-current="page" class="mono"\>\{\{COMM\_ID\}\}\</span\>\</li\>

      \</ol\>

    \</nav\>

    \<h1 class="title"\>\{\{TITLE\}\}\</h1\>

    \{\{IF\_SUBTITLE\}\}\<p class="subtitle"\>\{\{SUBTITLE\}\}\</p\>\{\{/IF\_SUBTITLE\}\}


    \<!-- AUTHORS\_BLOCK: one \<li\> per author. Generator contract in §“Generator contract”.

         Template for each item:

         \<li\>

           \<span class="name"\>Family, Given\</span\>

           \<a class="orcid" href="https://orcid.org/0000-0000-0000-0000"

              rel="author me" aria-label="ORCID iD of Family, Given"\>ORCID\</a\>

           \<span class="affil"\>GSFN\</span\>

         \</li\>

    --\>

    \<ul class="authors" aria-label="Authors"\>

      \{\{AUTHORS\_BLOCK\}\}

    \</ul\>

  \</header\>


  \<main id="main"\>


    \{\{IF\_NOT\_LATEST\}\}

    \<p class="notice" role="note"\>

      A newer version of this record exists: \<a href="\{\{LATEST\_URL\}\}"\>v\{\{LATEST\_VERSION\}\}\</a\>.

      The current page presents v\{\{VERSION\}\} (\{\{DATE\_PUBLISHED\}\}).

    \</p\>

    \{\{/IF\_NOT\_LATEST\}\}


    \<!-- Abstract --\>

    \<section class="abstract" aria-labelledby="abstract-h"\>

      \<h2 id="abstract-h"\>Abstract\</h2\>

      \{\{ABSTRACT\_PARAGRAPHS\}\}

    \</section\>


    \<!-- Downloads --\>

    \<div class="actions" role="group" aria-label="Downloads"\>

      \<a class="btn primary" href="\{\{PDF\_URL\}\}" rel="alternate" type="application/pdf"\>

        \<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"

             stroke-linecap="round" stroke-linejoin="round" aria-hidden="true" focusable="false"\>

          \<path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/\>

          \<polyline points="7 10 12 15 17 10"/\>

          \<line x1="12" y1="15" x2="12" y2="3"/\>

        \</svg\>

        Download PDF

      \</a\>

      \<a class="btn" href="\{\{XML\_URL\}\}" type="application/xml"\>JATS XML\</a\>

    \</div\>


    \<!-- Record --\>

    \<section class="meta" aria-labelledby="meta-h"\>

      \<h2 id="meta-h"\>Record\</h2\>

      \<dl class="record"\>

        \<dt\>Identifier\</dt\>       \<dd class="mono"\>\{\{COMM\_ID\}\}\</dd\>

        \<dt\>DOI\</dt\>              \<dd\>\<a href="https://doi.org/\{\{DOI\}\}" class="mono"\>\{\{DOI\}\}\</a\>\</dd\>

        \<dt\>ISSN\</dt\>             \<dd class="mono"\>\{\{ISSN\}\}\</dd\>

        \<dt\>Series\</dt\>           \<dd\>\<a href="\{\{SERIES\_URL\}\}"\>\{\{SERIES\_FULL\}\}\</a\> · \{\{SERIES\_SHORT\}\}\</dd\>

        \<dt\>Volume\</dt\>           \<dd\>\{\{VOLUME\}\}\</dd\>

        \<dt\>Version\</dt\>          \<dd class="mono"\>\{\{VERSION\}\}\</dd\>

        \<dt\>Published\</dt\>        \<dd\>\<time datetime="\{\{DATE\_PUBLISHED\}\}"\>\{\{DATE\_PUBLISHED\}\}\</time\>\</dd\>

        \<dt\>Status\</dt\>           \<dd\>\{\{STATUS\}\}\</dd\>

        \<dt\>Peer review\</dt\>      \<dd\>\{\{PEER\_REVIEW\}\}\</dd\>

        \<dt\>Language\</dt\>         \<dd\>English (en)\</dd\>

        \<dt\>Publisher\</dt\>        \<dd\>\<a href="\{\{PUBLISHER\_URL\}\}"\>\{\{PUBLISHER\}\}\</a\> · \{\{PUBLISHER\_LOCATION\}\}\</dd\>

        \<dt\>License\</dt\>          \<dd\>\<a href="\{\{LICENSE\_URL\}\}" rel="license"\>\{\{LICENSE\}\}\</a\> · © \{\{PUBLISHER\}\}\</dd\>

        \<dt\>Keywords\</dt\>         \<dd\>\<ul class="tags"\>\{\{KEYWORDS\_CHIPS\}\}\</ul\>\</dd\>

        \<dt\>Search method\</dt\>    \<dd\>\{\{SEARCH\_METHOD\}\}\</dd\>

      \</dl\>

    \</section\>


    \<!-- Cite as --\>

    \<section class="cite" aria-labelledby="cite-h"\>

      \<h2 id="cite-h"\>Cite this record\</h2\>

      \<p id="citation-text"\>\{\{CITATION\_TEXT\}\}\</p\>

      \<div class="row"\>

        \<button class="btn" type="button" data-copy="\#citation-text" aria-describedby="copy-status"\>

          Copy citation

        \</button\>

        \<a href="\{\{BIB\_URL\}\}"\>BibTeX\</a\>

        \<a href="\{\{RIS\_URL\}\}"\>RIS\</a\>

        \<a href="\{\{CSL\_URL\}\}"\>CSL-JSON\</a\>

        \<a href="https://doi.org/\{\{DOI\}\}"\>DOI\</a\>

        \<span class="copied" id="copy-status" role="status" aria-live="polite"\>\</span\>

      \</div\>

    \</section\>


  \</main\>


  \<footer class="doc"\>

    \<div class="row"\>

      \<span\>

        \<strong\>\{\{PUBLISHER\}\}\</strong\> · \{\{PUBLISHER\_LOCATION\}\}\<br\>

        \<a href="\{\{PUBLISHER\_URL\}\}"\>gsfn.org\</a\> ·

        \<a href="\{\{SERIES\_URL\}\}"\>\{\{SERIES\_FULL\}\}\</a\>

      \</span\>

      \<span class="id"\>ISSN \{\{ISSN\}\} · \{\{LICENSE\}\}\</span\>

    \</div\>

  \</footer\>


\</div\>


\<!-- Progressive enhancement. Page is fully functional without JS. --\>

\<script\>

(function () \{

  "use strict";

  var btn = document.querySelector('\[data-copy\]');

  if (!btn) return;

  var status = document.getElementById('copy-status');

  function announce(msg) \{

    if (!status) return;

    status.textContent = msg;

    if (msg) setTimeout(function () \{ status.textContent = ''; \}, 2400);

  \}

  function fallbackCopy(text) \{

    var ta = document.createElement('textarea');

    ta.value = text;

    ta.setAttribute('readonly', '');

    ta.style.position = 'absolute';

    ta.style.left = '-9999px';

    document.body.appendChild(ta);

    ta.select();

    var ok = false;

    try \{ ok = document.execCommand('copy'); \} catch (e) \{ ok = false; \}

    document.body.removeChild(ta);

    announce(ok ? 'Copied.' : 'Copy failed — please select and copy manually.');

  \}

  btn.addEventListener('click', function () \{

    var node = document.querySelector(btn.getAttribute('data-copy'));

    if (!node) return;

    var text = (node.textContent || '').trim();

    if (navigator.clipboard && window.isSecureContext) \{

      navigator.clipboard.writeText(text).then(

        function () \{ announce('Copied.'); \},

        function () \{ fallbackCopy(text); \}

      );

    \} else \{

      fallbackCopy(text);

    \}

  \});

\})();

\</script\>


\</body\>

\</html\>
