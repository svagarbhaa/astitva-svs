---

title: "\[Title of the Short Communication\]"

subtitle: "\[Subtitle or primary text reference, e.g., JUB 3.5.4–5\]"

comm\_id: "SC-2026-001"

series: "Astitva Series — Short Communications"

collection: "Svādhyāya-Saṃhitā"

volume: "\[Year / Volume\]"

version: "0.2.0"

date: "YYYY-MM-DD"

status: "\[Draft | Expert review | Final | Published\]"

author: "\[Author Full Name\]"

author\_details:

  - name: "\[Author Full Name\]"

    affiliation: "\[Affiliation / Institution\]"

    email: "\[email@institution.edu\]"

    orcid: "\[0000-0000-0000-0000\]"

    isni: "\[0000 0000 0000 0000\]"

    ror: "\[https://ror.org/...\]"

thanks: "\[Affiliation / Institution\] · \[email@institution.edu\] · ORCID \[0000-0000-0000-0000\] · ISNI \[0000 0000 0000 0000\]"

doi: "\[Assigned on deposit\]"

license: "\[e.g., CC BY 4.0\]"

lang: en

keywords: \[Veda, Vyākaraṇa, Nirukta, Ritual terminology, Philology\]

feeds\_module: \[\]

bibliography: references.bib

csl: chicago-author-date.csl

link-citations: true

documentclass: article

classoption: \[twoside\]

geometry: "inner=3.6cm, outer=2.6cm, top=2.6cm, bottom=2.6cm"

header-includes: |

  \\usepackage\{fancyhdr\}

  \\usepackage\{booktabs\}

  \\usepackage\{microtype\}

  \\pagestyle\{fancy\}

  \\fancyhf\{\}

  \\fancyhead\[L\]\{\\small Astitva Series — Short Communications\}

  \\fancyhead\[R\]\{\\small Svādhyāya-Saṃhitā\}

  \\fancyfoot\[C\]\{\\thepage\}

  \\fancypagestyle\{plain\}\{%

    \\fancyhf\{\}%

    \\fancyhead\[L\]\{\\small Astitva Series — Short Communications\}%

    \\fancyhead\[R\]\{\\small Svādhyāya-Saṃhitā\}%

    \\fancyfoot\[C\]\{\\thepage\}%

  \}

abstract: |

  \[60–120 words: the textual locus, the single claim, the evidence, and its status.\]

landing\_page:

  url: "\[https://.../SC-2026-001\]"

  canonical\_url: "\[https://.../SC-2026-001\]"

  repository: "\[Repository / platform\]"

  handle: "\[Handle/ARK\]"

  citation\_key: "\[AuthorYYYYShortTitle\]"

  citation\_formats: \[BibTeX, RIS, CSL-JSON, EndNote\]

  social\_image: "\[URL to 1200×630 image\]"

  og\_type: "article"

  schema\_type: "ScholarlyArticle"

peer\_review:

  status: "\[Draft | Expert review | Final | Published\]"

  dates:

    submitted: "YYYY-MM-DD"

    accepted: "YYYY-MM-DD"

    published: "YYYY-MM-DD"

identifiers:

  doi: "\[Assigned on deposit\]"

  orcid: "\[0000-0000-0000-0000\]"

  isni: "\[0000 0000 0000 0000\]"

  ror: "\[https://ror.org/...\]"

rights:

  license: "\[e.g., CC BY 4.0\]"

  copyright: "\[Author/Institution\]"

subjects:

  discipline: "\[Indology / Sanskrit philology / ...\]"

  keywords: \[Veda, Vyākaraṇa, Nirukta, Ritual terminology, Philology\]

  temporal\_coverage: "\[e.g., Vedic period\]"

  geographic\_coverage: "\[e.g., South Asia\]"

text:

  corpus: "\[RV, TS, ŚB, JB, JUB, etc.\]"

  edition: "\[edition\]"

  recension: "\[Śākhā\]"

  passage: "\[e.g., JUB 3.5.4–5\]"

search\_method:

  tools: "\[e.g., GRETIL, TITUS, Digital Corpus of Sanskrit, VedaWeb\]"

  terms: "\[search terms\]"

  date\_accessed: "YYYY-MM-DD"

oai\_pmh:

  endpoint: "\[URL\]"

  set: "\[set\]"

funder:

  - name: "\[Funder\]"

    award: "\[Grant\]"

    fundref\_doi: "\[10.13039/...\]"

---


\<!--

INSTRUCTIONS FOR AUTHORS

HTML comments are stripped by Pandoc; delete before submission if desired.


