# PowerShell Package Installer
This script automates the installation and verification of specified NuGet packages for your project.

# Usage
Requirements: Ensure PowerShell is installed on your system.
Clone Repository: Clone this repository to your local machine.
Run the Script: Execute the script Install-NuGetPackages.ps1.
Review Output: Check the output for installation statuses and any errors encountered.
Script Overview
The script fetches the latest available versions of specified NuGet packages from the specified NuGet source. It then checks if these packages are installed and, if not, proceeds to install them. The process displays installation progress and any encountered errors.

# Packages
The script is pre-configured to install the following packages:

Azure.Core
Azure.Identity
Azure.Storage.Blobs
Azure.Storage.Common
Microsoft.ApplicationInsights.WorkerService
Microsoft.Azure.Functions.Worker
Microsoft.Azure.Functions.Worker.ApplicationInsights
Microsoft.Azure.Functions.Worker.Extensions.Timer
Microsoft.Azure.Functions.Worker.Sdk
Microsoft.Azure.WebJobs
Microsoft.Azure.WebJobs.Extensions
Microsoft.Azure.WebJobs.Extensions.Timers.Storage
Microsoft.Identity.Client
Microsoft.PowerBI.Api
WindowsAzure.Storage

# How It Works
The script iterates through the package list, checking for the latest available version of each package on the specified NuGet source. It compares the installed version, if present, and installs the package if the latest version differs. It provides real-time updates on the installation progress and any encountered issues.

# Important Notes
Ensure an active internet connection to access the specified NuGet source.
Review the script output for any error messages or failed installations.
# Disclaimer
This script assumes the availability of packages on the specified NuGet source and may encounter issues due to network connectivity or package availability changes. I do not take responsibility when using this script for yourself. It's just for educational purposes.

Feel free to modify the $packages array with your required package names.

For any concerns or improvements, open an issue or contribute to this repository. Your feedback is appreciated!

