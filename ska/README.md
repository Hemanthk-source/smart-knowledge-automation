# Smart Knowledge Automation

A simple base project that turns notes and text files into a searchable knowledge base.

## Features
- Add notes or import .txt / .md files
- Automatic summaries (extractive, sentence scoring)
- Automatic keywords/tags (TF-IDF)
- Ranked search with highlighting
- Related-note suggestions (cosine similarity)
- Export to JSON; data saved in browser localStorage

## How to run
Open `index.html` in any modern browser. No installation or internet needed.

## Structure
- index.html : HTML, CSS and JavaScript (NLP helpers, automation, search, UI) in one file

## Ideas to extend
- Backend (Flask/Node) with SQLite/MongoDB
- Claude API for better summaries and tags
- PDF/Word upload, login, Q&A chat over notes
