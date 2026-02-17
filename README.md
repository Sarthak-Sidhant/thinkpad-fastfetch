# thinkpad styled fastfetch config

thinkpaid inspired fastfetch, with ANSI logo and boxed interface to display detailed information about your system

### ASCII art credits to https://github.com/roadkell/ascii-logos

## 🛠 Installation
Please have curl and fastfetch pre-installed, not tested for windows

Run these commands in your terminal to set up the config and logo automatically:

```bash
# Create the config directory
mkdir -p ~/.config/fastfetch

# Download the custom logo
curl -sL https://raw.githubusercontent.com/Sarthak-Sidhant/thinkpad-fastfetch/main/thinkpad.txt -o ~/.config/fastfetch/thinkpad.txt

# Download the config file
curl -sL https://raw.githubusercontent.com/Sarthak-Sidhant/thinkpad-fastfetch/main/config.jsonc -o ~/.config/fastfetch/config.jsonc
```
## Usage

just run `fastfetch`

