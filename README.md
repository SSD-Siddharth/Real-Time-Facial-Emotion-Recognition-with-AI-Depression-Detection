# Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection
![image](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/dd42a141-a96c-44d1-8eee-3d1dff03dbd0)

* **Unique and Novel feature of our project,** 
We  were able to get the real time Emotion of the User and save it in a dataset, which will be really helpful to learn about the User’s Emotion history and can also be used to Cure Depression, know and warn about Stress, etc.

![image](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/175ac9a6-77cb-4d09-93cb-3df1bd1f7108)

![image](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/2e688f2b-69ea-49f6-bd74-4502d4472e49)


## Highlights of our Work:
* **1.**	Increased Dataset size from 33k to 40k by combining CK+ dataset(link, ) and fer2013 
![image](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/d2d149c6-5f4d-4d5f-9051-1d430d463008)

* **2.**	We did batch Normalization and CNN+ResNet50(instead of CNN alone)
* **3.**	Architectural Change, they used 4 layers CNN, and we did 6 layers CNN along with 48 layers 
* **4.**	They did from the compressed .csv data, and we did with Original dataset that has all the images. Initially after 20 epochs our accuracy was: 56% 
![image](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/1b482018-3080-41dc-95f2-2925e8649c0f)

* After doing the normalizations and adding CNN layers, different types of optimizers+Algorithms, we were able to achieve 66%. Which was somewhat same as the Research Paper’s values
* **5.** After this, as we proved that the data had inconsistent values, so we combined 2 datasets, i.e., the FER2013 dataset along with CK+ dataset which contains 593 video sequences from a total of 123 different subjects, ranging from 18 to 50 years of age, again tried. The results weren’t satisfiable, so after seeing the comparison, we came to know that if we add more CNN layers, then the accuracy can be increased, so we used ResNet50 model, with has 48 Convolution layers, and were able to achieve an Accuracy of 76%(after adding more epochs+data, we can even make it up to 79%, as overfitting wasn’t happening).
![image](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/badaf438-ee4a-43cd-bdfa-6b34a571cda9)
![image](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/0a433bbe-c2c3-4780-b3aa-4cf2103a0428)



![2022-04-27 16_24_16-](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/4f507489-615a-46ba-896c-b36bb88efda9)
![2022-04-25 11_53_27-](https://github.com/SSD-Siddharth/Real-Time-Facial-Emotion-Recognition-with-AI-Depression-Detection/assets/72315144/fc9fe271-fe1a-4370-80f7-d731340be40e)


### Group Members:
- Siddharth Shankar Das
- Prithvi MR
- Rakesh Kumar KS
