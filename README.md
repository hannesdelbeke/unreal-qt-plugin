> [!WARNING]
> Not sure if you can set the order of pugins in unreal, so this might run after another plugin tries to launch qt code

# unreal-qt plugin
This plugin runs the [unreal-qt](https://github.com/hannesdelbeke/unreal-qt) setup on startup.

### Install instructions

<details>
<summary>0. install dependencies (TODO automate this)</summary>
  
Use pip to install the Python dependencies to Unreal site packages.
  - [unreal-qt](https://github.com/hannesdelbeke/unreal-qt)
  - PySide6
</details>


<details>
<summary>1. Copy the plugin to unreal's plugin folder</summary>
  
  - [Download](https://github.com/hannesdelbeke/unreal-qt-plugin/archive/refs/heads/main.zip) and Unzip  
  - Copy the extracted `UnrealQt` folder to Unreal's plugins folder  
</details>


<details>
<summary>2. Enable the plugin</summary>
  
  - Open the Unreal plugin editor from the menu `edit/Plugins`
  - Enable the `Unreal Qt` plugin
  - Restart Unreal
</details>

## Other
- plugget [manifest](https://github.com/plugget/plugget-pkgs/tree/main/unreal/unreal-qt)
