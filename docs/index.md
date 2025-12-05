<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>AI Data Production Landscape</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="container">
   <h1>
      Welcome to the companion repository for <em>“Understanding AI Data Production & Community Impacts Worldwide: A Multivocal Literature Review”</em>
    </h1>
    <div class="links">
      <a href="./REVISION_ADC_Multivocal.pdf">📄 Read the draft paper</a>
      <a href="https://github.com/chifod2025/ai-data-production-landscape" target="_blank" rel="noopener">GitHub repository</a>
    </div>
  </header>
    <!-- ABSTRACT -->
    <section id="abstract">
      <h2>Abstract</h2>
      <p>
      Artificial intelligence (AI) depends on data production: the sociotechnical process that transforms human knowledge into computational resources. The connections among AI systems, data practices, and impacts on Indigenous, underrepresented, and underserved communities—though critical—have not been systematically examined. To this end, we conduct a Multivocal Literature Review (MLR) integrating 350 academic and grey-literature sources to analyze how AI systems, data practices, and community impacts intersect. Across five analytic domains—Data Relations, Data Labor, Data Representation, Data Infrastructure, and Data Governance—we distinguish extractive data production mechanisms that centralize control from high-agency pathways in which communities exercise authority. We contribute (1) a multivocal review that positions data production as a site of sociotechnical power rather than a technical prerequisite; (2) implications for HCI research including upstream infrastructure as a design site, provenance-first architectures, and federated data governance supporting community sovereignty; (3) methodological validation of multivocal synthesis for bridging academic critique with community practice; and (4) an open corpus mapping sources across pipeline stages, historical eras, and geographic contexts.
      </p>
        <main class="container">
 
      <figure>
        <img src="./assets/tri-2.png" alt="Orientation triangle diagram" />
        <figcaption>
          Fig. 1. A/D/C scoping framework for identifying relevant literature across three interrelated domains of AI (A), Data Production (D), and Community Impacts (C)..
        </figcaption>
      </figure>
          
      <figure>
        <img src="./assets/pipe-1.png" alt="AI development pipeline diagram" />
        <figcaption>
          Fig. 2. Simplified AI development pipeline with three interwoven sine waves representing AI (purple), data production (orange), and community impacts (green) flowing continuously through all pipeline stages. Pipeline diagram derived from Martin (2020).
        </figcaption>
      </figure>
 
<!-- DOMAINS OVERVIEW (cards) -->
<section id="domains" class="container">
  <h2>Analytic Domains (overview)</h2>

  <div class="cards cards--domains" aria-label="Analytic domains as cards">
    <article class="card card--domain">
      <h3>Data Relations</h3>
      <p class="stake">Authority over purpose, scope, consent, and access.</p>
      <ul class="mini">
        <li><strong>Extractive:</strong> outside agenda-setting; bundled consent.</li>
        <li><strong>High-agency:</strong> co-authored scope; granular & revocable consent.</li>
      </ul>
    </article>

    <article class="card card--domain">
      <h3>Data Labor</h3>
      <p class="stake">Who does the work; who is credited, paid, and protected.</p>
      <ul class="mini">
        <li><strong>Extractive:</strong> invisible, piece-work; no share of value.</li>
        <li><strong>High-agency:</strong> attributed labor; context pay; value-sharing.</li>
      </ul>
    </article>

    <article class="card card--domain">
      <h3>Data Representation</h3>
      <p class="stake">Which ontologies and labels make communities legible—or erase context.</p>
      <ul class="mini">
        <li><strong>Extractive:</strong> external taxonomies; category erasure.</li>
        <li><strong>High-agency:</strong> community ontologies; context-preserving schemas; refusal.</li>
      </ul>
    </article>

    <article class="card card--domain">
      <h3>Data Infrastructure</h3>
      <p class="stake">Where data lives and flows; provenance and control.</p>
      <ul class="mini">
        <li><strong>Extractive:</strong> centralized silos; opaque lineage; one-way flows.</li>
        <li><strong>High-agency:</strong> provenance-first storage; tiered access; federated spaces.</li>
      </ul>
    </article>

    <article class="card card--domain">
      <h3>Data Governance</h3>
      <p class="stake">Rights, licensing, oversight, redress—and enforceable refusal.</p>
      <ul class="mini">
        <li><strong>Extractive:</strong> rights-washing; non-consensual reuse; weak redress.</li>
        <li><strong>High-agency:</strong> community licenses; sovereign oversight; enforceable refusal.</li>
      </ul>
    </article>
  </div>

  <p class="domains-note">See the <a href="#taxonomy">taxonomy</a> and datasheet for detailed mappings.</p>
