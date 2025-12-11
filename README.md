# MOSR: Stationary Algorithmic Balancing For Dynamic Email Re-Ranking Problem

The dataset(sorted_emails1.csv) could be download at https://drive.google.com/drive/folders/19FjAjzdQMP6DZUo036DxKUG-KxXR5n5d?usp=sharing Please put it in data/

data/organization2.csv is crawled by us. And it is already in data/ folder.

## To run our code:
cd code
## generate the .json file we need
python check_data_distance_2.py  

Or you can download .json file directly at https://drive.google.com/drive/folders/19FjAjzdQMP6DZUo036DxKUG-KxXR5n5d?usp=sharing, then
## EnronA 
python model_new.py --md 10 -v 0 -lr 0.99
