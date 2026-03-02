# technical-synthesis-engine

# 🔍 Technical Synthesis Engine: High-Context Policy Audit

### 🚀 Overview
A high-performance AI workflow designed to audit massive (200+ page) technical and legal documents with 100% citation accuracy. 

### 🛡️ The Problem
Traditional RAG (Retrieval-Augmented Generation) often suffers from "Lost in the Middle" syndrome, where AI misses details in the center of long documents. This engine utilizes Gemini 1.5 Pro's **2-million-token context window** to maintain full visibility across the entire dataset.

### 🛠️ Tech Stack
* **Engine:** Google AI Studio (Gemini 3.1 Pro)
* **Logic:** Zero-Shot System Instruction with Temperature 0.0
* **Input:** [e.g., EU AI Act / AWS Security Framework]

### 📊 Key Deliverables
1. **Automated Risk Matrix:** A table of all financial penalties and compliance deadlines.
2. **Citation Verification:** Every claim includes a specific Page Number and Section Title.
3. **Cross-Document Synthesis:** Linked Section 4 (Data Privacy) directly to Section 12 (Enforcement).

---
*Developed as part of an AI Productivity Portfolio for High-Ticket Consulting.*

URL to the prompt and model response for reference :-
https://aistudio.google.com/app/prompts?state=%7B%22ids%22:%5B%221N8nPgWj13UhAHCYG-2GV-8zxSfhQPa4y%22%5D,%22action%22:%22open%22,%22userId%22:%22116080054008612041388%22,%22resourceKeys%22:%7B%7D%7D&usp=sharing
