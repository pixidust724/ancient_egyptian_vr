# Master-Thesis
![Captura de pantalla 2023-04-27 040624](https://user-images.githubusercontent.com/43790840/234986193-c8aab325-5c6d-409c-94e7-e0cb95da5c46.jpg)


## Introduction
Immersive Gamified Application to Enhance Visitor Experience in Heritage Museums

## Requirements
- Unity Editor 2021.3.22f1 with Android Build Support
- git

## Getting started
To get the project running follow the instructions below.

### **Importing Packages**
To import the missing packages, follow these steps:

#### **Git**
- You need to have installed [**git**](https://github.com/git-guides/install-git) in your computer and next time you open the project, the git packages will be installed automatically. 

#### **Unity Asset Store**
Go to the [Unity Asset Store](https://assetstore.unity.com/) and look for the following packages:
- Oculus Integration: https://assetstore.unity.com/packages/tools/integration/oculus-integration-82022

To install these packages follow these steps:
- Make sure you have a Unity Account to access assets on the Asset Store
- Make sure the Unity Account is linked to your Unity Hub
- Go to `Window -> Package Manager`
- Choose on the top left `Packages: My Assets`
- Select the packages, press `Download` and then `Import`

### **OpenAI**
Instructions from [OpenAI Unity](https://github.com/srcnalt/OpenAI-Unity) repository

#### **Setting Up Your OpenAI Account**
To use the OpenAI API, you need to have an OpenAI account. Follow these steps to create an account and generate an API key:

- Go to https://openai.com/api and sign up for an account
- Once you have created an account, go to https://beta.openai.com/account/api-keys
- Create a new secret key and save it

#### **Saving Your Credentials**
To make requests to the OpenAI API, you need to use your API key and organization name (if applicable). To avoid exposing your API key in your Unity project, you have to save it in your device's local storage.

To do this, follow these steps:

- Create a folder called `.openai` in your home directory (e.g. `C:User\UserName\` for Windows or `~\` for Linux or Mac)
- Create a file called `auth.json` in the `.openai` folder
- Add an api_key field and a organization field (if applicable) to the auth.json file and save it
- Here is an example of what your auth.json file should look like:

```json
{
    "api_key": "sk-...W6yi",
    "organization": "org-...L7W"
}
```
