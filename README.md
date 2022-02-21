<h1 align="center">myTermux</h1>

## Installation Dependecies

> **Attention!**
> - [Termux must be **F-Droid** Version](https://f-droid.org/en/packages/com.termux/) because Termux from Playstore no longer maintained because there are some problems with the Playstore publishing
> - [Termux:API must be installed](https://f-droid.org/en/packages/com.termux.api/) myTermux use API command from Termux:API like fetch `termux-battery-status`

  <details open>
  <summary><strong>Update Repository & Upgrade Package</strong></summary>

  ```bash
  pkg update && pkg upgrade
  ```
  </details>

  <details>
  <summary><strong>git & bc</strong></summary>

  - Package `git` for cloning or downloading repository
  - Package `bc` for calculate repository size which will be cloning or downloading

  ```bash
  pkg i -y git bc
  ```

  </details>

## Installation myTermux

  <details open>
  <summary><strong>Clone or Download This Repository</strong></summary>

  ```bash
  git clone --depth=1 https://github.com/mayTermux/myTermux.git
  ```

  </details>

  <details>
  <summary><strong>Run Script Installer</strong></summary>

  - Move to Folder

  ```bash
  cd myTermux
  ```

  - export variable `COLUMNS` and `LINES`

  > This variable function so that the installer script can read the
  > `column` and `row` widths of Termux Application so that later it
  > matches the output during the installation process.

  ```bash
  export COLUMNS LINES
  ```

  - Execute Installer

  ```bash
  ./install.sh
  ```

  ![Error](https://i.ibb.co/mDV3hd0/Screenshot-20220216-200813-Termux.png)

  > If you get error message `Please Zoom Out`.
  > Zoom Out on Termux Application then run again the script

  > If the row and column widths of the application are correct,
  > the script will automatically run, like this:

  ![Running](https://i.ibb.co/hMbzWxx/Screenshot-20220216-202655-Termux.png)

  > Then follow the installation until it's finished

  </details>



## :camera_flash: Screenshots

> This screenshot take by [**Awesomeshot**](https://github.com/mayTermux/awesomeshot)

- System Fetch

  > rxfetch

  ![rxfetch](https://i.postimg.cc/SRxmSBd1/Screenshot-20220216-203051-Termux.png)

  > rxfetch hydra

  ![rxfetch hydra](https://i.postimg.cc/QCDVDYKH/Screenshot-20220216-205938-Termux.png)

  > neofetch

  ![neofetch](https://i.postimg.cc/xCsWRcGg/Screenshot-20220216-203404-Termux.png)

- Colorscheme (Theme)

  > Change colorscheme or theme with command:

  ```bash
  chcolor
  ```

  ![chcolor](https://i.postimg.cc/BvjY0M25/Screenshot-20220216-203436-Termux.png)

  <details>
  <summary>Show Preview</summary>

  ![colorscheme](https://i.ibb.co/4Vjdk89/out2.png)

  </details>

- Fonts

  > Change font used with command:

  ```bash
  chfont
  ```

  ![chfont](https://i.postimg.cc/cHMQynkM/Screenshot-20220216-203506-Termux.png)

- ZSH Theme

  > Change ZSH Theme with command:

  ```bash
  chzsh
  ```

  ![chzsh](https://i.postimg.cc/1RvqGPkt/Screenshot-20220216-203529-Termux.png)

- Text Editor

  ![NvChad](https://i.postimg.cc/43R7f398/Screenshot-20220216-203928-Termux.png)

  <details>
  <summary>Show Theme</summary>

  ![NvChad Theme](https://i.ibb.co/6DqyPqT/final-text-editor.png)

  </details>

- Music

  ![ncmpcpp](https://i.ibb.co/bPRrbyD/final-music.png)

## Credits

- [siduck](https://github.com/siduck) Neovim Setup (NvChad), Colorscheme (onedark-siduck)
- [owl4ce](https://github.com/owl4ce) First time getting to know dotfiles
- [adi1090x](https://github.com/adi1090x) Termux Setup
- [bandithijo](https://github.com/bandithijo) Awesome screenshot like MacOS using imagemagick script
- [lwotcynna](https://github.com/lwotcynna) Contibutor
- [nekonako](https://github.com/nekonako) Colorscheme nekonako-djancoeg, nekonako-hue, nekonako-om-mar
- [Dotfiles Indonesia](https://t.me/dotfiles_id)
- [Vim Indonesia](https://t.me/VimID)
- [Bashid.org](https://t.me/bashidorg)

## Colorscheme

- [catppuccin/termux](https://github.com/catppuccin/termux)
