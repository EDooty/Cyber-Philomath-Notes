# Cyber-Philomath-Notes
Cyber Security all-in-one (HTML) note taking application.

<img width="1917" height="978" alt="image" src="https://github.com/user-attachments/assets/e06765e6-ec2e-47c2-87f3-7dcf0adb26ba" />


**Left Pane**
Includes a markdown (.md) formatted note taking section with a starting template to use during any
penetration testing engagement, CTF, or HackTheBox box, etc.

**Right Pane**
Includes functionallity to export the flowchart as a .png file, .zip file including .png flowchart, .md markdown of notes, screenshots, and threat library entries.
Additionally, included functionally is saving workspaces as .json files that can be loaded later and the ability to reset the workspace. 
** Select option in browser settings to "alway's ask where to save files" if you dont want the exports always going to the Downloads folder.

The upload screenshot button lets you upload screenshots. The ability to paste screenshots (CTRL + V) is also supported. Screenshots are saved separately from the main markdown file
this is mostly to save space, I might change it later.

The "Threat Library" allows the entry of title and category of any threats found while on engagements. The entries are saved in the browsers cache and will be deleted if your browser is set to delete cache on closing. The menu does allow the library to be exported and saved for later imports.

<img width="805" height="404" alt="image" src="https://github.com/user-attachments/assets/1bc105ec-67ee-4c25-acd6-5a2df57b9f30" />


**Shortcuts**

CTRL + V - Can paste screenshots (saved as base64 in json file and included in right pane). 

** Click out of the markdown editor in order to paste screenshot

| - used to add new line to node in flowchart

ALT + T - Inserts timestamp in markdown area

**Flowchart** 

Everything added in-between the **```attackpath** is added to the flowchart. 
Accepts code format for commands in-between back ticks **(``)** and newlines with **(|)**.

```attackpath
- Target
 - Discovery
  - Web|Directories
   - `gobuster`
    - /admin
 - Initial Access
  - *Vulnerability*|CVE-2021-44228
```
   
<img width="761" height="419" alt="image" src="https://github.com/user-attachments/assets/737d92d5-4a6e-46f7-ba25-0df22ec63e2e" />

**Goals:**

- template for penetration testing engagements
  
- note template for CTFs
  
- note template for HackTheBox boxes
  
- ability to add flowchart of methodology used
  
- ability to paste in screenshots
  
- export full zip of .md file, .png flowchart, and any screenshots
  
