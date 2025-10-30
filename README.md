<div align="center">

# 📘 Introduction to R Programming  
### *A Gentle and Short Start*

[![RMarkdown](https://img.shields.io/badge/Made%20with-RMarkdown-276DC3?logo=r&logoColor=white)](https://rmarkdown.rstudio.com/) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GitHub Repo](https://img.shields.io/badge/GitHub-statskaren%2FGentle--Introduction--to--R-blue?logo=github)](https://github.com/statskaren/Gentle-Introduction-to-R)

</div>

---

 **# Author:**
  Karen Gomes
📧 kare.kgomes@usp.br
🎓 MSc Student in Public Health – University of São Paulo
🏥 HTA Assistant – NATS/UNIFESP-Diadema
💻 Focus: R | Biostatistics | Causal Inference

---

What you’ll learn:

This tutorial walks through the essential foundations of R programming, from the very first command to data visualization.
It’s ideal for **beginners, students**, and anyone starting to explore data analysis in R, using inbuilt functions.

Section Overview:

| Section | Topic | Description |
|----------|--------|-------------|
| **1.1** | Interacting with R | Basic commands and using R as a calculator |
| **1.2** | Working with Variables | Assigning and manipulating objects |
| **1.3** | Vectors | Creating, accessing, and modifying vectors |
| **1.4** | Matrices | 2D data structures and indexing |
| **1.5** | Data Types | Numeric, character, and logical data |
| **1.6** | Logical Operations | Boolean expressions and filtering |
| **2.1–2.3** | Functions | Built-in functions, numerical and statistical operations |
| **3.1–3.3** | Data Frames | Creating, reading, and modifying tabular data |
| **4.1** | Manipulating Data | Filtering, sorting, and computing descriptive stats |
| **5.1** | Graphs | Plot, hist, and boxplot in base R |
| **6.1** | Closing | Final notes and encouragement to keep learning |

---
  
  ## Structure and main files
  
  Each chapter of the book has its own folder with R Markdown files and outputs:
  
  ```bash
📁 Gentle-Introduction-to-R/
├── 📄 introduction_to_R.Rmd          # Main R Markdown file
├── 📄 template.odt                   # ODT template for rendering
├── 📁 data/                          # Example datasets used in the tutorial
│ ├── 📄 athletes_data.csv
│ ├── 📄 modified_athletes_data.csv
└── 📁 figures/                       # Graphs generated in Section 5
  ```  
---

  Now, we're gonna see how to reproduce, step by step

# 1. Download or clone this repository:
git clone https://github.com/statskaren/Gentle-Introduction-to-R.git

# 2. Open in RStudio:  
Open the introduction_to_R.Rmd file in RStudio.

# 3.Render the tutorial to generate a .odt file:
rmarkdown::render("introduction_to_R.Rmd",
                  output_format = "odt_document",
                  output_file = "Introduction_to_R.odt",
                  output_options = list(reference_odt = "template.odt"))
                  
📝 Note:
Make sure that the file template.odt is in the same directory as your .Rmd.
This ensures your rendered document keeps the custom formatting you defined (fonts, spacing, etc.).

The template was made in .odt format using LibreOffice, but you can also use Microsoft Word by saving it as .docx.
The objective of this template is to follow the main academic styles used in Brazil (Vancouver and sometimes ABNT).
With this .odt or .docx document, you can save everything that you've done in R and share it with others.

# 4. Explore and modify the code:
#You can modify any chunk of code and save as a R script, for example.
#Feel free to change variables or replace the example dataset (athletes_data.csv) with your own data.

# 5. Share and collaborate:
#If you find any errors or have suggestions, please open an issue or submit a pull request.
#Feel free to send me an e-mail!

---
  
  ## License
  
  This project is licensed under the MIT License - see the LICENSE file for details.
  
  ---
  
  ## Citation
  
If you use or adapt this tutorial in your course or project, please cite:
Gomes, K. (2025). Introduction to R Programming: A gentle and short start. GitHub Repository. https://github.com/statskaren/Gentle-Introduction-to-R.git