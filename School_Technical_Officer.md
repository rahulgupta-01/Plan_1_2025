# School Technical Officer (STO) in Queensland State Schools

School Technical Officers (STOs) are the backbone of IT support in Queensland state schools, managing daily operations, software, hardware, security, and troubleshooting to keep technology running smoothly for teaching and learning. This document outlines their responsibilities, the systems they handle, and the challenges they face, all while ensuring a reliable digital environment.

---

## 📅 Daily Operations & Responsibilities

STOs are the on-site IT experts, tackling everything from morning checks to ongoing support and maintenance.

- **Proactive Morning Routine**:
  - ✅ Verify servers are operational and backups completed successfully.
  - 🌐 Ensure internet and Wi-Fi connectivity are stable.
  - 🖥️ Prepare IT labs and devices for the day's classes.

- **Support Throughout the Day**:
  - 📞 Respond to help requests via phone, email, or in-person visits.
  - 🚨 Prioritize issues affecting teaching (e.g., printer failures, login problems, smartboard/projector issues).
  - 🔧 Troubleshoot on the spot—fixing teacher laptops (e.g., Wi-Fi issues), student PCs (e.g., login failures), or office email/internet outages.
  - 🎫 **Log and escalate complex issues** through the **Department’s ICT Service Centre** via the **Services Catalogue Online (SCO) ticketing system** or by calling **1800 680 445**.

- **Preventative Maintenance**:
  - 🔄 Update software and apply security patches.
  - 🔋 Reboot and optimize servers for performance.
  - 🧹 Clean hardware (e.g., projector filters, laptop charging carts) to prevent breakdowns.

- **Planning & Coordination**:
  - 📆 Schedule major tasks (e.g., lab upgrades, network changes) during student-free periods.
  - 📞 Escalate complex issues to the **ICT Service Centre (1800 680 445)** or **Regional Systems Technicians (RSTs)** for on-site support.

> **How IT Support Works in Queensland State Schools:**
> - **Services Catalogue Online (SCO):** The official **ticketing system** where staff log IT issues.
> - **ICT Service Centre:** Resolves most technical issues logged via SCO and provides phone support (1800 680 445).
> - **Regional Systems Technicians (RSTs):** On-site support for **network, infrastructure, or major IT failures**.

STOs maintain detailed notes to manage their workload, ensuring no issue is missed. They act as both first-line support and local IT coordinators, communicating with stakeholders to resolve technical challenges efficiently.

---

## 🖥️ Software & Systems Managed by an STO

STOs support a wide range of Department-approved software critical to school operations.

- **OneSchool**:
  - 📚 All-in-one platform for **student data, attendance, reports, finance, and asset tracking**.
  - 🛠️ STOs fix access issues, ensure browser compatibility, and assist with report printing.
  - *Note:* OneSchool is a **centralized school management system** used across Queensland state schools.

- **Managed Operating Environment (MOE)**:
  - 🪟 Standardized **Windows setup (MOE v6)** deployed across school computers.
  - 🛠️ STOs **deploy system images, install software, and apply Group Policies** using tools like **Microsoft Deployment Toolkit (MDT) or Intune**.
  - *Note:* MOE ensures **security, compliance, and uniformity** across all state school IT environments.

- **Office 365**:
  - 📧 Provides **email, OneDrive storage, and Microsoft Teams collaboration**.
  - 🛠️ STOs configure **Outlook, troubleshoot login issues (Azure AD/MFA), and integrate Microsoft apps**.
  - *Note:* Office 365 supports **collaboration and communication** across the school community.

- **QLearn**:
  - 🎓 Digital **learning platform** (**Canvas-based LMS**) with **single sign-on (SSO)** via the Department network.
  - 🛠️ STOs ensure **access, troubleshoot login problems, and support app installations**.
  - *Note:* QLearn is Queensland’s **official online learning platform**, replacing legacy LMS systems.

