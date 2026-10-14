# Awesome-Digital-Chemotherapy

# Top Digital Chemotherapy Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Chemotherapy Prescribing, Dose Calculation & Oncology Data Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Chemotherapy**. These tools enable oncology teams to prescribe, calculate, and document chemotherapy regimens safely and consistently—reducing medication errors and standardizing care across clinical and low-resource settings.

**Examples** include iQemo, Flatiron Assist, ChemoCare, EpiSoft, OncoEMR, CenseoRx, Varian ARIA, Elekta MOSAIQ, IntellidoseTxM, and CureMD (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, AI-assisted prescribing, and open oncology data management—ideal for oncologists, clinical informaticists, and developers seeking transparent, vendor-independent chemotherapy platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[iQemo](https://www.iqemo.com/)**
  Electronic chemotherapy prescribing system with integrated dose calculation, regimen templates, and clinical decision support. Designed for UK NHS and international oncology workflows.

- **[Flatiron Assist](https://flatiron.com/)**
  Clinical decision support integrated with OncoEMR. Provides evidence-based regimen recommendations, clinical trial matching, and real-world evidence insights.

- **[ChemoCare](https://www.chemocare.com/)**
  Chemotherapy regimen database and patient information resource maintained by the Cleveland Clinic. Provides drug profiles, regimen details, and side effect management guidance.

- **[EpiSoft](https://www.episoft.com.au/)**
  Oncology information system with chemotherapy prescribing, day unit management, and clinical documentation for Australian and New Zealand markets.

- **[OncoEMR](https://flatiron.com/oncoemr/)**
  Cloud-based oncology EHR from Flatiron Health. Features chemotherapy ordering, regimen management, clinical workflow optimization, and integration with real-world evidence.

- **[CenseoRx](https://www.censeohealth.com/)**
  Oncology clinical decision support platform with treatment pathways, prior authorization automation, and regimen analytics.

- **[Varian ARIA](https://www.varian.com/products/software/aria-oncology-information-system)**
  Comprehensive oncology information system integrating medical oncology, radiation oncology, and patient management. Features chemotherapy prescribing, scheduling, and treatment documentation.

- **[Elekta MOSAIQ](https://www.elekta.com/products/software/mosaiq/)**
  Oncology information system with chemotherapy management, workflow automation, and clinical documentation. Integrates with Elekta radiotherapy systems.

- **[IntellidoseTxM](https://www.intellidose.com/)**
  Chemotherapy dose management and analytics platform. Focuses on dose accuracy, protocol compliance, and cost management.

- **[CureMD](https://www.curemd.com/)**
  Cloud-based EHR with oncology-specific modules including chemotherapy management, patient portals, and billing.

## Open-Source GitHub Projects

- **[ChemoThon 3.0](https://www.sciencedirect.com/science/article/pii/S0923753425025736)**  
  Open-source, AI-assisted chemotherapy prescribing platform for clinical and educational use (license varies). **The most directly applicable open-source chemotherapy prescribing tool available.** Evolved from a Python script to a full browser-based web application using Streamlit, with development assisted by ChatGPT v4/v4o. **67 curated regimens** across breast (12), colorectal (14), gastrointestinal (16), gynecological (6), and immunotherapy (19) cancers. Supports classical cytotoxic agents, targeted therapies, and immunotherapy with appropriate dose adjustments. Follows standard dose-calculation methods (BSA, weight, or fixed dosing) and emulates real-world prescribing steps. Cancer-type-based regimen selection with automated dose generation. **Any oncologist can adapt or extend the platform for local use**—open-source structure lowers technical barriers to localized regimen support. English version freely accessible .

- **[Caisis](https://github.com/Caisis/Caisis)**  
  Open-source cancer data management system (GPL) designed to bridge the gap between research and clinical practice. **The most mature open-source oncology data platform**, started in 2002 at Memorial Sloan-Kettering Cancer Center to replace urology department database, later expanded to all cancer types. Features patient history capture, clinical data management, tumor banking, protocol management, project tracking, and patient education modules. Web-based with ASP.NET/C# and Microsoft SQL Server. HIPAA-compliant security designed for deployment outside institutional firewalls. **Used by institutions worldwide** with significant improvements in publishing higher quality research in less time. Version 6.0 with enhanced e-forms. **Zero software investment** with access to source code and community collaboration .

- **[OpenMRS Chemotherapy Module](https://pubmed.ncbi.nlm.nih.gov/31438001/)**  
  Open-source oncology EMR functionality developed within OpenMRS for low-resource settings (Mozilla Public License). Work-in-progress from 2019 describing chemotherapy prescription and documentation functionality developed with cancer care providers from low- and middle-income countries (LMICs). Followed rapid application development approach to elicit and prioritize requirements. **Designed for safe and standardized cancer care in resource-constrained environments** where commercial oncology systems are unaffordable. Integrates with OpenMRS platform already deployed in many LMIC health facilities .

- **[QATrack+](https://github.com/qatrackplus/qatrack)**  
  Fully configurable, free, and open-source (MIT/Apache-2.0) web application for managing QA data for radiation therapy and medical imaging equipment. **The most actively maintained open-source medical physics QA platform.** Features QA/QC tracking, break-fix/preventative maintenance logging, and full quality management for radiation therapy facilities. Django-based with 3,117 commits and active community support. Goal: provide a tool any site can rely upon without vendor lock-in. Funded by Ottawa Hospital Cancer Centre and Canadian Nuclear Safety Commission. **Critical infrastructure for chemotherapy-adjacent quality assurance** .

- **[Unified Oncology Treatment Database](https://zenodo.org/records/22181331)**  
  Reproducible multisource database harmonizing oncology drugs, drug synonyms, regimens, regimen synonyms, condition-regimen associations, and clinical-trial intervention names (CC BY-NC-SA 4.0 for data, MIT for code). From Oak Ridge National Laboratory and National Cancer Institute. Includes **11 production CSV tables**, implementation code, source manifests, RxNorm mapping audits, and QA reports. Incorporates HemOncKB release (largest freely available wiki of anticancer regimens) and DrugBank Vocabulary Open Data. **The most comprehensive open oncology terminology database available** for building regimen systems .

- **[dicompyler](https://github.com/dicompyler/dicompyler)**  
  Extensible radiation therapy research platform and viewer for DICOM and DICOM RT (BSD license). Features import of CT/PET/MRI images, RT structure sets, RT dose and RT plan files. Plugin architecture with 2D image viewer, DVH viewer, DICOM tree viewer, and patient anonymizer. **The most widely used open-source DICOM-RT visualization platform** for radiation oncology research .

- **[matRad](https://github.com/e0404/matRad)**  
  Open-source radiation treatment planning system in MATLAB (license varies). Features Monte Carlo dose calculation, robust/4D optimization, biological modeling, DICOM import/export, and experimental brachytherapy module. Funded by German Research Foundation, German Cancer Aid, and German Federal Ministry of Education and Research. **The most comprehensive open-source treatment planning research platform** .

- **[OpenTPS](https://www.opentps.org/)**  
  Open-source treatment planning system for research and innovation (license varies). Features Monte Carlo dose calculation (MCsquare), plan optimization with multiple solvers (LBFGS, FISTA, linear programming), DVH evaluation, and robustness assessment. Initially built for proton therapy research with IMPT delivery, expanding to IMRT/VMAT. **The most modern open-source treatment planning platform** for research .

### Additional Strong Open-Source Options

- **[CanReg5](https://www.iarc.who.int/)**: Open-source cancer registry software from IARC for data entry, quality control, consistency checks, and analysis. **The standard open-source platform for population-based cancer registries** in many countries. IARC and HISP Centre collaborating to integrate CanReg5 with DHIS2 for national health information systems .
- **[DHIS2 Cancer Module](https://dhis2.org/)**: Free open-source platform for cancer data collection, validation, and analysis. Deployed in Jamaica for national cancer registry, replacing paper-based reporting. Aligned with IARC CanReg5 requirements for interoperability .
- **[OpenClinica](https://www.openclinica.com/)**: Open-source clinical data management platform (free tier available) suitable for oncology clinical trials and research data collection .
- Community **n8n** workflows for regimen data synchronization and clinical alert routing.

**Frameworks for building custom systems**: Combine **ChemoThon 3.0** for chemotherapy prescribing and dose calculation with **Caisis** for oncology data management, **Unified Oncology Treatment Database** for regimen terminology, **QATrack+** for quality assurance, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade digital chemotherapy platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Digital chemotherapy systems handling patient data and medication orders must comply with HIPAA, GDPR, and clinical safety regulations. All prescribing decisions require qualified oncologist oversight.
- **Open-source digital chemotherapy is emerging, not mature.** ChemoThon 3.0 provides AI-assisted prescribing for 67 regimens with localized adaptation potential . Caisis provides comprehensive oncology data management but is not a prescribing system . OpenMRS chemotherapy module is work-in-progress for low-resource settings . **No open-source platform provides the end-to-end clinical chemotherapy system of Varian ARIA or Elekta MOSAIQ.** Integration work is required.
- **AI-assisted prescribing requires clinician validation.** ChemoThon 3.0 was developed with ChatGPT assistance but emphasizes "clinician-led digital tool development" . All AI-generated dose calculations must be verified by qualified oncology professionals before clinical use.
- **Open-source oncology data management is mature.** Caisis has been used since 2002 at institutions worldwide . QATrack+ is actively maintained with community support and funding from Canadian Nuclear Safety Commission . These are production-grade platforms.
- Self-hosted open-source solutions require proper security hardening, clinical validation, and ongoing maintenance. Chemotherapy data is safety-critical—access controls, audit trails, and integration with pharmacy systems are essential.

---

**Made for oncologists, clinical informaticists, oncology pharmacists, and developers building transparent digital chemotherapy solutions.**  
Let's make Digital Chemotherapy more open, data-driven, and safe.
