# Gaming-on-Ubuntu
You don't need Windows for gaming any more. Ubuntu comes with graphics drivers. Steam has Steam Play and Lutris has a huge library of install scripts, so everything is handled for you. The one thing you will need to do occasionally is experiment with different Wine distributions.
This guide provides an overview of setting up your Ubuntu 23.10 system for a smooth gaming experience.

Prerequisites:

* A system running Ubuntu 23.10
* Basic understanding of the terminal (command line) is helpful

## Getting Started:

Update and Upgrade:

Ensure your system has the latest security patches and software updates by running the following commands in the terminal:

```
sudo apt update && sudo apt upgrade
```
Enter your password when prompted.

## Install Additional Software:

Several applications can enhance your gaming experience. Here are some popular choices:

* Graphics Drivers: For optimal performance, install the latest graphics drivers for your hardware. You can usually find them through the "Software" application or by searching online for your specific graphics card model and Ubuntu version. - This applys mainly to Nvidia
* Game Launchers: Consider installing launchers like Steam, Lutris, or Playnite to manage your games and simplify launching them through a user-friendly interface. For example installing steam on Ubuntu
  ```
  sudo apt install steam
  ```
  
* Media Codecs: Some games might require additional media codecs for playback. You can install them using the following command:
  ```
  sudo apt install ubuntu-restricted-extras
  ```
## Explore Gaming Platforms:

Several options exist for playing games on Ubuntu:

* Steam Play: Steam offers a compatibility layer called Proton that allows you to play many Windows games on Linux. You can enable Steam Play in the Steam settings under "Steam Play."
* Native Linux Games: Many games are available natively for Linux on platforms like Steam or through the official repositories.
* Emulators: You can use emulators to play games from other consoles, but legality and compatibility may vary. Research emulators before using them.

## Optimizations (Optional):

Kernel Selection: Consider using a custom kernel like Xanmod (https://www.reddit.com/r/archlinux/comments/xxtv28/is_xanmod_kernel_worth/) that might offer better performance for specific hardware. Research and choose a kernel suitable for your needs.
Game-Specific Tweaks: Some games might benefit from additional configuration tweaks. You can find online guides or community forums dedicated to specific games for optimization tips.
Resources:

* GamingOnLinux: https://www.gamingonlinux.com/ (Provides news, reviews, and tutorials for Linux gaming)
* Ubuntu Wiki - Gaming: https://www.youtube.com/watch?v=z3T2TAagyrw (Official Ubuntu documentation on gaming)
* ProtonDB: https://www.protondb.com/ (Database of game compatibility with Proton)

## Important Notes:

* Not all games will run perfectly on Linux. Compatibility can vary.
* The Linux gaming landscape is constantly evolving, so new tools and resources might emerge.
* This guide offers a starting point. Feel free to explore further and customize your setup based on your specific needs and preferences.

### Enjoy gaming on Ubuntu!
