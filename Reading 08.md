# What is the Windows Registry, and How Does It Work?
 # The Windows registry is a collection of several databases. There are system-wide registry settings that apply to all users, and each Windows user account also has its own user-specific settings.

# On Windows 10 and Windows 7, the system-wide registry settings are stored in files under C:\Windows\System32\Config\ , while each Windows user account has its own NTUSER.dat file containing its user-specific keys in its C:\Windows\Users\Name directory. You can’t edit these files directly.

# But it doesn’t matter where these files are stored, because you’ll never need to touch them. When you sign in to Windows, it loads the settings from these files into memory. When you launch a program, it can check the registry stored in memory to find its configuration settings. When you change a program’s settings, it can change the settings in the registry. When you sign out of your PC and shut down, it saves the state of the registry to the disk.

# The registry contains folder-like “keys” and “values” inside those keys that can contain numbers, text, or other data. The registry is made up of multiple groups of keys and values like HKEY_CURRENT_USER and HKEY_LOCAL_MACHINE. These groups are called “hives” because of one of the original developers of Windows NT hated bees. Yes, seriously.

# Most Windows users will never need to touch the registry. Windows itself and many programs use the registry, and you usually don’t have to worry about it.

# However, you can edit the registry yourself with the Registry Editor, included with Windows. It lets you click through the registry and change individual registry settings.

# The registry itself is a big mess of a database, and you won’t find much by clicking through it yourself, of course. But you can often find “registry hacks” online that tell you what settings you need to change to accomplish a particular task.

# How to Edit the Registry
 # + To get started, you’ll open the Registry Editor application. To do so, press Windows+R to open the Run dialog. Type “regedit” and then press Enter. You can also open the Start menu, type “regedit.exe” into the search box, and press then Enter.
 # + You’ll be asked to agree to a User Account Control prompt before continuing. This gives the Registry Editor the ability to modify system settings.
# + Navigate to whatever key you need to modify in the left pane. You’ll know where you need to be because the instructions for the registry hack you’re trying to apply will tell you.
 # + On Windows 10, you can also just copy-paste an address into the Registry Editor’s address bar and press Enter.





## Things I want to know more about
 # + I just want to keep learning and progressing day by dayS 