
<pre align="center">
 █▀▀ █ █▀▀ █   █▀▀ ▀█▀ ▄▄ █▀▀ █▀█ █▄ █ ▀█▀ █▀ 
█▀  █ █▄█ █▄▄ ██▄  █     █▀  █▄█ █ ▀█  █  ▄█
</pre>

### **⚙️ Installation**
  - **For Windows:**

    ```
    winget install Python.Python.3.12
    winget install Git.Git
    pip install pyfiglet
    ```

  - **For Linux:**

    ```
    sudo apt-get update
    sudo apt-get install -y git python3 python-pip figlet
    ```

  - **For macOS:**

    ```
    brew install python git figlet
    ```

  - **For Termux:**

    ```
    apt update
    apt install git python figlet -y
    ```

### **✅Setup Fonts**

- **Install in Windows:**
* [x] Powershell Required.

```powershell
git clone https://github.com/imegeek/figlet-fonts

$pythonDirectoryPath = (Get-Command python).Path | Split-Path -Parent
cp figlet-fonts\* "$pythonDirectoryPath\Lib\site-packages\pyfiglet\fonts"
```

- **Install in Linux:**
```sh
git clone https://github.com/imegeek/figlet-fonts
cp -rf figlet-fonts/* /usr/share/figlet
```

- **Install in macOS:**
* [x] Brew Required.
```sh
git clone https://github.com/imegeek/figlet-fonts
cp -rf figlet-fonts/* usr/local/Cellar/figlet/2.2.5/share/figlet/fonts
```

- **Install in Termux (Android):**
```sh
git clone https://github.com/imegeek/figlet-fonts
cp -rf figlet-fonts/* $PREFIX/share/figlet
```
