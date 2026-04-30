# Cyber-Philomath-Notes
Cyber Security Notes Template 
All-in-one HTML note taking application.

<img width="1912" height="982" alt="image" src="https://github.com/user-attachments/assets/1d984e4c-7a0c-4aa0-8625-3c6af43aff9e" />

**Left Pane**
Includes a markdown (.md) formatted note taking section with a starting template to use during any
penetration testing engagement, CTF, or HackTheBox box, etc.

**Right Pane**
Includes functionallity to export the flowchart as a .png file. Export .zip file including .png flowchart, .md markdown of notes, and any screenshots.
Additionally, included functionally is saving workspaces as .json files that can be loaded later and the ability to reset the workspace

The upload screenshot button lets you upload screenshots. The ability to paste screenshots (CTRL + V) is also supported. Screenshots are saved separately from the main markdown file
this is mostly to save space, I might change it later.

**Shortcuts**

CTRL + V - Can paste screenshots (saved as base64 in json file and included in right pane). 
** May need to CTRL + V where it says Upload Screenshot in the top right pane

| - used to add new line to node in flowchart

ALT + T - Inserts timestamp in markdown area

**Flowchart** 

Everything added in-between the **```attackpath** is added to the flowchart. Accepts code format for commands in-between back ticks **(``)** and newlines with **(|)**.

```attackpath
- Target
 - Discovery
  - Web
   - Directories|`gobuster`
    - `/admin`
 - Initial Access
```
   
<img width="370" height="627" alt="image" src="https://github.com/user-attachments/assets/7a5810db-d0a0-49a0-b913-8111e6de3468" />


**Goals:**

- template for penetration testing engagnments
  
- note template for CTFs
  
- note template for HackTheBox boxes
  
- ability to add flowcharts of users methodology
  
- ability to copy in screenshots
  
- export full zip of .md file, .png flowchart, and any screenshots
  