LENGTH AND STYLE

- 2–4 pages. One focused claim supported by primary evidence. No survey.

- The note must stand alone: the reader needs no other paper to follow it.

- The YAML abstract is a summary of the result; the Opening Note states the problem

  and the passport. Do not duplicate one in the other.


CONVENTIONS

- IAST transliteration throughout; Devanagari (Unicode) for quoted Sanskrit.

  Use ṃ (not ṁ) for anusvāra, consistently, in running text and titles.

  Accent marks (e.g., mānasá) only when the accent is part of the argument.

- Translation policy: key terms stay untranslated in the argument and are glossed once;

  the same gloss is used throughout. Say whose translation is used (own or published).

- Numbering is automatic (--number-sections): Opening Note and Notes are unnumbered;

  Textual Locus = 1, Analysis = 2, Concluding Remark = 3, Optional Extension = 4.

  Do not type numbers into headings.

- Primary sources: standard abbreviations (RV, TS, ŚB, JB, JUB, etc.) with exact location

  (e.g., RV 1.164.1; JUB 3.5.4–5; ŚB 6.3.1.12 ff.) and edition, tabulated under Notes.

- Secondary sources: author–year via references.bib (\[@fujii2015\]); full bibliography optional.

- Label every claim: \[T\] Textual, \[G\] Grammatical, \[S\] Stipulated, \[D\] Derived,

  \[E\] Established external, \[O\] Observational, \[I\] Interpretive, \[C\] Conjectural.

  Verbs follow status: "attested" for \[T\]; "derived" for \[D\]; "argued" for \[I\]; "conjectured" for \[C\].

- Any claim about "attested range" or "absence" must state the search method

  (corpus or tool, search terms, date accessed).

- A heading that does not apply: write "Not applicable, because …"; do not leave it empty.

