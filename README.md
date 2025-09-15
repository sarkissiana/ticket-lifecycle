# osTicket - Lifecycle Examples  


This repository demonstrates the **lifecycle of a ticket in osTicket**, from creation to resolution, showcasing how help desk staff and users interact with the system! 




---

## 🖥️ Environments and Technologies Used  
- **Microsoft Azure** (Virtual Machines / Compute)  
- **Remote Desktop (RDP)**  
- **Internet Information Services (IIS)**  
- **MySQL / HeidiSQL**  
- **osTicket (User & Admin Panels)**  

---

## 💻 Operating Systems Used  
- **Windows 10 (21H2)**  

---

## 📋 Ticket Lifecycle Stages  

1. **Ticket Creation** (by a user or agent).  
2. **Ticket Assignment** (auto/manual assignment to department/team/agent).
3. **Observe the ticket’s properties & SLA Monitoring** (ensures response/resolution meets service level).
4. **Ticket Resolution** (agent closes the ticket).  
5. **Post-Resolution Review** (user can review or re-open if needed).  

---

## ⚙️ Lifecycle Example Walkthrough  

### 1. Ticket Creation  
A user submits a **“Online Banking Outage”** via the osTicket User Portal.  
- Create a new ticket:  
  - *Issue:* “Entire mobile/online banking system is down.”  

📸 
<img width="1558" height="861" alt="Screenshot 2025-09-15 183815" src="https://github.com/user-attachments/assets/eb4206a7-1fc6-4e87-84d7-a295580a2ac9" />



---

### 2. Ticket Assignment  
osTicket automatically routes the ticket to the **IT Support Department**.  
The ticket is assigned to an **agent** (e.g., John Doe).  

📸 
<img width="1569" height="907" alt="Screenshot 2025-09-15 183920" src="https://github.com/user-attachments/assets/7f155d0e-9e70-41d2-952b-fdccd78b4261" />


---

### 3. Observe the ticket’s properties & SLA Monitoring
The ticket is tracked under an SLA (e.g., must be resolved within 8 business hours).  
SLA countdown is visible in the admin panel. 
- Observe the ticket’s properties:  
  - Priority  
  - Department  
  - SLA  
  - Assigned To  

- Set properties:  
  - SLA: **Sev-A (1 hour, 24/7)**  
  - Department: **Online Banking**  

📸   
<img width="1919" height="1040" alt="Screenshot 2025-09-15 185435" src="https://github.com/user-attachments/assets/46b957df-00cd-4f74-b46b-0cc19ea7960b" />

---

### 4. Ticket Resolution  
Agent resolves the issue and marks the ticket as **Resolved/Closed**.  

📸 
<img width="959" height="192" alt="Screenshot 2025-09-15 190647" src="https://github.com/user-attachments/assets/49aefbee-6d2a-42aa-9958-f79d04a1cd15" />



---

### 5. Post-Resolution Review  
- User confirms the issue is resolved.  
- Ticket can be **reopened** if the problem persists.  

📸 **Screenshot:**  
![Post-Resolution](images/step7_post_resolution.png)  

---

## 📂 Repository Structure  

