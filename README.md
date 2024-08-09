# Data Growth Engineering Project

This project is a key component of the learning path designed by Data Growth Community, tailored specifically for aspiring Data Engineers. Data Growth Community (DGC) is a dynamic network focused on data science and big data, empowering young professionals across Latin America with valuable knowledge and opportunities.

![DATA GROWTH](./images/DGC_Logo.jpg)

## 📚 Table of Contents

1. [🚀 Introduction](#introduction)
2. [📋 Prerequisites](#prerequisites)
3. [⚙️ Setup](#setup)
4. [🛠 Usage](#usage)
5. [📊 Analysis](#analysis)
6. [📈 Visualization](#visualization)

## 🚀 Introduction

### Description

This project is designed to help develop data engineering skills, focusing on ingestion, processing and using tools such as Hadoop. The project will be based on a real-world scenario, where we will simulate a data
growth environment and apply data engineering techniques to handle the increasing volume of data.

### Diagram of the path to the solution

![DATA GROWTH](./images/diagram%202.webp)

## 📋 Prerequisites

Before starting this project, ensure that you have the following programs downloaded and installed on your local machine:

Before starting this project, ensure that you have the following programs downloaded and installed on your local machine:

1. **[VirtualBox](https://www.virtualbox.org/):**
   - VirtualBox is essential for creating and managing virtual machines on your computer. This project requires you to set up a virtual machine in VirtualBox to run Hadoop, Hive, and other related services.
   - Make sure to download the latest version that is compatible with your operating system.

2. **[PuTTY](https://www.putty.org/):**
   - PuTTY is an SSH client that will allow you to remotely connect to your virtual machine and manage the operating system through a terminal. It is a key tool for executing commands on the virtual machine without needing to access its graphical interface.
   - Download and install the version appropriate for your operating system.

3. **[WinSCP](https://winscp.net/):**
   - WinSCP is an SFTP/FTP client that enables you to securely transfer files between your local machine and the virtual machine. You will use it to upload and download files, scripts, and datasets between your local environment and the virtual machine's file system.
   - Ensure you have the latest version installed and configured.

## ⚙️ Setup

### Step 1: Install VirtualBox and Create a Virtual Machine

1. **Download and install VirtualBox:**
   - Visit the [official VirtualBox website](https://www.virtualbox.org/) to download and install the latest version of VirtualBox compatible with your operating system.

2. **Create and configure a new virtual machine:**

   - Download the Cloudera virtual machine with Hadoop and Hive from the [Cloudera Hortonworks Sandbox](https://www.cloudera.com/downloads/hortonworks-sandbox.html).
   - Follow the detailed installation instructions provided by Cloudera to set up the virtual machine in your environment.
   - After the virtual machine is set up, verify that you can access it using PuTTY for command execution and WinSCP for file transfer.
   - During setup, allocate sufficient RAM and disk space to ensure optimal performance for the virtual machine.

3. **Configure network settings:**
   - After the installation is complete, configure the network settings of the virtual machine to ensure it can access both the internet and your local machine.
   - This configuration is crucial for enabling communication between the virtual machine and other tools used in this project.

4. **Connect Hive to Power BI:**
   - To connect Hive with Power BI, you need to download and install the appropriate ODBC connector based on your version of Power BI (32-bit or 64-bit).
   - Once installed, configure the ODBC connector by selecting the HIVE option, entering the required connection details, and ensuring the connection is successful.
   - This will enable you to seamlessly import data from Hive into Power BI for analysis and visualization.

## 🛠 steps to follow

### 🗂️ Project Steps



## 📊 Analysis
Análisis de los resultados.

## 📈 Visualization

