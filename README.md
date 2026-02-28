# 🎮 Digital-Forensics-Courseware-Game ( Digital Shadows )
> Digital Shadows is an interactive Unity-based game designed to teach the public and cybersecurity students the complete 5-phase Digital Forensics Investigation Process — through a real simulated case.

---

## 📖 Overview
This project was developed as a Major Project for the Diploma in Cybersecurity & Digital Forensics at Temasek Polytechnic. It takes the form of a Unity game that walks players through a fictional but **$\color{#90D5FF}{realistic}$** **$\color{#90D5FF}{forensic}$** **$\color{#90D5FF}{investigation}$** of Jimmy Wilson — an employee accused of running a covert digital forgery business.
The game is designed to be beginner-friendly for the general public, while also serving as **$\color{#90D5FF}{hands-on}$** **$\color{#90D5FF}{training}$** **$\color{#90D5FF}{material}$** for cybersecurity students.

---

## 🎥 Gameplay Video

> Click the Link below to watch a full walkthrough of the game.

![Image](https://github.com/user-attachments/assets/2c603365-8935-4233-847b-a4f2202a507c)
[![Digital Forensics Game Gameplay](https://img.youtube.com/vi/-EGm1B11H8Y/maxresdefault.jpg)](https://youtu.be/-EGm1B11H8Y)

*▶ Full gameplay walkthrough — covering all 5 forensic investigation phases*

---

## 🧩 The 5-Phase Investigation (Gameplay)


| Phase | Description | What Players Do |
|-------|-------------|-----------------|
| **1. Identification** | Understand the crime context and identify evidence | Review the case brief and device information |
| **2. Preservation** | Protect evidence integrity | Photograph the device, complete a Chain of Custody form, remove and image the hard disk |
| **3. Analysis** | Examine the forensic image | Use a **$\color{#90D5FF}{simulated}$** **$\color{#90D5FF}{Autopsy}$** **$\color{#90D5FF}{interface}$** to find emails, documents, web searches, and bookmarks |
| **4. Documentation** | Record findings | Identify and tag forensic artefacts across multiple evidence categories |
| **5. Presentation** | Present conclusions | Accumulate enough evidence points to prove the suspect guilty |

---

## 🔬 Key Features

- 🖥️ **Simulated Autopsy Interface** — players navigate a realistic forensic tool to uncover evidence
- 📸 **Evidence Photography** — photograph all 6 sides of a device before analysis
- 📋 **Chain of Custody Form** — interactive form with validation and error handling
- 💾 **Disk Imaging Scene** — drag-and-drop forensic imaging with source/destination logic
- 🔍 **Multi-category Artefact Analysis** — web searches, bookmarks, documents, deleted files, and emails
- 🏆 **Scoring System** — players need ≥14,000 points to prove the suspect guilty

---

## 🛠️ Technologies & Tools

| Category | Tools |
|----------|-------|
| Game Engine | Unity |
| Forensic Analysis | Autopsy, FTK Imager |
| Metadata Editing | ExifTool, SetMace |
| Scripting | C#, Powershell |

---

## 💭 Personal Reflection

#### Understanding real forensic workflows ####
Working through each phase of the investigation — from photographing evidence to filling a Chain of Custody form to imaging a disk — gave me a much deeper appreciation for how structured and meticulous real forensic work is. Recreating these workflows in a game format forced me to understand *why* each step matters, not just *what* it involves. I now see digital forensics not just as a technical discipline, but as one where process integrity is everything.

#### Manipulating metadata to create a realistic challenge ####
The steganography challenge was the most technically demanding part of the project for me personally. Using ExifTool SetMace to carefully alter timestamps so the modified files would blend seamlessly into the original forensic image was a real eye-opener. It made me realise how easily metadata can be manipulated — and by extension, how important it is for forensic investigators to scrutinise it carefully. This directly deepened my interest in forensic anti-tampering techniques.

#### Connecting forensics concepts to real-world crime scenarios ####
Grounding the game in a realistic case — identity theft, forgery, and links to a drug distribution network — made the learning feel meaningful rather than academic. Researching how real investigators would approach such a case, what artefacts would be significant, and how evidence is presented in a legal context gave me a much more complete picture of what a career in cybersecurity and digital forensics actually looks like in practice.

#### Learning C# and Unity from scratch ####
Coming into this project, I had no prior experience with Unity or C#. It was initially intimidating to pick up a new language and engine simultaneously under a project deadline. I bridged the gap by drawing parallels between C# and languages I already knew — Python and JavaScript — which helped me get up to speed faster than expected. By the end, I was writing interactive game logic, handling UI events, and managing scene transitions confidently. It proved to me that the ability to learn new tools quickly is just as valuable as mastering any single one.

#### Collaborating as a team on a large project ####
This was by far the largest and most complex project I had worked on as part of a team. Coordinating across game development, forensic content, and documentation required clear communication and trust. There were moments where technical decisions affected each other's work, and navigating those dependencies taught me a lot about how to collaborate effectively under pressure. I came away with a much stronger appreciation for how good teamwork multiplies what any individual can achieve alone.

