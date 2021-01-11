# HackTheNorth2021
Workshop instructions for Hack the North 2021

## Table of Contents
- [Resources](#resources)
- [Instructions](#instructions)

## Resources


## Set up
1. Register or login to the [IBM Cloud](https://cloud.ibm.com).
1. Go to the [catalog](https://cloud.ibm.com/catalog) in the header.
1. [Filter by Software](https://cloud.ibm.com/catalog#software) in the left nav.
1. Under the Software category, select the checkbox for [Starter Kits](https://cloud.ibm.com/catalog?search=label%3Aboilerplate#software).
1. Select the [Natural Language Understanding Node.js App](https://cloud.ibm.com/developer/watson/create-app?defaultDeploymentToolchain=&defaultLanguage=NODE&env_id=ibm%3Ayp%3Aus-south&navMode=starterkits&starterKit=b62c00f1-65b2-38a4-9f91-d429fb6745a6) boilerplate.
1. Click the `Create` tab.
1. Leave the defaults and click the `Create` button.
1. Click `Deploy your app` once the boilerplate is created.
1. Create a [Cloud Foundry org](https://cloud.ibm.com/account/cloud-foundry) if you don't already have one. We recommend using `Washington DC` as the region.
1. Select `Cloud Foundry` as the deployment target (you may have to refresh if you just created an org). Ensure the region you have selected is the one you have a Cloud Foundry org and space in.
1. Create a new `IBM Cloud API key`. You may want to save this for the future so you don't have to re-create it every time. Then click `OK`.
1. Note the region you have selected on this page and then click `Next`.
1. We recommend changing the region if necessary to the same region you chose in the previous step and then click `Create`.
1. Wait for the toolchain to finish creating.

## Using your toolchain
1. Once the toolchain is created, you can always go to it by going to the [DevOps section](https://cloud.ibm.com/devops) of IBM Cloud and clicking the top left hamburger menu and clicking `DevOps`.
1. Once it is created, you can watch your app build and deploy by clicking the `Delivery Pipeline` icon ![pipeline-icon](./images/pipeline.svg) under Tool Integrations (it is green and orange).
