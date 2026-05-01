# Cyber-Philomath-Notes
Cyber Security all-in-one (HTML) note taking application.

<img width="1920" height="1005" alt="image" src="https://github.com/user-attachments/assets/b147a673-d21b-48e8-bb7c-7816763873a6" />


**Left Pane**
Includes a markdown (.md) formatted note taking section with a starting template to use during any
penetration testing engagement, CTF, or HackTheBox box, etc.

**Right Pane**
Includes functionallity to export the flowchart as a .png file. Export .zip file including .png flowchart, .md markdown of notes, and any screenshots.
Additionally, included functionally is saving workspaces as .json files that can be loaded later and the ability to reset the workspace. 
** Select option in browser settings to "alway's ask where to save files" if you dont want the exports always going to the Downloads folder.

The upload screenshot button lets you upload screenshots. The ability to paste screenshots (CTRL + V) is also supported. Screenshots are saved separately from the main markdown file
this is mostly to save space, I might change it later.

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
   
<img width="427" height="677" alt="image" src="https://github.com/user-attachments/assets/0f6956de-99ba-4815-b219-d0159c1e163e" />


**Goals:**

- template for penetration testing engagements
  
- note template for CTFs
  
- note template for HackTheBox boxes
  
- ability to add flowchart of methodology used
  
- ability to paste in screenshots
  
- export full zip of .md file, .png flowchart, and any screenshots
  
