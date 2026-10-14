# Awesome-Digital-Chemotherapy

## Top Digital Chemotherapy Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Chemotherapy Prescribing, Dose Calculation & Oncology Data Management*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Chemotherapy**. These tools enable oncology teams to prescribe, calculate, and document chemotherapy regimens safely and consistently—reducing medication errors and standardizing care across clinical and low-resource settings.



**Examples** include iQemo, Flatiron Assist, ChemoCare, EpiSoft, OncoEMR, CenseoRx, Varian ARIA, Elekta MOSAIQ, IntellidoseTxM, and CureMD (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, AI-assisted prescribing, and open oncology data management—ideal for oncologists, clinical informaticists, and developers seeking transparent, vendor-independent chemotherapy platforms.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Oncology Information Systems (OIS) and digital chemotherapy market is estimated at approximately **$5.7 billion to $10.3 billion**, projected to grow at a CAGR of **7.5%–8.5%**. The sector exhibits a **concentrated, oligopolistic core** among enterprise giants (such as Siemens Healthineers/Varian, Elekta, and Roche/Flatiron) that control core hospital radiation and medical oncology systems, complemented by **moderate fragmentation** across specialized ambulatory CDS plugins, regional EHRs, and dosing regimen tools.

## SaaS/Hosted Platforms

| Platform | Company / Parent | Valuation / Revenue (Size Indicator) | Description & Focus | Starting Pricing | Free Tier / Trial Limits |
|:---|:---|:---|:---|:---|:---|
| **[IntellidoseTxM](https://www.intellidose.com/)** | Cencora (AmerisourceBergen) | ~$293.96B annual revenue | Chemotherapy dose management and infusion analytics platform optimizing protocol compliance, order tracking, and oncology drug cost control. | Contact vendor for custom quote (Enterprise pricing structured per infusion chair / practice site; IntrinsiQ acquired for $35M) | No free tier or self-service free trial; access requires a scheduled clinical demo and guided implementation. |
| **[OncoEMR](https://flatiron.com/oncoemr/)** | Flatiron Health (Roche Group) | $1.9B acquisition valuation | Cloud-based oncology-specific EHR supporting chemotherapy order entry, regimen management, clinical workflows, and real-world evidence. | Starts at ~$1,300–$1,400 per provider/month (plus one-time setup/implementation fees) | No free tier or self-service free trial; access provided via scheduled institutional live demonstrations. |
| **[Flatiron Assist](https://flatiron.com/)** | Flatiron Health (Roche Group) | $1.9B acquisition valuation | Clinical decision support platform embedded in OncoEMR offering NCCN-aligned chemotherapy regimen recommendations and trial matching. | Add-on module licensing to OncoEMR (integrated contract, starting per provider/clinic baseline) | No free tier or self-service free trial; demo access and workflow evaluation provided via Flatiron sales team. |
| **[Varian ARIA](https://www.varian.com/products/software/aria-oncology-information-system)** | Siemens Healthineers | $16.4B acquisition valuation (~$24B parent revenue) | Enterprise oncology information system unifying medical oncology, chemotherapy prescribing, and radiation therapy workflows. | Software modules start around ~$75,000 baseline deployment fee (scales based on concurrent user licenses and linac connectors) | No free tier or public free trial; access provided via scheduled product consultations and sandbox demonstrations. |
| **[Elekta MOSAIQ](https://www.elekta.com/products/software/mosaiq/)** | Elekta AB | ~$1.7B annual revenue (~SEK 18B) | Comprehensive oncology EHR & information system managing medical oncology, chemotherapy orders, pharmacy verification, and radiation. | Enterprise software licensing starting per server/database instance + annual maintenance (quote-based) | No free tier or public free trial; vendor-guided workflow demonstrations available upon request. |
| **[CenseoRx](https://www.censeohealth.com/)** | Signify Health (CVS Health) | $8.0B acquisition valuation by CVS | Clinical decision support platform with oncology treatment pathways, regimen analytics, and prior authorization management. | Enterprise contract pricing per covered lives / member population | No free tier or self-service free trial; access restricted to health plan and provider enterprise demonstrations. |
| **[ChemoCare](https://www.chemocare.com/)** | Cleveland Clinic Cancer Center | ~$14.5B annual system revenue | Comprehensive chemotherapy drug profiles, standard dosing references, regimen details, and adverse effect management database. | $0 (100% free open public access resource funded by Cleveland Clinic Cancer Center) | Free forever for all users globally with unlimited web queries and regimen searches. |
| **[CureMD](https://www.curemd.com/)** | CureMD Healthcare | ~$50M–$100M estimated revenue | Cloud-based oncology EHR offering chemotherapy regimen management, clinical charting, patient portals, and billing/RCM. | Starts at $295 per provider/month (EHR only) or $395 per provider/month (All-in-One EHR + Practice Management) | No free tier or free trial; access provided via scheduled live product walk-through and guided demo. |
| **[EpiSoft](https://www.episoft.com.au/)** | EpiSoft Pty Ltd | ~$10M–$20M estimated revenue | Specialty oncology information system featuring chemotherapy prescribing, chair management, and protocol tracking for ANZ markets. | Utilization-based SaaS priced per billable treatment visit (implementation budgeted around 3-year license fee) | No free tier or public trial; prospective clinics receive guided product sandbox trials upon consultation. |
| **[iQemo](https://www.iqemo.com/)** | iQ HealthTech (Altera Digital Health) | ~$5M–$15M estimated revenue | Electronic chemotherapy and SACT prescribing system with regimen templates and dose calculation designed for NHS Trusts. | Cloud SaaS subscription priced according to SACT patient volume / trust size (available via UK Crown Commercial G-Cloud framework) | No free tier or public trial; access is restricted to NHS/hospital staff via scheduled institutional pilot demos. |



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
