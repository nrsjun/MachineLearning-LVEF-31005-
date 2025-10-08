# MachineLearning-LVEF
This repo is for my machine learning UTS project about LVEF 

# Step 1:
Install jupyter notebook
Key Dependencies
PyTorch – model training & inference
OpenCV – video & image processing
NumPy / Pandas – data handling
Matplotlib / Seaborn – visualizatin
tqdm – progress bars
wandb – experiment trackin
pyCompare – Bland altman analysis
 
# Step 2: 
Download the echonet dynamic file and place it inside the same folder
Link: https://echonet.github.io/dynamic/

# Step 3:
Run the notebooks

notebooks are:
1. task1_create_segmentation : used to create the segmentation mask (combination of my own work and then AI to help with using a centroid and morphological dilation

2. task2_video_segmentation : used to preprocess the videos, create dataloader (with AI), create UNET model (entirely from scratch after watching youtube videos), loss, optimiser, scheduler

3. task3_measure_lvef: mostly AI coded due to time constraints and scope creep

4. segmentation_mask_testing: the notebook used to test how various methods of mask creation performed

5. stat_analysis.ipynb: the final notebook that was used to analyse the results from the 'final_filtered_results_75px.csv' -- used to make the conclusions and analyse improvements

