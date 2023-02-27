Sample Java SpringBoot web app used to demo CI/CD using Azure DevOps and deploying to Azure App Service.

[![Build status](https://dev.azure.com/romeshdharamgudi/java-springboot/_build)]
(https://dev.azure.com/romeshdharamgudi/java-springboot/_build/results?buildId=39&view=results)

CI/CD pipelines on Azure DevOps:
https://dev.azure.com/romeshdharamgudi/java-springboot



# Steps :-

# Create a new project in Azure DevOps and select the appropriate repository type 
![Screenshot 2023-02-18 005913](https://user-images.githubusercontent.com/113555417/219774313-1863e6ec-dd71-4a17-ae20-947796aa6092.jpg)

![Screenshot 2023-02-18 010107](https://user-images.githubusercontent.com/113555417/219774325-d7a721fe-6593-43bc-a3d5-b7f01e00bdfb.jpg)


# Create a new pipeline by clicking on the "Pipelines" tab in the left-hand navigation menu and selecting "Create Pipeline".

![image](https://user-images.githubusercontent.com/113555417/221552383-6269d7e0-cd3b-49ed-964f-2c6842fe3f43.png)

![image](https://user-images.githubusercontent.com/113555417/221552655-f9790c5c-0ff9-4f2d-afd6-d2e3a10655a9.png)


# Select the appropriate template for your build process. For Java applications using Maven, select the "Maven" template.

![image](https://user-images.githubusercontent.com/113555417/221552758-83e61530-5d5f-44f5-8093-8136fa3b8366.png)

![Screenshot 2023-02-18 013202](https://user-images.githubusercontent.com/113555417/219782278-0b8f3577-2b20-4f10-a172-1e23a4b284e4.jpg)

# Save & queue 

![Screenshot 2023-02-18 010143](https://user-images.githubusercontent.com/113555417/219774342-0db73dee-c180-4ed1-9ce4-3308c577c205.jpg)

# Run CI Pipeline

![Screenshot 2023-02-18 010220](https://user-images.githubusercontent.com/113555417/219774364-87b527d5-bfdc-4b8a-884c-ff4fc34f8eaf.jpg)

# Set up your build triggers by specifying when the build should be triggered 

![image](https://user-images.githubusercontent.com/113555417/221554468-2a54a3aa-a43e-4714-8484-ced7a33ea936.png)

![image](https://user-images.githubusercontent.com/113555417/221553982-e62005c4-2c52-49d4-96dc-621b819cf643.png)

![Screenshot 2023-02-18 010257](https://user-images.githubusercontent.com/113555417/219774379-921e26af-4191-4d19-9d25-4c1a22a1584f.jpg)

![Screenshot 2023-02-18 013415](https://user-images.githubusercontent.com/113555417/219782118-1b042dff-ec49-4782-96f7-ac1f37776e48.jpg)

