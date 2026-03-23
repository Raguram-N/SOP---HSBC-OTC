# 📄 OTC Document Review Tool – Sample SOP & prototype

## 🧭 Purpose
This SOP defines the standardized process for reviewing Over-The-Counter (OTC) documents using an automated tool, ensuring accuracy, compliance, and consistency across contract validation workflows.

- Prototype [link](https://raguram-n.github.io/SOP---HSBC-OTC/)
- Flowchart [Link](https://github.com/Raguram-N/OTC-flow-chart/blob/main/README.md)

---

## 📌 Scope
This applies to all team members involved in reviewing OTC agreements such as:

- ISDA (Derivatives Master Agreement)  
- CSA (Credit Support Annex)  
- GMRA (Repurchase Agreement)  
- GMSLA (Securities Lending Agreement)  

---

## ⚙️ Prerequisites

- Access to OTC Review Tool  
- Basic understanding of OTC agreements  
- Assigned document for review  
- Stable internet connection  

---

## 👥 Roles & Responsibilities

| Role              | Responsibility |
|------------------|--------------|
| Analyst          | Upload and review documents |
| QA/UAT Tester    | Validate tool functionality and outputs |
| Compliance Team  | Review flagged risks and provide decisions |
| Tech Team        | Resolve tool defects and system issues |

---

## 🪜 Step-by-Step Procedure

### Step 1: Login
- Access the OTC Review Tool  
- Enter credentials  
- Ensure dashboard loads successfully  

---

### Step 2: Upload Document
- Click **Upload Document**  
- Select OTC agreement file  
- Confirm successful upload  

---

### Step 3: Run Automated Check
- Click **Run Analysis**  
- Tool scans for:
  - Missing clauses  
  - Risk indicators  
  - Non-standard terms  

---

### Step 4: Review Output
- Analyze flagged sections:
  - Termination clauses  
  - Collateral terms  
  - Netting provisions  
- Compare with standard templates  

---

### Step 5: Decision Making
- ✅ No issues → Proceed to finalize  
- ⚠️ Issues found:
  - Perform manual validation  
  - Add comments and observations  

---

### Step 6: Escalation (if required)
- Escalate to Compliance/Legal Team  
- Attach:
  - Screenshots  
  - Tool output  
  - Observations  

---

### Step 7: Finalization
- Mark document as:
  - Approved ✅  
  - Rejected ❌  
- Save review notes  

---

### Step 8: Archive
- Store document in repository  
- Update tracking system  

---

## 🧪 UAT Validation Scenarios

| Test Scenario | Expected Result |
|--------------|----------------|
| Upload valid OTC document | Successfully uploaded |
| Upload invalid/corrupt file | Error message displayed |
| Missing clause in document | Tool flags correctly |
| Incorrect clause tagging | Identified during manual validation |
| Tool crash during analysis | Error logged and reported |
| Duplicate document upload | Warning message displayed |

---

## ✅ Validation Checklist

- [ ] Document uploaded correctly  
- [ ] All clauses scanned  
- [ ] Flags reviewed  
- [ ] Manual validation completed  
- [ ] Final decision recorded  

---

## 🛠️ Error Handling / Troubleshooting

| Issue | Action |
|------|--------|
| Tool not loading | Refresh or contact Tech Team |
| Incorrect flags | Re-run analysis or perform manual validation |
| Upload failure | Verify file format and retry |

---

## 📊 Reporting & Documentation

- Maintain daily logs of reviewed documents  
- Track defects in issue tracking system  
- Share summaries with stakeholders  

---

## 🎓 Training & Knowledge Transfer

- Provide screen recordings for walkthrough  
- Use annotated screenshots for clarity  
- Conduct team training sessions  

---

## 🔁 Version Control

| Version | Date | Updated By | Changes |
|--------|------|-----------|--------|
| 1.0 | DD/MM/YYYY | Your Name | Initial SOP |

---

## ⚠️ Notes

- Follow compliance and regulatory guidelines  
- Do not skip manual validation for critical clauses  
- Ensure data confidentiality and security  

---

## 🚀 Business Impact

This SOP enables:

- ✅ Consistent OTC document review process  
- ✅ Reduced manual errors and operational risk  
- ✅ Faster onboarding for new team members  
- ✅ Improved compliance and audit readiness  
- ✅ Efficient UAT validation for tool enhancements  

---

## 💡 Tech Perspective

- Supports automated clause detection (rule-based / NLP)  
- Enhances contract review efficiency  
- Enables scalable document validation workflows  
