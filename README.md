# Carolina Aguilar – Revit Python Scripts

Welcome to my collection of Revit Python scripts. These tools are designed to enhance BIM workflows, supporting QA/QC, management reporting, automation, and diagnostics. Each script is documented, tested, and organized for easy use.

---

## 📂 Repository Structure

- **QAQC (Inside-Model Checks)**
  - `Color By Family Version` – Visually distinguishes family instances by version.
  - `Reset Overrides` – Resets all overrides in the active view.
  - `Annotate Family Names to GA` – Adds family names to generic annotations.
  - `Annotate Type Names to GA` – Adds type names to generic annotations.

- **Management / Reporting / Audit**
  - `TextNote Usage Analyzer` – Audits usage of TextNote types across views.
  - `List View Templates with Selected Parameters` – Checks key metadata in view templates.
  - `List All Parameters for View Templates` – Audits all parameters in view templates.
  - `List Families and Types (Not Placed)` – Lists all family content in the project.
  - `List Families in Active View` – Lists visible family instances with category counts.
  - `List All View Filters` – Lists all view filter objects in the project for quick auditing.

- **Automation / Model Modification**
  - `Delete Spaces Without Bounding Boxes` – Cleans up invalid or orphaned spaces.
  - `Assign Unit Groups to Spaces (No Rotation)` – Automatically places model groups into MEP spaces.
  - `Convert Group Members to Workplane-Hosted` – Converts face-based or link-hosted families into workplane-hosted instances.

- **Diagnostics / Debugging**
  - `Space Boundary Validator` – Verifies space elements inside a group.
  - `Group Member Debugger` – Lists all elements in a selected group.
  - `Orientation & Bounding Box Debugger` – Outputs bounding box info to debug misalignment.

---

## ⚙️ Environment

Most scripts were developed using:

- **Revit Versions:** 2021 – 2024 (varies per script)  
- **Python Engine:** IronPython 2.7.7 or 3.4.1  
- **RevitPythonShell:** 1.0.0.0 – 2023.0.0.0  
- **.NET Framework:** 4.0 – 4.8  

Each script contains a detailed header docstring with environment, functionality, inputs, outputs, and status.

---

## 📄 Usage

1. Open Revit and the desired project.  
2. Open RevitPythonShell.  
3. Load the script from the appropriate folder.  
4. Follow the instructions in the script docstring.  

> **Note:** Scripts do not modify existing logic; they include inline comments and documentation for clarity.

---

## 📜 License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## ✉️ Contact

**Carolina Aguilar**  
Email: carolinaguilar8@gmail.com
LinkedIn: https://www.linkedin.com/in/carolina-aguilar-8x

