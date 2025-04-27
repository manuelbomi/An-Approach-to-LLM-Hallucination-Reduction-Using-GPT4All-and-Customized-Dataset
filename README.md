# An-Approach-to-LLM-Hallucination-Reduction-Using-GPT4All-and-Customized-Dataset


### **OVERVIEW**
In this discourse, we show how GPT4All can be installed on an enterprise system and how models can be used along with selected dataset in order to reduce the model's hallucination and thus improve on the model's reponse to queries. 

As an illustrative example, Hertz Global Holdings Inc. publicly available datasets (available here: https://github.com/manuelbomi/A-Method-of-Retriever-Augmented-Generation-Implementation-on-GCP-Vertex-AI- )  are used for a case study

---

### **Background Discussion**
GPT4All is a free, open-source ecosystem that allows users to run large language models (LLMs) locally on their own computers, without needing an internet connection or a powerful GPU. It provides a platform for interacting with LLMs through a chat interface and also supports using local documents as information sources. GPT4All is open-source, meaning the code is freely available for anyone to use, modify, and contribute to. It is also completely free to use, with no licensing fees or subscriptions required. 

---
To start using GPT4All to improve LLM's response to queries, install it and after installation, open it and use it to upload a high quality dataset that you intend to use as part of the database for your LLM

---

Select folder and create collection

![Image](https://github.com/user-attachments/assets/67c01372-6b8a-4307-ae1f-f3fba555d562)
---

 

![Image](https://github.com/user-attachments/assets/c72a9d87-de7f-415d-a34f-22bde1c47a11)

---
GPT4All will index the files. It may take some time depending on the your data volume.


![Image](https://github.com/user-attachments/assets/e9f082fd-21f2-4f1e-8069-484947537272)

---
GPT4All will turn your document into a vector embedding. That will also take some time based on your file volume.


![Image](https://github.com/user-attachments/assets/5e762afe-cd0a-4b12-a1f2-3a354850fed7)

---
You must add LLMs (models) to your GPT4All if this is your first time of use. Go to models. Add model.


![Image](https://github.com/user-attachments/assets/762cb382-6c25-4f7e-83b3-4b63b90d0b5b)

---
Explore and download models


![Image](https://github.com/user-attachments/assets/b93ff91e-78cc-48e2-92c2-5716a1e26502)

---

![Image](https://github.com/user-attachments/assets/65a1c0d4-5e42-4cba-af4b-933b87c4fe62)

---

![Image](https://github.com/user-attachments/assets/0196a8fe-d463-4665-8eab-214ef188bf18)

---
In this discourse, llama 3.2 b selected due to its low RAM (memory) use
You may also choose remote providers
You can also browse for and choose models from Huggingface
Installed models will be under existing model

![Image](https://github.com/user-attachments/assets/6718147c-06f8-4f94-b17a-dc9b9a160f2d)

---
Go into chat

![Image](https://github.com/user-attachments/assets/29a2f9d3-4576-4158-ba3f-6f5665c965b0)

---
12 c result retuend with references
12 go to local docs and select the Hertz docs repo
12 select an installed model and chat

![Image](https://github.com/user-attachments/assets/aa34c6ba-5bfa-47ed-a0c6-509d9b72b2e9)
![Image](https://github.com/user-attachments/assets/69a76dbc-3a4a-4933-bddb-e0549569d66f)
![Image](https://github.com/user-attachments/assets/1fe7e5d1-7444-44de-8252-af42749a2825)

---
13 load model and chat

![Image](https://github.com/user-attachments/assets/92896a90-98b4-4cfa-a515-f8243cc33720)

---
14 follow up questions

![Image](https://github.com/user-attachments/assets/4da427f5-45e4-4796-a3d0-df8bdc14e38d)

---
15 suggested follow up questions
![Image](https://github.com/user-attachments/assets/7b18e4f2-3511-46c9-9dfb-0041cb1e9c7e)
![Image](https://github.com/user-attachments/assets/2c49ec1b-c0f9-4609-a7aa-5571b5376eba)

![Image](https://github.com/user-attachments/assets/233d1367-d668-4393-a595-f03b68c95c60)





---
Thank you for reading through

---

Author's Background

```

Author's Name:  Emmanuel Oyekanlu
Skillset:   I have experience spanning several years in developing scalable enterprise data pipelines, architecting enterprise data solutions, deep learning and LLM applications as well as deploying solutions (apps) on-prem and in the cloud. I can be reached through: manuelbomi@yahoo.com
Website:  http://emmanueloyekanlu.com/
Publications:  https://scholar.google.com/citations?user=S-jTMfkAAAAJ&hl=en
LinkedIn:  https://www.linkedin.com/in/emmanuel-oyekanlu-6ba98616
Github:  https://github.com/manuelbomi

```

[![Icons](https://skillicons.dev/icons?i=aws,azure,gcp,scala,mongodb,redis,cassandra,kafka,anaconda,matlab,nodejs,django,py,c,anaconda,git,github,mysql,docker,kubernetes&theme=dark)](https://skillicons.dev)



