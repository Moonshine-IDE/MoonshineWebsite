---
title: Creating a Dynamic Pie Chart uisng SuperHumanInstaller and Moonshine-IDE
layout: docpage
---

# Creating a Dynamic Pie Chart uisng SuperHumanInstaller and Moonshine-IDE

We're excited to share with you a step-by-step guide on creating a dynamic pie chart using some incredible tools. Whether you're a seasoned developer or just starting out, this walkthrough promises to be both informative and enjoyable!

## Getting Ready: Tools of the Trade

Before diving in, let's make sure we have all the necessary tools:

1. **VirtualBox:** This is a fantastic, free open-source hosted hypervisor for x86 virtualization. It's going to be the backbone of our setup.
2. **Vagrant:** A superb tool for building and managing virtual machine environments. It makes handling different development environments a breeze.
3. **Super.Human.Installer:** The key to setting up your server environment efficiently. Trust me, this makes things a lot easier!

## The First Steps: Setting Up Your Environment

Setting up your environment correctly is crucial. Here's how to do it:

1. **Installing the Essentials:**
   - First, grab and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads), [Vagrant](https://developer.hashicorp.com/vagrant/downloads), and [Super.Human.Installer](https://superhumaninstaller.com/). These tools are going to be the foundation of our project.

2. **Server Time:**
   - Next up, set up at least one server with Domino 12.0.1. You can find detailed instructions at [Superhumaninstaller.com](https://superhumaninstaller.com#configuration-steps). Remember to note down your hostname and organization certifier.
   - A pro tip: Don't forget to set up your etc/hosts!

## Crafting the Development Environment

With our server ready, let's set up the development environment:

1. **Moonshine IDE & SDK:**
   - Download and install [Moonshine IDE](https://moonshine-ide.com/) and [Moonshine SDK Installer](https://moonshine-ide.com/download-sdk-installer/). These will be our tools for the actual development process.

2. **Preparing the Tools:**
   - Use the SDK Installer to download Git and the latest Apache Royale nightly version. These are essential for our project development.

## Building the Pie Chart Database Project

Now, the fun part begins – creating the Pie Chart!

1. **Project Setup:**
   - Open Moonshine-IDE and go to `File -> New -> Domino on Disk Project`. Name your project `PieChartNsf` and click 'Create'.

2. **Configuration:**
   - Right-click on the project in the project list, go to `Settings -> Domino Tab -> Target Server`, and enter your hostname and organization certifier. Don't forget to save these settings!

![](.\img\target-server.png)

3. **Designing the Database:**
   - Navigate to `src/main/formbuilder/PieChartNsf.dfb` in your project and open it. This is where we'll be adding the data for our pie chart.

![](.\img\form.png)

4. **Adding Data:**
   - We'll input data in the form of country names and their corresponding percentage areas. ECharts pie chart expects data in 'name' and 'value' pairs, and that's exactly how we'll set up our columns.
   - Click the 'Add' button to create the 'name' and 'value' columns, populating them as shown in the screenshots.

![](.\img\add-name.png)

![](.\img\add-value.png)

5. **The Final Look:**
   - Once you've added your data, the table should look something like this (refer to the screenshots for a visual guide).

![](.\img\form-done.png)

To be continued...

<!-- And there you have it! By following these steps, you're well on your way to creating a dynamic and visually appealing pie chart. Stay tuned for more posts where we delve deeper into customizing and enhancing our chart.

Happy coding! -->