</section>


    <!-- TAXONOMY -->
    <section id="taxonomy">
      <h2>Taxonomy (illustrative, not exhaustive)</h2>
      <p>This project synthesizes extractive patterns and less-extractive pathways identified across the literature.</p>
      <div class="cards">
        <div class="card">
          <h3>Extractive Patterns</h3>
          <ol>
            <li>Excluding underrepresented groups from decision-making</li>
            <li>Collecting vast amounts of data to train AI systems</li>
            <li>Reproducing biases through synthetic data generation</li>
            <li>Scraping or repurposing sensitive data</li>
            <li>Prioritizing data wants over community needs</li>
            <li>Soliciting data without reciprocal benefits</li>
            <li>Exploitative and invisible data labor</li>
            <li>Biased pre-processing and category erasure</li>
            <li>Opaque data practices</li>
            <li>Ethics dumping</li>
            <li>Deploying AI systems trained without local, contextual data</li>
            <li>Western-centric research infrastructures</li>
          </ol>
        </div>
        
        <div class="card">
          <h3>High-Agency Pathways</h3>
          <ol>
            <li>Decentering Western ontologies</li>
            <li>Taking a needs-based approach to developing AI</li>
            <li>Early co-design and participatory initiatives</li>
            <li>Establishing consent and contextually appropriate compensation</li>
            <li>Creating culturally inclusive datasets</li>
            <li>Community-engaged data production</li>
            <li>Crowdsourcing data collection</li>
            <li>Building public visibility in dataset development</li>
            <li>Developing equitable data licensing models</li>
            <li>Developing federated data spaces</li>
            <li>Participatory data ownership and governance</li>
          </ol>
        </div>
      </div>
    </section>

    <!-- RESOURCES -->
    <section id="resources">
      <h2>Resources</h2>
      <div class="cards">
        <div class="card">
          <h3>Paper</h3>
          <p><a href="./REVISION_ADC_Multivocal.pdf">Read the latest paper draft (PDF)</a></p>
        </div>
        <div class="card">
          <h3>Dataset</h3>
          <p>
            <ul>
    <li><a href="https://docs.google.com/spreadsheets/d/1NJBIsDhtqp5CrCTJtfccObCneRLaRtoun6VfPuNTims/edit?usp=sharing" target="_blank" rel="noopener">Live Google Sheet</a></li> 
    <li><a href="https://github.com/ADC-chi/ai-data-production-landscape/blob/main/data/raw/REVISED%20Datasheet.csv">Raw Excel</a></li>
    <li><a href="https://github.com/ADC-chi/ai-data-production-landscape/blob/main/data/processed/REVISED%20Datasheet.xlsx">Processed CSV</a></li>
    </ul>
          </p>
        </div>
        <div class="card">
          <h3>Interactive collections (open-source</h3>
          <p>Curated sets of publicly available sources (≤50 per collection), grouped by orientation.</p>
          <ul>
    <li><a href="https://notebooklm.google.com/notebook/a048fa59-64b2-4b13-a98e-0e739bca49d7" target="_blank" rel="noopener">Extractive Patterns</a></li>
    <li><a href="https://notebooklm.google.com/notebook/f11a7a3b-dfbf-47a1-93e9-ee53683611ba" target="_blank" rel="noopener">High-Agency Principles</a></li>
    <li><a href="https://notebooklm.google.com/notebook/bd97ea3f-b516-48d5-b8c6-720ca8e47bca" target="_blank" rel="noopener">High-Agency Practices</a></li>
  </ul>
      

        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:chifod2025@gmail.com">chifod2025@gmail.com</a></p>
    </section>
  </main>
