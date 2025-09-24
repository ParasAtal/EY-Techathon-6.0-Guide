
## 📚 Table of Contents
- [Problem Statement](#problem-statement)
- [Existing Tools / Research & How They Compare](#existing-tools--research--how-they-compare)
- [Gaps & Opportunities](#gaps--opportunities)
- [Deliverables for Techathon](#deliverables-for-techathon)
- [Suggested Tools / Integration Resources](#suggested-tools--integration-resources)

---

## 🧾 Problem Statement

The project focuses on automating the B2B RFP response process for a large industrial products manufacturer operating across FMCG, wires, and cables. The objective is to increase the number of RFP qualifications and responses while reducing bottlenecks in the process.

The current workflow is entirely manual:

- Sales Team manually identifies RFPs from various sources.
- Technical Team matches RFP requirements with OEM product SKUs.
- Pricing Team estimates product prices and additional testing costs.
- Sales Team consolidates inputs and submits the RFP response.

This project uses an **Agentic AI approach** to orchestrate multiple agents:

- **Sales Agent** identifies RFPs due in the next three months and summarizes requirements.
- **Technical Agent** maps RFP product requirements to the closest OEM SKUs.
- **Pricing Agent** assigns unit prices and test costs based on predefined tables.
- **Master Agent** consolidates outputs and produces the final RFP response.

The goal is to automate end-to-end RFP processing and improve the timeliness and quality of submissions.

---

## 🔧 Existing Tools / Research & How They Compare

| **Name / Project** | **What It Does** | **Overlap with Project** | **Limitations / Gaps** | **Resource Link** |
|--------------------|-----------------|-------------------------|------------------------|-----------------|
| **RFP Automation Tools** | Automates RFP discovery and basic response generation | Supports Sales Agent functionality | Commercial, limited customization for multi-agent orchestration | [RFPIO](https://www.rfpio.com/) |
| **Intelligent Document Processing** | Extracts structured data from documents using NLP | Supports requirement extraction for Technical Agent | Requires custom training for product specs | [ABBYY FlexiCapture](https://www.abbyy.com/flexicapture/) |
| **AI-Powered B2B Sales Automation** | Automates lead identification and prioritization | Supports Sales Agent in scanning URLs and identifying RFPs | Limited to lead generation; not end-to-end RFP workflow | [Salesforce Einstein](https://www.salesforce.com/products/einstein/overview/) |
| **Product Specification Matching Tools** | Matches product datasheets to required specs | Supports Technical Agent in spec match scoring | Requires structured product datasheets | [DataRobot Docs](https://www.datarobot.com/platform/documentation/) |

---

## 🧭 Gaps & Opportunities

- Automating the complete RFP orchestration reduces manual handoffs and turnaround time.  
- AI-based spec matching ensures faster and more accurate product recommendations.  
- Pricing automation speeds up response consolidation.  
- The system scales to handle multiple RFPs simultaneously.  

---

## 🎯 Deliverables for Techathon

- **RFP Identification:** Sales Agent scans URLs to identify upcoming RFPs.  
- **Technical Matching:** Technical Agent recommends top OEM SKUs with spec match metrics.  
- **Pricing Automation:** Pricing Agent assigns prices and calculates test costs.  
- **Consolidated Response:** Master Agent generates the final RFP response.  
- **Demonstration:** A live or recorded video (max 4 minutes) showcasing end-to-end workflow and agent orchestration.  

---

## 🧪 Suggested Tools / Integration Resources

| **Tool / Resource** | **Purpose** | **Link** |
|--------------------|------------|---------|
| **BeautifulSoup / Selenium** | Scrape RFPs from URLs | [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) / [Selenium](https://www.selenium.dev/) |
| **spaCy / NLTK** | NLP for parsing RFP text and extracting product specs | [spaCy](https://spacy.io/) / [NLTK](https://www.nltk.org/) |
| **Pandas / NumPy** | Tabular data processing | [Pandas](https://pandas.pydata.org/) / [NumPy](https://numpy.org/) |
| **Scikit-learn** | Spec matching and recommendation models | [Scikit-learn](https://scikit-learn.org/stable/) |
| **Streamlit / Dash** | Build dashboards for workflow visualization | [Streamlit](https://streamlit.io/) / [Dash](https://dash.plotly.com/) |
| **Google Sheets API / Excel** | Manage pricing and product tables | [Google Sheets API](https://developers.google.com/sheets/api) |
| **GitHub / Git** | Version control | [GitHub](https://github.com/) |

---


