---
title: Create and Build Projects
sidebar: moonshine_sidebar
permalink: moonshine_create_and_build_projects.html
folder: moonshine
toc: true
---
## Create and Build Desktop Projects

1. To create a new desktop based Apache Flex® project do one the following:
   * In Moonshine choose `File -> New -> Flex Desktop Project (MacOS, Windows)` : MXML and ActionScript support
   * In Moonshine choose `File -> New -> ActionScript Project (SWF, Desktop)` : Choose this if you want pure ActionScript project
   * In Moonshine choose `File -> New -> Feathers Desktop Project (MacOS, Windows)` : MXML and ActionScript support
   * Choose _ActionScript Project (SWF, Desktop)_ in Moonshine splash screen
   * Choose _Flex Desktop Project (MacOS, Windows)_ in Moonshine splash screen
   * Choose _Feathers Desktop Project (MacOS, Windows)_ in Moonshine splash screen
2. Choosing any above option will open the New Project tab:
![Screenshot: new Flex desktop project](/images/moonshine/new_flex_desktop_project.png)
3. In _ActionScript Project (SWF, Desktop)_ options you’ll find an extra option to choose between Desktop or Web as the platform type:
![Screenshot: new ActionScriipt project dialog](/images/moonshine/new_project_dialog_as.jpg)
    * Editable fields are:
      * Project Name
      * Parent Directory
      * Select Project Type (ActionScript Project only)
    * After entering the necessary fields above, click _Create_ to generate a new project
    * Create option immediately creates a new **Apache Flex®** project, open the project in Moonshine workspace (left-hand tree menu) and it’s application file in Moonshine editor
    ![Screenshot: create new Flex desktop project](/images/moonshine/created_new_flex_desktop_project-1.png)
    * Moonshine generates any project with it’s supported types with demo ‘Hello World!‘ text, so you can immediately build the project and check it’s output; an optional **Apache Ant®** build script fully configured so you build a desktop package immediately as well!
    * To run the project choose `Project -> Build & Run` or press `CTRL`+`ENTER` (WIN)
    or `CMD`+`ENTER` (Mac OS). You can see command line output in Moonshine’s console window (at the bottom of the interface)
    ![Screenshot: console build](/images/moonshine/console_build.png)
    * If your project compiles, an AIR window will open running your code.

## Create and Build Web Projects

1. To create a new web based Apache Flex® project do either one the following things:
   * In Moonshine choose File -> New -> Flex Browser Project (SWF) : MXML and ActionScript support
   * In Moonshine choose File -> New -> ActionScript Project (SWF, Desktop) : Choose this if you want pure ActionScript project
   * Choose ActionScript Project (SWF, Desktop) in Moonshine splash screen
   * Choose Flex Browser Project (SWF) in Moonshine splash screen
2. Choosing any above option will open new project creation dialogue:
    ![New Apache Flex browser project](/images/moonshine/new_flex_browser_project.png)
3. In ActionScript Project (SWF, Desktop) options you’ll find an extra option to choose between Desktop and Web as output type:
    ![CreateWebAS3](/images/moonshine/create_web_as3.jpg)
   * Editable fields are:
     * Project Name
     * Parent Directory
     * Select Project Type (ActionScript Project only)
   * After necessary in the fields above, click Create to generate a new Apache Flex® Web project
   * Create option immediately create a new Apache Flex® project, open the project in Moonshine workspace (left-hand tree menu) and it’s application file in Moonshine editor
    ![Created New Apache Flex Browser project](/images/moonshine/created_new_flex_browser_project.png)
   * Moonshine generates any project with it’s supported types with demo ‘Hello World!‘ text, so you can immediately build the project and check it’s output; an optional Apache Ant® build script fully configured so you build a release SWF immediately as well!
   * To run the project choose Project -> Build & Run. You can see command line outputs in Moonshine’s console window (at bottom)
    ![Console build Apache Flex browser project](/images/moonshine/console_build_browser.png)
   * If everything goes fine, Moonshine will generate the SWF and runs inside default browser window

## Create and Build Mobile Projects

1. To create a new mobile based **Apache Flex®** project do either one the following things:
   * In Moonshine choose `File -> New -> Flex Mobile Project (iOS, Android)` : MXML and ActionScript support
   * Choose _Flex Mobile Project (iOS, Android)_ in Moonshine splash screen
  
2. Choosing any above option will open new project creation dialogue:

    ![New Apache Flex Mobile project](/images/moonshine/new_flex_mobile_project.png)

   * Editable fields are:
     * Project Name
     * Parent Directory

3. After necessary inputs in the fields above, click _Create_ to generate a new **Apache Flex®** Mobile project

4. _Create_ option immediately creates a new **Apache Flex®** project, opens the project in Moonshine workspace (left-hand tree menu) and makes it an application file in Moonshine editor.

5. Moonshine generates any project with it’s supported types with demo ‘Hello World!‘ text, so you can immediately build the project and check it’s output; an optional **Apache Ant®** build script is fully configured so you build a mobile package (.apk or .ipa) immediately as well!

6. To run the project choose `Project -> Build & Run`. You can see command line outputs in Moonshine’s console window (at bottom)

    ![Build and Run Apache Flex Mobile project](/images/moonshine/build_and_run_new_flex_mobile_project-1.png)

## Create and Build Apache Royale® Projects

1. To create a new Apache Royale® project do either one the following things:
   * In Moonshine choose `File -> New -> Royale Browser Project`
   * Choose Royale Browser Project in Moonshine splash screen

2. Choosing any above option will open new project creation dialogue:

    ![New Apache Royale project](/images/moonshine/new_royale_project.png)
    * Editable fields are:
      * Project Name
      * Parent Directory

3. Click _Create_ to generate a new **Apache Royale®** project

4. Create option immediately create a new Apache Royale® project, open the project in Moonshine workspace (left-hand tree menu) and it’s application file in Moonshine editor

    ![Created Apache Royale project](/images/moonshine/Created-Apache-Royale-project.png)

5. To run the project choose Project -> Build & Run. You can see command line outputs in Moonshine’s console window (at bottom)

    ![Apache Royale build SWF](/images/moonshine/Apache-Royale-build-SWF.png)

6. If everything goes fine, an browser window will open running the current project

7. To create Html/JS choose Project->Build & Run as JavaScript.you can see command line outputs in Moonshine’s console window (at bottom)

    ![Apache Royale build JS](/images/moonshine/Apache-Royale-build-JS.png)

8. JavaScript files has been created in Project->bin->js-debug directory

    ![Apache Royale after build](/images/moonshine/Apache-Royale-after-build.png)
