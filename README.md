# Fellowship.ai
Fellowship.ai code challenge submission

**NLP Challenge:** IMDB Dataset of 50K Movie Reviews to perform Sentiment analysis

**DataSet Used:** [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Challenge Completed in Azure Machine Learning Studio

### What I did:
1. Created an Azure Machine Learning workspace (Via Azure portal)
2. Created a compute instance for development
   ![Screenshot From 2025-04-18 22-38-04](https://github.com/user-attachments/assets/1ae4452f-6a7b-46cc-bf0a-2af5879afd8a)
   ![Screenshot From 2025-04-18 22-46-08](https://github.com/user-attachments/assets/5e2d57e0-fa2f-4e3f-9e78-a42ef98ef898)
   But I utilized a custom compute instance to reduce cloud cost/bill (thus have to install some libraries later)
   
4. Registered the IMDB dataset in Azure ML (on second try, uploaded dataset.csv directly to Jyupter Lab instance)
   
   3.1. Upload to default datastore
   
   ![Screenshot From 2025-04-18 22-32-58](https://github.com/user-attachments/assets/aba2a108-18fa-44e3-af84-e90a0bd1e721)
   
   3.2. Create data asset
   
   ![Screenshot From 2025-04-18 22-33-15](https://github.com/user-attachments/assets/5ed92d2b-bca1-40d3-b196-5adcb8b4daf3)
   
5. Installed some specific libraries in the compute instance (By default, many libraries are already installed)
   ![Screenshot From 2025-04-18 23-04-31](https://github.com/user-attachments/assets/e292fe8d-c232-4912-9c52-805b9155b6ed)
7. Explored & preprocessed the dataset in a notebook
   ![Screenshot From 2025-04-18 23-20-25](https://github.com/user-attachments/assets/0af81ec7-f073-478c-84a5-77236efcbcd7)
   ![Screenshot From 2025-04-18 23-21-35](https://github.com/user-attachments/assets/217c2433-04c9-4000-a2a1-8fca20babe1d)
   ![Screenshot From 2025-04-18 23-22-31](https://github.com/user-attachments/assets/5d5cb035-4b40-4b4e-8dd0-503d69038522)
   
9. Trained the sentiment analysis model
   ![Screenshot From 2025-04-18 23-23-19](https://github.com/user-attachments/assets/a915ac0b-3d50-48ba-b0ae-b9d2ff0e1ec6)
   ![Screenshot From 2025-04-18 23-23-47](https://github.com/user-attachments/assets/bbf1c976-f9f4-4042-88d9-fd848fffb35a)
    
10. Evaluated model performance
![Screenshot From 2025-04-18 23-24-11](https://github.com/user-attachments/assets/34a72699-3b01-4604-be3b-1e07e3dc7568)
![Screenshot From 2025-04-18 23-24-36](https://github.com/user-attachments/assets/3ecdab3d-249f-43bd-875b-deb0c4540e49)

11. Downloaded the trained model
![Screenshot From 2025-04-18 23-24-52](https://github.com/user-attachments/assets/928d9fb6-2945-4cc4-ad9e-877d620cb395)

12. Deploy the model endpoint in Azure for evaluation on new data over public internet (Optional, not in the scope of the challenge)
    (May be I will update this project and try the endpoint idea some days later)
