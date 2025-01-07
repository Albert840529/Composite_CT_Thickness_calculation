# Composite_CT_Thickness_Calculation

This repository contains code for calculating the thickness of CaSO4 domains as described in the paper: [Upcycling Plastic Waste into Fully Recyclable Composites through Cold Sintering](https://doi.org/10.1039/D3MH01976D) (DOI: 10.1039/D3MH01976D).

## Dataset

### CT-Images

The dataset used for this analysis can be accessed via the following link:
[CT-Images Dataset](https://drive.google.com/drive/folders/1M4rYcE8KqSGjYIP5dHxOa0G2gUy6G3wt?usp=share_link)

### Data Folder Naming Rule

- **Folder Structure**: In the `Images` folder, you will find all the µ-CT images analyzed. Each subfolder contains:
  - 100 images
  - One CSV file with the name and features of each image

- **Subfolder Naming**: Each subfolder name represents the name of the composite and its mechanical properties. The naming convention is as follows:
  - `IPP_5%_4_0.44_1.403_0.245`
    - `IPP_5%_4`: Name of the composite
    - `0.44`: UTS (MPa)
    - `1.403`: Young's modulus (GPa)
    - `0.245`: Elongation at break (%)

This naming convention is used in the data preprocessing code to match the images with their properties.

## Usage

1. **Download the dataset** from the provided [Google Drive link](https://drive.google.com/drive/folders/1M4rYcE8KqSGjYIP5dHxOa0G2gUy6G3wt?usp=share_link).
2. **Place the images and CSV files** into the `Images` folder as described in the data folder naming rule.
3. **Run the provided code** to calculate the thickness of CaSO4 domains. Detailed instructions on how to use the code are included in the provided notebooks/scripts.

## Note

Ensure that the data folder structure matches the expected format to avoid errors during processing. If you have any questions or issues, feel free to open an issue on this repository.

