# AR-TUTORIAL
Tutorial on deploying AR apps to Samsung Galaxy S10e for UTOPH's Unity Team Besties

# Table of Contents
* Setting up your project
* Package Management
* Modifying Settings
* Keystore
* Building

# Setting up your project
From the Unity Editor, create a new AR core project
<img width="760" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/f25d9650-db75-4058-bbb3-661a22adf671">

# Package Management
Open the Package Manager: Go to **Window** > **Package Manager**
<img width="960" alt="Untitled" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/31fa33a3-9cc8-408d-8d3c-fcc4686b4685">

At the top left of the Package Manager window, switch to **Packages: Unity Registry**

<img width="352" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/f69395a9-c6be-40e3-93a7-0171bacc702a">

Now, browse the package list (on the left side of the Package Manager window). Ensure that you have the following packages (you should see a green checkmark beside them):
* AR Foundation
* ARCore XR Plugin
* Input System

<img width="369" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/9fa1f939-139e-4324-8267-db648201ea13">

# Modifying Settings
Open the Build Settings: Go to **File** > **Build Settings**
<img width="960" alt="Untitled" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/0bc3a9de-06ad-455c-91b3-7f1cba838be5">

Go to **Player Settings** (click the bottom left of the Build Settings window)

<img width="960" alt="Untitled" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/13d56ec1-e16e-4f61-a627-8c346cd4f360">

1. Take note of the **Company Name** and **Product Name**
2. Click on the **Android** tab
3. Open **Other Settings**

<img width="960" alt="Untitled" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/702e3a3b-3554-4481-9970-3e9032911f4d">

Under **Rendering**, make sure **Auto Graphics API** is **UNCHECKED**
<img width="720" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/b13179fb-26b8-4d9b-ac29-5f3f54983bf3">

Under **Identifcation** and **Configuration**:
1. Make sure your **Package Name** is in the format: **com.<insert Company name here>.<insert Product name here>**
2. Make sure your **Minimum API level** is **24**
3. Make sure your **Scripting Backend** is **IL2CPP**
<img width="694" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/af8c7bf3-e32d-4425-b523-dd8eef5f2b72">


