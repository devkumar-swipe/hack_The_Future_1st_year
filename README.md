# **Hack the Future 1st year : A Hands-On Exercise**

This project provides a structured approach to investigating a suspicious email and its attachment. The goal is to identify phishing elements and uncover hidden metadata or malicious content. This exercise is designed for cybersecurity awareness and practical analysis training.

---

## **Overview**

In this exercise, you will:
1. Analyze the email header and content for signs of phishing.
2. Examine an attached file for hidden metadata or malicious elements.
3. Identify key red flags that indicate a phishing attempt.

---

## **Tasks**

### **Task 1: Analyzing the Email Header**

The first step is to carefully examine the sender’s email address. Phishing emails often:
- **Spoof legitimate email addresses**.
- Use **slightly altered domains** to impersonate trusted entities.

#### **Steps**:
- Verify whether the domain in the sender’s email is legitimate or suspicious using tools like WHOIS or DNS lookups.

---

### **Task 2: Inspecting the Email Content**

Phishing emails are designed to deceive and manipulate. Carefully analyze the following:

1. **Language and Tone**:
   - Look for urgency tactics in the email body, such as:
     - “Immediate approval”
     - “Process immediately”
   - These phrases aim to pressure recipients into quick, thoughtless action.

2. **Links or Buttons**:
   - Phishing emails often include links or buttons like:
     - "Approved"
     - "This is approved"
     - "Yes, approved"
   - **Inspect these links without clicking them.** Hover over the buttons to view the destination URLs. Use tools like `curl` or `wget` to safely check their targets.

---

### **Task 3: Examining the Attachment**

The email includes an attachment named `payment_invoice.pdf`. Attachments in phishing emails can:
- Contain **malicious payloads**.
- Hide information in metadata or embedded scripts.

---

### **Thank you**
-team cyber swipe

