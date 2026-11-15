---
title: Home
nav_order: 1
description: "HyperTaxonomy: a suite of WordPress plugins for connecting concepts within a site, across sites, and onto the semantic web."
---

<div class="hero">
  <img class="hero-logo" src="{{ '/assets/images/plugins/hypertaxonomy.png' | relative_url }}" alt="" width="120" height="120">
  <div>
    <h1 class="hero-title">HyperTaxonomy Suite</h1>
    <p class="hero-tagline">HyperText: linking pages.<br>HyperTaxonomy: connecting concepts.</p>
    <div class="hero-actions">
      <a class="btn btn-primary" href="#getting-started">Get started</a>
      <a class="btn" href="#the-plugins">Explore the plugins</a>
      <a class="btn" href="https://github.com/HyperTaxonomy">GitHub</a>
    </div>
  </div>
</div>

Currently WordPress powers over 40% of all websites on the internet — more than any other content management system (CMS). In stock WordPress, a post reaches a tag or category archive only if it carries exactly the right term. Building a comprehensive site means constant re-tagging,
or accepting gaps. The HyperTaxonomy Suite fixes this at the taxonomy level: define how your terms relate to each other, connect that vocabulary to the wider web, and let every related post surface where it belongs — in archives, in search results, and in linked-data clients — with no re-tagging.
{: .lead }

<div class="feature-callout">
  <p class="feature-callout-title">Why this exists</p>
  <p>Hypertext connected documents, and in doing so changed how people do almost everything. HyperTaxonomy takes the same step for what those documents are about: it connects concepts — within sites, across sites, and across systems — into a decentralized network of meaning.</p>
  <p><a href="{% link vision.md %}">Read the full essay →</a></p>
</div>

## The plugins

The HyperTaxonomy Suite is a set of focused WordPress plugins. **HyperTaxonomy**
is the core and acts as the hub. The companion plugins build on the same term vocabulary
and do more when HyperTaxonomy is present, but don't require it;
**TermConnect Social** does require **TermConnect**.

