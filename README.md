If QTL-seq_GUI_ver1.tgz is downloaded to your Desktop

1. Start WSL
Open Ubuntu (or another WSL distribution) from the Windows Start Menu.
When the terminal window opens, enter the following commands step by step.

2. Extract the application
Run these commands:
mkdir -p ~/apps
# Create the target folder for extraction

tar xzf "$(wslpath "$USERPROFILE")/Desktop/QTL-seq_GUI_ver1.tgz" -C ~/apps
# Extract the tgz file from your Desktop into ~/apps
# Replace "Desktop" with the folder where you saved the file if different


3. Grant execute permission (only the first time)
chmod +x ~/apps/QTL-seq_GUI_ver1


5. Launch the application
~/apps/QTL-seq_GUI_ver1


7. How to run it from the second time onward
cd ~/apps
./QTL-seq_GUI_ver1
