[![Banner](https://github.com/Omni-guides/Wabbajack-Modlist-Linux/blob/main/images/WabbajackModlistsBanner2.png)](https://github.com/Omni-guides/Wabbajack-Modlist-Linux)

<p align="center"><b>Skyrim Deck/PC -</b> 
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Licentia-DECK">Licentia DECK</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Legends-of-the-Frost">Legends of the Frost</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Eldryn">Eldryn</a>
</p>

<p align="center"><b>Skyrim PC Only -</b>
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/General-Linux-Guide-(AVO)">AVO</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Nordic-Souls">Nordic Souls</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Keizaal">Keizaal (Refresh Required)</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Living-Skyrim-4">Living Skyrim 4</a>
</p>

<p align="center"><b>Fallout 4 -</b>
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Fallout-4:-Welcome-to-Paradise">Welcome to Paradise</a>
  &emsp; &emsp; <b>Fallout New Vegas -</b>
  
</p>

<p align="center"><b>Experimental -</b>
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Tuxborn">Tuxborn (Deck)</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Skyrim:-Anvil">Anvil (PC)</a>

</p>

<p align="center"><b>Other -</b>
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki">Home</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Using-the-omni%E2%80%90guides.sh-Automation-Script">Automation Script</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/General-Linux-Guide-(AVO)">General Linux</a> ·
  <a href="https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/ENB,-Reshade-and-Community-Shaders">ENB, Reshade & Community Shaders</a>
</p>

---

DISCLAIMER - I am not affiliated with the Wabbajack group in any way, just a gamer trying to help other gamers. You may be able to get assistance with this guide from the #unofficial-linux-help channel of the main [Official Wabbajack Discord](https://discord.gg/wabbajack), but it may be best to @ me on Discord (@omni). Due to this being an unofficial guide, assistance on this from Wabbajack support directly, or the Modlist developers, is highly unlikely.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/D1D8H8WBD)

***

## Introduction

The contained guides are a work in progress, based mostly on my own tests and collaboration with multiple users posting in the #unofficial-linux-help channel of the [Official Wabbajack Discord](https://discord.gg/wabbajack). With thanks to all involved. Feedback is always welcome.

The steps included have been used to get Wabbajack Modlists running on Linux, but not the Wabbajack application itself. As it stands, there is currently **no way** to run Wabbajack itself on Linux - the best efforts so far still result in instability and lack of function. With the steps in this guide, I have confirmed success with Modlists for Skyrim, Fallout 4, Oblivion and more, and on platforms such as SteamDeck (SteamOS/Arch), Garuda Linux (Arch) and Fedora/Nobara - though the process should be largely the same for most Linux distros.

Until there is an officially supported version of Wabbajack for Linux, my recommendation is to use a Windows system to run the Wabbajack application and perform the initial download of the Wabbajack Modlist you want to use. I run a small-ish Windows VM on my gaming desktop with the sole purpose of running Wabbajack and to download Wabbajack lists. Utilising Samba, I download and install the modlists directly to my Linux Filesystem, and then carry out the steps in these guides. You can read more about my setup [here](https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/My-Wabbajack-VM-Setup).

SteamDeck users can follow the Modlist-specific guides linked, to get step-by-step instructions to get you up and running for your chosen Modlist.

For general Linux systems (i.e. not the SteamDeck), you can follow the steps in the [General Linux](https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/General-Linux-Guide-(AVO)) guide. This guide uses AVO 8 as an example list, but you can replace it with your Modlist of choice, the steps should be largely the same. If you have some issues, you could check the Modlist specific guide in case there are additional steps specific to that Modlist.

I have also recently published an automation script that aims to carry out most of the steps required, for any modlist, on any Linux system, automatically. You can see more about this [here](https://github.com/Omni-guides/Wabbajack-Modlist-Linux/wiki/Using-the-omni%E2%80%90guides.sh-Automation-Script).

Finally, if you're a Modlist developer and you want me to test your Modlist, let me know! Happy gaming!

***
