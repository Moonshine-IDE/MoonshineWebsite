---
title: Set Apache Flex®, Apache Royale® or Feathers SDK in Moonshine
sidebar: moonshine_sidebar
permalink: moonshine_set_sdk.html
folder: moonshine
toc: true
---

## Set default SDK:

1. Start Moonshine

2. In Moonshine go to `File -> Settings -> Default SDK`

    ![Screenshot: default SDK](/images/moonshine/default_sdk.png)

3. If you are using Moonshine that bundled with different SDKs, then you can use any of them to set default **Apache Flex® SDK** to Moonshine, or even you can download **Apache Flex® SDK** with **AIR SDK** at [http://flex.apache.org/installer.html](http://flex.apache.org/installer.html){:target="_blank"}

4. If you are using **OSX El Capitan** or higher, make sure you downloaded SDK to `~/Downloads` folder. Because of the many restrictions applied to **El Capitan**, a sandbox app can execute/use SDK's stuff only if it's in user’s _Downloads_ folder.

5. (OSX) If you have setup **Apache Flex® SDKs** downloaded by Moonshine’s helper application **App Store Helper** then you should probably see Moonshine’s default SDK already set by a bundled SDK.

6. You can also set your own SDK as _default_ by clicking on the _Change_ link inside teh _Default Flex SDK_ section. This will open a popup named _Select Flex SDK_ consisting of available/added SDK entries.

7. To use any SDK from the above entry, simply double-click on it, and it’ll be updated to default **Apache Flex®**, **Apache Royale®** or **Feathers** SDK. Alternatively you can add your own SDK by clicking on a plus button in _Select SDK_ popup and completing the _Define an SDK Path_ form.

8. When done, click on _Save_ button in _Default SDK_ section.

## Set SDK to individual project:

1. Right click on your project name and select _Settings_ then at the left _Build options_.

    ![Screenshot: custom SDK](/images/moonshine/custom_sdk.png)

2. Click on _Change_ link inside the _Custom SDK_ section, this will open a file browse dialogue.
   
   * Locate the **Apache Flex®**, **Apache Royale®** or **Feathers** SDK folder (as previously downloaded) and choose _Select Folder_.

   * You should see _Custom SDK_ is now pointing to **Apache Flex®**, **Apache Royale®** or **Feathers** SDK directory you chose.

   * Click _Save_.

