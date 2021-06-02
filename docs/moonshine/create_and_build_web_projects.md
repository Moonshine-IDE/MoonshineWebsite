---
title: Create and Build Web Projects
layout: docpage
---

## Create and Build Web Projects

1. To create a new web based **Apache Flex®** project do either one the following things:
   * In Moonshine choose `File -> New -> Flex Browser Project (SWF)` : MXML and ActionScript support
   * In Moonshine choose `File -> New -> ActionScript Project (SWF, Desktop)` : Choose this if you want pure ActionScript project
   * Choose _ActionScript Project (SWF, Desktop)_ in Moonshine splash screen
   * Choose _Flex Browser Project (SWF)_ in Moonshine splash screen

2. Choosing any above option will open new project creation dialogue:

    ![New Apache Flex browser project](/images/moonshine/new_flex_browser_project.png)

3. In ActionScript Project (SWF, Desktop) options you’ll find an extra option to choose between Desktop and Web as output type:

    ![CreateWebAS3](/images/moonshine/create_web_as3.jpg)

    Editable fields are:
     * Project Name
     * Parent Directory
     * Select Project Type (ActionScript Project only)

4. After necessary in the fields above, click _Create_ to generate a new **Apache Flex®** Web project

5. _Create_ option immediately creates a new **Apache Flex®** project, opens the project in Moonshine workspace (left-hand tree menu) and its application file in Moonshine editor.

    ![Created New Apache Flex Browser project](/images/moonshine/created_new_flex_browser_project.png)

6. Moonshine generates any project with its supported types with demo 'Hello World!' text, so you can immediately build the project and check its output. An optional **Apache Ant®** build script is fully configured so you can build a release SWF immediately as well!

7. To run the project choose `Project -> Build & Run`. You can see command line's output in Moonshine's console window (at the bottom).

    ![Console build Apache Flex browser project](/images/moonshine/console_build_browser.png)

8. If everything goes fine, Moonshine will generate the SWF and run it inside the default browser's window.