- **Curriculum Software**:
  - 🎨 Includes **Adobe Creative Cloud, Autodesk CAD, and specialized education software**.
  - 🛠️ STOs deploy and manage these applications via **Microsoft Intune or SCCM**.

- **Microsoft Intune**:
  - 📱 Manages **school-owned and BYO devices (via BYOx Link program)**.
  - 🛠️ STOs enroll devices, push **Wi-Fi profiles, security policies, and software updates**.
  - *Note:* **Zero-touch provisioning and remote troubleshooting** are becoming standard for device management.

- **PaperCut MF**:
  - 🖨️ Manages **printing quotas and follow-me printing**.
  - 🛠️ STOs administer print servers, fix queues, and troubleshoot **device connection issues**.
  - *Note:* PaperCut MF helps schools **monitor and control printing costs**.

- **NAPLAN Online**:
  - 📝 Requires a **lockdown browser** for **secure student testing**.
  - 🛠️ STOs install, update, and troubleshoot **NAPLAN software**.
  - 🚀 Uses **bulk deployment tools (Intune, SCCM, Group Policy)** for automation.
  - 🌐 **Test network readiness** to ensure sufficient bandwidth and that content filtering doesn’t block test sites.
  - *Note:* NAPLAN Online ensures **secure, standardized assessments** across schools.

- **Asset Tracking**:
  - 🏷️ Managed via the OneSchool Asset Register (Agresso-based).
  - 🛠️ STOs update records, log new devices, and handle warranty claims.
  - 📊 **Regular stocktakes** of IT assets for budgeting and compliance.
  - ⏳ **Track warranties** to arrange replacements before devices fail.
  - *Note:* Accurate asset tracking ensures schools maintain an **accurate inventory** of IT resources, supporting **budgeting and compliance**.

---

## 🔧 Hardware Infrastructure & Devices

STOs oversee all hardware, from servers to classroom gadgets, ensuring functionality and reliability.

- **Servers**:
  - 🖥️ Windows servers for Active Directory, file shares, and print services (often virtualized with VMware/Hyper-V).
  - 🛠️ STOs monitor health, apply updates, and manage backups (to drives or cloud).

- **Network Hardware**:
  - 🔌 Switches, routers, and Wi-Fi access points (e.g., Cisco Meraki, Aruba).
  - 🛠️ STOs check connectivity, reboot devices, and perform basic configurations.
  - 🌐 **Basic networking skills** (e.g., setting VLANs, troubleshooting performance issues, understanding subnetting, DHCP, RADIUS, firewall rules).
  - ☁️ Some schools use **cloud-based management** (e.g., Meraki) for remote Wi-Fi monitoring.

- **End-User Devices**:
  - 💻 Includes student PCs, teacher laptops (via Computers for Teachers), iPads, interactive whiteboards, projectors, and printers.
  - 🛠️ STOs configure, update, and repair these devices.

- **Niche Equipment**:
  - 📸 Covers digital cameras, 3D printers, robotics kits, and science loggers.
  - 🛠️ STOs ensure integration and functionality.

- **AV & Networked Systems**:
  - 📢 Manages PA systems, CCTV (on separate networks), and bell controllers.
  - 🛠️ STOs assist with setup and troubleshooting.

STOs unbox and configure new devices, repair or replace faulty ones, and maintain accurate asset records in OneSchool.

---

## 🔒 Network Security & Safety

STOs enforce cybersecurity measures to protect the school’s digital environment.

- **Content Filtering**:
  - 🌐 Uses **Symantec/Broadcom WebFilter** to **block malicious/inappropriate websites**.
  - 🛠️ STOs troubleshoot blocks and report bypass attempts.

- **Antivirus & Firewall**:
  - 🛡️ **Microsoft Defender for Endpoint** protects against malware threats.
  - 🛠️ STOs monitor alerts, isolate infections, and apply patches.

