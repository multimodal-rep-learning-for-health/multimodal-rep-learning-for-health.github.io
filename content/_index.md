+++
title = "MMRL4H @ EurIPS 2025"
+++

---

<section id="about">

## About {#about}
Clinical decision making often draws on multiple diverse data sources including, but not limited to, images, text reports, electronic health records (EHR), continuous physiological signals and genomic profiles and yet most AI systems deployed in healthcare remain unimodal. However, integrating diverse medical modalities presents significant challenges including data heterogeneity, data scarcity, missing or asynchronous modalities, variable data quality and the lack of standardized frameworks for aligned representation learning. This workshop aims to bring the EurIPS community together to tackle the problem of fusing these heterogeneous inputs into interpretable, coherent patient representations, aiming to mirror the holistic reasoning of clinicians.
We aim to bring together machine learning researchers, clinicians and industry partners dedicated to the theory, methods, and translation of multimodal learning in healthcare.

### Goals
In this workshop, we aim to:
- Advance methods for learning joint representations from images, text, signals, and genomics.  
- Investigate foundation-model pretraining at scale on naturally paired modalities.  
- Address robustness, fairness, and missing-modality issues unique to healthcare fusion.  
- Foster clinician–ML collaboration and outline translational paths to deployment.  

</section>

---

<section id="key-info">

## Key Info {#key-info}

### Important Dates

