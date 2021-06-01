---
title: Apache Ant® build
permalink: docs/moonshine/apache_ant_build
layout: docpage
---

## Apache Ant® build

1. Starting an **Apache Ant®** build requires Ant installed in your system and setup as environment variable (ensure Ant version meets minimum requirement of 1.9.2)

2. Moonshine sources supplies with it’s Ant build scripts and configured. Upon completion, the process will output desktop installer files for Windows and MacOS. You can immediately start an Ant build process if you already setup Ant in your system; to start an Ant build process we need to locate the Ant build script file (_build.xml_) prior to run the process. Moonshine supplies Ant build script file in it’s project’s build folder.

3. Build your project by choosing `Ant -> Build Apache Ant® File` from top menu. In opening file browser dialogue navigate to your **Apache Ant®** folder. Next select Ant script and click _Ant Build_ in order to start **Apache Flex®** project build. Ant build should produce _.swf_ and it’s HTML wrapper file set.

    ![Apache Ant build configuration](/images/moonshine/ant_build_configuration.png)

4. Upon successful completion of the process, installer files can be located at _DEPLOY_ folder inside build folder.
