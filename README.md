# Eclipse plugin installation

### 1. Install Eclipse
- Download the **Eclipse Modeling Tools** package from the official page:
    https://www.eclipse.org/downloads/packages/

### 2. Install Xtext
- Install Xtext following this instructions:
https://www.eclipse.org/Xtext/download.html

### 3. Import the plugin
- Inside Eclipse select File > Import > Plug-in Development > Plug-ins and fragments
- Select Next
<img src="https://user-images.githubusercontent.com/26405870/83297277-95774280-a1f2-11ea-9a18-824fc247a888.png" width="500">

- Download the files in the folder **msc-use plugin** and place them in a directory (e.g. C:/some_folder)
- Set the value of the field *Directory* to the path in which you placed the plugin files and set the rest of the configuration parameters as shown in the image

<img src="https://user-images.githubusercontent.com/26405870/83297567-18000200-a1f3-11ea-9119-98e3448b8ee8.png" width="500">

- Select *Add All* to add all the plugins and select finish

<img src="https://user-images.githubusercontent.com/26405870/83297766-71683100-a1f3-11ea-9540-37b7d903bd5e.png" width="500">

### 4. Run the tool
- In the *Model Explorer*, right-clik over z120ToSoil and select the option *Run As..* > *Eclipse Application*
<img src="https://user-images.githubusercontent.com/26405870/83298104-26025280-a1f4-11ea-8f13-41d17e492312.png" width="500">

- In the new Eclipse IDE, create a new project. Select *File > New > Project > General > Project*
- Create a new folder inside the project. Right-click on the project and select *New > folder*
- Create a file inside the folder with the extension .z120. The next window will pop when you try to create the file. Select *Yes*.

<img src="https://user-images.githubusercontent.com/26405870/83299747-0fa9c600-a1f7-11ea-99a6-55b6a83d75f3.png" width="500">

- You are done! Paste your MSC and the test cases will be generated inside the project.

<img src="https://user-images.githubusercontent.com/26405870/83299963-69aa8b80-a1f7-11ea-9a58-421e857b92a4.png" width="500">
