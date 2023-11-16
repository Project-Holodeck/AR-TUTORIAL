# AR-TUTORIAL
Tutorial on deploying AR apps to Samsung Galaxy S10e for UTOPH's Unity Team Besties

# Table of Contents
* Install Android SDK
* Setting up your project
* Package Management
* Modifying Settings
* Keystore
* Building

# Install Android SDK
1. On the Unity Editor, go to **Installs** and choose your favorite Unity version.
2. Click on its gear icon
3. Hit **Add Modules**
<img width="750" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/a9578b09-1461-4c43-a1f3-783ad0300afe">

Check off **Android Build Support** and hit **Continue**

<img width="516" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/9dffdc7d-8527-4b1f-88f9-ce274c1ba8d9">

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

# Keystore
Open **Publishing Settings**, then **Keystore Manager**
<img width="946" alt="Untitled" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/90f5b76d-6881-4a55-89f7-4a8d8f118ed8">

At the top left of the Keystore Manager window, click on **Keystore** and **Create New**

<img width="359" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/de7bc42a-7c6a-401a-b47c-df253565e64b">

Afterwards, fill in the following form inputs

<img width="373" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/91ca8915-8855-40cd-b6f6-9629dd1a529c">

Back under publishing settings, make sure you have **Custom Keystore** checked, and entered your password

<img width="686" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/0e3435e3-4b3a-4788-973e-d23577c329ca">

# Building
Back in your Build Settings:
1. Hit **Add Open Scenes**
2. Make sure your **Run Device** is the Samsung phone we are using
3. Check **Development Build**
4. Hit **Build and Run**
<img width="946" alt="Untitled" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/842a780a-403c-4c6b-b2d1-007381aa0894">

Save your .apk file in a new folder called "Builds"

<img width="465" alt="image" src="https://github.com/Project-Holodeck/AR-TUTORIAL/assets/86282459/34c709a9-e7e1-452b-bbdc-a66592bf0a86">

You are done! Make sure you let Scott (Zazzscoot) know on Discord if you have any issues!

