# 🚇 The Daily Commute Map

An interactive **Google Maps–style navigation system** built in **C++** using **EZGL** and the **OpenStreetMap (OSM) Database API**. Designed to provide **commuter-friendly route planning** with support for multimodal travel (subways, bike routes, and roads), real-time pathfinding, and a clean, intuitive user interface.

---

## ✨ Features

- **Interactive Map Rendering**  
  - Displays streets, intersections, points of interest, and major landmarks.  
  - Supports **zoom in/out** and **night mode** for improved usability.  

- **Multimodal Commuting**  
  - Subway routes drawn with **colored transit lines** for easy recognition.  
  - Bike paths and traffic lights integrated into map view.  

- **Smart Pathfinding**  
  - Implemented **A\*** and **Dijkstra’s algorithm** for shortest-path routing.  
  - Provides **step-by-step directions** (with distance & estimated travel time).  

- **UI Controls**  
  - Find paths between intersections by typing street names.  
  - Clear or re-draw routes on demand.  
  - Toggle subway, bike, and traffic overlays.  

---

## 🛠️ Tech Stack

- **Language**: C++  
- **Graphics Library**: EZGL  
- **Data Source**: OpenStreetMap (OSMDatabaseAPI.h)  
- **Algorithms**: A\* Search, Dijkstra’s Algorithm  
- **Environment**: Linux (X11 GUI)  

---

## 🚀 Demo

### Main Map View  
Interactive city rendering with streets, subways, and overlays.  

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

- Real-time traffic integration.  
- Multi-stop route planning.  
- Mobile-friendly deployment.  


