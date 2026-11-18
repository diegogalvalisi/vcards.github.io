---
title: European Civic Tech Protocol Residency @ Liminal Village
type: propuesta-de-proyecto
status: borrador
date: 2026-11-08
pais: Italia
aliases:
  - Protocol Residency
  - Residencia Civic Tech
tags:
  - civic-tech
  - deliberative-democracy
  - citizen-participation
  - open-government
  - free-software
  - data-sovereignty
---
 
# European Civic Tech Protocol Residency @ Liminal Village
 
*Concept note — draft for discussion · November 2026*
 
## 1. Executive summary
 
The European Civic Tech Protocol Residency is a proposed three-month, in-person co-creation programme hosted at Liminal Village in central Italy. It would bring together civic-tech developers, researchers, public-interest technologists, democratic-innovation practitioners, public administrations and open-source communities to build shared protocols, interoperability standards, reference implementations and reusable digital public goods for democratic participation.
 
The residency would run continuously for approximately 12 weeks. Participants would not necessarily stay for the full period: the model is intentionally flexible, with a small continuity team present throughout and other contributors joining for focused periods depending on the workstream. Subject to the funding instrument used, travel, accommodation, subsistence and programme costs would be covered for selected participants.
 
The central principle is simple: rather than creating another standalone civic-tech platform, the residency would help existing tools work together.
 
Possible outputs include:
 
- open standards for deliberation and participatory-process data;
- reference APIs and connectors between civic-tech platforms;
- an open workflow/orchestration layer for participatory processes;
- interoperability test suites and compliance profiles;
- federated identity, consent and provenance patterns;
- prototypes for a federated Democracy Data Space;
- integrations with public-administration systems and open-source collaboration environments;
- research comparing what works, what fails and under which institutional conditions;
- documentation, governance models and implementation guides.
 
## 2. Why Liminal Village
 
Liminal Village describes itself as an open-source innovation eco-tech hub and a co-living/co-creation space in central Italy, in the Marche region. Its existing model is unusually compatible with this proposal: it hosts temporary communities, collaborative "Hackalongs", workshops and long-form co-creation; it offers high-speed internet, private and shared rooms, caravans and tents, co-creation spaces and outdoor presentation facilities.
 
The residency would use this existing physical and social infrastructure as a European "protocol lab": a place where people who normally collaborate remotely can spend sustained time together designing, implementing and testing shared infrastructure.
 
**Liminal Village resources**
 
