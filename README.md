<p align="center">
  <img src="./NortekLogo.png" alt="Project Logo" width="150"/>
</p>

# KiCad Project Name

## 📌 Overview
This repository contains a **KiCad** project for designing [describe your PCB, circuit, or purpose]. It includes schematics, PCB layout, and related design files.

## 🚀 Features
- ✅ **feat 1**: **blabla**
- ✅ **feat 2**: **blablabla**

### **What’s New?**
✅ **Added a section explaining how to convert `README.md` to `meta/info.html` for KiCad**  
✅ **Included `pandoc` commands**  
✅ **Explained how to remove emojis using `sed` or Python**  

## 📂 Project Structure
```
📦 Project-Name/
 ├── 📁 DOCUMENTATION/    # Project documentation
 ├── 📁 FABRICATION/      # Files related to PCB fabrication
 ├── 📁 GERBER/           # Gerber files for PCB manufacturing
 ├── 📁 MECHANICAL/       # Mechanical drawings and 3D models
 ├── 📁 meta/             # Metadata and additional configuration files
  │   ├──NortekLogo.png        # Project logo
  │   ├──preview.png        # Project preview
 ├── 📁 SCHEMATICS/       # KiCad schematic files (.sch, .lib, .dcm)
 ├── 📁 SIMULATION/       # Simulation files and test results
 ├── 📜 Project-Name.pro  # KiCad project file
 ├── 📜 README.md         # Project documentation
 └── ...
```
### **Convert Markdown to HTML with `pandoc`**
To generate `meta/info.html`, use **Pandoc**:
pandoc README.md -o meta/info.html
or
sed 's/[🚀📌✅🛠🎨🤝📜📦├──📁📂└──│]//g' README.md | pandoc -o meta/info.html


## 🛠 Installation & Usage
1. **Install KiCad** (if not already installed):  
   Download the latest version from [KiCad’s official website](https://www.kicad.org/download/).

2. **Open the Project**:  
   - Open **KiCad** and select **File > Open Project** (`.pro` file).
   - Load the **schematic** (`.sch`) and **PCB layout** (`.kicad_pcb`).

3. **Editing the Design**:  
   - Modify components in **Eeschema** (schematic editor).
   - Adjust PCB layout in **Pcbnew**.

4. **Generating Gerber Files** (for manufacturing):
   - In **Pcbnew**, go to **File > Plot** and generate **Gerber** files.
   - Export the **Drill Files** as well.

5. **3D Visualization**:
   - Open **Pcbnew**, press `ALT+3` to view the 3D model.

## 🎨 Preview
<p align="center">
  <img src="./preview.png" alt="Project Preview" width="600"/>
</p>


## 🤝 Contributing
Contributions are welcome! Feel free to **fork** the project, open **issues**, or submit **pull requests**.

## 📜 License
This project is licensed under the [MIT License](LICENSE).
