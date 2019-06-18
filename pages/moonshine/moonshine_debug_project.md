---
title: Debug a Project in Moonshine
sidebar: moonshine_sidebar
permalink: moonshine_debug_project.html
folder: moonshine
toc: false
---

## How to Debug a Project in Moonshine IDE

1. Open the project in Moonshine that you wants to debug

2. To set breakpoint (optional), open the class file in Moonshine editor and click once at far-left numbered bar to set breakpoint to any line – line’s numbered bar will change color to mark set as breakpoint – click again to remove breakpoint:

    ![Set breaking point in Apache Flex Desktop project](/images/moonshine/debugging_application_1.png)

    (In the image above the breakpoint is set to line# 12)

3. To start a debug choose `Debug -> Build & Debug` from top menus. Moonshine will start a debug session, all the debug command line output can be viewable in bottom Moonshine console window, Moonshine will add a new _Debug View_ at left panel, too. Debugger will halt where breakpoint raised and current memory items will be shown in _Debug View_ panel:

    ![Debugging Apache Flex Desktop application](/images/moonshine/debugging_application_2.png)

4. To step over while debugging you can press `F6` in keyboard or choose `Debug -> Step Over`

5. To resume while debugging you can press `F8` in keyboard or choose `Debug -> Resume`

6. To stop/terminate debug process choose `Debug -> Stop`
