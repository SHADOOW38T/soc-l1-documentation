# 🛡️ SOC L1 Documentation | توثيق SOC L1

<img width="2560" height="1447" alt="Image" src="https://github.com/user-attachments/assets/ecf000c2-33ed-4da7-ae80-bf81757755cc" />

A practical and structured documentation framework for **Security Operations Center (SOC) Level 1 analysts**, focused on alert triage, investigation, evidence collection, incident documentation, and escalation.

إطار عملي ومنظم لتوثيق عمل **محلل مركز العمليات الأمنية (SOC L1)**، يركز على فرز التنبيهات، التحقيق، جمع الأدلة، توثيق الحوادث، والتصعيد.

---

## 📌 Repository Overview | نظرة عامة

This repository demonstrates a structured approach to common SOC L1 activities.

يستعرض هذا المستودع منهجية منظمة لأهم مهام SOC L1.

- 🔎 **Alert Triage** — فرز وتحليل التنبيهات
- 🕵️ **Security Event Investigation** — التحقيق في الأحداث الأمنية
- 📝 **Incident Documentation** — توثيق الحوادث الأمنية
- 🎯 **IOC & IOA Analysis** — تحليل مؤشرات الاختراق والهجوم
- 🗺️ **MITRE ATT&CK Mapping** — ربط الأنشطة بتقنيات MITRE ATT&CK
- 🚨 **Incident Escalation** — تصعيد الحوادث عند الحاجة
- ✅ **Alert Closure** — إغلاق التنبيهات وتوثيق النتيجة
- 📋 **Investigation Checklists** — قوائم التحقق للتحقيقات

---

# 🔄 SOC L1 Investigation Process | مراحل التحقيق

The standard SOC L1 workflow used in this repository:

منهجية التحقيق الأساسية المستخدمة في هذا المستودع:

### 1️⃣ Alert Received | استلام التنبيه

Receive and review the security alert.

استلام التنبيه الأمني ومراجعته.

### 2️⃣ Initial Triage | الفرز الأولي

Review the alert and understand its basic context.

مراجعة التنبيه وفهم السياق الأساسي له.

### 3️⃣ Validate the Alert | التحقق من التنبيه

Determine whether the alert is relevant and requires investigation.

التأكد من أن التنبيه حقيقي ويحتاج إلى تحقيق.

### 4️⃣ Investigate the Activity | التحقيق في النشاط

Analyze the related user, host, process, IP address, timestamp, and other available information.

تحليل المستخدم والجهاز والعملية وعنوان IP والوقت وغيرها من المعلومات المتاحة.

### 5️⃣ Collect Evidence | جمع الأدلة

Collect relevant logs, events, screenshots, hashes, IPs, domains, and other evidence.

جمع السجلات والأحداث ولقطات الشاشة والـ Hashes وعناوين IP والنطاقات وغيرها من الأدلة.

### 6️⃣ Identify IOCs / IOAs | تحديد المؤشرات

Identify **Indicators of Compromise (IOCs)** and **Indicators of Attack (IOAs)**.

تحديد **مؤشرات الاختراق (IOC)** و**مؤشرات الهجوم (IOA)**.

### 7️⃣ Determine Severity | تحديد مستوى الخطورة

Assess the potential impact and determine the appropriate severity.

تقييم التأثير المحتمل وتحديد مستوى الخطورة المناسب.

### 8️⃣ Respond or Recommend Action | الاستجابة أو التوصية

Take the appropriate action within the SOC L1 role or recommend the next step.

اتخاذ الإجراء المناسب ضمن صلاحيات SOC L1 أو التوصية بالخطوة التالية.

### 9️⃣ Escalate if Required | التصعيد عند الحاجة

Escalate the incident to SOC L2, Incident Response, or the appropriate team when required.

تصعيد الحادث إلى SOC L2 أو فريق الاستجابة للحوادث أو الفريق المختص عند الحاجة.

### 🔟 Document and Close | التوثيق والإغلاق

Document the investigation, final decision, actions taken, and close the alert when appropriate.

توثيق التحقيق والقرار النهائي والإجراءات المتخذة ثم إغلاق التنبيه عند الحاجة.

---

# 📝 Documentation Standards | معايير التوثيق

Every investigation should clearly answer these questions.

