# Introduction & Goals
The following project encompasses the development of a simple API utilising python's FastAPI framework. The API itself is run locally on on an ubuntu docker contianer utilising WSL-Linux.

The API is based off of simple data pertaining to an actual UK retailer in conjunction with its customers (and associated attributes) as well as invoices of their transactions. 

# Contents
- [Set up and Application code](#Set-up-and-Application-code)
- [Testing and modification](#Testing-and-modification)
- [Conclusion](#Conclusion)

# Set up and Application code 
As per the introduction, the code is organised into a singular file and run on a docker container on my local environment. 

![](/Visualisations/SetUp1.png)
![](/Visualisations/SetUp2.png)

The code itself if organised into a singular file whereby the class for 2 primary objects are declared , namely customer and invoice. 
The subsequent code in the file is fairly straightforward in terms of the structure whereby an instance of the fast API app is initialised along with the various endpoints to interact with the data. 
It is worth nothing that an URL-Link object is utilised to assist in the cross-functionality between the endpoints and provide guidance to the end user. 

![](/Visualisations/Code1.png)
![](/Visualisations/Code2.png)

Once set up , FastAPI automatically generates a neat visual of the coded structure. 

![](/Visualisations/AutoDocumentation.png)

# Testing and modification 
The functionality of the API can be tested from the FastAPI documentation URL. Moreover, FastAPI creates a json file outlaying the visualised structure allowing you to create an environment for testing outside of your local or to be used with say Swagger to generate the workspace to implement the functionality utilising a different framework. 

![](/Visualisations/TestAPI_localhost.png)
![](/Visualisations/UsingPostMan.png)
![](/Visualisations/SwaggerOutput.png)

# Conclusion

Whilst I have experience working with the output of an API , I wanted to see how efficiently I was able to create a backend for such an API to enable a different form of access to data from the internet. 
Such an API can be hosted on the cloud whereby the interaction can be far more secure should you implement the additional features (highlighted on the FastAPI documentation in the text file) and control access in a far more secure manner through the cloud. 

[Add the link to your LinkedIn Profile](https://www.linkedin.com/in/jeremie-verdoodt-7832a4166)
