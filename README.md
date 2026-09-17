# ai_in_ecourts_of_india
AI in eCourts of India: Intelligent Penal Code Analysis System
Welcome to the Intelligent Penal Code Analysis System, a production-ready, offline-first legal tech dashboard designed to bring AI-assisted analysis to the Indian Penal Code (IPC 1860). Built explicitly for zero-dependency environments, this system requires no server, no package managers, and no build steps. It operates entirely within a single HTML file, ensuring extreme portability, absolute privacy, and instant execution.

Core Features
Natural Language Search Engine: A client-side lexical matcher translates conversational, situational inputs (e.g., "A shopkeeper sold adulterated baby food") into highly relevant penal provisions using weighted token scoring, stop-word filtering, and synonym expansion.

Comprehensive Legal Corpus: An embedded JSON database covers major IPC sections, meticulously breaking them down into core elements like Actus Reus (the prohibited act) and Mens Rea (the guilty intent), alongside procedural tags (bailable, cognizable) and punishments.

Constitutional Precedents: Tracks landmark Supreme Court rulings and constitutional validity (e.g., Navtej Singh Johar, Mithu v. State of Punjab), ensuring that evolving historical context is immediately accessible.

Case Brief Exporter: Enables users to bookmark relevant sections during research and export a cleanly formatted, printable legal brief directly from the local browser session.

Technical Architecture
The architecture is divided into four virtual layers executing seamlessly within the browser:

Presentation Layer: A responsive, high-trust civic tech UI powered by Tailwind CSS, featuring glassmorphism cards, interactive modals, and dynamic category filters.

State Controller: Vanilla ES6 JavaScript manages active filters, UI states, and the session's pinned bookmarks with zero latency.

Search Engine: A custom, lightweight NLP algorithm calculating dynamic confidence match metrics (e.g., "94% Match") without relying on external APIs.

Data Layer: A normalized, highly curated embedded JSON corpus acting as the single source of truth.