Our [Call for Papers](https://openreview.net/) is now open!




Please note all deadlines are Anywhere on Earth (AOE).

- **Submission Deadline:** October 10, 2025
- **Acceptance Notification:** October 31, 2025 
- **Workshop Date:** December 6/7, 2025 (TBC)

---

## Call for Papers {#call-for-papers}

Authors are invited to submit 4-page abstracts on topics relevant to multimodal representation learning in healthcare. These include, but are not limited to, vision-language models for radiology, temporal alignment of multimodal ICU streams, graph and transformer architectures for patient data fusion, cross-modal self-supervised objectives, and multimodal benchmarks with fairness and bias analysis.

### Submission

- **Submission site:** via [OpenReview (to be updated)](https://openreview.net/)
- **Format:** [NeurIPS 2025 template](https://media.neurips.cc/Conferences/NeurIPS2025/Styles.zip)
- **Length:** max 4 pages excluding references
- **Review:** Double-blind
- **Anonymization:** Required, ensure that there are no names or affiliations in all parts of the submission including any code.

All accepted papers will be published on the website. Please note that there will be no workshop proceedings (non-archival).

---

<section id="schedule">

## Preliminary Schedule {#schedule}

| Time        | Session                                  |
|-------------|-------------------------------------------|
| 09:00–09:15 | Opening Remarks                           |
| 09:15–10:00 | Sonali Parbhoo                            |
| 10:00–10:20 | Spotlight Session I (3x7mins)             |
| 10:20–11:00 | Coffee & Poster Session I                 |
| 11:00–11:45 | Patrick Schwab                            |
| 11:45–12:30 | Panel - "Translating Multimodal ML to the Bedside" |
| 12:30–14:00 | Lunch & Networking                        |
| 14:00-14:45 | Rajesh Ranganath                          |
| 14:45-15:15 | Spotlight Session II (3x7mins)            |
| 15:15–15:45 | Coffee & Poster Session II                |
| 15:45–16:30 | Round-table Discussion                    |
| 16:30-16:50 | Open Q&A                                  |
| 16:50-17:00 | Closing Remarks & Awards                  |

</section>

---
<section id="speakers">

## Confirmed Speakers {#confirmed-speakers}

<style>
.speaker-grid {
    display: grid;
    gap: 2rem;
    margin-top: 3rem;
    margin-bottom: 2rem;
    /* Mobile first: single column */
    grid-template-columns: 1fr;
}

.speaker-item {
    text-align: center;
    margin: 0 1rem;
}

.speaker-item .text-muted {
    text-align: center;
}

.speaker-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin: 0 auto 1rem auto;
    display: block;
}

/* Tablet: 2 columns */
@media (min-width: 600px) {
    .speaker-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Desktop: 3 columns for 5 speakers with centered bottom row */
@media (min-width: 900px) {
    .speaker-grid {
        grid-template-columns: repeat(6, 1fr);
        max-width: 1200px;
        margin-left: auto;
        margin-right: auto;
    }
    
    .speaker-item:nth-child(1) { grid-column: 1 / 3; }
    .speaker-item:nth-child(2) { grid-column: 3 / 5; }
    .speaker-item:nth-child(3) { grid-column: 5 / 7; }
    .speaker-item:nth-child(4) { grid-column: 2 / 4; }
    .speaker-item:nth-child(5) { grid-column: 4 / 6; }
    
    .speaker-img {
        width: 180px;
        height: 180px;
    }
}

/* Very wide screens: still maintain the same layout but with better spacing */
@media (min-width: 1400px) {
    .speaker-grid {
        gap: 3rem;
    }
}
</style>

<div class="speaker-grid">
    <div class="speaker-item">
        <img src="patrick-schwab.jpg" alt="Patrick Schwab" class="speaker-img">
        <h4>Patrick Schwab</h4>
        <p class="text-muted">GSK.ai, CH</p>
    </div>
    <div class="speaker-item">
        <img src="sonali-parbhoo.jpg" alt="Sonali Parbhoo" class="speaker-img">
        <h4>Sonali Parbhoo</h4>
        <p class="text-muted">Imperial College London, UK</p>
    </div>
    <div class="speaker-item">
        <img src="stephanie-hyland.jpg" alt="Stephanie Hyland" class="speaker-img">
        <h4>Stephanie Hyland</h4>
        <p class="text-muted">Microsoft Research, UK</p>
    </div>
    <div class="speaker-item">
        <img src="rajesh-ranganath.jpg" alt="Rajesh Ranganath" class="speaker-img">
        <h4>Rajesh Ranganath</h4>
        <p class="text-muted">New York University, USA</p>
    </div>
    <div class="speaker-item">
        <img src="bianca-dumitrascu.jpg" alt="Bianca Dumitrascu" class="speaker-img">
        <h4>Bianca Dumitrascu</h4>
        <p class="text-muted">Columbia University, USA</p>
    </div>
</div>


</section>

---

<section id="organizers">

## Organizers {#organizers}

<style>
.organizer-grid {
    display: grid;
    gap: 2rem;
    margin-top: 3rem;
    margin-bottom: 2rem;
    /* Mobile first: single column */
    grid-template-columns: 1fr;
}

.organizer-item {
    text-align: center;
    margin: 0 1rem;
}

.organizer-item .text-muted {
    text-align: center;
}

.organizer-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin: 0 auto 1rem auto;
    display: block;
}

/* Tablet: 2 columns */
@media (min-width: 600px) {
    .organizer-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Desktop: 3 columns (3x2 layout for 6 items) */
@media (min-width: 900px) {
    .organizer-grid {
        grid-template-columns: repeat(3, 1fr);
        max-width: 1200px;
        margin-left: auto;
        margin-right: auto;
    }
    
    .organizer-img {
        width: 180px;
        height: 180px;
    }
}

/* Very wide screens: still maintain 3 columns but with better spacing */
@media (min-width: 1400px) {
    .organizer-grid {
        gap: 3rem;
    }
}
</style>

<div class="organizer-grid">
    <div class="organizer-item">
        <img src="stephan-mandt.jpg" alt="Stephan Mandt" class="organizer-img">
        <h4>Stephan Mandt</h4>
        <p class="text-muted">Associate Professor, UC Irvine, USA</p>
    </div>
    <div class="organizer-item">
        <img src="ece-ozkan-elsen.jpg" alt="Ece Ozkan Elsen" class="organizer-img">
        <h4>Ece Ozkan Elsen</h4>
        <p class="text-muted">Assistant Professor, University of Basel, CH</p>
    </div>
    <div class="organizer-item">
        <img src="samuel-ruiperez-campillo.jpg" alt="Samuel Ruiperez-Campillo" class="organizer-img">
        <h4>Samuel Ruiperez-Campillo</h4>
        <p class="text-muted">PhD Student, ETH Zurich, CH</p>
    </div>
    <div class="organizer-item">
        <img src="thomas-sutter.jpg" alt="Thomas Sutter" class="organizer-img">
        <h4>Thomas Sutter</h4>
        <p class="text-muted">Postdoctoral Researcher, ETH Zurich, CH</p>
    </div>
    <div class="organizer-item">
        <img src="julia-vogt.jpg" alt="Julia Vogt" class="organizer-img">
        <h4>Julia Vogt</h4>
        <p class="text-muted">Associate Professor, ETH Zurich, CH</p>
    </div>
    <div class="organizer-item">
        <img src="nikita-narayanan.jpg" alt="Nikita Narayanan" class="organizer-img">
        <h4>Nikita Narayanan</h4>
        <p class="text-muted">PhD Student, Imperial College London, UK</p>
    </div>
</div>

### Contact
- General inquiries: <mmrl4h@gmail.com>

</section>
