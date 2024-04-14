# CI/CD Pipeline for Streamlit Python App with Docker and Render.com

# [Checkout Medium Article at](https://medium.com/geeky-bawa/master-ci-cd-using-github-actions-your-ultimate-guide-to-build-test-and-deploy-e8af9fdb6057)
## [Checkout Live Model Api at ](https://cicd-with-streamlit.onrender.com/):[https://cicd-with-streamlit.onrender.com/)
```
[https://cicd-with-streamlit.onrender.com/]
```
[Deployed Model](https://cicd-with-streamlit.onrender.com/)



 # Overview
 <img src ="images/1.PNG">

This repository demonstrates how to set up a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Python application built with Streamlit using GitHub Actions. The pipeline automates the process of building a Docker image for the Streamlit app, deploying it to Docker Hub, and then deploying it on Render.com.

### Prerequisites
Before getting started, ensure you have the following:

- A GitHub account
- Docker installed locally
- Accounts on Docker Hub and Render.com
- Docker Hub access token and Render.com API key (to be stored as secrets in your GitHub repository)

### Steps to run
To run Server on Local machine 
'''
streamlit run app.py
'''



## Workflow Overview

The CI/CD pipeline consists of two stages:

* Build Stage: This stage builds the Docker image for the Streamlit app and pushes it to Docker Hub.
* Deploy Stage: This stage deploys the Docker image from Docker Hub to Render.com using the Render API.

## Setting Up Secrets
To securely store your Docker Hub access token and Render.com API key, follow these steps:

- Go to your GitHub repository.
- Navigate to "Settings" > "Secrets" > "New repository secret".
- Add the following secrets:
- `DOCKERHUB_TOKEN`: Your Docker Hub access token.
- `RENDER_API_KEY`: Your Render.com API key.

## Workflow Configuration
The workflow is defined in the 
'''
.github/workflows/main.yml file.
'''
It consists of two jobs: build and deploy.

Workflow Configuration
The workflow is defined in the .github/workflows/main.yml file. It consists of two jobs: build and deploy.
============================================================================ 



# Resources 

To learn more about these Resources you can Refer to some of these articles written by Me:-

- [Medium](https://medium.com/geeky-bawa)
- [geeky Traveller](https://sites.google.com/view/geeky-traveller/)
- [Blogs](https://github.com/vaibhavhariaramani/blogs)
- [Youtube](https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)[![Youtube Badge](https://img.shields.io/badge/-Geeky_Bawa-1ca0f1?style=flat-circle&labelColor=d54b3d&logo=youtube&logoColor=white&link=https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)](https://www.youtube.com/channel/UCy7amUpLnsRLEMIaJGGBYog)

### Don't forget to tag us

if you use this repo in  your project don't forget to mention us as Contributer in it . And Don't forget to tag us [Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/),[ instagram](https://www.instagram.com/geeky_baba_/?hl=en),[ facebook](https://www.facebook.com/jayesh.hariramani.3) ,[ twitter](https://www.linkedin.com/in/vaibhav-hariramani-087488186/), [ Github](https://github.com/vaibhavhariaramani) 

============================================================================
# Made with ❤️by Vaibhav Hariramani
#### About me

I am a Machine Learning enthusiast, an Actions on Google, Internet of things, Alexa Skills, and Image processing developer.
I have a keen interest in Image processing and Andriod development.
I am Currently studying at  Chandigarh University, Punjab.

[My PortFolio](https://vaibhavhariaramani.github.io/)
You can find me at:-
[Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/) or [Github](https://github.com/vaibhavhariaramani) .

Email: [vaibhav.hariramani01@gmail.com](mailto:vaibhav.hariramani01@gmail.com)


# Download [THE VAIBHAV HARIRAMANI APP](https://play.google.com/store/apps/details?id=com.geeky.developer)

# [<img src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/gh-bannner-light.png">](https://play.google.com/store/apps/details?id=com.geeky.developer) 
<p align='center'>
<a href="https://www.linkedin.com/in/vaibhav-hariramani-087488186/"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/linkedin.png"></a>&nbsp;&nbsp;
<a href="https://twitter.com/vaibhavhariram2"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/twitter.png"></a>&nbsp;&nbsp;
<a href="https://www.instagram.com/vaibhav.hariramani/?hl=en"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/instagram.jpg"></a>&nbsp;&nbsp;
<a href="https://www.buymeacoffee.com/vaibhavJii"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/by-me-a-coffee.png"></a>
<a href="https://wa.me/+917790991077"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/whatsapp.png"></a>&nbsp;&nbsp;
<a href="mailto:vaibhav.hariramani01@gmail.com"><img height="30" src="https://github.com/vaibhavhariaramani/vaibhavhariaramani/blob/master/icon/email.png"></a>&nbsp;&nbsp;
</p>


[<img width="150" align='center' src="https://archive.org/download/download-button-png/download-button-png.png">The Vaibhav Hariramani App (Latest Version) ](https://play.google.com/store/apps/details?id=com.geeky.developer)

Download [THE VAIBHAV HARIRAMANI APP](https://play.google.com/store/apps/details?id=com.geeky.developer) consist of Tutorials,Projects,Blogs and Vlogs of our Site developed Using Android Studio with Web View try installing it in your android device.

Happy coding ❤️ .
