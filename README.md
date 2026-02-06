# Smart-Solar Wiring Dashboard
☀️ Smart-Solar Wiring Dashboard

A high-performance, browser-based utility designed for solar engineers to automate the visualization of electrical wiring schematics from Excel data.

🚀 Overview
This project solves a common challenge in solar plant design: manually mapping string inverters and panel sequences. By uploading a coordinate-based Excel file, the tool automatically generates a precise wiring diagram, calculates string distributions (11, 12, or 13-panel strings), and provides professional export options.

🛠 Features
Automated Schematic Drawing: Instantly converts grid-based Excel coordinates into a visual panel layout.

Intelligent String Logic: Automatically calculates and groups panels into optimal string sizes (prioritizing 13, 12, and 11-panel configurations).

Dual-Language Interface: Fully localized in English and Korean (한국어) for international professional use.

Smart Numbering: - Top Row: Incremental numbering from Left-to-Right.

Bottom Row: Incremental numbering from Right-to-Left (tailored for specific site alignment needs).

Z-Pattern Routing: Automatically generates a "snake" or Z-pattern wiring path to minimize cable length.

High-Resolution Exports:

PDF: Vector-calibrated PDF for printing and official documentation.

PNG: High-quality image export for quick sharing and reports.

Real-Time Statistics: Dynamic dashboard showing the total panel count and the specific number of 11, 12, and 13-panel strings created.

📋 How to Use
Prepare Data: Create an Excel file where cell values represent Group IDs (Inverter/String IDs) and their position in the grid matches the physical layout.

Upload: Click the "SELECT EXCEL" button.

Generate: Click "DRAW SCHEMATIC".

Analyze: Review the statistics panel for string distribution.

Export: Download your professional report via the Image or PDF export buttons.

💻 Technical Stack
Frontend: HTML5, CSS3 (Modern UI with Glassmorphism effects).

Engine: Vanilla JavaScript + HTML5 Canvas API.

Libraries: - SheetJS (XLSX) for complex Excel data parsing.

jsPDF for client-side PDF generation.

🎯 Project Purpose
The purpose of this project is to eliminate human error in solar wiring documentation. It provides a standardized way to visualize electrical strings, ensuring that field technicians have a clear, easy-to-read map for installation, thereby reducing labor time and preventing incorrect connections.

