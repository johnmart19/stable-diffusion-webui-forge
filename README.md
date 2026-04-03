# Stable Diffusion WebUI Forge
# Windows AMD gfx1100 (RX 7900 XTX) Launch Modification Instructions:
* Potentially can work with other AMD GPU-s

How to use on AMD:

* Install [Python 3.12](https://apps.microsoft.com/detail/9ncvdn91xzqp) and [Git for Windows](https://github.com/git-for-windows/git/releases/download/v2.50.1.windows.1/Git-2.50.1-64-bit.exe)
* Install [Microsoft C++ Build Tools for Nexa AI Dependency compilation](https://visualstudio.microsoft.com/visual-cpp-build-tools/)

Installation:
1) Clone Repo
* `git clone https://github.com/johnmart19/stable-diffusion-webui-forge sdwebui && cd sdwebui`
2) Make Venv
* `python -m venv venv`
3) Activate it
* `.\venv\Scripts\activate`
4) Update pip (Optional)
* `python.exe -m pip install --upgrade pip`
5) Install appropriate AMD Torch versions (Mandatory):
* `pip install -r extra-requirements.txt`

6) Install main requirements (Will overwrite latest packages with older ones)
* `pip install -r requirements_versions.txt`

7) Launch Stable Diffusion WebUI as usual (It will finalize installation)
* Open webui-user.bat

## Original Stable Diffusion WebUI Forge Readme: https://github.com/lllyasviel/stable-diffusion-webui-forge/blob/main/README.md