- Author name prints in the title block; affiliation, e-mail, ORCID and ISNI print as a

  first-page footnote (the \`thanks\` field) and in the Passport table.

- Reproducing manuscript images or long extracts: record permission under Declarations.


BUILD (PDF)

pandoc comm.md --citeproc --number-sections --pdf-engine=lualatex \\

  -V mainfont="Noto Serif" -V mainfontfallback="NotoSerifDevanagari:mode=harf" -o comm.pdf

(Use a recent Pandoc 3.x; check that diacritics and Devanagari render. Raw HTML such as

 \<div align="center"\> is ignored in PDF output, so it is not used here.)

--\>


\#\# Opening Note and Passport \{-\}


\*A concise statement of the problem or the textual locus under examination, then the passport.\*


| Field | Entry |

|---|---|

| \*\*Author, affiliation, contact\*\* | \[Name · Affiliation · e-mail · ORCID · ISNI\] |

| \*\*Series / volume / comm\_id\*\* | Astitva Series — Short Communications · Svādhyāya-Saṃhitā · \[Year / Volume\] · \[comm\_id\] |

| \*\*Locus\*\* | \[Text, edition, passage\] |

| \*\*Single claim\*\* | \[One sentence\] |

| \*\*Type of claim\*\* | \[Philological · Grammatical/Etymological · Interpretive · Ritual-technical · Ontological · Cross-disciplinary (see Section 4)\] |

| \*\*Overall status\*\* | \[one label from the legend below\] |

| \*\*Persistent identifiers\*\* | DOI: \[ \] · Handle/ARK: \[ \] · ORCID: \[ \] · ISNI: \[ \] · ROR: \[ \] |

| \*\*Landing page / canonical URL\*\* | \[ \] |

| \*\*Rights / license\*\* | \[ \] |

| \*\*Review status and dates\*\* | \[ \] |

| \*\*Metadata / indexing profile\*\* | Schema.org ScholarlyArticle · Highwire Press · Dublin Core · OAI-PMH · Crossref/DataCite |

| \*\*Search method for attestation claims\*\* | \[corpus/tool, search terms, date accessed\] |

| \*\*What this note does \*not\* claim\*\* | |

| \*\*How to cite\*\* | \[Author, title, comm\_id, version, DOI\] |


\*\*Status labels used in this note:\*\* \*\*\[T\]\*\* Textual (attested in a cited source) · \*\*\[G\]\*\* Grammatical (follows by cited rule) · \*\*\[S\]\*\* Stipulated (adopted by definition) · \*\*\[D\]\*\* Derived (follows from stated premises) · \*\*\[E\]\*\* Established external (accepted result of another discipline) · \*\*\[O\]\*\* Observational (empirical or clinical data) · \*\*\[I\]\*\* Interpretive (one reading among live alternatives) · \*\*\[C\]\*\* Conjectural (proposed, not demonstrated).


\#\# The Textual Locus


\#\#\# Passage and Translation


Set the original in a distinct block, followed by transliteration and a precise translation.


\> \*\*\[Devanagari text, e.g., ततो ह वै स्तोमं ददर्श … इदं मनो युक्तम् ।\]\*\*

\>

\> \*\[IAST transliteration\]\*

\>

\> “\[Translation.\]” \*(Translation: own / \[translator, year\].)\* \*(Placeholder: replace with your passage.)\*


\*\*Word-by-word gloss\*\* (only for terms on which the argument depends):


| Word (IAST) | Form / analysis | Gloss here |

|---|---|---|

| | | |


\#\#\# Edition, Recension, and Variants

- \*\*Edition and recension used:\*\* \[Śākhā, edition, page/line; critical edition if available\].

- \*\*Variant readings or manuscript issues bearing on the passage:\*\* \[list, or "none relevant" with the basis for saying so\].

- \*\*Accent, metre, ritual context (\*svara, chandas, viniyoga\*):\*\* \[only if relevant to the claim\].


\#\#\# Context and Prior Scholarship

The immediate context and the principal earlier treatments, in a few tightly written paragraphs (commentators such as Sāyaṇa, Yāska, or Skandasvāmin where relevant; modern scholars by author–year). State precisely what is \*unresolved\*; the note's claim should address that gap. Cite the nearest \*\*parallel passages\*\* (RV, TS, JB, ŚB, Upaniṣads, etc.) in standard abbreviation.


\#\#\# Declared Presuppositions

Brief, in the format \*\*Presupposition → adopted / rejected / suspended → what changes if it fails.\*\* Include only those on which the claim rests:


- \*\*Textual:\*\* corpus, recension, stratification and dating assumed.

- \*\*Grammatical:\*\* governing system (Pāṇinian, Nirukta, comparative philology) and its priority.

- \*\*Hermeneutic:\*\* interpretive rules (e.g., Mīmāṃsā \*tātparya\* indicators, historical-contextual method) and level of reading (\*adhiyajña / adhidaiva / adhyātma\*).

- \*\*Anachronism control:\*\* the sense of each term is fixed from textual and grammatical evidence \*before\* any wider correspondence is considered.


\#\# Analysis and Argument


\*Develop the central observation in the dense, economical style of classical Indological short notes. Number propositions so they can be cited (e.g., SC-2026-001:P2).\*


\#\#\# Philological and Grammatical Observation

State the point, cite the supporting verse or passage, and draw the implication. Where technical terms appear (e.g., \*yukti\*, \*stoma\*, \*dhur\*, \*manas\*, \*yuj\*), define them on first occurrence and use them consistently thereafter.


| Term | Root / stem / affix (with sūtra or Nirukta reference) | Attested range (with search method) | Sense adopted here |

|---|---|---|---|

| | | | |


\#\#\# Interpretive Observation

The reading proposed, the textual cross-references supporting it, and the implication for the wider vocabulary or practice.


\#\#\# Evidence Ledger


| ID | Statement | Depends on | Warrant (passage / rule / citation) | Status |

|---|---|---|---|---|

| \*\*P1\*\* | | | | |

| \*\*P2\*\* | | | | |

| \*\*P3\*\* | | | | |


Each proposition is stated once; dependencies refer only to earlier IDs; each warrant begins by naming its type (textual, grammatical, formal, empirical).


\#\#\# Alternative Readings and Objections

- \*\*Rival reading(s):\*\* at least one for every \[I\] proposition, with the reason it is not adopted.

- \*\*Strongest objection (Pūrva-pakṣa)\*\* from a specialist's standpoint (philologist, traditional \*paṇḍita\*, or other) → \*\*Reply (Uttara-pakṣa)\*\* → \*\*Residual\*\* (what remains unsettled, and whether the thesis is answered, narrowed, or conceded).


\#\# Concluding Remark


- \*\*Restatement of the contribution:\*\* a crisp paragraph giving the claim and its exact warranted status.

- \*\*Limits:\*\* what the note does not establish; cases needing a longer study.

- \*\*Open questions / next steps:\*\* each with a pointer to what would settle it (a manuscript check, a corpus search, a fuller monograph).

- \*\*Wider implications\*\* for the understanding of concentration, ritual, or philosophical vocabulary, stated without opening a new paper.


\#\# Optional Extension: Cross-Disciplinary Bearing


\*Include only if the note touches physics, mathematics, systems theory, or Ayurveda. Otherwise write "Not applicable, because this note is purely philological."\*


- \*\*Correspondence claimed (choose one):\*\* isomorphism · homomorphism · analogy · heuristic parallel · historical claim. (An isomorphism requires both sides to be formalised as structures.)

- \*\*Elements mapped; what is preserved and what is not.\*\*

- \*\*Presuppositions on the other side\*\* (physical, mathematical, clinical) that the mapping requires.

- \*\*Testable consequence and what would refute it.\*\*

- \*\*Clinical safety statement\*\* (if Ayurveda is touched): state that no clinical recommendation is made, or give the evidence and its status \[O\]/\[C\].

- \*\*Pointer\*\* to the full module (module\_id) where the argument is developed.


\#\# Digital Landing Page, Discoverability, and Digital Handshake \{-\}


\*This section is for the landing-page build. It may be removed from the PDF or kept as an appendix. It does not add a numbered section.\*


\*\*Digital handshake\*\* here means the machine-readable links among author, institution, article, version, license, and repository: ORCID, ISNI, ROR, DOI, FundRef, Handle/ARK, Crossref/DataCite, OAI-PMH, JATS XML, and Schema.org JSON-LD.


\#\#\# Required landing-page metadata

- \*\*Canonical URL:\*\* \[ \]

- \*\*DOI:\*\* \[ \]

- \*\*Handle/ARK:\*\* \[ \]

- \*\*ORCID / ISNI / ROR:\*\* \[ \]

- \*\*Citation key and export formats:\*\* \[ \]

- \*\*License and rights:\*\* \[ \]

- \*\*Peer-review status and dates:\*\* \[ \]

- \*\*Subjects, keywords, temporal/geographic coverage:\*\* \[ \]

- \*\*Textual corpus, edition, recension, passage:\*\* \[ \]

- \*\*Search method and date accessed:\*\* \[ \]


\#\#\# Digital handshake checklist

- \[ \] DOI deposited with Crossref/DataCite; metadata includes ORCID, ISNI, ROR, FundRef, license, abstract, references.

- \[ \] ORCID iDs authenticated and connected to the work.

- \[ \] Institutional affiliation uses ROR.

- \[ \] Author names use ISNI where available.

- \[ \] Landing page exposes OAI-PMH endpoint and set.

- \[ \] Citation exports: BibTeX, RIS, CSL-JSON, EndNote.

- \[ \] Indexing: Google Scholar, BASE, OpenAIRE, CORE, Semantic Scholar, Dimensions, WorldCat, Wikidata.

- \[ \] Schema.org JSON-LD ScholarlyArticle present.

- \[ \] Open Graph and Twitter Card tags present with 1200×630 image.

- \[ \] JATS XML or repository-native XML deposited.

- \[ \] Versioned DOI or version statement; preservation copy with checksum.

- \[ \] Accessibility: \`lang\`, semantic headings, alt text, table headers, screen-reader labels.

- \[ \] Search-method statement for any attestation/absence claim.


\#\#\# Landing-page HTML head block (template; not printed in PDF)


\`\`\`html

\<!-- Highwire Press / Google Scholar --\>

\<meta name="citation\_title" content="\[Title\]"\>

\<meta name="citation\_author" content="\[Author Full Name\]"\>

\<meta name="citation\_author\_orcid" content="\[https://orcid.org/0000-0000-0000-0000\]"\>

\<meta name="citation\_publication\_date" content="YYYY-MM-DD"\>

\<meta name="citation\_series\_title" content="Astitva Series — Short Communications"\>

\<meta name="citation\_journal\_title" content="Svādhyāya-Saṃhitā"\>

\<meta name="citation\_volume" content="\[Year / Volume\]"\>

\<meta name="citation\_issue" content="\[Issue\]"\>

\<meta name="citation\_firstpage" content="\[First page\]"\>

\<meta name="citation\_lastpage" content="\[Last page\]"\>

\<meta name="citation\_doi" content="\[DOI\]"\>

\<meta name="citation\_language" content="en"\>

\<meta name="citation\_abstract\_html\_url" content="\[Landing page URL\]"\>

\<meta name="citation\_pdf\_url" content="\[PDF URL\]"\>


\<!-- Dublin Core --\>

\<meta name="DC.title" content="\[Title\]"\>

\<meta name="DC.creator" content="\[Author Full Name\]"\>

\<meta name="DC.date" content="YYYY-MM-DD"\>

\<meta name="DC.identifier" content="\[DOI\]"\>

\<meta name="DC.language" content="en"\>

\<meta name="DC.rights" content="\[License\]"\>


\<!-- Open Graph --\>

\<meta property="og:title" content="\[Title\]"\>

\<meta property="og:description" content="\[Short abstract\]"\>

\<meta property="og:type" content="article"\>

\<meta property="og:url" content="\[Canonical URL\]"\>

\<meta property="og:image" content="\[1200×630 image URL\]"\>


\<!-- Twitter --\>

\<meta name="twitter:card" content="summary\_large\_image"\>

\<meta name="twitter:title" content="\[Title\]"\>

\<meta name="twitter:description" content="\[Short abstract\]"\>

\<meta name="twitter:image" content="\[1200×630 image URL\]"\>


\<!-- Schema.org JSON-LD --\>

\<script type="application/ld+json"\>

\{

  "@context": "https://schema.org",

  "@type": "ScholarlyArticle",

  "headline": "\[Title\]",

  "author": \[

    \{

      "@type": "Person",

      "name": "\[Author Full Name\]",

      "identifier": "https://orcid.org/0000-0000-0000-0000",

      "affiliation": \{

        "@type": "Organization",

        "name": "\[Affiliation\]",

        "identifier": "https://ror.org/..."

      \}

    \}

  \],

  "datePublished": "YYYY-MM-DD",

  "doi": "\[DOI\]",

  "license": "\[License URL\]",

  "isPartOf": \{

    "@type": "PublicationSeries",

    "name": "Astitva Series — Short Communications"

  \},

  "publisher": \{

    "@type": "Organization",

    "name": "\[Publisher/Repository\]"

  \},

  "abstract": "\[Abstract\]",

  "keywords": \["Veda", "Vyākaraṇa", "Nirukta", "Ritual terminology", "Philology"\]

\}

\</script\>

\`\`\`


\#\# Notes, Sources, and References \{-\}


\#\#\# Primary Sources

Standard abbreviation, exact location, and edition.


| Abbrev. | Text | Edition / translator / recension | Passage(s) cited |

|---|---|---|---|

| | | | |


\#\#\# Secondary Literature

Brief author–year (through \`references.bib\`) or short title. A full bibliography is optional; essential items must be listed. Example format \*(replace; verify against your own record before use)\*: Fujii, M. “The Yukti of the Stoma (JUB 3.5.4–5): A Precursor of Yoga as Concentration.” 16th World Sanskrit Conference, Bangkok, 2015.


\#\#\# Declarations

Conflicts of interest · funding · data and corpus-search availability · permissions for manuscript images or extracts · use of AI or software tools (if any) · acknowledgments and expert readers · CRediT roles · ethics approval or “Not applicable, because …”.


\#\#\# Version History


| Version | Date | Change | Reader / Discipline |

|---|---|---|---|

| 0.1.0 | | Initial draft | |

| 0.2.0 | | Added discoverability, PID, landing-page, and digital-handshake metadata | |


---


\#\# Pre-Submission Checklist \*(delete this section before submission)\* \{-\}


- \[ \] Length 2–4 pages; one claim, stated in one sentence in the Passport.

- \[ \] Passage, edition, recension, and variants are given; translation is precise and its source named.

- \[ \] Every technical term is defined at first use and used consistently.

- \[ \] Presuppositions declared, each with an "if it fails" consequence.

- \[ \] Every proposition has an ID, a warrant, and a status label; verbs match status.

- \[ \] Any claim about attested range or absence states its search method and date.

- \[ \] At least one rival reading and one objection answered, with the residual stated.

- \[ \] Limits and open questions stated.

- \[ \] Cross-disciplinary extension completed (correspondence type, refutation condition) or marked "Not applicable".

- \[ \] IAST consistent (ṃ throughout); \`.bib\` and \`.csl\` present; PDF shows Devanagari, diacritics, header, and first-page footnote correctly.

- \[ \] DOI, ORCID, ISNI, ROR, license, and citation key entered in YAML and Passport.

- \[ \] Landing-page URL and canonical URL set.

- \[ \] Highwire/Dublin Core/Open Graph/Twitter/Schema.org metadata generated.

- \[ \] Citation exports tested: BibTeX, RIS, CSL-JSON, EndNote.

- \[ \] OAI-PMH endpoint/set and JATS XML deposit recorded, if applicable.

- \[ \] Accessibility checks passed: \`lang\`, headings, alt text, table headers.

- \[ \] All instructional comments and this checklist removed.


\*End of template. Replace all placeholders before finalising.\*
