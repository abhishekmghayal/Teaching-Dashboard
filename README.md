# StudySpace — Revision & Learning Dashboard
## BSERC GenAI Internship — Week 1, Project 2, Option 1

**Package status: PARTIAL — one of the three required project pages is complete.**

### What this project is
StudySpace is a responsive, single-file HTML revision dashboard for students. It uses embedded HTML, CSS and JavaScript and does not require a build step or backend.

### Run it
1. Extract this ZIP.
2. Open `StudySpace_Revision_Learning_Dashboard.html` in a modern browser.
3. Use the navigation to explore the dashboard, subjects, revision tools, flashcards, quiz and analytics.
4. Browser local storage is used to retain the user's data on that browser/device. Export a JSON backup before clearing browser data.

### Implemented functionality
- Student overview and navigation across five sections
- Subject creation, search, editing, deletion and topic progress
- Daily goals and actual study-time logging
- Exam countdown and revision checklist/task management
- Flashcards and a short quiz
- Study analytics and a rolling seven-day view
- Light and dark themes
- JSON backup export/import with validation
- Responsive layout, mobile sidebar dismissal, keyboard focus indicators and reduced-motion support
- Local-date handling and consecutive-day study streak calculation

### Development history
- Version 1: initial dashboard and core study features.
- Round 1: corrected metric accuracy; removed misleading prefilled study-time/quiz data; made weekly activity and streak-related reporting depend on actual logged activity.
- Round 2: added subject search/edit/delete, task removal, JSON import validation, Escape-to-close modal behavior, visible focus and reduced-motion handling.
- Round 3: corrected local date handling, implemented consecutive-day streak logic, strengthened imported-data validation, prevented duplicate subject names and improved mobile sidebar dismissal.

### QA status
The user reported that all 12 Round 3 final QA checks passed. See `QA_REPORT.md` for the test record.

### Important submission gap
The Week 1 Project 2 brief requires **at least three interactive web pages from at least three different project options**, with each page delivered as a standalone HTML file, and a ZIP containing the three HTML files plus prompt documentation. This package contains only Option 1 (Revision & Learning Dashboard). It is therefore a working partial package, **not a compliant final submission yet**. Two additional pages from two different options must be built and tested before submission.
# Teaching-Dashboard
