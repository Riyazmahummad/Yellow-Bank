# 🏦 Riyaz Yellow Bank GenAI Banking Agent

A GenAI-powered Banking Virtual Assistant built using Yellow.ai.  
The agent securely authenticates users and displays their loan details using dynamic rich media cards.

## 🚀 Features

- Intent recognition for loan-related queries  
- Secure authentication (Phone Number + DOB + OTP)  
- Multi-step API workflows  
- Token optimization using projection (middle-man instruction)  
- Dynamic Rich Media Cards for loan selection  
- Loan details rendering  
- CSAT feedback agent  
- Edge case & failure handling  
- English-only language enforcement  

---

## 🛠 Tech Stack

- **Yellow.ai** – Conversational AI platform  
- **Beeceptor** – Mock APIs  
- **GenAI Prompt Engineering**

---

## 🔄 High-Level Flow

User  
→ Intent Detection  
→ Phone + DOB Collection  
→ OTP Verification  
→ Loan Accounts (DRM Cards)  
→ Loan Details (DRM)  
→ CSAT Feedback

---

## Project Structure

- `system-prompts/` – System instructions for the GenAI agent  
- `workflows/` – Workflow logic definitions (OTP, Loan Accounts, Loan Details)  
- `mock-apis/` – Sample API responses (Beeceptor)  
- `architecture/` – System architecture description  
- `docs/` – Assignment explanation and design notes  

---

## 🧪 Mock APIs

APIs are mocked using Beeceptor for:
- OTP generation  
- Loan account list  
- Loan details  

---

## 👤 Author

**Riyaz Mahummad**   

