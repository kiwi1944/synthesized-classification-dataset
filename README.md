# synthetized-classification-dataset
This is the synthetized dataset used for paper "Integrated Communication and Learned Recognizer with Customized RIS Phases and Sensing Durations".

The dataset inludes five kinds of objects: toy cars, humans, pets, potted plants, and tables. Each of them possesses 1,200 gray images. Thus, the dataset is composed of 6,000 images.
Each of the images has been resized to 30x30.
This dataset can be utilized for training classification networks with radios signals, as studied in our paper.

The original images of the categories of toy cars, humans, pets, and potted plants come from segmentation datasets in Kaggle:

toy-car: "Carvana image masking challenge," https://www.kaggle.com/c/carvana-image-masking-challenge

human: "Human segmentation dataset - tiktok dances," https://www.kaggle.com/datasets/tapakah68/segmentation-full-body-tiktok-dancing-dataset

pet: "The oxford-iiit pet dataset with annotations," https://www.kaggle.com/datasets/julinmaloof/the-oxfordiiit-pet-dataset

pot-plant: "Synthetic rgb data for grapevine detection," https://www.kaggle.com/datasets/carmenca/synthetic-rgb-data-for-grapevine-detection

The original images in these datasets are first tailored to delete empty margins and then resized to a same resolution.

The table images are generated by MATLAB through our personal codes.
