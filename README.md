# XPSPEAK 4.1 (Archived & Fixed for Modern Windows)

This repository contains a working, archived copy of **XPSPEAK 4.1**, the classic freeware tool written by Raymund Kwok for X-ray photoelectron spectroscopy (XPS) peak fitting and spectral analysis. 

Because the original host links and mainstream software aggregators have dead download buttons, this repository serves as a permanent, functioning mirror.

---

## How to Download the Software

To get the software immediately without cloning the entire repository, follow these steps:

1. Click on the **[xpspeak41.zip](xpspeak41.zip)** file in the list above.
2. Click the **Download raw file** button (look for the download icon 📥 on the right side of the screen).
3. The zip file will download directly to your computer.

---

## Installation & Setup Guide

Since XPSPEAK 4.1 is a legacy 32-bit program, it does not use a modern installation wizard. Follow these exact steps to ensure it runs on **Windows 10** or **Windows 11** without crashing:

### Step 1: Extract the Files
* Locate your downloaded `xpspeak41.zip`.
* **Right-click** the file and choose **Extract All...**
* Extract the contents to a dedicated folder on your local drive (e.g., `C:\XPSPEAK` or your Desktop). *Do not run the software from inside the zip file.*

### Step 2: Configure Compatibility Mode (Crucial)
Before opening the software for the first time, you must give it legacy permissions:
1. Open your extracted folder and find **`XPSPEAK41.exe`** (the file with the blue icon).
2. **Right-click** on `XPSPEAK41.exe` and select **Properties**.
3. Navigate to the **Compatibility** tab at the top.
4. Under *Compatibility mode*, check the box for **"Run this program in compatibility mode for:"** and select **Windows 7** or **Windows XP (Service Pack 3)**.
5. Under *Settings* at the bottom, check the box for **"Run this program as an administrator"**.
6. Click **Apply**, then click **OK**.

### Step 3: Run the Application
* Double-click **`XPSPEAK41.exe`**. The main grey grid workflow window will open.

---

## Quick Start Tips for Users

* **Importing Data:** The software works best with 2-column ASCII data (`.txt` or `.dat` files consisting of *Binding Energy* and *Intensity*). 
* **The "Greyed Out" Button Fix:** If the peak fitting buttons are locked or greyed out when you open your data, you must go to the **Background** tab first. Define and accept your baseline/background type (e.g., Shirley, Tougaard, or Linear). Once the background is set, the peak addition options will immediately become active.

---

## License & Disclaimer
This is legacy freeware originally distributed openly for academic and research purposes by Raymund Kwok. It is provided here strictly as a data-preservation archive for the scientific community. Use at your own discretion.
