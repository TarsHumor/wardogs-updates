# Wardogs Patch Notes Feed

This repository hosts the official JSON patch notes feed for **Wardogs**.  
It provides a simple, bot‑friendly endpoint that can be fetched by Discord bots, PatchBot, automation scripts, or any external service that needs update information.

---

## 📌 Purpose
Wardogs does not have a built‑in update API, so this repo acts as the canonical source for version information, changelogs, and release metadata.

The JSON file(s) in this repo are designed to be:
- Easy to read  
- Easy to update  
- Easy to fetch programmatically  
- Compatible with PatchBot, GitHub raw URLs, and custom bots  

---

## 📁 Files
### **`patches.json`**
Contains the latest update information in a structured JSON format.

Example structure:
```json
{
  "latest": {
    "version": "1.0.0",
    "title": "Initial Release",
    "notes": "First public release of Wardogs.",
    "date": "2026-09-30"
  }
}
