# Personalized Yoga Recommendation System

A rule-based wellness web app that generates safe, structured daily yoga routines based on user constraints.

---

## Overview

The system is not medical.  
It is a **recommendation-only wellness tool** designed for beginners and intermediate users.

---

## User Inputs

Users select:
- Symptoms (back pain, stiffness, knee pain, etc.)  
- Age, gender  
- Pregnancy status  
- Experience level  
- Time commitment (30, 60, 120 minutes)  

All inputs are checkbox-based to stay controlled.

---

## Recommendation Logic

1. Safety filtering using contraindications  
2. Rule-based scoring and ranking  
3. Duration-based routine assembly  
4. Structured output (warm-up, poses, pranayama, relaxation)  

---

## Data

Yoga data came from handwritten notebooks and was manually:
- Digitized  
- Normalized  
- Enriched with contraindications  
- Stored in database tables  

---

## Tech Stack

- Flask  
- SQLite  
- Jinja2  
- HTML, CSS  
- Vue.js  
- Python  

---

## Design Philosophy

Safety, structure, and explainability over black-box ML.
