# Scenario: Password Reset

## 📝 Issue
User **Test User One** reported being unable to log in to Microsoft 365 services.  

## 🔧 Action Taken
- Accessed Microsoft Entra ID (Azure AD) Admin Center.  
- Reset user password and generated temporary credentials.  
- Verified sign-in flow, user prompted to set new password at first login.  

## ✅ Resolution
Password successfully reset. User was able to log in and update credentials.  

---

## 📂 Documentation

### Azure AD (Microsoft Entra ID)
- ![Reset Password Screen](./images/password-reset/change_pw.png)  
- ![Temporary Password Generated](./images/password-reset/temp_pw1.png)  -> ![Temporary Password Generated2](./images/password-reset/temp_pw2.png)

### Jira Service Management
- ![Ticket Created](./images/password-reset/jira/ticket-created.png)  
- ![Ticket In Progress](./images/password-reset/stage2_progress.png)  
- ![Ticket Resolved](./images/password-reset/stage3_ticket_closed.png)  

---

## 🗂 Ticket Log
**Ticket ID:** ITHD-1  
**Summary:** Password reset for Test User One  
**Priority:** Medium  
**Status:** Closed ✅  

**Notes:**  
- User unable to log in due to forgotten/mistyped password.  
- Temporary password issued, user required to change at next login.  

---

## 🎯 Skills Demonstrated
- Identity & Access Management (Azure AD)  
- User account troubleshooting  
- Ticket creation and lifecycle management (Jira)  
- Clear IT documentation practices  

---
