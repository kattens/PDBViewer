#PDBViewer

A lightweight, browser-based tool for exploring **PDB files** and related molecular data.  
This project allows you to host protein structures, CSV datasets, and interactive 3D viewers directly on GitHub Pages—no server required.

---

##Features
-  **CSV Viewer** – Upload or auto-load CSV files for structured data exploration.  
-  **3D Protein Viewer** – View `.pdb`, `.cif`, `.bcif`, `.sdf`, or `.mol2` files interactively using [NGL Viewer](http://nglviewer.org/).  
-  **Hyperlinks** – Connect data rows (e.g., PDB IDs, gene IDs) to external databases like RCSB PDB and PlasmoDB.  
-  **GitHub Pages Hosting** – Simple deployment, just push to your repo.  

---

##Installation:
 - You can access the PDBViewer here: https://kattens.github.io/PDBViewer/

or

 - Add the folder path:
  
 - cd "Your\Folder\path\PDBviewer"
  
 - set this up:
  
 - py -3 -m http.server 8000
  
 - run on : http://localhost:8000/
  
 - add the "Data.csv" in the PDBviewer as the csv 

 - click on the "filename" to see the structure

 - if not seeing the ligand, turn on the ligand check
