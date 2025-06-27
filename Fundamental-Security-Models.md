# CORE SECURITY MODELS

### ✅ CIA Triad

**Confidentiality** – Prevent unauthorized access to data  
**Integrity** – Ensure data is accurate and unaltered  
**Availability** – Keep systems and data accessible when needed

> 🧠 I understand CIA as the base checkpoint when looking at any security measure. If something breaks one of these three, it’s a security risk.

---------------------------------------------------------------------------------------------------------------------------------------------------------

### ❌ DAD Triad

**Disclosure** – Exposure of data to unauthorized users  
**Alteration** – Unauthorized changes made to data  
**Denial** – Blocking users from accessing systems or info

> 🧠 DAD is basically the attacker's perspective on breaking CIA. I use it to map threat examples to specific CIA failures.

--------------------------------------------------------------------------------------------------------------------------------------------------------

### 🔷 Parkerian Hexad

Extends the CIA model with three more elements:

- **Possession/Control** – Who physically or digitally holds the asset  
- **Authenticity** – Verifies that the data or source is genuine  
- **Utility** – Whether the data is actually usable in its current form

> 🧠 This helped me think beyond the basic three — for example, encrypted data might be confidential but useless without the decryption key (breaks Utility).

--------------------------------------------------------------------------------------------------------------------------------------------------------

### 🔒 Bell-LaPadula Model (focus: confidentiality)

- Used in systems that handle classified data  
- **"No read up, no write down"** — users can't read higher-level info or leak info to lower levels

> 🧠 Makes sense in environments like defense or military, where secrecy matters more than anything else.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

### 🛡️ Biba Model (focus: integrity)

- Opposite of Bell-LaPadula  
- **"No write up, no read down"** — low-trust users can't modify high-trust data

> 🧠 I think of this in contexts like medical records or finance, where tampering is a bigger risk than secrecy.

----------------------------------------------------------------------------------------------------------------------------------------------------------

### 📚 Clark-Wilson Model (focus: process integrity)

- Based on **well-formed transactions** and **separation of duties**  
- Data can only be modified through approved programs

> 🧠 This reminds me of systems like banking apps where only specific workflows can trigger changes — not just direct DB edits.

-----------------------------------------------------------------------------------------------------------------------------------------------------------

### 🧱 Brewer-Nash Model (Coca-Cola Model)

- Dynamic access control based on user’s history  
- Prevents conflict of interest (e.g. can’t access competing clients’ data)

> 🧠 Useful where consultants or law firms serve competing parties — it adjusts access based on real-time usage patterns.