- Website: [liminalvillage.com](https://liminalvillage.com/)
- Documentation: [docs.liminalvillage.com](https://docs.liminalvillage.com/)
 
## 3. The problem
 
European civic-tech is rich but fragmented. Tools for participatory budgeting, citizen assemblies, deliberation, collective sensemaking, voting, consultation, AI-assisted facilitation and institutional feedback often operate in separate technical and organisational silos.
 
This creates several recurring problems:
 
- participants cannot easily move between tools or carry context with them;
- deliberations held in different places and at different times are difficult to connect;
- platforms use incompatible data models;
- public administrations receive outputs in inconsistent formats;
- researchers struggle to compare processes systematically;
- organisations risk vendor lock-in;
- innovations are repeatedly rebuilt rather than composed;
- the field lacks a shared experimentation environment where standards can be tested against real workflows.
 
The residency would therefore focus on infrastructure *between* tools rather than on replacing the tools themselves.
 
## 4. Core concept: from civic-tech tools to a composable democratic stack
 
The programme would explore a layered architecture.
 
| Layer                                 | Focus                 | What it covers                                                                                                                                                                                                                                                                                            |
| ------------------------------------- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1. Civic-tech applications**        | Existing tools        | Platforms for consultation, deliberation, citizen assemblies, sensemaking, participatory budgeting, discussion and voting.                                                                                                                                                                                |
| **2. Open deliberation protocols**    | Shared language       | Vocabularies, schemas and standards describing participants, proposals, arguments, deliberative stages, decisions, provenance, permissions and institutional responses.                                                                                                                                   |
| **3. Workflow orchestration**         | Composition           | A modular "n8n for deliberation": a visual or declarative way to compose democratic workflows across multiple tools through APIs. A process could begin in Decidim, move to an AI-assisted sensemaking tool, continue in an online assembly, and return to an institutional platform for formal response. |
| **4. Federated Democracy Data Space** | Shared infrastructure | A federated layer that keeps processes and results discoverable, interoperable and analysable across organisations, territories and time, while preserving governance, consent, provenance and access controls.                                                                                           |
| **5. Institutional interfaces**       | Uptake                | Connectors and protocols through which public administrations, political organisations, universities and civil-society organisations can receive, respond to and reuse participatory outputs.                                                                                                             |
 
## 5. Proposed residency format
 
### Duration
 
Approximately 12 weeks.
 
### Participation model
 
A rolling residency rather than a fixed three-month retreat. A small core team would remain for continuity; other residents could join for one or more focused periods. For funding instruments based on formal secondments or mobility, participant dates would be pre-agreed and documented even if the overall residency remains flexible.
 
### Indicative participant mix
 
- civic-tech developers and maintainers;
- researchers in democratic innovation, HCI, political science, public administration and data governance;
- open-standard and semantic-web specialists;
- facilitators and citizen-assembly practitioners;
- representatives of public administrations;
- civil-society organisations;
- open-source community builders;
- selected political-organisation practitioners where relevant.
 
### Working rhythm
 
- weekly protocol/design sessions;
- implementation sprints;
- interoperability "plugfests";
- real-user testing;
- research seminars;
- public demos;
- documentation days;
- governance and standards workshops.
 
## 6. Indicative workstreams
 
### A. Deliberation Data Standard
 
Develop or align an open semantic model for participatory and deliberative processes, including provenance, decisions, arguments, consent and feedback.
 
### B. Civic-Tech Workflow Engine
 
Build a modular orchestration layer connecting APIs from different civic-tech tools.
 
### C. Interoperability Connectors
 
Create reference integrations between selected tools and publish reusable connectors.
 
### D. Democracy Data Space
 
Prototype a federated architecture for connecting participatory processes across institutions, territories and time.
 
### E. Identity, Consent and Data Governance
 
Develop privacy-preserving patterns for identity, permissions, pseudonymisation, consent and data portability consistent with GDPR and European data-governance principles.
 
### F. Public Administration Interface
 
Test how participatory outputs can enter real administrative workflows and how institutions can provide traceable responses.
 
### G. Research and Evaluation
 
Compare technical and democratic performance: inclusiveness, usability, deliberative quality, institutional uptake, interoperability cost, governance risks and sustainability.
 
### H. Open-Source Sustainability and Standards
 
Define governance, licensing, maintenance, standardisation pathways and stewardship models so that outputs remain public digital commons after the residency.
 
## 7. Potential participants and ecosystem
 
The residency could build on existing relationships across the Democracy Innovators ecosystem and invite a deliberately mixed cohort rather than a single-vendor consortium.
 
Potential profiles include:
 
- **civic-tech platforms and implementers** such as Decidim/Open Source Politics, Go Vocal, CitizenOS, Citizens Foundation, Agora Citizen Network, Harmonica, Dembrane and deliberAIde;
- **interoperability and data-space actors** such as Startin'blox, Crown-shy, semantic-web/knowledge-graph researchers and Metagov;
- **public-sector integration actors** such as Maggioli and other PA software providers;
- **academic partners** working on democratic innovation, digital politics, HCI, public administration, data governance and interoperability;
- **public administrations** willing to provide real use cases;
- **open-source and standardisation communities**.
 
Participation should remain non-exclusive: the objective is to test interoperability across heterogeneous tools, not to privilege one vendor or architecture.
 
## 8. Outputs after three months
 
The residency should end with concrete, public deliverables rather than only networking.
 
Minimum target outputs:
 
- 1 shared technical architecture;
- 1 open deliberation/interoperability specification or major revision of an existing one;
- 3–6 working connectors or reference integrations;
- 1 workflow-orchestration prototype;
- 1 federated Democracy Data Space demonstrator;
- 2–4 real process demonstrations;
- interoperability test documentation;
- a research/evaluation report;
- an open-source governance and sustainability plan;
- a roadmap toward formal standardisation and future EU projects.
 
## 9. Funding strategy
 
The residency is more likely to be funded successfully as a modular programme than through one single grant. Different instruments can finance different layers without double funding.
 
| Instrument                                        | Role in the stack                                    | Scale                                   | Call / deadline                                                       |
| ------------------------------------------------- | ---------------------------------------------------- | --------------------------------------- | --------------------------------------------------------------------- |
| **MSCA Staff Exchanges 2027**                     | Core research collaboration and staff mobility       | \~€95 million call budget               | HORIZON-MSCA-2027-SE-01 · opens 15 Dec 2026 · deadline mid-April 2027 |
| **Open Internet Stack — Restack (2nd open call)** | Protocols and software components                    | €5,000–€50,000 per project              | 3 Jan 2027, 12:00 Brussels time                                       |
| **HORIZON-CL4-2027-04-HUMAN-07**                  | International digital standardisation                | €7 million, one project expected        | Opens 17 Nov 2026 · deadline 18 Mar 2027                              |
| **European Startup and Scaleup Hubs pilot**       | Large-scale route, only as a node in a wider network | €40 million, \~2 networks of 10–18 hubs | HORIZON-EIE-2027-02-CONNECT-01 · 5 Jan 2027, 17:00 CET                |
| **Erasmus+ Cooperation Partnerships**             | Training and peer-learning layer                     | Per programme rules                     | See current programme guide                                           |
 
### A. MSCA Staff Exchanges 2027 — strongest fit for the residency/mobility model
 
**Why it fits.** MSCA Staff Exchanges finances international, inter-sectoral and interdisciplinary research and innovation collaboration through temporary staff exchanges. A three-month stay is directly compatible with the action because secondments can last from short periods up to 12 months. It can combine universities, companies, NGOs and other socio-economic actors.
 
**Key requirements**
 
- at least 3 independent legal entities in 3 different countries;
- at least 2 entities must be in different EU Member States or Horizon Europe Associated Countries;
- the consortium must include both academic and non-academic organisations;
- participants must be staff of participating organisations and are selected by their sending organisations;
- after the secondment, participants return to their sending organisation to maximise knowledge transfer;
- the sending organisation continues paying salary; MSCA provides mobility/top-up and institutional unit contributions.
 
**Important implication.** MSCA is an excellent fit if the residency is built around staff from partner organisations. It is not a completely open fellowship for unaffiliated individuals. Independent contributors would need another funding mechanism or a formal relationship with an eligible sending organisation.
 
**Timing**
 
- Call: HORIZON-MSCA-2027-SE-01
- Opening: 15 December 2026
- Deadline: official Commission pages currently show slightly different dates in mid-April 2027 — the REA page lists 13 April 2027, while the dedicated MSCA page still shows 15 April as tentative. Confirm when the call formally opens.
- Indicative call budget: about €95 million.
 
**Official source:** [MSCA Staff Exchanges — REA](https://rea.ec.europa.eu/funding-and-grants/horizon-europe-marie-sklodowska-curie-actions/msca-staff-exchanges_en)
 
**Strategic use.** Use MSCA to finance the research collaboration, staff mobility, protocol co-development, training, networking and knowledge transfer underpinning the residency.
 
### B. Open Internet Stack — Restack, 2nd Open Call — strongest short-term companion funding for protocols/software
 
**Why it fits.** Restack explicitly supports free/open-source software and hardware, open standards, open data, open science and operational internet commons. Grants are small enough to fund specific protocol or software modules quickly.
 
**Funding.** €5,000–€50,000 per project, with potential follow-on scaling for projects showing strong potential.
 
**Deadline.** 3 January 2027 at 12:00 Brussels time.
 
**Official sources**
 
- [NGI open calls](https://ngi.eu/opencalls/)
- [NLnet / Restack](https://nlnet.nl/restack/)
 
**Strategic use.** Do not use Restack to finance the whole residency. Use it to fund concrete components generated by the residency, for example:
 
- deliberation standard;
- workflow engine;
- federation protocol;
- interoperability connector kit;
- consent/provenance layer.
 
Several technically distinct teams could potentially pursue separate eligible work packages, subject to the call rules and avoidance of double funding.
 
### C. HORIZON-CL4-2027-04-HUMAN-07 — International Digital Standardisation
 
**Why it fits.** This €7 million Coordination and Support Action is designed to strengthen European participation in international digital standardisation, especially involving SMEs, R\&I organisations, open-source communities, academia and societal stakeholders. It can support international standards work, expert participation, workshops, education and standardisation landscape/gap analysis.
 
**Timing**
 
- Opening: 17 November 2026
- Deadline: 18 March 2027
 
**Scale.** Indicative budget of €7 million, with one project expected.
 
**Official source:** [EU Funding & Tenders Portal](https://ec.europa.eu/info/funding-tenders/opportunities/portal/)
 
**Strategic use.** The residency could become one European "standards laboratory" or recurring workshop within a much larger consortium. This is not suitable as a stand-alone Liminal Village application. It becomes relevant if the deliberation/interoperability protocol has a credible pathway toward W3C, ISO/IEC, OASIS or another recognised standards ecosystem.
 
### D. European Startup and Scaleup Hubs pilot — potential large-scale route, but only as part of a major network
 
**Call.** HORIZON-EIE-2027-02-CONNECT-01.
 
**Why it is relevant.** The action funds networks of European innovation hubs and explicitly supports shared infrastructures, short-term mobility, accelerators lasting several months, startup bootcamps, hackathons and cross-border access to research and innovation services.
 
**Deadline.** 5 January 2027, 17:00 CET.
 
**Scale.** €40 million total budget; the Commission expects approximately two networks, each involving around 10–18 startup/scaleup hubs.
 
**Official source:** [European Startup and Scaleup Hubs pilot — EISMEA](https://eismea.ec.europa.eu/funding-opportunities/calls-proposals/european-startup-and-scaleup-hubs-pilot-horizon-eie-2027-02-connect-01_en)
 
**Limitation.** This call is focused strongly on deep-tech startup scaling and mature innovation hubs. A civic-tech residency alone would not satisfy the scope. Liminal Village could instead participate as a specialised residency node inside a much larger hub network, provided the consortium can demonstrate the required startup, investment and scaling track record.
 
### E. Erasmus+ Cooperation Partnerships — good alternative if framed as training/peer learning rather than R\&D
 
**Why it may fit.** Cooperation Partnerships support transnational cooperation, peer learning, development of innovative practices and learning/training activities. Digital transformation and civic engagement/participation are established Erasmus+ priorities.
 
**General requirements under the current programme rules**
 
- minimum 3 organisations from 3 different EU Member States or associated countries;
- coordinator generally must have been legally established for at least 2 years;
- projects last 12–36 months;
- transnational learning/training activities can be included when justified by the project;
- activities normally take place in countries of participating organisations.
 
**Current programme guide:** [Erasmus+ Cooperation Partnerships](https://erasmus-plus.ec.europa.eu/programme-guide/part-b/key-action-2/cooperation-partnerships)
 
**Strategic use.** Potentially fund a recurring Civic Tech Academy/Residency focused on skills, peer learning, open-source governance, democratic participation and capacity building. It is less appropriate if the dominant purpose is software R\&D.
 
## 10. Recommended funding bundle
 
The strongest architecture is a stack, not a single grant:
 
- **MSCA Staff Exchanges** → pays for structured international staff mobility, research collaboration and knowledge exchange.
- **Restack / Open Internet Stack** → finances individual FOSS protocols and infrastructure components.
- **Horizon Standardisation** → provides a future route for formal standardisation, international engagement and standards governance if the protocol matures sufficiently.
- **Erasmus+** → can support a training/academy layer and recurring peer-learning cohorts.
- **Horizon Democracy / other larger R\&I projects** → can use the residency as an intensive development and integration environment for specific Democracy Data Space, civic-tech interoperability and participatory-governance work packages.
 
This creates a funding stack rather than forcing one grant to pay for every aspect.
 
## 11. Funding principle: "all paid", but realistically structured
 
The intended participant experience is that selected residents do not personally bear the cost of participation. Funding should aim to cover:
 
- accommodation;
- meals/subsistence;
- travel;
- programme infrastructure;
- technical resources;
- facilitation;
- accessibility needs;
- where the funding scheme allows, personnel or fellowship costs.
 
However, the funding mechanism matters:
 
- **MSCA** normally assumes the sending organisation continues paying salary and the EU contribution adds mobility/top-up and institutional support;
- **Restack** pays R\&D work, not a general residential programme;
- **Erasmus+** funds project activities and mobility according to its programme rules;
- **Horizon collaborative projects** can budget residency activities when they are necessary and proportionate to the work plan.
 
Therefore "fully funded residency" should be treated as the design objective, with the exact cost coverage depending on the combination of grants.
 
## 12. Indicative governance
 
**Programme convener.** A European civic-tech/democracy organisation coordinates the programme concept, partnerships and funding portfolio.
 
**Residency host.** Liminal Village provides the physical environment and local operational support.
 
**Scientific board.** Researchers ensure methodological quality, evaluation and publication.
 
**Technical council.** Open-source maintainers and protocol specialists decide technical roadmaps through transparent governance.
 
**Public-interest and ethics board.** Civil-society, privacy, accessibility and public-sector representatives oversee rights, data governance and public value.
 
**Resident teams.** Small cross-organisational groups work on defined outputs with public repositories and milestones.
 
## 13. Immediate next steps
 
1. Confirm Liminal Village's interest, indicative hosting costs, available periods and maximum practical capacity.
2. Decide whether the first edition is primarily an MSCA staff-exchange research programme, an open-source protocol lab, or a hybrid.
3. Form a founding group of 5–8 organisations across at least 3–4 countries, including universities and non-academic civic-tech actors.
4. Select 3–5 protocol/infrastructure challenges narrow enough to be completed during the residency.
5. Identify which outputs can be submitted immediately to Restack before 3 January 2027.
6. Begin an MSCA Staff Exchanges consortium design before the call opens on 15 December 2026.
7. Explore participation in the international digital standardisation consortium opening on 17 November 2026.
8. Prepare a preliminary 12-week programme, budget per resident-week and host cost model.
9. Define open-source, IP, data-governance and conflict-of-interest rules before selecting technology partners.
10. Build the first residency as a demonstrator that can later become a recurring European Civic Tech Protocol Residency.
 
## 14. One-sentence proposition
 
> A three-month European residency at Liminal Village where civic-tech developers, researchers, public institutions and democratic-innovation practitioners live and work together to build the open protocols and interoperable infrastructure that allow democratic technologies to function as an ecosystem rather than as isolated platforms.
 
## Sources consulted
 
**Liminal Village**
 
- <https://liminalvillage.com/>
- <https://docs.liminalvillage.com/>
 
**MSCA Staff Exchanges**
 
- <https://rea.ec.europa.eu/funding-and-grants/horizon-europe-marie-sklodowska-curie-actions/msca-staff-exchanges\_en>
- <https://marie-sklodowska-curie-actions.ec.europa.eu/funding/msca-staff-exchanges-2027>
 
**Open Internet Stack / Restack**
 
- <https://ngi.eu/opencalls/>
- <https://nlnet.nl/restack/>
 
**European Startup and Scaleup Hubs**
 
- <https://eismea.ec.europa.eu/funding-opportunities/calls-proposals/european-startup-and-scaleup-hubs-pilot-horizon-eie-2027-02-connect-01\_en>
 
**Erasmus+ Cooperation Partnerships**
 
- <https://erasmus-plus.ec.europa.eu/programme-guide/part-b/key-action-2/cooperation-partnerships>
 
**Horizon Europe Digital / Standardisation**
 
- <https://ec.europa.eu/info/funding-tenders/opportunities/portal/>
 