---
layout: default
title: One Handed Spears
parent: Tutorials
nav_order: 1
---

# One Handed Spears

{: .summary}
> Estimated Time: 10 minutes
> 
> Changes spears to be one-handed weapons.

### What You'll Need

* A text editor (Notepad, Notepad++, [VS Code](https://code.visualstudio.com/download))
* The `baseitems.2da` file from [here](https://neverwintervault.org/project/nwnee/other/nwn-ee-819334-full-2da-source)


---

### Step 01: Open baseitems.2da
![Screenshot of baseitems.2da](../assets/img/spears_00.png)

### Step 02: Find "shortspears"
![Screenshot of the shortspear row](../assets/img/spears_01.png)

### Step 03: Change "WeaponSize" From 4 to 3
![Screenshot of the WeaponSize column](../assets/img/spears_02.png)
![Screenshot of the existing value](../assets/img/spears_03_01.png)
![Screenshot of the value being changed](../assets/img/spears_03_02.png)

### Step 04: Move baseitems.2da To The Override Folder

![Screenshot of the override folder](../assets/img/spears_04.png)

{: .summary}
> * If you're on Windows, the folder is at `My Documents\Neverwinter Nights\override`.
> * If you're on Linux, the folder is at `~/.local/share/Neverwinter Nights/override`.

### Step 05: Test Your Changes

![Screenshot of character wielding spear and shield](../assets/img/spears_05.png)

---

## Summary

* We are overriding the size of spears (details [here](https://nwn.wiki/spaces/NWN1/pages/38174935/baseitems.2da)).
  * Spears can now be equipped in one hand with a shield.