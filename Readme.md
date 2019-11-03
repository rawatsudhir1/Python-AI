# Python + AI
This repo contains how to run image classification example using Microsoft cognitive services  and Python. 


## Prerequiste
- Python 3.7
- Microsoft Azure Subscription


## Hands on

1. If you don't have Azure subscription then create [Azure trial account](https://azure.microsoft.com/en-us/free/?wt.mc_id=AID2463800_QSG_SCL_361865&ocid=AID2463800_QSG_SCL_361865&utm_medium=Owned%20%26%20Operated&utm_campaign=FY20_APAC_Dev%20Community_CFT_Internal%20Social)

2. Clone a repo using below command on your disk

```
git clone https://github.com/rawatsudhir1/Python-AI.git

```

3. Open [Custom Vision](https://www.customvision.ai/) in a browser
 ![SignIn](/HandsOnImages/0.png)


4. Sign in with the account you used for seeting up Azure Subscription

5. Click **NEW PROJECT**
![NewProject](/HandsOnImages/1.png)

6. On the screen **Ceate new project** provide Name, Description (optional) 
![CreateNewProject](/HandsOnImages/2.png)

7. On **Resource** drop down menu, if no value is there then click **create new**

8. On **Create New Resource** provide Name, Subscription, Resource Group (create new resource group if you want), Kind, Location, Pricing Tier
![CreateNewResource](/HandsOnImages/3.png)

9.  For creating a new Resource Group (click new for Resource Group as mentioned above), provide Name and Location 
![CreateNewResourceGroup](/HandsOnImages/3-1.png)

10. Once all the information provided click **Create resource**
![CreateNewResourceGroup](/HandsOnImages/4.png)

11. Once resources got created, select **Project Types**, **Classification Types**, **Domains** and click **Create Project**
![CreateProject](/HandsOnImages/5.png)

12. Once project creation done, Click **Add images**
![AddImages](/HandsOnImages/6.png)