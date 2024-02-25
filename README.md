## Project Name: tarjuman

### Description:
**tarjuman** is a basic and personal keybinding system tailored for diacritic extensions on Linux Keyboards utilizing Wayland + Hyprland.

### Keybindings:

- **ā**: Left Alt + 'a'
- **Ā**: Left Alt + Shift + 'a'

- **ī**: Left Alt + 'i'
- **Ī**: Left Alt + Shift + 'i'

- **ū**: Left Alt + 'u'
- **Ū**: Left Alt + Shift + 'u'

- **ẓ**: Left Alt + 'z'
- **Ẓ**: Left Alt + Shift + 'z'

- **ḍ**: Left Alt + 'd'
- **Ḍ**: Left Alt + Shift + 'd'

- **ḥ**: Left Alt + 'h'
- **Ḥ**: Left Alt + Shift + 'h'

### Dependencies:
- None noted in the provided scripts or description.

### Installation:
1. Copy the provided script into your preferred keybinding configuration file: (Typically this will be `.conf/hypr/hyprland.conf`
```
# Custom bindings for Arabic Transliteration work
bind=Alt_R,a,exec,wtype "ā" # Bind ā to Left Alt + 'a'
bind=Alt_L_SHIFT,A,exec,wtype "Ā" # Bind Ā to Left Alt + 'A'

bind=Alt_L,i,exec,wtype "ī" # Bind ī to Left Alt + 'i'
bind=Alt_L_SHIFT,I,exec,wtype "Ī" # Bind Ī to Left Alt + 'I'

bind=Alt_L,u,exec,wtype "ū" # Bind ū to Left Alt + 'u'
bind=Alt_L_SHIFT,U,exec,wtype "Ū" # Bind Ū to Left Alt + 'U'

bind=Alt_L,z, exec,wtype "ẓ" # Bind ẓ to Left Alt + 'z'
bind=Alt_L_SHIFT,Z, exec,wtype "Ẓ" # Bind Ẓ to Left Alt + 'Z'

bind=Alt_L,d, exec,wtype "ḍ" # Bind ḍ to Left Alt + 'd'
bind=Alt_L_SHIFT,D, exec,wtype "Ḍ" # Bind Ḍ to Left Alt + 'D'

bind=Alt_L,h, exec,wtype "ḥ" # Bind ḥ to Left Alt + 'h'
bind=Alt_L_SHIFT,H, exec,wtype "Ḥ" # Bind Ḥ to Left Alt + 'H'


```
2. Reload the keybinding configuration or restart the system to apply changes.

### Usage:
- Once installed, use the specified key combinations to input the corresponding diacritic characters.

### Note:
- This setup is specifically designed for systems running Wayland + Hyprland. Compatibility with other configurations may vary.

### License:
- This project is under [INSERT LICENSE HERE].