يجب أن يجيب كل تحقيق بشكل واضح عن الأسئلة التالية:

| English | العربية |
|---|---|
| **What happened?** | ماذا حدث؟ |
| **When did it happen?** | متى حدث؟ |
| **Where did it happen?** | أين حدث؟ |
| **Who was involved?** | من المستخدم أو الجهاز المتأثر؟ |
| **How was it detected?** | كيف تم اكتشافه؟ |
| **What evidence was found?** | ما الأدلة التي تم العثور عليها؟ |
| **True Positive or False Positive?** | هل هو True Positive أم False Positive؟ |
| **What action was taken?** | ما الإجراء الذي تم اتخاذه؟ |
| **Does it require escalation?** | هل يحتاج إلى تصعيد؟ |

---

# 📄 Templates | القوالب

## SOC L1 Incident Report Template

A ready-to-use incident and alert triage report containing sections for:

نموذج جاهز لتوثيق الحوادث وفرز التنبيهات ويحتوي على:

- **Incident Summary** — ملخص الحادث
- **Evidence & Screenshots** — الأدلة ولقطات الشاشة
- **IOC Analysis** — تحليل مؤشرات الاختراق
- **MITRE ATT&CK Mapping** — ربط MITRE ATT&CK
- **Actions Taken** — الإجراءات المتخذة
- **Escalation** — التصعيد
- **Final Disposition** — القرار النهائي

📄 **[Download SOC L1 Incident Report Template](https://github.com/user-attachments/files/32688836/SOC_L1_Incident_Report_Template.docx)**

---

# 🛠️ Tools | الأدوات

Examples of tools commonly used during SOC investigations.

أمثلة على الأدوات المستخدمة أثناء التحقيقات الأمنية:

- **Wazuh** — SIEM / Security Monitoring
- **Windows Event Logs** — تحليل أحداث Windows
- **Sysmon** — Endpoint Event Monitoring
- **VirusTotal** — File, Hash, IP & Domain Analysis
- **AbuseIPDB** — IP Reputation Analysis
- **MITRE ATT&CK** — Adversary Tactics & Techniques
- **Threat Intelligence Platforms** — استخبارات التهديدات

---

# 🎯 Purpose | الهدف

The purpose of this repository is to demonstrate practical **SOC L1 investigation, alert triage, analysis, and documentation skills** through structured examples, checklists, and repeatable procedures.

الهدف من هذا المستودع هو استعراض المهارات العملية في **SOC L1**، مثل فرز التنبيهات والتحقيق والتحليل والتوثيق، من خلال أمثلة وقوائم تحقق وإجراءات قابلة للتكرار.

---

# 🧠 SOC L1 Investigation Mindset | عقلية محلل SOC L1

During an investigation, always ask yourself:

أثناء التحقيق، اسأل نفسك دائمًا:

### 👤 Who? | من؟

**Who is generating the activity?**

من يقوم بالنشاط أو المحاولات؟

---

### ❓ What? | ماذا؟

**What activity is occurring?**

ما النشاط الذي يحدث؟

---

### 📍 Where? | أين؟

**Which endpoint, account, or system is involved?**

ما الجهاز أو الحساب أو النظام المتأثر؟

---

### 🕐 When? | متى؟

**When did the activity begin and end?**

متى بدأ النشاط ومتى انتهى؟

---

### 📊 How Much? | إلى أي مدى؟

**How extensive or frequent is the activity?**

ما مدى انتشار النشاط أو تكراره؟

---

### 🔎 Why? | لماذا؟

**Why might this activity be occurring?**

ما السبب المحتمل لحدوث هذا النشاط؟

---

# 🔐 Core SOC L1 Principle | المبدأ الأساسي

> **Do not just close alerts. Investigate, validate, document, and make decisions based on evidence.**

> **لا تكتفِ بإغلاق التنبيهات؛ قم بالتحقيق والتحقق والتوثيق واتخاذ القرارات بناءً على الأدلة.**

---

## 🚀 Repository Goal | هدف المستودع

This repository is continuously updated with practical SOC L1 documentation, investigation procedures, and examples.

سيتم تحديث هذا المستودع باستمرار بإضافة توثيقات وإجراءات وأمثلة عملية خاصة بـ SOC L1.
