# Multi-Agent Supplier Evaluation and Procurement System

An AI-assisted procurement workflow built with **n8n** to help evaluate supplier quotations, review supplier performance, identify purchasing risks, and support informed procurement decisions.

## 📌 Project Overview

This project simulates a laptop procurement scenario for **Everest Manufacturing**. The workflow evaluates supplier quotations against purchasing requirements, considers supplier history, flags potential risks, and generates a recommendation for human review.

## 🏢 Procurement Scenario

- **Organization:** Everest Manufacturing
- **Purchase:** 25 laptops
- **Total Budget:** NPR 2,500,000
- **Delivery Deadline:** 14 days
- **Warranty Requirement:** 2 years
- **Payment Preference:** 30 days after delivery
- **Minimum Specifications:** 16 GB RAM, 512 GB storage, Intel Core i5-equivalent processor or better, and Windows 11 Pro

## ⚙️ Key Features

- Evaluates supplier quotations against procurement requirements.
- Reviews supplier ratings and historical delivery performance.
- Flags suppliers with ratings below 3.
- Flags suppliers with more than 2 late deliveries.
- Supports supplier comparison and AI-assisted recommendations.
- Maintains an evaluation log for tracking results.
- Preserves human oversight, with the Operations Manager making the final approval decision.

## 🔄 Workflow Components

The project organizes procurement information into the following components:

1. **Purchase Request** — Defines purchasing requirements and constraints.
2. **Supplier Quotations** — Contains supplier offers and quoted terms.
3. **Supplier History** — Provides supplier performance information.
4. **Evaluation Log** — Records evaluation outcomes and recommendations.

The n8n workflow coordinates the evaluation process and supports a structured, risk-aware procurement decision.

## 🛠️ Technology Stack

- **n8n** — Workflow automation and orchestration
- **AI / LLM integration** — AI-assisted evaluation and recommendations
- **JSON** — Workflow export and configuration

## 🚀 Getting Started

1. Download the `.json` workflow file from this repository.
2. Open your n8n instance.
3. Import the workflow JSON.
4. Configure any required credentials and integrations in your own environment.
5. Review the workflow nodes and configure the required input data.
6. Test the workflow and verify its outputs before using it for any real procurement decisions.

## 🛡️ Human-in-the-Loop Decision Making

The system is designed to assist procurement evaluation rather than replace human judgment. AI-generated recommendations are advisory, and the Operations Manager retains responsibility for the final approval.

## 📚 Learning Outcomes

Through this project, I explored:

- Workflow automation using n8n
- Supplier evaluation and quotation comparison
- AI-assisted decision-support workflows
- Risk identification and evaluation criteria
- Human-in-the-loop system design

## 👩‍💻 Author

**Aalishma Paneru**

Computer Science undergraduate interested in software development, AI applications, and workflow automation.
