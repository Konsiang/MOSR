# MOSR: Stationary Algorithmic Balancing For Dynamic Email Re-Ranking Problem

Dataset come from kaggle at https://www.kaggle.com/datasets/acsariyildiz/the-enron-email-dataset-parsed
The dataset(sorted_emails1.csv) could be download at https://drive.google.com/drive/folders/19FjAjzdQMP6DZUo036DxKUG-KxXR5n5d?usp=sharing Please put it in data/
data/organization2.csv is crawled by us. And it is already in data/ folder.

## To run our code:
cd code
## generate the .json file we need
python check_data_distance_2.py  

Or you can download .json file directly at https://drive.google.com/drive/folders/19FjAjzdQMP6DZUo036DxKUG-KxXR5n5d?usp=sharing, then
## OWA_1 
python model_new.py --md 10 -v 0 -lr 0.99

## OWA_2
python model_new2.py --md 10 -v 0 -lr 0.99

## Evaluate Result
python evaluate_results.py 
