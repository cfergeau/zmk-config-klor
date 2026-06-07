<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/docs/images/klor-font-logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="/docs/images/klor-font-logo-bright.svg">
  <img alt="KLOR logo font" src="/docs/images/klor-font-logo-bright.svg">
</picture>

# ZMK MODULE FOR THE KLOR SPLIT KEYBOARD

This repository is a fork of [GEIGEIGEIST zmk-config-klor](https://github.com/GEIGEIGEIST/zmk-config-klor).
It turns it into a [ZMK module](https://zmk.dev/docs/features/modules) and
follows recommendations from the ZMK project:
> A common ZMK setup thus consists of the following separate components, commonly housed in their respective Git repositories:
> - A single ZMK config maintained by the user, containing the .conf and .keymap files for one or multiple keyboards. This is also where files from ZMK or modules should be overridden/modified, if there is a need.
> - Any number of ZMK modules, maintained by the module's owner. Some modules may contain multiple keyboards or functionalities. If all of your keyboards and functionalities are internal to ZMK's tree, then no modules are necessary.
> - The ZMK firmware itself, maintained by its contributors.

This git repository only contains the code for the KLOR shield (read "keyboard" if you are unfamiliar with ZMK terminology).
It’s meant to be used in combination with a separate "config" git repository which will contain your own keymap definitions.

Its `main` branch has the necessary changes to make it build with ZMK `main` branch.

Both branches also have support for ZMK Studio.

# ZMK CONFIG FOR THE KLOR SPLIT KEYBOARD

[Here](https://github.com/GEIGEIGEIST/qmk-config-klor) you can find the QMK config for the KLOR.\
[Here](https://github.com/GEIGEIGEIST/klor) you can find the hardware files and build guide.

KLOR is a 36-42 key column-staggered split keyboard. It supports a per key RGB matrix, encoders, OLED displays, a Pixart Paw3204 trackball and four different layouts, through brake off parts.

![KLOR layouts](/docs/images/klor-layouts.svg)

Polydactyl is the default layout. If you choose one of the other layouts you can use the matching template in the default keymap.
