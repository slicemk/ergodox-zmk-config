This repository contains the default ZMK user configuration for the [ErgoDox
Wireless](https://www.slicemk.com/pages/ergodox-wireless) keyboard. While the
[SliceMK Keymap Configurator](https://config.slicemk.com/) is recommended for
the majority of users, the GitHub Actions workflow provides some additional
options for customization.

If you have questions, feel free to join the [SliceMK
Discord](https://discord.gg/FQvyd7BAaA).

# Instructions

- Fork this repository on GitHub.
- Modify the `board` and `shield` values in `build.yaml` to match the ZMK build
  target based on your hardware (see below).
- If you have a dongleless setup, delete `config/slicemk_ergodox_dongle.conf`
  and create an empty `config/slicemk_ergodox_leftcentral.conf` in its place.

# Board/Shield

Here are some of the common dongle options:

- **Raytac MDBT50Q-RX (Blue)**
	- Board `raytac_mdbt50q_rx`
	- Shield `slicemk_ergodox_dongle`
- **Nordic nRF52840 Dongle (Blue)**
	- Board `nordic_nrf52840_dongle_slicemk`
	- Shield `slicemk_ergodox_dongle`
- **SliceMK USB C Dongle MDBT50Q Blue**
	- Board `slicemk_usbc_mdbt50q_blue`
	- Shield `slicemk_ergodox_dongle`

Here are some of the common dongleless options:

- **SliceMK ErgoDox Wireless 202104 (Blue)**
	- Board `slicemk_ergodox_202104`
	- Shield `slicemk_ergodox_leftcentral`
- **SliceMK ErgoDox Wireless 202108 Blue**
	- Board `slicemk_ergodox_202108_blue_left`
	- Shield `slicemk_ergodox_leftcentral`
- **SliceMK ErgoDox Wireless 202108 Green**
	- Board `slicemk_ergodox_202108_green_left`
	- Shield `slicemk_ergodox_leftcentral`
- **SliceMK ErgoDox Wireless 202109 (Green)**
	- Board `slicemk_ergodox_202109`
	- Shield `slicemk_ergodox_leftcentral`
- **SliceMK ErgoDox Wireless 202205 Green**
	- Board `slicemk_ergodox_202205_green_left`
	- Shield `slicemk_ergodox_leftcentral`
- **SliceMK ErgoDox Wireless 202207 Green**
	- Board `slicemk_ergodox_202207_green_left`
	- Shield `slicemk_ergodox_leftcentral`
