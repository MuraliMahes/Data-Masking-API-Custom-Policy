# Data Masking Policy (MuleSoft Custom Policy)

## Data Masking Policy

The **Data Masking Policy** enhances data security and privacy by masking sensitive information in API response payloads. This ensures that confidential data is not exposed to client applications.

### 🔐 Key Features

- Protects sensitive fields such as:
  - SSN
  - Address
  - Payroll
  - Other confidential data

- Masks values of defined fields in the **response payload**

- Ensures sensitive information is not exposed to downstream consumers

---

### 📦 Supported Payload Formats

This custom policy supports masking for APIs returning responses in the following formats:

- XML
- JSON
- CSV

---

### ⚙️ Masking Options

The policy provides flexible masking approaches to support different developer needs:

#### ✅ Generic Masking
- Masks field values **globally**
- Applies masking **anywhere and everywhere** in the payload
- Suitable when field presence is not fixed

#### ✅ Path-Based Masking
- Masks field values based on **defined paths or hierarchy**
- Targets specific fields at a **particular payload level**
- Useful for structured and predictable payloads

---

### 🚀 Benefits

- Improves **data privacy and compliance**
- Prevents accidental exposure of sensitive information
- Flexible implementation across various response structures
- Developer-friendly configuration

---
