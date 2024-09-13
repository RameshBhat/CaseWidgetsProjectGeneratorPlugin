# CaseWidgetsProjectGeneratorPlugin
Eclipse Plug-in can be used to generate boilerplate maven project setup with default necessary files for IBM BAW Case page widgets development.

Eclipse plugin jar is created by exporting the Plug-in Development project as Deployable plug-ins and fragments.
Plugin works well with the latest eclipse versions, with default settings and configurations like JDK and maven. My Eclipse IDE version used to build and test the plugin: 
Version: 2024-06 (4.32.0)
Build id: 20240606-1231

How to use the plugin:

1. Download the plugin from github.
2. Deploy the plugin jar file into eclipse/dropins directory.
3. Start/Restart the Eclipse.
4. ICM menu should be visible in the eclipse main toolbar, on clicking the menu there will be an option to Create Case Widgets Maven project.
   CTR+9 shortcut key also will work for this menu action.
5. Enter the project name in the dialog.
6. Close your eyes for 2 seconds, widgets package project will be ready.
7. Open the pom.xml inside the Plugin project and provide navigatorAPI jar dependency as per your local maven repository.
8. Necessary files have been created by default, you can modify them or directly start adding new custom widgets/actions without wasting time.
   
Enjoy customizing the Case client!

For any suggestions:
This Eclipse Plug-in is developed by Ramesh Bhat.
contact: ramgb90@gmail.com
LinkedIn: https://www.linkedin.com/in/rameshbhat
