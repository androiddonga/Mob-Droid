# Mob-Droid - Android Metasploit Payload Generator

![Mob-Droid](https://i.postimg.cc/NFkc0wrM/android.jpg)

**Mob-Droid** is an advanced tool for generating and injecting Metasploit payloads into Android APK files. It also provides an easy way to install Apktool, Apksigner, and Zipalign for APK modification and signing.

## 📌 Features

- Generate Android Metasploit payloads easily.
- Inject payloads into original APK files.
- Install Apktool, Apksigner, and Zipalign automatically.
- Fully interactive and user-friendly interface.
- Colored UI for a better experience.
- Compatible with Kali Linux & Termux.

## 🚀 Installation

### Prerequisites
Ensure you have **Metasploit-Framework** installed:
```sh
sudo apt update && sudo apt install metasploit-framework
```

### Clone the Repository
```sh
git clone https://github.com/androiddonga/Mob-Droid.git
cd Mob-Droid
chmod +x mob-droid.py
```

### Run the Tool
```sh
python3 mob-droid.py
```

## 🎯 Usage

Upon running `mob-droid.py`, you will see the following options:

1️⃣ **Generate Android Payload**
```sh
LHOST: Enter your local host IP
LPORT: Enter the port number
Output Filename: Choose a name for your APK
```

2️⃣ **Inject Payload into Original APK**
```sh
Provide path to the original APK
Enter LHOST and LPORT
Enter output filename
```

3️⃣ **Install Apktool, Apksigner, Zipalign**
```sh
This option downloads and installs necessary tools for APK modifications.
```

4️⃣ **Exit**

## 📦 Dependencies
- Python 3
- Metasploit-Framework
- Wget (for downloading tools)
- Apktool, Apksigner, Zipalign


## 🛠 Troubleshooting
- Ensure Metasploit is installed properly.
- Run `mob-droid.py` with `python3`.
- Use Wallpaper template /output/template.apk to generate a wallpaper App payload
- If tools are missing, install them manually with:
  ```sh
  sudo apt install apktool apksigner zipalign
  ```

## ✨ Credits
- Developed by **AndroidDonga** ([@androiddonga](https://github.com/androiddonga))

## ⚠ Disclaimer
This tool is intended for **educational purposes only**. The author is not responsible for any misuse.

## 📜 License
[MIT License](https://opensource.org/licenses/MIT)

---
⭐ **Star this repository** if you find it useful!

📢 **Follow us on:**
- 🌐 Website: [Androiddonga](https://androiddonga.online)
- 📺 YouTube: [AndroidDonga](https://www.youtube.com/@androiddonga)

