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
3. **Agent Response** (communication with the user begins).  
4. **Ticket Status Updates** (open → in progress → resolved).  
5. **SLA Monitoring** (ensures response/resolution meets service level).  
6. **Ticket Resolution** (agent closes the ticket).  
7. **Post-Resolution Review** (user can review or re-open if needed).  

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

### 3. Agent Response  
The assigned agent replies to the ticket, asking for additional details.  
The user receives an email notification.  

📸 **Screenshot:**  
![Agent Response](images/step3_agent_response.png)  

---

### 4. Ticket Status Updates  
- Ticket moves from **Open → In Progress**.  
- Agent documents troubleshooting steps.  

📸 **Screenshot:**  
![Ticket Progress](images/step4_ticket_progress.png)  

---

### 5. SLA Monitoring  
The ticket is tracked under an SLA (e.g., must be resolved within 8 business hours).  
SLA countdown is visible in the admin panel.  

📸 **Screenshot:**  
![SLA Monitoring](images/step5_sla.png)  

---

### 6. Ticket Resolution  
Agent resolves the issue, resets the user’s password, and marks the ticket as **Resolved/Closed**.  

📸 **Screenshot:**  
![Ticket Resolution](images/step6_ticket_resolution.png)  

---

### 7. Post-Resolution Review  
- User confirms the issue is resolved.  
- Ticket can be **reopened** if the problem persists.  

📸 **Screenshot:**  
![Post-Resolution](images/step7_post_resolution.png)  

---

## 📂 Repository Structure  

