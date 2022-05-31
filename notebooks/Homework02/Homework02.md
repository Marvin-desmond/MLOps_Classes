python preprocess_data.py --raw_data_path ../../datasets --dest_path ./output
mlflow ui --backend-store-uri sqlite:///output/homework02_01.db
