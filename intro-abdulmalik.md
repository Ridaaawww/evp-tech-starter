hello
NAME: I'm Abdul Malik,
COLLEGE: III,I CSE 
Shadan College of Engineering and Technology, peerancheru
ROLE/SPECIALTY: No specific tech stack yet, need to find it.My codebase is usually filled with C, because of CS50 and my love for the langauge, I also have experience with WASM and a bit in python, and lastly some HTML & CSS with a tiny sprinkle of Java (my god that's one ugly looking lang)
IDEA:
A summerizer to keep ~~lazy~~ busy CLs upto date on the disscussions of the CL WhatsApp Group Chat, this is to avoid people repetitive queries in the group. (also so that you won't need to read 200+ messages to know it was actually all about games)

graph TD
    Browser[WhatsApp Web in Browser] -->|DOM Scrape| Scraper[Playwright/Selenium Script]
    Scraper --> Storage[(SQLite / JSON)]
    Storage --> Summarizer[NLP/LLM Summarizer]
    Summarizer --> Dashboard[Console / Web UI / Notifications]
