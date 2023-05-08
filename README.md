# DRAGON

Pytorch implementation for "Enhancing Dyadic Relations with Homogeneous Graphs for Multimodal Recommendation"

## Data
Data could be download from xx: [Baby/Sports/Clothing](xx)  
## Run the code
1. Download the data from the data link we provided above, then put the download data to the ./data folder
2. Use ```conda env create -f dragon.yml``` to create the enviroment with correct dependencies
2. Run generate-u-u-matrix.py on the dataset you want to generate the user co-occurrence graph
3. Enter the src folder and run with
`python main.py -m DRAGON -d dataset_name`  
## The parameters to reproduce the result in our paper
| Datasets | learning rate | reg weight |
|----------|--------|---------|
| Baby     | 0.0001      | 0.001     |
| Sports   | 0.0001      | 0.001     |
| Clothing     | 0.0001      | 0.1     |

