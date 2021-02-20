# Town Of Impostors
Town Of Impostors Mod is an Among Us modification for Windows. This mod aims to add new classes and abilities to the game to enhance the gameplay. It can also **be used in public servers**.

More classes and abilities will be added in future versions.

<img src="Pics/TownOfImpostors-Sheriff.PNG" width="300"></img>
<img src="Pics/TownOfImpostors-Doctor.PNG" width="300"></img>
<img src="Pics/TownOfImpostors-Impostor.PNG" width="300"></img>

---

# New Classes and Abilities?
## Sheriff
The Sheriff is a class that has the ability to kill Impostors. However, if they attempt to kill a fellow crewmate, they will lose their own life instead as a punishment.

## Doctor
The Doctor is a class that has the ability to revive dead players. However, this means they are also able to revive Impostors that have been killed by the Sheriff.

## Impostor
The Impostor has additional abilities they can make use of:
- **Drag & Drop Bodies** - Impostors can drag around and drop dead bodies to reposition them. They may also drag bodies through vents.
- **Dispose Bodies** - Impostors can dispose a body they are dragging if they are close to a vent or inside the vents.
- **Disguise** - Impostors can disguise as another player for set duration. They must first sample the DNA of a player by being nearby the player.

---

# Custom Game Options:
| Sheriff | Doctor | Impostor |
| --- | --- | --- |
| <ul><li>Sheriff Count</li><li>Sheriff Kill Cooldown</li><li>Sheriff Visibility Toggle</li></ul> | <ul><li>Doctor Count</li><li>Revive Cooldown</li></ul> | <ul><li>Dispose Ability Toggle</li><li>Dispose Ability Cooldown</li><li>Disguise Ability Toggle</li><li>Disguise Ability Cooldown</li></ul> |

---

<h1 id="installation">Installation</h1>

- Download the Mod for your specific game version. You are not able to launch the game if the versions do not match.
- Make a copy of your game’s root directory ("Steam/steamapps/common/Among Us") and rename it to whatever you want (e.g. "Steam/steamapps/common/Among Us Town Of Impostors")
- Extract the contents TownOfImpostors.zip into the copied folder you created
- **Make sure to launch the game via Among Us.exe**

**Verifying installation success**
- Launch the game via Among Us.exe
- In the top-left corner, below Among Us version, you should see _Town Of Impostors vX.X.X Mod by AJMix_

<p>If you don't see this message please take a look at the 
  <a href="#troubleshooting">troubleshooting section</a>.
</p>
 
<h2>Releases and Compatibility</h2>
<table style="width:100%">
  <tr>
    <th>Among Us Version</th>
    <th>Mod Version</th>
    <th>Link</th>
  </tr>
   <tr>
    <td>v2020.12.9s</td>
    <td>v1.0.0</td>
    <td><a href="https://github.com/AJMix/TownOfImpostors/releases/download/v1.0.0/TownOfImpostors1.0.0.zip">Download</></td>
  </tr>
</table>

<details>
  <summary>Changelog</summary>
</details>

---

# Q&A
 
### Can you play Proximity Chat (Crewlink) with it?
Yes, Crewlink supports Among Us Modifications

### Can you get banned for playing on public Servers?
At the current state of the game there is no perma ban system for the game. The mod is designed in a way, that it does not send prohibited server requests.
You are also able to join your own custom server to be safe <a href="https://github.com/Impostor/Impostor">(Impostor)</a></p>

### How can I join a custom server?
Go to your game directory and open BepInEx/config/org.bepinex.plugins.TownOfImpostors.txt. There you can set the hostname or IP of the server. Then set the server region to CUSTOM.

### Do my friends need to install the mod to play it together?
Yes. Every player in the lobby must have the mod installed.

### If you'd like to contact me about anything else:
- **Discord:** AJMix#1111
- **Email:** <a href="mailto:ajmixdev@gmail.com">ajmixdev@gmail.com</a>

---

<h1 id="troubleshooting">Troubleshooting</h1>

### The mod isn't installed or game doesn't launch
- Please make sure you're using the latest version of the mod and the correct version of Among Us for it
- Make sure you have followed all the <a href="#installation">installation steps</a>, especially launching the game via the Among Us.exe file
- You might be missing some cpp libs (software libraries used by the mod); please install <a href="https://aka.ms/vs/16/release/vc_redist.x86.exe">visual studio c++</a>

### I can't find my issue
You can <a href="https://github.com/AJMix/TownOfImpostors/issues/new">raise an issue within GitHub</a> documenting your issue. You will need to be logged into GitHub to do this.

---

<h1>License</h1>
<p>This software is distributed under the <b>GNU GPLv3</b> License.
<a href="https://github.com/BepInEx/BepInEx">BepinEx</a> is distributed under <b>LGPL-2.1</b> License.</p>
