# Targetless Drug Discovery Pipeline

The code here is an implementation of the idea presented in the conference IEEE BIBM 2021, through a paper called **Target-less Drug Discovery Pipeline using Feature Driven Development (FDD) model**. The content can be accessed here at IEEExplore: https://ieeexplore.ieee.org/document/9669585. I'm open sourcing the implementation here on Github as the primary author of this work.

This document aims to provide a brief user manual that could help users run this
project in a straightforward manner. Comments have been added in the notebook
as well, for better understanding.
The steps are as follows:
1. The first step is to open the concerned Google Colab notebook available in this repository.
2. This file is viewable only - changes can be made but won't be saved. Hence, the 
user needs to click on the 'File' menu, and choose 'Save a copy in Drive'. This will
create an editable copy of this notebook.
3. The user then needs to make sure that all the necessary model files are either
uploaded in the session storage (accessible from the Folder icon on the right),
or in their Google drive itself, exactly as provided in the supplied 'Necessary
Uploads' folder. If present in drive, they may need to mount the Drive, for
which the code block has been clearly indicated. This folder is available here -
https://drive.google.com/drive/folders/186OZQBjX1mJEO5blm2xYKvaHQ_o2e81e?usp=sharing
4. Depending on step 3, the user needs to update all directory paths, in the
predictive code blocks.
5. The user can then proceed to running the notebook. First few blocks are re-
sponsible for installation of the necessary libraries in the Colab environment.
Without them, important functionalities might break.
6. The user provides the required inputs in the input form.
7. All the code blocks after this can be run one by one after this. One may
choose to skip certain blocks if those properties are not required.
8. The final output file i.e. Res.csv will be available in the session storage,
downloadable for reference.
9. The chemical 2D structures can be seen at the end of the file.
