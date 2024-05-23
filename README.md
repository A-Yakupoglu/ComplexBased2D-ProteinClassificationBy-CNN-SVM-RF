# ComplexBased2D-ProteinClassificationBy-CNN-SVM-RF
#### Protein/amino acid sequences are represented with 2D images with a new complex-based approach proposed in this project. These images are then classified using Support Vector Machines (SVM), Random Forests (RF) and Convolutional Neural Networks.

## THE STUDY PROCEEDS IN THE FOLLOWING STEPS:

### STEP 1: (DATA IMPORT) 
Amino acid sequences of kinase and GPCR proteins are imported separately in fasta form from the NCBI gene bank using accession numbers.

### STEP 2: (DATA PREPROCESSING) 
The amino acid sequences of kinase and GPCR proteins are labeled as “1” and “0”, randomly shuffled and saved as a single data frame in fasta form.

### STEP 3: (COMPLEX CODING) 
The data frame in fasta form is converted into complex numbers with our proposed Complex Encoding Method and saved as a complex-valued data frame.

### STEP 4: (CONVERSION TO 2D IMAGES) 
The amino acid sequences converted into complex numbers are converted into 2D images to create a meaningful and distinct pattern specific to each protein and to be given as input to neural networks. The images are labeled and saved as a new 2D image data frame.

### STEP 5: (CNN-2D PROTEİN CLASSIFICATION) 
2D complex image data representing kinase and GPCR proteins are classified using Convolutional Neural networks.

### STEP 6: (SVM-2D PROTEİN CLASSIFICATION) 
2D complex image data representing kinase and GPCR proteins are classified using Support vector machines.

### STEP 7: (Random Forest-2D PROTEİN CLASSIFICATION) 
2D complex image data representing kinase and GPCR proteins are classified using Random Forest.
