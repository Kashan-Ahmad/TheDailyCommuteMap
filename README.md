# 🚇 The Daily Commute Map

The **Daily Commute Map** is a full-featured **map visualization and route-planning application** built in **C++** using the **EZGL graphics library** and the **OpenStreetMap (OSM) Database API**.  

It was designed to answer a simple question that millions of commuters ask every day:  
👉 *“What’s the best way for me to get from Point A to Point B in my city?”*  

Unlike a static paper map or a basic navigation app, this project provides an **interactive, commuter-friendly experience** that brings together **roads, bike routes, subways, and traffic signals** in a single platform. The application doesn’t just show you where to go — it guides you step by step, highlighting **multimodal travel options** that reflect how real people move through cities.

---

## 🌍 Why This Project is Useful

Urban commuting is messy — it involves switching between buses, bikes, subways, and cars. Most mapping tools either oversimplify the experience or overwhelm users with too much data.  

The Daily Commute Map is built with the **commuter in mind**:  
- **Easy-to-read overlays** for subways, bike routes, and traffic lights.  
- **Color-coded paths** (e.g., green/yellow/red for traffic conditions, distinct subway line colors).  
- **Step-by-step directions** with estimated travel times and distances.  
- A **night mode** for comfortable viewing during evening commutes.  

It’s essentially a **Google Maps–style system**, but created from scratch in C++ with efficient algorithms and a custom rendering pipeline.

---

## ✨ Features

- **Interactive Map Rendering**
  - Real-time visualization of intersections, roads, and points of interest.  
  - Smooth zooming and panning with GUI controls.  
  - Switch between day and night modes for better readability.  

- **Multimodal Commuting**
  - Display subway lines in their real-world colors.  
  - Show bike routes overlaid on the road network.  
  - Highlight traffic lights to aid realistic navigation.  

- **Smart Pathfinding**
  - Implemented both **Dijkstra’s Algorithm** and **A\* Search** to compute shortest paths.  
  - Provides **step-by-step turn instructions**, estimated travel times, and distances.  
  - Handles complex urban grids efficiently using priority queues and heuristic search.  

- **User-Friendly UI**
  - Input intersections by street names to find paths.  
  - Clickable buttons for showing/hiding overlays (subways, bikes, traffic).  
  - Clear and reset routes with a single click.  

---

## 🛠️ Technical Skills Showcased

This project demonstrates a wide range of **computer engineering and software development skills**:

- **C++ Programming**
  - Object-oriented design, data encapsulation, and modular architecture.  
  - Memory management for large OSM datasets.  
  - Use of STL containers (`vectors`, `maps`, `priority_queue`) for efficiency.  

- **Algorithms & Data Structures**
  - **Graph representation** of city networks (nodes = intersections, edges = streets).  
  - **Shortest path algorithms** (Dijkstra & A\*) with heuristics for scalability.  
  - Efficient data lookup with hash maps and indexing for intersections & street names.  

- **GUI & Visualization**
  - Built on the **EZGL graphics library** (C++ wrapper around GTK and Cairo).  
  - Implemented **event-driven programming** (mouse/keyboard input, button callbacks).  
  - Designed an **interactive UI** with toggles, overlays, and responsive rendering.  

- **Databases & APIs**
  - Parsed **OpenStreetMap (OSM) data** through the `OSMDatabaseAPI.h`.  
  - Extracted and structured map data (streets, points of interest, coordinates).  
  - Integrated external datasets (bike routes, subway stations).  

- **Software Engineering Practices**
  - Modular project structure with separation of concerns (`renderer`, `pathfinding`, `ui`).  
  - Version control using Git & GitHub.  
  - Documented design decisions and feature tradeoffs.  

---

## 🚀 Demo

### Main Map View  
Interactive city rendering with streets, subways, and overlays.  

- Zoomed out image of map
<img width="1905" height="909" alt="Screenshot 2025-09-21 224315" src="https://github.com/user-attachments/assets/72a45c1c-ad53-4813-b1e1-de9661a46af5" />


---

### Night Mode  
Dark-themed view for nighttime commuting.  
<img width="1905" height="923" alt="Screenshot 2025-09-21 224417" src="https://github.com/user-attachments/assets/1568a17e-d571-4796-a0ef-7c4d74eb2b2c" />


---

### Path Input  
Enter street intersections to find a route.  
<img width="1375" height="886" alt="Screenshot 2025-09-21 224809" src="https://github.com/user-attachments/assets/a6353254-6b1e-4273-b7ff-10e12879925e" />


---

### Step-by-Step Directions  
Generated route with distance, estimated travel time, and turn-by-turn instructions.  
<img width="1913" height="874" alt="Screenshot 2025-09-21 224911" src="https://github.com/user-attachments/assets/ad6c62e4-0f96-4093-891a-1a7292273764" />


---

## 📌 Future Improvements

- Add **real-time traffic data integration**.  
- Support **multi-stop route planning** (e.g., errands + work + home).  
- Implement **transit schedules** (bus & subway timings).  
- Deploy as a **cross-platform mobile/desktop app**.  


