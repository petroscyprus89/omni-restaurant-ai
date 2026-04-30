# 🚀 Omni-Restaurant AI: Autonomous Voice & API Routing Architecture

## System Overview
An enterprise-grade, end-to-end web application architecture designed to completely automate restaurant front-of-house operations. This system ingests unstructured voice data via LLM, processes it through a custom API routing layer, and dispatches dynamic database and UI updates with zero human friction.

## Tech Stack (The Core)
* **Frontend UI (Client Dashboard):** React.js (Strict adherence to 4px/8px grid base and 1.25 typography ratio for mathematical scaling).
* **Backend Logic & API Routing:** Node.js / Express (Simulated via n8n middleware).
* **Database Management:** Schema-agnostic JSON payload structuring.
* **Integrations:** Google Calendar API v3, SMTP Digital Dispatch, Vapi (Voice LLM).

## The Engineering Challenge & Solution
**Problem:** Traditional restaurants lose revenue due to missed calls and manual data entry errors.
**Solution:** I built a conditional, binary-routing API that replaces manual labor.
1. **Ingestion Layer:** Captures millisecond webhook payloads from a live AI voice agent.
2. **Classification Router:** Evaluates JSON intent (`book_table` vs `submit_takeaway_order`).
3. **Execution Layer (Branch A):** Injects standardized RFC 3339 timestamps directly into Google Calendar via OAuth2.
4. **Execution Layer (Branch B):** Dynamically formats an HTML email ticket via Gmail API for immediate kitchen display.

## Proof of Execution
> "I don't just write code; I build systems that acquire clients and protect revenue."

The attached `backend-middleware/omni-restaurant-routing-logic.json` contains the complete, source-available backend routing mechanics. Simply import this into an n8n environment to view the live mathematical formulas, API structure, and security bypass protocols.
