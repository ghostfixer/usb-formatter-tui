# USB Quick Formatter

## Installation
- Copy `usb-formatter` to `/usr/local/bin/` to install the application system-wide.
- Ensure `/var/log/usb_formatter.log` exists with correct permissions

## Running the Program
Once installed, you can launch the application with:
```sh
sudo usb-formatter
```

## Usage
- **Use UP/DOWN arrows** to select a drive.
- **Use LEFT/RIGHT arrows** to select a format (FAT32, UFS, NTFS, Ext4).
- **Press ENTER** to format.
- **Press Q** to quit.

## Logging
Formatting logs are stored in `/var/log/usb_formatter.log`. If errors occur, check this log file for details.
