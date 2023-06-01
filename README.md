# Briefing
This project is a little example of the use of Azure cognitive services from an azure hosted Web App. You can access the currently working project [here](https://msdocs-python-postgres-translate.azurewebsites.net/).

# Setting
If you want to reproduce the results shown here, you first must have an Azure suscription where you must create a resource group with the following resources:
* An azure cognitive services account
* A python web-app service with its attached resources (private DNS, Virtual Network, App Service plan).

![MyResources](./ResourceGroupPIC "a title")

After doing so, you need to fork this repository on your own GitHub and configure your Web-App for continous integration from GitHub, don´t forget to replace the credentials of your own cognitive services account on this [file](./app.py) (lines 10 and 11).

# Using
After you access the service from the link in the briefing, you should see a page like the one bellow, where you write your text in the space and click on "traducir".

![MyPage](./PageFrontPIC "a title")