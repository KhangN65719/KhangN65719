# Hi, I'm Khang Nguyen

Computer Science student at the **University of Illinois Chicago**, graduating **May 2027**. Seeking **software engineering internships and entry-level full-time roles**, with an interest in backend development, algorithms, and data-driven applications.

I started studying computer science at Nashville State Community College before transferring to UIC. My projects span C++ graph algorithms, Java data structures, relational database design, Python data analysis, and Go applications.

[Portfolio](https://khangn65719.github.io/Personal-Portfolio/Index.html) · [LinkedIn](https://www.linkedin.com/in/khang-nguyen-b044ba279) · [Email](mailto:KhangN44345@gmail.com)

## Selected projects

### [Campus Pathfinding System](https://github.com/KhangN65719/Campus-Pathfinding-System)
**C++20 · Graphs · Dijkstra’s algorithm · JSON · HTTP · Leaflet**

A campus navigation application that models buildings and walkways as a weighted graph and finds walking routes with Dijkstra’s algorithm.

- Builds a graph from campus map data and connects buildings to nearby walkway nodes.
- Supports excluding intermediate vertices during route computation.
- Includes an HTTP server and interactive map for finding buildings and displaying routes.
- Includes Google Test suites for graph operations, graph construction, and shortest paths.

### [Chicago Traffic Camera Data Analysis](https://github.com/KhangN65719/Chicago-Traffic-Camera-Data-Analysis)
**Python · SQLite · SQL · Matplotlib**

A menu-driven application for exploring Chicago’s red light and speed camera violations, built for CS 341 at UIC.

- Searches intersections and cameras using parameterized SQL queries.
- Aggregates violations by camera, intersection, month, and year.
- Plots trends and camera locations with Matplotlib.
- Separates database queries, data processing, and the command-line interface into distinct layers.

### [URL Shortener](https://github.com/KhangN65719/url-shortener)
**Go · net/http · GORM · SQLite** — In progress

A backend service that creates short links and redirects visitors to their original URLs.

- Accepts URL submissions through an HTTP endpoint and generates six-character short codes.
- Stores URL mappings in SQLite through GORM and reuses codes for previously submitted URLs.
- Returns redirects for known codes and a 404 response for missing links.
- Separates HTTP handlers from the storage layer.

### [Hospital Database System](https://github.com/KhangN65719/Hospital-Database-System)
**MySQL · Relational modeling · SQL · Transactions**

A CS 480 database project modeling hospital staff, patients, treatment, room assignments, and billing across 16 tables. Includes 15 analytical queries, three reporting views, three insert-validation triggers, and transaction examples.

### [Java Dictionary Implementations](https://github.com/KhangN65719/Java-Dictionary-Implementations)
**Java · Generics · Binary search trees · Hash tables · JUnit · Maven**

Two dictionary implementations behind a shared interface: a binary search tree and an open-addressed hash table with linear probing, tombstones, and resizing. The existing JUnit suite passes all 30 tests.

### [Go Shape Renderer](https://github.com/KhangN65719/Go-Shape-Renderer)
**Go · Interfaces · Raster graphics · File I/O**

An interactive program that draws rectangles, triangles, and circles into a pixel buffer and exports PPM images using the standard library. Verified by building the program and checking pixels in an exported sample image.

## More projects

- **[Personal Portfolio](https://github.com/KhangN65719/Personal-Portfolio)** — My website, project summaries, and background.
- **[Weather App](https://github.com/KhangN65719/Weather-App)** — A JavaScript project using OpenWeatherMap’s geocoding and weather APIs to display current conditions by city.

## Technologies used in these projects

- **Languages:** C++, Java, Go, Python, SQL, JavaScript, HTML, CSS
- **Backend and data:** Go’s standard HTTP library, GORM, MySQL, SQLite, Matplotlib
- **Web and tooling:** Leaflet, Vite, Git, GitHub, Make, Google Test, Maven, JUnit

## Currently learning

- Backend development with Go and HTTP APIs
- Data structures, graph algorithms, and software design
