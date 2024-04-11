# Keychron Q6 Pro UK ISO Layout with Knob - VIA Configuration with Fn keys active

This repository contains VIA configuration files for the Keychron Q6 Pro mechanical keyboard with an ISO layout and a knob, mainly so that i have a backup. The only modification made in these configurations is the remapping of function keys to be active by default. This is the same as the MacOS setting "Use F1, F2, etc. keys as standard function keys" option in System Settings. This is needed because [the System Setting configuration item only applies to Apple keyboards](https://www.reddit.com/r/Keychron/comments/ptxbof/comment/hei61p5).

## Repository Contents

- `keychron_q6_pro_iso_knob.layout.fn_keys_active.json` - This is the modified VIA layout file where the function keys are set to be active by default.
- `keychron_q6_pro_iso_knob.layout.original.json` - The original VIA layout file for the Keychron Q6 Pro with an ISO layout and a knob, without any modifications.
- `q6_pro_iso_knob.via_definition_file.json` - The VIA definition file required by the VIA software to recognize the Keychron Q6 Pro with ISO layout and a knob.

## How to Use

To apply the modified function keys layout to your Keychron Q6 Pro, follow these steps:

1. Go to the [official VIA website](https://usevia.app/), connect and authorize your keybooard. No need to download anything, just use Chrome.
2. Click on the Design tab (and confirm that you're aware you're modifying settings).
3. Upload the definition file.
4. Go to the "Configure" tab, and select "SAVE + LOAD" on the left. If you want, save your current mapping (although you could always reset the keyboard, and i've saved it in this repo), and then load the updated mapping above.

For more information on using VIA with your Keychron keyboard, visit the [official Keychron support page](https://www.keychron.com/pages/how-to-use-via-to-pair-with-keychron-q-series-keyboard).
