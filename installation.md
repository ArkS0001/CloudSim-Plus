# Installation Guide

This guide provides instructions for installing and setting up the project.
Make Sure it is the CloudSim Plus Examples folder: It is the start point to understand how to use the framework and create your own simulations.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) 21
- [Maven](https://maven.apache.org/download.cgi)

## Installation Steps

Follow these steps to set up the project on your system:

### 1. Clone the Repository

```bash
git clone https://github.com/cloudsimplus/cloudsimplus-examples.git
```

#### Windows:

Navigate to the cloned repository folder:

```bash
cd folderName
```

### 2. Install Maven

Download the Apache Maven distribution and unzip it in the same folder as the cloned repository.

### 3. Set Up Maven

Set Maven as a system variable. Verify the Maven installation:

```bash
mvn -v
```

### 4. Bootstrap Maven Invocation

Bootstrap the download and invocation of Maven using the Maven wrapper:

```bash
mvn wrapper:wrapper
```

### 5. Verify Maven Wrapper Script

Check the Maven wrapper script:

```bash
mvnw -v
```

### 6. Validate Maven Project

Ensure everything is correct by validating the Maven project:

```bash
mvnw validate
```

### 7. Open Project in IDE

Open the project directory in your preferred IDE.

Now, your project is ready for development!

Feel free to reach out if you encounter any issues during setup. 
