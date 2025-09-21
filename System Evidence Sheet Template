# System Evidence Sheet Template

## 1. System Overview
- **Name:**  
- **Sector:** (Healthcare / Finance)  
- **Provider / Organization:**  
- **Deployment status:** (Pilot / Production / Research)  
- **Reference link(s):**  

---

## 2. Evidence Matrix (Facts only)
*(Fill only what is explicitly stated in papers, blogs, or official docs. If unknown → `Unclear`)*  

| Category        | Evidence Value (from source) | Source Reference |
|-----------------|-------------------------------|-----------------|
| Pipeline Type   |                               |                 |
| Latency         |                               |                 |
| Compliance Noted|                               |                 |
| Architecture    |                               |                 |
| Tool Stack      |                               |                 |
| Deployment      |                               |                 |
| Scalability     |                               |                 |

---

## 3. Assumption Matrix (if evidence is unclear)
*(Fill based on sector baseline rules; cite Assumption Log IDs like A1, A2…)*  

| Category        | Assumed Value                 | Assumption IDs | Justification |
|-----------------|-------------------------------|----------------|---------------|
| Pipeline Type   |                               |                |               |
| Latency         |                               |                |               |
| Compliance      |                               |                |               |
| Architecture    |                               |                |               |
| Tool Stack      |                               |                |               |
| Deployment      |                               |                |               |
| Scalability     |                               |                |               |

---

## 4. Notes
- **Transparency score:** (e.g., how many fields are “Unclear” in evidence)  
- **Special features / context:** (e.g., integration with EHR, regulatory environment)  
- **Limitations in available data:**  

---

## 5. Sources
- [1] DOI / URL – Peer-reviewed or official doc  
- [2] Blog / press release 

-----------------------------------------------------------------------------------------

##Example template for reference

## 1. System Overview
- **Name:** Nuance DAX Copilot (Epic EHR integration)  
- **Sector:** Healthcare  
- **Provider / Organization:** Nuance (Microsoft subsidiary) + Epic  
- **Deployment status:** Production rollout (used by US hospitals)  
- **Reference link(s):**  
  - [Nuance press release](https://news.nuance.com/2023-06-27-Nuance-and-Epic-Expand-Ambient-Documentation-Integration-Across-the-Clinical-Experience-with-DAX-Express-for-Epic)  
  - Haberle et al., 2024. *The impact of Nuance DAX ambient listening AI documentation: a cohort study.* JAMIA. https://doi.org/10.1093/jamia/ocae022  

---

## 2. Evidence Matrix (Facts only)

| Category        | Evidence Value (from source)                                    | Source Reference |
|-----------------|------------------------------------------------------------------|-----------------|
| Pipeline Type   | Unclear                                                          | [Press Release] |
| Latency         | Unclear                                                          | [Press Release] |
| Compliance Noted| “Secure integration with Azure OpenAI” (HIPAA-aligned)           | [Press Release] |
| Architecture    | Unclear                                                          |                 |
| Tool Stack      | Nuance DAX Copilot + Azure OpenAI + Epic integration             | [Press Release] |
| Deployment      | Not explicitly stated (likely hospital + cloud)                  | [Press Release] |
| Scalability     | Unclear                                                          |                 |

---

## 3. Assumption Matrix (if evidence is unclear)

| Category        | Assumed Value                                | Assumption IDs | Justification |
|-----------------|----------------------------------------------|----------------|---------------|
| Pipeline Type   | Streaming                                    | A3             | Live scribing requires continuous data feed |
| Latency         | Real-time                                    | A3             | Doctors need immediate note-taking |
| Compliance      | Encryption + RBAC + Audit logging + Consent  | A1, A2         | HIPAA/FHIR security baselines |
| Architecture    | Microservices                                | A5             | Modern EHR-AI integrations follow this |
| Tool Stack      | Audio capture + transcription + FHIR APIs    | A1, A3, A5     | Typical for voice-EHR integration |
| Deployment      | Hybrid (hospital EHR on-prem + Azure cloud)  | A4             | Cloud AI + on-prem EHR pattern |
| Scalability     | High                                         | A5             | Microservices scaling assumed |

---

## 4. Notes
- **Transparency score:** 5/7 fields unclear in evidence → High reliance on assumptions.  
- **Special features / context:** Designed for ambient scribing and reducing clinician burden; tightly integrated with Epic workflows.  
- **Limitations in available data:** No technical documentation of pipelines or latency published by Nuance/Epic.  

---

## 5. Sources
- [1] Haberle, T. *et al.*, 2024. *The impact of Nuance DAX ambient listening AI documentation: a cohort study.* JAMIA. https://doi.org/10.1093/jamia/ocae022  
- [2] Nuance + Epic Press Release, 2023. https://news.nuance.com/2023-06-27-Nuance-and-Epic-Expand-Ambient-Documentation-Integration-Across-the-Clinical-Experience-with-DAX-Express-for-Epic
