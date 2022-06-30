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

HTTPS Request url : POST /knowledgebases/d822ee9c-7004-4b07-a6eb-5d374ad013c8/generateAnswer
Host: https://covid-qna-final.azurewebsites.net/qnamaker
Authorization: EndpointKey 02c645ce-bfd3-4d7c-8d8a-87a0c8ae4fc7
Content-Type: application/json
{"question":"<Your question>"}



Check the QnA File to check for the eligible questions..
and wait for 1-2 minutes after startup for responsiveness.

To Access the project - 
Go to link  -- https://aryan2022.z13.web.core.windows.net/
