# Week 1 – Stack Recommendations  
Team 4A – Bot Architecture & Integration  
 
---
 
## Overview
 
This document presents three complete architecture stacks combining:
 
- WhatsApp API provider  
- Voice bot platform  
- Orchestration layer  
- Website integration approach  
 
Each stack includes:
- Architecture diagram  
- Monthly cost modeling at 1K / 10K / 100K users  
- Implementation complexity  
- Pros and cons  
- Recommended use case  
 
---
 
## Assumptions for Cost Modeling
 
- Average voice interaction: 3 minutes per user  
- 5 WhatsApp messages per user  
- Moderate CRM logging and workflow automation  
- WhatsApp pricing varies by region and Meta message category  
- Estimates are directional for academic modeling  
 
---
 
# Stack 1 — Custom Modular Architecture (Maximum Control)
 
### Components
 
- **WhatsApp API:** Meta Business Platform (Direct API)  
- **Voice Bot:** VAPI  
- **Orchestration:** n8n (self-hosted)  
- **Website Integration:** Shared backend API with dynamic site context switching  
 
---
 
### Architecture Diagram
