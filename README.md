# ReviewEID
ReviewAID is an open-access workspace that unifies systematic reviews into one local state machine. It automates ingestion across 12 databases, drives three-tier LLM screening with clear provenance, and instantly updates real-time PRISMA 2020 charts alongside a grounded manuscript drafting engine.


### Installation Procedure for ReviewAID

ReviewAID is distributed as a compressed package (Review_AID_Final.zip) containing the complete source code, build scripts, and configuration files required for installation and execution on Microsoft Windows operating systems.

#### Step 1: Extract the Package

Download and extract the contents of **Review_AID_Final.zip** to a local directory on the computer. The extracted folder contains all application source files, configuration files, and build scripts required for installation.

#### Step 2: Execute the Installation Script

Locate the file **build-ReviewAID.bat** within the extracted folder.

Right-click the file and select **Run as Administrator**. Administrative privileges are required to allow the script to install software dependencies and build the application.

#### Step 3: Automatic Dependency Installation

The installation script automatically checks whether Node.js is installed on the system.

If Node.js is not detected, the script will:

1. Download the required Node.js installer.
2. Install Node.js silently in the background.
3. Configure the environment for application compilation.

#### Step 4: Application Build Process

After verifying the required dependencies, the script automatically performs the following tasks:

1. Installs all required project dependencies using npm.
2. Builds the ReviewAID web application.
3. Packages the application into a standalone Windows desktop executable using Electron Builder.

No manual configuration is required during this process.

#### Step 5: Locate the Generated Application

Upon successful completion of the build process, the Windows application will be generated in:

dist\win-unpacked\ReviewAID

#### Step 6: Launch ReviewAID

Open the generated folder and double-click the **ReviewAID** application icon to launch the software.

The application will start as a standalone desktop program, providing access to the ReviewAID systematic review filtering and literature screening platform.

#### System Requirements

* Microsoft Windows 10 or later
* Internet connection (required only during the initial dependency installation process)
* Administrative privileges for software installation
* Minimum 4 GB RAM recommended
* Approximately 1 GB of available disk space for dependencies and build files