<div class="plugin-grid">
  <div class="plugin-card plugin-card--core">
    <div class="plugin-card-head">
      <img class="plugin-card-icon" src="{{ '/assets/images/plugins/hypertaxonomy.png' | relative_url }}" alt="" width="64" height="64">
      <div>
        <h3>HyperTaxonomy</h3>
        <p class="plugin-card-role">The core</p>
        <p class="plugin-card-tagline">Structure the unstructured</p>
      </div>
    </div>
    <p class="plugin-card-desc">At its simplest, it organizes your terms: arrange tags, categories, and custom terms into nested groups, manage them in bulk, and display them — as term lists, collapsible trees, or filtered tag clouds — anywhere on your site. From there, model any semantic connection in your domain: inclusions (any term pulls in another's posts), group inclusions, synonyms (mutual inclusions), redirects — or define your own relationships between terms. Enrich archives with descriptions and sticky posts, order posts by recent comment activity or various other criteria, build faceted search widgets — all from the WordPress admin, no coding required. As the suite's hub, it also surfaces companion plugin data — locations from As the Crow Flies and mapped peer site terms from TermConnect — through a single API, so consumers like WP-SKOS read everything in one place.</p>
    <div class="plugin-card-footer">
      <span class="req-badge">Requires nothing</span>
      <span class="plugin-links"><a href="https://hypertaxonomy.org/hypertaxonomy/">Docs</a><a href="https://github.com/HyperTaxonomy/hypertaxonomy">GitHub</a></span>
    </div>
  </div>
  <div class="plugin-card">
    <div class="plugin-card-head">
      <img class="plugin-card-icon" src="{{ '/assets/images/plugins/termconnect.png' | relative_url }}" alt="" width="64" height="64">
      <div>
        <h3>TermConnect</h3>
        <p class="plugin-card-role">Across the web</p>
        <p class="plugin-card-tagline">Vocabulary without borders</p>
      </div>
    </div>
    <p class="plugin-card-desc">Connect your term vocabulary to the global web of knowledge. Attach external identifiers (peer sites' tags and categories, Wikipedia links, GeoNames IDs, or any other URI), delegate term definitions to authoritative sources of your choice, mirror shared vocabularies from peers locally, and pull related content from a decentralized network of trusted sites and feeds — curated, not crawled.</p>
    <div class="plugin-card-footer">
      <span class="req-badge">Requires nothing · better with HyperTaxonomy</span>
      <span class="plugin-links"><a href="https://hypertaxonomy.org/termconnect/">Docs</a><a href="https://github.com/HyperTaxonomy/termconnect">GitHub</a></span>
    </div>
  </div>
  <div class="plugin-card">
    <div class="plugin-card-head">
      <img class="plugin-card-icon" src="{{ '/assets/images/plugins/termconnect-social.png' | relative_url }}" alt="" width="64" height="64">
      <div>
        <h3>TermConnect Social</h3>
        <p class="plugin-card-role">Across social networks</p>
        <p class="plugin-card-tagline">Hashtags unleashed</p>
      </div>
    </div>
    <p class="plugin-card-desc">Write <code>#hashtags</code> and <code>@mentions</code> inline in the editor and let them turn into real taxonomy terms, assigned to posts automatically from your content. Each token links out to the social networks that you enable in settings — hashtags to a network's hashtag page, mentions to a person's profile. Aggregate content from peer sites by common hashtags dynamically.</p>
    <div class="plugin-card-footer">
      <span class="req-badge">Requires TermConnect</span>
      <span class="plugin-links"><a href="https://hypertaxonomy.org/termconnect-social/">Docs</a><a href="https://github.com/HyperTaxonomy/termconnect-social">GitHub</a></span>
    </div>
  </div>
  <div class="plugin-card">
    <div class="plugin-card-head">
      <img class="plugin-card-icon" src="{{ '/assets/images/plugins/as-the-crow-flies.png' | relative_url }}" alt="" width="64" height="64">
      <div>
        <h3>As the Crow Flies</h3>
        <p class="plugin-card-role">Across space</p>
        <p class="plugin-card-tagline">Location management and distance filtering</p>
      </div>
    </div>
    <p class="plugin-card-desc">Attach one or more physical locations (addresses and/or coordinates) to any taxonomy term and filter WordPress content by distance — from any postal code, IP or browser geolocation, or from a chosen reference point. No map API key required; works worldwide.</p>
    <div class="plugin-card-footer">
      <span class="req-badge">Requires nothing · better with HyperTaxonomy</span>
      <span class="plugin-links"><a href="https://hypertaxonomy.org/as-the-crow-flies/">Docs</a><a href="https://github.com/HyperTaxonomy/as-the-crow-flies">GitHub</a></span>
    </div>
  </div>
  <div class="plugin-card">
    <div class="plugin-card-head">
      <img class="plugin-card-icon" src="{{ '/assets/images/plugins/wp-skos.png' | relative_url }}" alt="" width="64" height="64">
      <div>
        <h3>WP-SKOS</h3>
        <p class="plugin-card-role">Onto the semantic web</p>
        <p class="plugin-card-tagline">Your taxonomies, as linked data</p>
      </div>
    </div>
    <p class="plugin-card-desc">Turn any WordPress taxonomy into a machine-readable SKOS vocabulary. Each term becomes a <code>skos:Concept</code> at a stable URI; each taxonomy a <code>skos:ConceptScheme</code>. A REST API that follows Skosmos's, a concept-aware document search endpoint, and a full export for loading into a triple store make your vocabulary browsable and queryable by SKOS tools, RAG pipelines, and AI agents.</p>
    <div class="plugin-card-footer">
      <span class="req-badge">Requires nothing · better with HyperTaxonomy</span>
      <span class="plugin-links"><a href="https://hypertaxonomy.org/wp-skos/">Docs</a><a href="https://github.com/HyperTaxonomy/wp-skos">GitHub</a></span>
    </div>
  </div>
</div>

## The ecosystem

HyperTaxonomy sits at the center as the hub. The arrows show how term data flows:
companions enrich the shared vocabulary, HyperTaxonomy feeds its relationships
back to them, and it exposes the combined picture — through a single term API — to
consumers like WP-SKOS. Every plugin except TermConnect Social, which
requires TermConnect, also works on its own.

```mermaid
graph LR
    TCS["<span style='font-size:1.2em'><b>TermConnect Social</b></span><br/><span style='font-size:0.95em'>#hashtags and @mentions as global terms</span>"] -->|"hashtag & mention terms"| TC["<span style='font-size:1.2em'><b>TermConnect</b></span><br/><span style='font-size:0.95em'>knowledge bases & peer sites</span>"]
    TC -->|"link storage & peer fetch"| TCS
    ATCF["<span style='font-size:1.2em'><b>As the Crow Flies</b></span><br/><span style='font-size:0.95em'>locations & proximity</span>"] -->|locations| HT
    TC -->|"links & peer content"| HT(("<span style='font-size:1.2em'><b>HyperTaxonomy</b></span><br/><span style='font-size:0.95em'>semantic term relationships</span>"))
    HT -->|"relationships & groups"| TC
    HT -->|"enriched terms"| SKOS["<span style='font-size:1.2em'><b>WP-SKOS</b></span><br/><span style='font-size:0.95em'>SKOS linked data</span>"]
```

## Getting started

1. **Install the core.** Add **[HyperTaxonomy](https://hypertaxonomy.org/hypertaxonomy/)**
   and define your term relationships — groups, inclusions, synonyms, redirects.
   This alone improves every archive page on your site, and site search once you
   turn on PowerSearch for it.

2. **Add companions as you need them.**
   - Connecting to external knowledge bases or peer sites? Add
     **[TermConnect](https://hypertaxonomy.org/termconnect/)**.
   - Turning #hashtags and @mentions into linked taxonomy terms? Add
     **[TermConnect Social](https://hypertaxonomy.org/termconnect-social/)** (with TermConnect).
   - Working with places and distances? Add
     **[As the Crow Flies](https://hypertaxonomy.org/as-the-crow-flies/)**.
   - Publishing linked data or feeding AI/RAG clients? Add
     **[WP-SKOS](https://hypertaxonomy.org/wp-skos/)**.
