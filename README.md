<h1>Azure Chatbot with Static Webpage Deployment </h1>

<h2> Project Statement/ Opportunity (Regarding the Need for this Project) </h2>

COVID-19 was one of the worst viruses our community has come in contact with and was also able to cripple our Economy and Health to a state from which recovery was very hard. On 30 January 2021 COVID-19 was declared as Endemic in many parts of the world but there is also a threat of of the fourth wave that we face. It is important for people to know the importance of the precautions that we have to take to avoid another lockdown. A chatbot with inbuilt knowledge base of the basic knowledge may prove helpful and may contribute in spreading important knowledge

<h2> Azure Technologies used </h2>
1  - Azure QnA Maker
2  - Azure Chatbot Services
3  - Azure Storage Blob (Static Webpages)


<h2> Overview of the Technologies used in this project </h2>

COVID-19 chatbot uses the underlying technology of QnA maker service which will be used to prepare the knowledge base for this COVID-19 chatbot, this QnA maker will help us to extract information from various certified health organization sites about the knowledge on COVID-19. Secondary, the Azure Bot (ChatBot) services will be used to publish the simple QnA knowledge Base created. Through this we can develop a Basic Chatbot that can answer basic queries on many platforms such as Facebook messenger, twitter etc. Lastly we will use Azure static webpages present in the Azure Storage Account services to make a website dedicated to the chatbot services which can be made available as a common ground to access the ChatBot regardless of the platform. To make the workflow easier we will be using Azure portal and publish all the steps with screenshots to be uploaded on GitHub.

<h2> Knowledge Base Using Azure QnA Maker</h2>

![plot](https://github.com/Aryaan202/AzureChatbot/blob/main/Screenshots/1.png)


Here is the proof of the knowledgebase present and all the questions in it corresponds to the csv file uploaded
![plot](https://github.com/Aryaan202/AzureChatbot/blob/main/Screenshots/2.png)
![11](https://user-images.githubusercontent.com/86037152/176746075-9d8fae82-c70c-41b7-adcf-780daa416924.png)



HTTPS Request url : POST /knowledgebases/d822ee9c-7004-4b07-a6eb-5d374ad013c8/generateAnswer
Host: https://covid-qna-final.azurewebsites.net/qnamaker
Authorization: EndpointKey 02c645ce-bfd3-4d7c-8d8a-87a0c8ae4fc7
Content-Type: application/json
{"question":"<Your question>"}
  
  
  <h2> Publishing The bot using Azure Chatbot (Proof Screenshots) </h2>
  ![3](https://user-images.githubusercontent.com/86037152/176742746-f21e9ee3-c5ee-45f1-a639-c68aca397526.png)
  
  Framework -
  ![5](https://user-images.githubusercontent.com/86037152/176742828-173ebc44-16ab-476b-a507-7d23a57f4468.png)
![6](https://user-images.githubusercontent.com/86037152/176742834-e528c2da-cb1d-4fe6-91ed-ef3196d2e21f.png)
  
  Active Channels - 
  
![4](https://user-images.githubusercontent.com/86037152/176742875-73b2c3cc-086a-4311-8a21-524b00989c1b.png)
  
  Deployment Details - 
  
  ![7](https://user-images.githubusercontent.com/86037152/176742947-72af33ce-81c7-407b-aa0c-7f63fe3a30e4.png)

  
  <h2> Azure Storage Blob (Static Web Page) </h2>
  

  ![8](https://user-images.githubusercontent.com/86037152/176743087-8bd4964f-bfce-477f-8e5b-e79423097459.png)
  
![9](https://user-images.githubusercontent.com/86037152/176743500-01b95f68-8664-4e01-8da2-8640e70dc4a9.png)


Check the QnA File to check for the eligible questions..
and wait for 1-2 minutes after startup for responsiveness.

To Access the project - 
Go to link  -- https://aryan2022.z13.web.core.windows.net/
  
  <h2> Microsoft Azure Dependencies</h2>
  
  The Modules mentioned in the Project file are core connection modules for Azure QnA Bot for this project and use used for deployment and is Mentioned in the file of
  QnAbot project in the Bot Source code branch of the main repository.
  ![10](https://user-images.githubusercontent.com/86037152/176745813-fc4fcf95-2fd4-41fd-8359-f00f92b81ad8.png)
  
  Working - 
  

https://user-images.githubusercontent.com/86037152/176748899-c9a606e2-9340-4151-99c7-70048e9c40bf.mp4



  
