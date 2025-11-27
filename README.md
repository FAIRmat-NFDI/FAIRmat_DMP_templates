# FAIRmat_DMP_templates

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![FAIRmat](https://img.shields.io/badge/FAIRmat-NFDI-blue)](https://www.fairmat-nfdi.eu/)
[![RDMO](https://img.shields.io/badge/Powered%20by-RDMO-green)](https://rdmorganiser.github.io/)

## 🧩 Purpose
This repository provides a collaborative space for developing, refining, and maintaining data management plan templates on RDMO created by **FAIRmat**.  
These templates are designed to support research data management (RDM) practices within the condensed-matter physics and materials-science communities and to align with the **DMP4NFDI** and related RDM initiatives.

The repository focuses primarily on **catalogues and option sets** in the `.xml` format, that can be imported into any local RDMO instance to support the creation of data management plans (DMPs) and related workflows.

---

## 🌍 Overview
The **FAIRmat RDMO Template** effort aims to:

- Provide a standardized, FAIR-aligned structure for research data management planning in condensed-matter physics and related domains.
- Contribute to the ongoing harmonization of RDMO templates with the *NFDI Template Framework* developed by the *DMP4NFDI*.

### Relevant Resources
- 🧾 **NFDI Template Framework:** [Link](https://doi.org/10.5281/zenodo.16737079)  
- 🧠 **RDMO Documentation:** [Link](https://rdmo.readthedocs.io/en/latest/)  
- 🧩 **FAIRmat DMP guide:** [Link](https://www.fairmat-nfdi.eu/uploads/Area%20F/FAIRmat%2520DMP%2520guide%252022%2520May%25202023.pdf)

## 🛠️ How to Contribute / Make Changes
We welcome contributions of all kinds — from improving catalogue content to correcting typos or suggesting enhancements. 

### 💬 For minor fixes (typos, wording, feedback):
*If you want to report typos, small corrections, or general feedback, you don’t need to edit the XML catalogue.
Simply create an issue:*
- Go to the repository’s [issues tab](https://github.com/FAIRmat-NFDI/FAIRmat_DMP_templates/issues).
- Click **New issue**.
- Describe your suggestion, correction, or feedback clearly.
- If possible, include the catalogue name, question ID, location, or a screenshot.

### 🔧 For catalogue changes or improvements:
*If you want to propose more substantial changes or improvements to an existing FAIRmat RDMO XML catalogue, please follow these steps:*

1. **Clone the repository**
   ```bash
   git clone https://github.com/FAIRmat-NFDI/FAIRmat_DMP_templates.git
   cd FAIRmat_DMP_templates
   ```

2. **Create a new branch for your update**
    ```bash
    git checkout -b update-<catalogue-name>-<yourname>
    ```

3. **Locate and import the latest XML file and load it into RDMO**
    - Navigate to the templates folder and identify the XML file you want to edit.
    - Open your local RDMO instance (you can use a test installation or local Docker setup).
    - Go to the Management → Import section and upload the XML file.

4. **Make changes using the RDMO interface**
    - Modify questions, options, or catalog structures as needed.
    - Follow FAIRmat conventions (e.g., naming, identifiers, question structure).

5. **Export and replace the updated catalogue**
    - Once your changes are complete, export the catalogue again as an XML file.
    - Rename the exported XML file to the same name as the original file. 
    - Save your updated XML file to the same folder and replace the older one.

6. **Commit and push your changes**
    ```bash
    git add <filename>.xml
    git commit -m "Update <catalogue-name> with <short description>"
    git push origin update-<catalogue-name>-<yourname>

7. **Create a Pull Request**
    - Open a pull request (PR) to merge your branch into main.
    - briefly describe: what you changed?, why you made the change?, and any related issue number (Closes #23, etc.)

