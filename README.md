<img width="1080" height="608" alt="image" src="https://github.com/user-attachments/assets/ec578266-4bd8-4e38-9c90-76fafbeb89e5" /># 3D Hierarchical Clustering Visualizer Prototype

## Overview
This project is a GUI-based tool for visualizing hierarchical clustering in **three dimensions**. It allows users to explore student datasets (grades, study hours, extracurricular activity levels) without writing any code. Users can manipulate clustering parameters and generate interactive 3D scatter plots to better understand the hidden relationships within the data.

---

## Problem Statement
Traditional clustering visualizations are mostly 2D and require programming knowledge. This makes it difficult for beginners, researchers, or students to:
- Understand multi-dimensional clustering relationships
- Adjust clustering parameters dynamically
- Explore hidden subgroups in datasets without coding

This prototype solves these problems by providing a **user-friendly interface** that allows dynamic interaction with clustering visualizations.

---

## Objectives
- Provide a **no-code interface** for hierarchical clustering visualization  
- Enable **3D exploration** of datasets across three features simultaneously  
- Allow users to **manipulate clustering parameters** such as distance cutoff and data point size  
- Demonstrate the **feasibility and usability** of a GUI for unsupervised machine learning

---

## Features

### 1. CRUD Operations
- Load, add, edit, or delete student dataset entries from CSV files

<img width="1080" height="608" alt="image" src="https://github.com/user-attachments/assets/666f677a-52b7-411c-83b2-9320149a0237" />


---

<!-- ### 2. 3D Feature Selection
- Select X, Y, and Z axes from available dataset features
- Explore multi-dimensional clustering interactively

![Feature Selection Demo](demo/feature_selection.gif)

--- -->

### 2. Adjustable Distance Cutoff
- Dynamically control the hierarchical clustering distance cutoff
- Higher cutoff → fewer clusters
- Lower cutoff → more fine-grained clusters

![Distance Cutoff Demo](demo/distance_cutoff.gif)

---

### 3. Adjustable Data Point Size
- Change the size of data points for better visibility across devices

![Data Point Size Demo](demo/point_size.gif)

---

### 4. Interactive 3D Visualization
- Rotate, zoom, and pan the 3D cluster plot  
- Hover over points to view additional information  

![3D Visualization Demo](demo/3d_visualization.gif)

---

## Conceptual Framework
This prototype is grounded in the following theoretical frameworks:

1. **Human-Computer Interaction (HCI)**  
   - Direct manipulation interface for parameter sliders and 3D interaction  
   - Designed following usability heuristics

2. **Hierarchical Clustering Theory**  
   - Agglomerative clustering with adjustable distance cutoff  
   - Reveals hidden subgroups in the dataset

3. **Visual Analytics Framework**  
   - Integrates data, machine learning, and interactive visualization  
   - Enables exploratory data analysis

4. **Prototyping Fidelity**  
   - High-fidelity interactive prototype demonstrating core functionality

---

## System Architecture
**Frontend (GUI)**
- Built with [Your GUI library, e.g., Tkinter, PyQt, CustomTkinter]  
- Handles user inputs and parameter adjustments

**Backend**
- Data loading and preprocessing (CSV files)  
- Hierarchical clustering engine (SciPy linkage + fcluster)  
- 3D plotting (Plotly)

**Data Flow**

![System Architecture Diagram](demo/system_architecture.gif)

---

## Demo Video
For a full walkthrough of the prototype:

[▶️ Watch Full Demo](https://youtu.be/your_video_id)

---

## Future Enhancements
- Add dendrogram visualization  
- Implement PCA for higher-dimensional datasets  
- Add export options for graphs (PNG, CSV with cluster labels)  
- Include additional clustering algorithms (K-Means, DBSCAN)  
- Develop a web-based version for wider accessibility
- Downloadable 3D graph as an html file
---

## Limitations
- Only supports a specific set of dataset attributes  
- CSV dataset format only  
- Does not yet support extremely large datasets  
- No dendrogram overlay yet 

---

## References
- Shneiderman, B. “Direct Manipulation Interfaces”  
- Nielsen, J. “10 Usability Heuristics”  
- Keim, D., et al. “Visual Analytics Process Model”  
- SciPy documentation (hierarchical clustering)


