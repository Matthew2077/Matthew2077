# Kon'nichiwa! Welcome and Sayōnara
My name is Matteo, though online I prefer to go by "Matthew."

I'm a junior back-end developer with experience building REST APIs using Python and working with PHP. More recently, I've also started exploring C# and the .NET ecosystem.

I chose a career in computer science because I love building complex systems that have a real-world impact. Not every aspect of the field appeals to me equally; through experience, I’ve discovered that it is the underlying structure of systems—rather than, say, a polished animation—that fascinates me the most.

My journey is still ongoing. This profile serves as a collection of personal projects I develop to gain experience, experiment with new technologies—such as AI—or simply because I want to build software that serves a purpose for myself or others.

## My Projects:

### 📚 [LibraryTools](https://github.com/Matthew2077/LibraryTools) — Python API for texts 
An API-first backend for managing and structuring knowledge through notes, categories, and tags. This was my first real project built without a tutorial holding my hand — the proving ground where I learned to choose my own stack, wire up new libraries, and actually design something meant to grow over time.
- **Stack:** Python, FastAPI, SQLAlchemy, Pydantic
- **Highlights:**
	  - Full CRUD for notes, categories, tags, and users
	  - Note status management (draft, published, archived)
	  - Many-to-many relationship mapping between notes and tags
- 📄 [Technical review (v1.0)](https://github.com/Matthew2077/LibraryTools/blob/main/v1_review.md)

### 🗡️ [Katana](https://github.com/Matthew2077/Katana) — python API for animes
Same stack as LibraryTools, built in a tight ~5-day sprint. Less about the final product, more a testbed for architecture patterns, error handling, and structured logging — the lessons here fed straight back into improving LibraryTools.

### 📊 [AZAproject](https://github.com/Matthew2077/AZAproject) — Full-stack data visualization tool
Originally developed during my ITS internship in collaboration with a colleague, with responsibilities divided between frontend and backend development.

After the internship, I revisited the project independently, substantially reworking its original implementation and improving its data-processing logic.

The application processes JSON datasets, extracts product-related information, aggregates KPIs, and provides interactive dashboards with country-based views.
- **Stack:** PHP, Python, JavaScript, HTML, CSS, Bootstrap
- **Highlights:**
    - JSON file upload and validation
    - Automated data aggregation and KPI calculation
    - Country-based data filtering and interactive dashboards
    - Product data visualization through charts and tables
    - PHP-Python integration for data processing

### Working in progress:
## 🎌 [AnimeTracker 2.0](https://github.com/Matthew2077/AnimeTracker2.0) — C# rewrite of my anime/manga tracker
A local-first web app for tracking a personal anime and manga library, rebuilt from my original vanilla JS version into a proper ASP.NET Core backend. This is where I'm moving from Python to C#, and where I'm learning to work with AI tools deliberately instead of just pasting output.
* Stack: C#, ASP.NET Core (.NET 10, Minimal APIs), EF Core, SQLite, vanilla JS frontend, xUnit
* Highlights:
   * Series containing multiple entries (anime, films, OVAs, manga, light novels) with custom ordering
   * Progress tracking with a single, centralized status-rules function (e.g. last episode watched → completed)
   * Genres, many-to-many tags, cover image uploads, search and filters
   * One-off importer that migrates the data from v1.1 (JSON) into the new schema
   * Unit tests covering status rules, ordering and stats

## Other Repositories
- [**TeleLibrary**](https://github.com/Matthew2077/TeleLibrary)**:** A Telegram bot written in Python that integrates with the LibraryTools API.
- [**AZAproject**](https://github.com/Matthew2077/AZAproject)**:** A full-stack data visualization tool developed during my ITS internship, featuring JSON data processing, KPI aggregation, and interactive dashboards.
- [**Magazzino**](https://github.com/Matthew2077/Magazzino)**:** A C# study project developed for my ITS final exam (December 2025).
- [**XProject**](https://github.com/Matthew2077/Xproject)**:** A Python project focused on OCR and text processing.