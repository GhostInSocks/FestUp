# Project Proposal

## Problem

Ljubitelji glasbe in obiskovalci festivalov se pogosto soočajo s težavami pri odkrivanju novih festivalov, raziskovanju neznanih glasbenih zvrsti ali obiskovanju novih prizorišč. Verodostojne informacije o manj znanih ali regionalnih dogodkih je težko najti, kar vodi v oklevanje zaradi tveganja zapravljanja časa in denarja za slabo organizirane dogodke (npr. slaba kakovost zvoka, dolge vrste, predraga hrana/pijača). Poleg tega je udeležba na novih festivalih v skupini bistveno varnejša in prijetnejša, vendar se posamezniki pogosto težko znajdejo pri iskanju prijateljev, ki delijo njihov glasbeni okus ali imajo na voljo prevoz.

FestUP to rešuje z zagotavljanjem enotne platforme za odkrivanje glasbenih festivalov (filtriranih po oznakah, zvrsteh in datumih), povezovanjem z udeleženci prek forumov, specifičnih za dogodke (za skupno vožnjo, kampiranje in ujemanje skupin) in objavljanjem večkriterijskih ocen.

## Users and roles

| Role | Description | What they can do | 
| ----- | ----- | ----- | 
| Guest / Unregistered | Unauthenticated user exploring the platform | Browse/filter festivals, view festival details and venue locations, read public discussion forums, and view AI-generated review summaries. | 
| Registered User | Authenticated festival-goer | Create and edit personal profile (music preferences, festival history), post and reply in event forums (carpooling, camping, group matching), leave multi-criteria reviews (venue, music, food, organization), and save favorite events. | 
| Admin | Platform administrator | Manage festival listings (create, edit, delete), moderate forum posts and user reviews, and manage user accounts. | 

## User stories

| \# | Story | Priority | Milestone | Issue | 
| ----- | ----- | ----- | ----- | ----- | 
| 1 | As a **user**, I want to **search and filter festivals by genre, location, tags, and dates**, so that **I can quickly find events matching my taste and schedule**. | M | Midterm | #1 | 
| 2 | As a **registered user**, I want to **post carpooling/camping requests in event-specific forums**, so that **I can find travel companions and share expenses**. | M | Midterm | #2 | 
| 3 | As a **registered user**, I want to **leave multi-criteria ratings and reviews for attended events**, so that **I can share my honest feedback on venues, sound quality, and amenities**. | S | Midterm | #3 | 
| 4 | As a **user**, I want to **view an AI-generated summary of reviews for a festival**, so that **I can quickly understand the pros and cons without reading dozens of comments**. | S | Final | #4 | 
| 5 | As a **registered user**, I want to **customize my profile with favorite genres and past festival history**, so that **other attendees can see my music preferences when connecting**. | C | Final | #5 | 

### Acceptance criteria (example for story 1)

* **Given** an unauthenticated or registered user on the festival discovery page

* **When** the user selects a date range, music genre filter (e.g., "Techno"), or venue tag

* **Then** the system displays a filtered list of matching festival cards showing dates, locations, and tag badges, or displays a friendly "No events found" message if there are no matches.

## Mobile app use case

On-the-go festival attendees need quick, mobile-friendly access to forum discussions and event details while traveling or at the festival ground. On a smartphone, users can quickly check carpool meet-up locations and receive real-time push notifications when someone replies to their ride request.

## AI features

* **LLM feature:** Natural-language search to structured filter (e.g., translating "rock festivals near Ljubljana next weekend with camping" into structured API query parameters).

* **Agent task:** Summarize all user reviews for a specific festival into a concise list of pros/cons and answer user questions regarding venue logistics (e.g., parking options or camping rules) using information from festival descriptions and discussions.

## Plan

| Milestone | Stories / features | 
| ----- | ----- | 
| Midterm (week 7) | Event discovery with multi-criteria filtering (US-1), user authentication and profiles, event-specific discussion forums for carpooling/group finding (US-2), and multi-criteria review system (US-3). | 
| Final (week 12) | AI-powered review summarization and FAQ agent (US-4), user profile customization & festival history (US-5), mobile app features, and UI polishing/bug fixes. | 

## Risks
