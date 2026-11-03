# VIN, Equipment & CoC Inspector

A lightweight, web-based inspection tool designed for External Inspection Committee evaluations. This application allows inspectors to quickly decode Vehicle Identification Numbers (VINs), verify standard safety equipment, and check Certificate of Conformity (CoC) statuses in the field.

## Features
* **VIN Decoding:** Quickly validates and parses 17-character VINs.
* **Equipment Checklist:** Built-in interactive checklist for mandatory vehicle safety equipment.
* **CoC Validation:** Status indicator for Certificate of Conformity records.
* **Print-Ready:** Includes a quick-print function to generate physical inspection reports on the spot.

## Deployment Instructions

This tool is designed to be hosted entirely for free using GitHub Pages.

1. Upload both `index.html` and `README.md` to the main branch of your GitHub repository.
2. Go to your repository's **Settings**.
3. Click on **Pages** in the left sidebar.
4. Under "Build and deployment", set the source branch to `main` (or `master`) and click **Save**.
5. Your tool will be live at `https://almohands87.github.io/vin-Inspector/` within a couple of minutes!

## Customization
All structural code, styling (via Tailwind CSS), and logic (JavaScript) is contained within the `index.html` file to ensure the application remains highly portable. 
* To integrate a live VIN API, modify the `inspectVehicle()` function inside the `<script>` tags.