- **User Education**:
  - 📚 Promote safe practices (e.g., strong passwords, phishing awareness).
  - 🛠️ Enforce policies like MFA and password changes.
  - 🧑‍🏫 **Train staff and students on cyber hygiene**:
    - Teach how to **spot phishing emails**.
    - Encourage **not reusing passwords**.
    - Promote **reporting suspicious activity**.
  - 🌍 Support **digital citizenship education** to foster cyber safety awareness among students.

- **Access Controls**:
  - 🔑 Set permissions on servers and OneSchool for appropriate access.
  - 🛠️ Adjust settings for staff roles or exam security.

- **Incident Response**:
  - 🚨 Isolate systems during breaches and report to the Department’s IT security team.
  - 🛠️ Use **Intune to remotely wipe lost or compromised devices**.
  - 🔑 Enforce **multi-factor authentication (MFA)** and access controls.
 
- **Department Policies & Compliance**:
  - 📜 Ensure adherence to MOE policies, cybersecurity standards, and DoE protocols.
  - 🔐 Enforce software licensing and restrict unauthorized applications.

---

## 🛠️ Common Troubleshooting Scenarios

STOs tackle a variety of issues daily, keeping the school operational.

- **Login & Account Issues**:
  - 🔑 Reset passwords or fix profile errors for network/Office 365 access.

- **Printing Problems**:
  - 🖨️ Clear queues, fix Papercut errors, or update drivers during high-demand periods.

- **Classroom Tech Glitches**:
  - 📽️ Resolve projector/whiteboard issues (e.g., cables, bulbs) under time pressure.

- **Network Connectivity Outages**:
  - 🌐 Diagnose and fix local outages:
    - 🔍 **Check switch uplinks** to ensure physical connections are intact.
    - 🔍 **Test VLAN assignments** to confirm devices are on the correct network segments.
    - 🔍 **Verify RADIUS authentication** to resolve login issues tied to network access.
  - 📞 **Coordinate with Regional IT** for larger issues:
    - Request **circuit replacements** when physical lines fail.
    - Escalate **DoE WAN issues** affecting multiple schools or regions.
  - 📢 Report broader outages and keep staff informed.

- **Slow or Sluggish Systems**:
  - 🐢 Investigate server load, malware, or update scheduling conflicts.

- **Software Installation & Compatibility**:
  - 💿 Install approved software and resolve conflicts with MOE standards.

- **Security Incidents**:
  - 🚨 Handle breaches or run virus scans, coordinating with the ICT Service Centre as needed.

STOs log issues and share knowledge to prevent repeats, maintaining composure amid urgent demands.

---

## 🚧 Challenges & Best Practices in the Role

STOs face unique challenges but adopt strategies to excel.

- **Managing Workload**:
  - 🎫 Use **Services Catalogue Online (SCO) ticketing system** to track IT tasks and prioritize urgent issues.
  - 🔄 Schedule **maintenance tasks efficiently** using tools like Intune.

- **Budget Constraints**:
  - 💰 Extend hardware life through **repairs and proper lifecycle management**.
  - 📊 Ensure accurate **asset tracking for budgeting purposes** via OneSchool.

- **Continuous Learning**:
  - 📚 Complete trainings (e.g., Orange Card) and network with peers.
  - 🤝 Stay updated on tools like QLearn or Intune.

- **Documentation**:
  - 📝 Record network setups and create staff guides to reduce support calls.
  - 📘 Ensure continuity for future technicians.

- **Communication & Training**:
  - 🗣️ Run PD sessions and mentor student tech teams.
  - 🤝 Build collaboration to enhance digital literacy.

- **Improving Digital Learning**:
  - 💡 Recommend tech enhancements (e.g., robotics, VR) and plan strategically.
  - 📈 Audit equipment for future-proofing.

- **Security Challenges**:
  - 🔐 Maintain robust defences (e.g., backups, segmentation).
  - 🛡️ Test restores and prepare for exams like NAPLAN.

---

STOs are vital to Queensland state schools, acting as troubleshooters, administrators, and educators. By managing operations, supporting systems, and overcoming challenges with best practices, they ensure a stable, secure IT environment that empowers teachers and students to thrive in a digital world.
