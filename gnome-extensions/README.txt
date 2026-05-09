GNOME Extensions Settings Backup & Restore

Backup current GNOME extension settings:
dconf dump /org/gnome/shell/extensions/ > gnome-extensions-settings.txt

Restore GNOME extension settings:
dconf load /org/gnome/shell/extensions/ < gnome-extensions-settings.txt
