---
layout: archive
title: "Curriculum Vitae — Veterinary"
permalink: /cv-vet/
author_profile: true
cv_view: vet
redirect_from:
  - /vet-cv
---

{% include base_path %}

{% include cv-toggle.html %}

Education
======
* D.V.M., Colorado State University – College of Veterinary Medicine and Biomedical Sciences, 2014
* Ph.D., University of California San Diego – Biomedical Sciences Graduate Program, 2022
* B.S. Biological Sciences with an emphasis in Medical Microbiology, University of California Davis, 2008

Veterinary Clinical Experience
======
* (2015-2017) Associate Veterinarian
  * Banfield Pet Hospital #0075 – Sand City, CA
  * Duties included: small animal clinical practice

* (2014-2015) Associate Veterinarian
  * Shively Animal Clinic and Hospital – Louisville, KY
  * Duties included: small animal clinical practice, emergency care

Animal Health & One Health Research
======
* (2026-present) Project Scientist
  * University of California San Diego - [Rob Knight's Lab](https://knightlab.ucsd.edu/)
  * Animal health projects: KittyBiome Reanalysis (domestic cat diet and the gut microbiome); conservation projects with the San Diego Zoo Wildlife Alliance – African Elephants/Southern White Rhinoceroses Project + Mountain Yellow Legged Frog Project; Multiomic Ocean Health (PacBio long read metagenomics, untargeted LC-MS/MS metabolomics, proteomics) supported by the Minderoo Foundation
  * Additional projects: Mouse models of atherosclerosis and interactions with bile acids, Gates Foundation Multi-omic Early Life Development Project

* (2022-2026) Postdoctoral Researcher
  * University of California San Diego - [Rob Knight's Lab](https://knightlab.ucsd.edu/)
  * Animal health work included diet change in a common marmoset colony and fecal microbiota transplantation in bottlenose dolphins

* (2017-2022) Graduate Student Researcher
  * University of California San Diego - [Amir Zarrinpar's Lab](https://zarrinparlab.org/)
  * Thesis: Temporal Microbiome Dynamics, From Circadian Rhythms to Probiotic Evolution (mouse models of human disease)
  * Supported by NIH T32 OD017863 (2019-2021)

Veterinary Student & Pre-Veterinary Research
======
* Summer 2012: NIAMS Summer Intern
  * National Institutes of Health – Hanson Laboratory, Bethesda, MD
  * Project: Finding NEMO - Optimization of immunofluorescence microscopy protocol to elucidate signaling abnormalities in the NF-kB pathway by checking p65 nuclear translocation in skin fibroblast samples from patients with rare mutations in the gene that encodes for the NF-kB essential modulator (NEMO).

* Summer 2011: Veterinary Student Researcher
  * Colorado State University – Dow Laboratory, Fort Collins, CO
  * Project: *Staphylococcus aureus* chronic biofilm tested against antigen vaccination and antibiotics

* (2010-2011) Veterinary Student Researcher
  * Colorado State University – Kendall Laboratory, Fort Collins, CO
  * Project: Mouse parvovirus (MPV) facility transmission, which resulted in a publication

* (2008-2010) Microbiology/Necropsy Assistant
  * Comparative Pathology Laboratory, University of California Davis, Davis, CA
  * Duties included: necropsies of rodents and other animals and complete microbiological analysis

Veterinary Service & Leadership
======
* Quarterly Newsletter Producer, Association for Veterinary Informatics (AVI)
* Morris Animal Foundation's Animal Health Advisory Council (AHAC) Member (2023-2025)
* Collaborator, San Diego Zoo Wildlife Alliance

Skills
======
* Veterinary Medical
	* Small animal clinical practice and emergency care
	* Necropsy and comparative pathology microbiology
* Research
	* PCR/qPCR/gel electrophoresis
	* Aerobic microbiological culture and identification
	* High-throughput DNA extraction, Library Prepartation, and sequencing methods
	* Bioinformatics
* Computer
  * Advanced Python (Jupyter Lab), Beginner R (R Studio)
  * Qiita/Qiime2
  * GitHub
  * Microsoft Office Suite, Adobe Photoshop and Illustrator

Veterinary, Wildlife & Comparative Medicine Publications
======
  <ul>{% for post in site.publications %}{% if post.vet %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>

Additional Publications
======
  <ul>{% for post in site.publications %}{% unless post.vet %}
    {% include archive-single-cv.html %}
  {% endunless %}{% endfor %}</ul>

Veterinary & Animal Health Talks
======
  <ul>{% for post in site.talks %}{% if post.vet %}
    {% include archive-single-talk-cv.html %}
  {% endif %}{% endfor %}</ul>

Additional Talks
======
  <ul>{% for post in site.talks %}{% unless post.vet %}
    {% include archive-single-talk-cv.html %}
  {% endunless %}{% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Outreach
======
  <ul>{% for post in site.outreach %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional Associations
======
* American Veterinary Medical Association Member (2014-current)
* California Veterinary Medical Association Member (2016-current)
* Association for Veterinary Informatics Member (2021-current)
* American Society for Microbiology Member (2019-current)
* American Gastroenterology Association Member (2019-current)
