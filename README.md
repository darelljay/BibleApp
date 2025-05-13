# Korean Bible App Project Plan

## Overview
A detailed 8-week, one-person project plan for building a Korean Bible app with the following MVP features:
- Text display & navigation (book/chapter/verse picker)
- Full-text search
- Bookmarks, highlights & notes
- Audio playback
- Offline support
- Settings: font size, dark mode

---

## Week 1: Project Setup & Planning
**Day 1:** Define scope & MVP features  
**Day 2:** Research translation versions & licensing terms  
**Day 3:** Select tech stack (Flutter vs. React Native; Firebase vs. custom backend)  
**Day 4:** Set up development environment, create GitHub repo & CI pipeline  
**Day 5:** Draft wireframes and user flows in Figma

**Deliverable:** Project scope document, approved wireframes, repo & CI setup

---

## Week 2: Data Preparation
**Day 1:** Acquire Korean Bible text files (e.g., 개역개정, 새번역)  
**Day 2:** Parse and convert text to structured JSON (book/chapter/verse)  
**Day 3:** Normalize punctuation, spacing, and special characters  
**Day 4:** Design database schema for text and user data  
**Day 5:** Import JSON into database; verify data integrity

**Deliverable:** Clean JSON data, database schema, imported dataset

---

## Week 3: Basic App Structure
**Day 1:** Initialize Flutter/React Native project  
**Day 2:** Implement navigation skeleton (tab & drawer navigation)  
**Day 3:** Integrate database connection / API client  
**Day 4:** Build book & chapter listing screens  
**Day 5:** Render verse text with basic styling

**Deliverable:** Navigable prototype showing static text

---

## Week 4: Search & Navigation
**Day 1:** Set up search service (Algolia/Elasticsearch)  
**Day 2:** Index Bible text for search  
**Day 3:** Build search UI with filters (testament, book)  
**Day 4:** Implement navigation from search results to verses  
**Day 5:** Test search accuracy and performance

**Deliverable:** Functional full-text search feature

---

## Week 5: User Annotation Features
**Day 1:** Implement bookmarks (UI + storage)  
**Day 2:** Implement verse highlighting  
**Day 3:** Build notes feature with text input & save  
**Day 4:** Create backend endpoints (if needed) for user data sync  
**Day 5:** Test CRUD operations for bookmarks, highlights, and notes

**Deliverable:** Working annotations & notes synced across sessions

---

## Week 6: Audio & Offline Support
**Day 1:** Source audio recordings & split by chapter  
**Day 2:** Host audio files and set up streaming endpoints  
**Day 3:** Implement in-app audio player controls  
**Day 4:** Add offline caching for text & audio  
**Day 5:** Test offline reading & listening workflows

**Deliverable:** Offline-capable text and audio playback

---

## Week 7: UI Polish & Settings
**Day 1:** Add font-size adjustment controls  
**Day 2:** Implement dark mode  
**Day 3:** Build Settings screen (language, theme, audio quality)  
**Day 4:** Perform localization review in Korean  
**Day 5:** General UI/UX polish (spacing, icons, responsiveness)

**Deliverable:** Polished UI with user settings

---

## Week 8: Testing & Release Prep
**Day 1:** Conduct end-to-end testing on multiple devices  
**Day 2:** Fix any critical bugs & performance issues  
**Day 3:** Prepare App Store & Google Play assets (screenshots, descriptions)  
**Day 4:** Write user documentation & README  
**Day 5:** Submit builds for review

**Deliverable:** Submitted apps to stores, project documentation

---

## Next Steps & Maintenance
- **Post-launch monitoring:** Track crashes & analytics (Firebase/Amplitude)  
- **User feedback:** Triage issues, plan minor/major releases  
- **Future enhancements:** Parallel-view translations, reading plans, social sharing

Good luck building your Korean Bible app—feel free to iterate on this plan as you go!
