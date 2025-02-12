# Interactome-Analysis-Tool

This interactome analysis platform identifies potential signaling interactions between cell types of interest using transcriptomic data provided by the user and a curated ligand-receptor database.

### To play around with the application you need two input files or use existing datasets

To use this platform, 2 input files are required- (1) gene expression data from the cell type(s) providing the ligands, and (2) gene expression data from the cell type(s) that are receiving the signal with receptors (Input data should be formatted as indicated in the template).

The platform will generate a large table of all possible interactions between the ligand cells and the receptor cells, and this can subsequently be filtered and ranked using criteria defined by the user.

The platform will also generate a sankey plot file that can be used to visualize the top interactions. The Final stage results need to be copied and pasted into the [SankeyMATIC](https://www.sankeymatic.com/build/) page embedded into the "Explore"  tab in the application.

### Using the Shiny Application
#### Detailed Step-by-Step Guide

This web application has an interactive interface for easy utilization of the interactome tool. You can use the Shiny application for interactome analysis by following these steps:
1. Navigate to the [Shiny application](https://sensoryomics.shinyapps.io/Interactome/).
   
2. You have the option to either upload your ligand and receptor data or use the existing data provided by the application.
 ![Step1](images/your-image.png)
3. Follow the step by step instructions in the application to run the interactome analysis.

For a more detailed step-by-step guide on using the [Shiny application](https://sensoryomics.shinyapps.io/Interactome/), refer to the attached "Interactome Application - User Guide.pdf" file.

## Notes
- Ensure all necessary data files are in the correct format as sample input format shown in the Shiny application.
- For any issues or questions on application, please open an issue in this repository.

---
Feel free to provide your valuuable feedback on the tool, any modifications or suggestions are welcome!
