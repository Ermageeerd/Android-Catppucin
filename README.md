# Android-Catppuccin
A collection of styles to attempt to style Android with a soothing pastel theme.
![The Heliboard keyboard with my Cattpuccin theme on.](https://raw.githubusercontent.com/Ermageeerd/Android-Catppucin/refs/heads/main/Images/Screenshot_20250802-2.png)
![Android 13 Easter Egg with my Material You theme.](https://raw.githubusercontent.com/Ermageeerd/Android-Catppucin/refs/heads/main/Images/Screenshot_20250801-234814.png)

# NOTE:

These styles are not made or endorsed by Catppuccin, It is an unofficial port.

# Setup

The Material You theme requires use of Shizuku, Learn how to set that up [here.](https://shizuku.rikka.app/)

It also needs [ColorBlendr](https://github.com/Mahmud0808/ColorBlendr) to apply the theme.

For the keyboard, you need to use [HeliBoard](https://github.com/Helium314/HeliBoard), as it was the one I made the styles for. Learn how to apply the theme [here.](https://github.com/Helium314/HeliBoard/wiki/Customization#theme-colors)

Or don't. I'm not a cop.

Copy this first.

Mocha:
``` json
{"name":"Catppuccin","moreColors":0,"colors":{"text":{"first":-3287308,"second":false},"functional_keys":{"first":-15066582,"second":false},"background":{"first":-14803410,"second":false},"keys":{"first":-15066582,"second":false},"spacebar":{"first":-15066582,"second":false}}}
```
Mocha Night:
``` json
{"name":"Catppuccin","moreColors":0,"colors":{"hint_text":{"first":null,"second":false},"spacebar":{"first":-14803410,"second":false},"functional_keys":{"first":-14803410,"second":false},"text":{"first":-3287308,"second":false},"background":{"first":-15724262,"second":false},"keys":{"first":-14803410,"second":false},"accent":{"first":-3496201,"second":false}}}
```
Go to Heliboard's app, and tap **Appearance**.

Tap **Colors**, then tap **Load**, before finally tapping Paste.

If the ColorBlendr theme does not work, use SetEdit to manually set the theme.

Go to Secure, and scroll until you see theme_customization_overlay_packages.

Tap on it, press "Edit", and set it to this:

```json
{"android.theme.customization.font":"default","android.theme.customization.accent_color":"1E1E2E","android.theme.customization.system_palette":"181825","android.theme.customization.color_source":"preset","_applied_timestamp":1755391601864,"android.theme.customization.theme_style":"VIBRANT"}
```
Tap Save Changes.
