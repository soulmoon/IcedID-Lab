# 🧊 IcedID Malware Analysis Lab

## Category
- **Threat Intel**

## Tools
- VirusTotal  
- Malpedia  
- Tria.ge  

---

## Scenario
A cyber threat group was identified for initiating widespread phishing campaigns to distribute further malicious payloads. The most frequently encountered payloads were IcedID. You have been given a hash of an IcedID sample to analyze and monitor the activities of this advanced persistent threat (APT) group.

---

## Questions & Answers

### Q1  
**What is the name of the file associated with the given hash?**  
> `document-1982481273.xlsm`  
**Source:** VirusTotal  
<img width="940" height="428" alt="image" src="https://github.com/user-attachments/assets/865c424d-86b2-4e55-b20c-7008932e02d0" />

---

### Q2  
**Can you identify the filename of the GIF file that was deployed?**  
> `3003.gif`  
**Source:** VirusTotal  
<img width="940" height="546" alt="image" src="https://github.com/user-attachments/assets/494a2fbc-85eb-49db-bf95-04b33901d79c" />

---

### Q3  
**How many domains does the malware look to download the additional payload file in Q2?**  
> `5`  
**Source:** VirusTotal  
<img width="940" height="316" alt="image" src="https://github.com/user-attachments/assets/ddc5f28c-4f7a-4127-82b5-45dfb47aa941" />

---

### Q4  
**From the domains mentioned in Q3, a DNS registrar was predominantly used by the threat actor to host their harmful content, enabling the malware's functionality. Can you specify the Registrar INC?**  
> `namecheap`  
**Source:** VirusTotal  
<img width="940" height="450" alt="image" src="https://github.com/user-attachments/assets/6eb403dc-0649-4b74-84c0-fd3dacd264ba" />

---

### Q5  
**Could you specify the threat actor linked to the sample provided?**  
> `GOLD CABIN`  
**Source:** [Malpedia - IcedID](https://malpedia.caad.fkie.fraunhofer.de/details/win.icedid)  
<img width="940" height="215" alt="image" src="https://github.com/user-attachments/assets/2bc74dc6-a4f3-4d85-8a7c-af24c03663e9" />

---

### Q6  
**In the Execution phase, what function does the malware employ to fetch extra payloads onto the system?**  
> `URLDownloadToFileA`  
**Source:** [Tria.ge Sandbox Report](https://tria.ge/210330-gbdr6k9jxx)  
<img width="940" height="235" alt="image" src="https://github.com/user-attachments/assets/a2005e73-ba97-47bc-b898-276db3dc9025" />

---

## 📖 Sources Used

| Source      | Purpose                                      | Link                                                                 |
|-------------|----------------------------------------------|----------------------------------------------------------------------|
| VirusTotal  | File/Hash lookup, domains, registrars, IOCs  | [VirusTotal](https://www.virustotal.com)                             |
| Malpedia    | Threat actor & malware family intelligence   | [Malpedia - IcedID](https://malpedia.caad.fkie.fraunhofer.de/details/win.icedid) |
| Tria.ge     | Dynamic analysis & API function calls        | [Tria.ge Report](https://tria.ge/210330-gbdr6k9jxx)                  |

---
