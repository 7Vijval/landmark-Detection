## Dataset & Model

Images dataset and trained model are available here:

train.csv: CSV with id,url,landmark_id fields. id is a 16-character string, url is a string, landmark_id is an integer. Available at: https://s3.amazonaws.com/google-landmark/metadata/train.csv.

Downloading the data
The train set is split into 500 TAR files (each of size ~1GB) containing JPG-encoded images. The files are located in the train/ directory, and are named images_000.tar, images_001.tar, ..., images_499.tar. To download them, access the following link:

https://s3.amazonaws.com/google-landmark/train/images_000.tar
