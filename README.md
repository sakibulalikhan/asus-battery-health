# Asus Battery Health Charging Script For Linux

Author: [@sakibulalikhan](https://github.com/sakibulalikhan)

![image](https://github.com/sakibulalikhan/asus-battery-health/assets/75080608/f72bc5c6-68f9-4a03-b7c4-463b30ee4d52)

Asus laptops come with a built-in feature known as Asus Battery Health Charging, which is often integrated into the MyAsus application. This feature enables users to set a charging threshold, typically at 60%, when the laptop is connected to AC power. Maintaining the battery charge at 60% helps mitigate heating issues, enhances performance, and significantly extends the overall lifespan of the laptop battery.

However, this feature is exclusively available for Windows operating systems, leaving Linux users, including those on Ubuntu, Linux Mint, Elementary OS, Pop OS, Fedora, Arch, and others, without official support. This void can deter users from transitioning to Linux for its performance benefits or other preferences.

Despite the absence of official support from Asus for Linux-based operating systems, this script provides a practical solution. It enables users to implement battery charging thresholds in Linux environments, ensuring the benefits of battery health charging are accessible across different platforms.

The script has undergone thorough testing on various Linux distributions, including Ubuntu, Linux Mint, PopOS, Elementary OS, Zorin OS, Fedora, AlmaLinux, Rocky Linux, Arch, Manjaro, and EndoverOS.

## Usage:

To use the script, execute the following command in your terminal:

```bash
abh [-t <charge_threshold>] [-r] [-v] [-h]
```
```bash
┏┓      ┳┓            ┓┏    ┓ ┓
┣┫┏┓┏┏  ┣┫┏┓╋╋┏┓┏┓┓┏  ┣┫┏┓┏┓┃╋┣┓
┛┗┛┗┻┛  ┻┛┗┻┗┗┗ ┛ ┗┫  ┛┗┗ ┗┻┗┗┛┗
                   ┛ @sakibulalikhan

Usage: /usr/bin/abh [-t <charge_threshold>] [-r] [-v] [-h]
Options:
  -t <charge_threshold>  Set the charge threshold (default: 60)
  -r                     Remove the charge threshold
  -v                     Enable verbose mode
  -h                     Display this help message
```

## Options:

- `-t <charge_threshold>`: Sets the charge threshold (default: 60). This option allows users to specify a custom charge threshold.
- `-r`: Removes the charge threshold. Use this option to disable battery health charging.
- `-v`: Enables verbose mode. This option provides additional output for troubleshooting purposes.
- `-h`: Displays the help message. Use this option to view the script's usage instructions.



## Installation

   ```bash
   wget clone https://raw.githubusercontent.com/sakibulalikhan/asus-battery-health/main/abh && sudo mv abh /usr/bin/ && sudo chmod +x /usr/bin/abh && abh
   ```

## Manual Installation

1. Clone this repository

```bash
git clone https://github.com/sakibulalikhan/asus-battery-health.git
```

2. Navigate to the cloned directory

```bash
cd asus-battery-health-script
```
3. Give execution permission

```bash
sudo chmod +x abh
```

4. Run script

```Bash
sh abh
```
  Or

```bash
./abh
```

## How to Use:


1. Execute the script with default options

```bash
abh -t # Sets charge threshold default to 60%
```
2. Execute the script with your preferred options

```bash
abh -t 80  # Sets charge threshold to 80%
```
3. 2. Execute the script with Verbose mode

```bash
abh -t -v
```

4. Help command
```bash
abh -h
```

5. Remove charge threshold
```bash
abh -r
```

## Contributing:

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please create an issue or submit a pull request.

## License:

This project is licensed under the [MIT License](https://github.com/sakibulalikhan/asus-battery-health/blob/main/LICENSE).

#### Follow me on Twitter [@sakibulalikhan](https://twitter.com/sakibulalikhan)

## Support Me:

<a href="https://www.buymeacoffee.com/sakibulalikhan" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
