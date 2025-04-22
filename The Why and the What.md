# Build your own Detection Engineering Program
 Don't just write detections, build a program that takes you from 0 to 1 - low to high maturity, involving key players and decision makers, to ingest, process, understand and create measurable and repeatable detects that fits into an overall program for cyber defense

#  Proactive Detections Process

We are aiming to move from **ad-hoc querying** to a **tested, repeatable, measurable** process for detecting threats and plugging visibility gaps in our EDR solution — **Microsoft Defender for Endpoint**.

---

## 1. Introduction: The Opportunity with M365 Security Portal for Proactive Investigations

Establishing a robust detection process is crucial for proactively mitigating cyber threats. By leveraging the capabilities of Microsoft 365 Defender, we can build a mature, responsive detection engineering workflow.

---

## 2. Standardized Process for Detection Engineering

We will follow the guidelines outlined in **Detection Engineering Maturity Models (DEMMs)** to evolve our processes systematically.

### Key Benefits of Using a Maturity Model:
- Framework for visualizing growth
- Roadmap from ad-hoc → optimized
- Realistic and achievable development goals

> Referenced Model: [Elastic DEBMM](https://www.elastic.co/security-labs/elastic-releases-debmm)

---

### Detection Engineering Maturity Model Table (Currently only focused on going from Tier 0 to 1. There exist higher levels of maturity that we will address in amendments to this document in the future)

| Feature of Detection Process     | DEBMM Tier 0: Foundation         | DEBMM Tier 1: Basic               |
|----------------------------------|----------------------------------|-----------------------------------|
| Rule Development & Management    | Ad-hoc, unstructured, untested   | Systematic rule management        |
| Documentation                    | Minimal to none                  | Basic documentation               |
| Version Control                  | Absent                           | Introduced                        |
| Threat Landscape Review          | Rare or non-existent             | Regular reviews initiated         |
| Personnel Training               | Limited or none                  | Initial training provided         |

> ✅ **Good to Haves:** Essential in Tier 1, but optional at Tier 0.

---

## 3. 🎯 Prioritizing Detection Engineering Efforts with Limited Resources

We prioritize detection building as follows:

### 🔸 Risk-Based Approach
Focus on the **organization's most significant risks** — data sensitivity, business continuity, and compliance requirements.

### 🔸 Leverage Threat Intelligence
Use vendor blogs, industry reports, OSINT, and community sources to focus on **actively exploited threats**.

### 🔸 Protect High-Value Assets
Detect attacks targeting **executive accounts, customer data, critical systems**.

### 🔸 Start with Known Threats
Implement detections for **documented TTPs** aligned with known adversaries in your industry.

### 🔸 Iterative Expansion
Begin with **basic, high-fidelity detections** and evolve as KQL and Defender knowledge deepens.

---

## 4. 📁 Organizing KQL Queries for Long-Term Efficiency

As our KQL detection library grows, structure and versioning become critical:

### 🔖 Naming Conventions
Use consistent names:

SOURCES : 
