# Setup

## MacOS

1. Install [Homebrew](https://brew.sh/)
  - `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`


- Run these commands in your terminal to add Homebrew to your PATH:
    ```
    echo >> /Users/bbecke01/.zprofile
    echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/bbecke01/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv zsh)"
    ```

2. Install [chezmoi](https://www.chezmoi.io/)
  - `brew install chezmoi`

3. Initialize chezmoi from my github dotfiles repo
  - `chezmoi init brbecker [--apply]`
