# CS5783-LMR-Project

A Comprehensive study of different NER Models (NLP)
This repository contains a comprehensive study of different NLP models for NER task. The problem we are focused on is to extract the lo-cations mentioned in social media posts especiallytwitter text data related to natural disasters over theyears. Since we need to extract the location from textand it is unstructured data, we plan on using exist-ing pretrained BERT models. And to cater to theproblem of Location recognition, we will customizethe BERT model by fine tuning the parameters forNamed entity recognition [3] i.e., BERT based Loca-tion mention recognition (LMR) model. The BERTmodel will be trained using two different approachesthe multi head classification problem where we willcheck for multiple labels as City, State, Country etcfor location types and second model will consist ofa unique label “location”. Using literature, we aretrying to assess and find the best algorithm for LMRproblem. We plan on implementing 3 different ap-proaches – a BERT based model fine tuned for loca-tion recognition, a CRF model, FLAIR based trans-former model. We will be assessing the performanceof the models and give a comparison study for thebest performing Location mention recognition model.We will use metrics like precision, recall, F1 score tocompare the models and finalize the best model.


<img width="459" alt="MicrosoftTeams-image" src="https://user-images.githubusercontent.com/89162639/206357468-d462fc3e-97c5-46a2-ba4c-ee2b8555a532.png">