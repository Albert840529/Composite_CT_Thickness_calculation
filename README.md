# Composite_CT_Thickness_calculation in Paper:\n https://doi.org/10.1039/D3MH01976D 
This is the code for calculating the thickness of CaSO4 domain in the paper.

CT-images dataset: For the access of the data set, please click on the following link: https://drive.google.com/drive/folders/1M4rYcE8KqSGjYIP5dHxOa0G2gUy6G3wt?usp=share_link

Data folder naming rule: In the folder Images, it contains all the µ-CT images that we analyzed. Each subfolder contains 100 images and one csv file that contain the name of each image and the features of each image. The subfolder name represents the name of each composite and the represents mechanical properties. For instance, IPP_5%_4_0.44_1.403_0.245, IPP_5%_4 is the name, 0.44 is the UTS(MPa), 1.403 is the young’s modulus(GPa), and 0.245 is the elongation at break(%). This naming method is related to how I do data preprocessing in the code.

