# School Technical Officer (STO) in Queensland State Schools

School Technical Officers (STOs) are the backbone of IT support in Queensland state schools. They manage daily operations, software, hardware, security, and troubleshooting to keep technology running smoothly for teaching and learning. This document outlines their responsibilities, the systems they handle, and the challenges they face—all while ensuring a secure and reliable digital environment.

> **Note:** Some legacy systems (e.g., MOE6, tape-based backups) are still in use but are being phased out in favor of modern solutions (e.g., MOE7, cloud/disk-based backups, OneDrive). This guide reflects the current landscape (2025) and upcoming transitions.

---

## 📅 Daily Operations & Responsibilities

STOs are the on-site IT experts, tackling everything from morning checks to ongoing support and maintenance.

- **Proactive Morning Routine**:
  - ✅ Verify that servers, network switches, and Wi-Fi access points are operational.
  - 🔄 Confirm that backups have completed successfully (note: legacy tape backups are being replaced by disk/cloud solutions).
  - 🌐 Ensure internet and Wi-Fi connectivity are stable.
  - 🖥️ Prepare IT labs, interactive displays, and devices for the day's classes.

- **Support Throughout the Day**:
  - 📞 Respond to help requests via phone, email, or in-person visits.
  - 🚨 Prioritize issues affecting teaching (e.g., printer failures, login problems, smartboard/projector glitches).
  - 🔧 Troubleshoot on the spot—fix teacher laptops (e.g., Wi-Fi issues), student PCs (e.g., login failures), or office email/internet outages.
  - 🎫 **Log and escalate complex issues** through the **Department’s ICT Service Centre** via the **Services Catalogue Online (SCO) ticketing system** or by calling **1800 680 445**.

- **Preventative Maintenance**:
  - 🔄 Update software and apply security patches.
  - 🔋 Reboot and optimize servers for performance.
  - 🧹 Clean hardware (e.g., projector filters, laptop charging carts) to prevent breakdowns.

- **Planning & Coordination**:
  - 📆 Schedule major tasks (e.g., lab upgrades, network changes) during student-free periods.
  - 📞 Escalate complex issues to the **ICT Service Centre (1800 680 445)** or **Regional Systems Technicians (RSTs)** for on-site support.

> **How IT Support Works in Queensland State Schools:**
> - **Services Catalogue Online (SCO):** The official ticketing system where staff log IT issues.
> - **ICT Service Centre:** Resolves most technical issues logged via SCO and provides phone support (1800 680 445).
> - **Regional Systems Technicians (RSTs):** Provide on-site support for network, infrastructure, or major IT failures.

STOs maintain detailed notes and documentation to ensure no issue is missed. They act as both first-line support and local IT coordinators, effectively communicating with stakeholders to resolve technical challenges.

---

## 🖥️ Software & Systems Managed by an STO

STOs support a wide range of Department-approved software critical to school operations.

- **OneSchool**:
  - 📚 All-in-one platform for student data, attendance, reports, finance, and asset tracking.
  - 🛠️ Troubleshoot access issues, ensure browser compatibility, and assist with report printing.
  - *Note:* OneSchool is the centralized school management system used across Queensland state schools.

- **Managed Operating Environment (MOE)**:
  - 🪟 **MOE6 (Windows 10) is still in use**, but **MOE7 (Windows 11) is being introduced** and will eventually replace MOE6.
  - 🛠️ Deploy system images, install software, and apply Group Policies using tools like Microsoft Deployment Toolkit (MDT) or Intune.
  - *Note:* MOE ensures security, compliance, and uniformity across all state school IT environments.

- **Office 365**:
  - 📧 Provides email, OneDrive storage, and Microsoft Teams collaboration.
  - 🛠️ Configure Outlook, troubleshoot login issues (Azure AD/MFA), and integrate Microsoft apps.
  - *Note:* Office 365 supports school-wide collaboration and communication. Cloud storage (OneDrive, SharePoint) is replacing on-prem file servers.

- **QLearn**:
  - 🎓 Digital learning platform (Canvas-based LMS) with single sign-on (SSO) via the Department network.
  - 🛠️ Ensure access, troubleshoot login problems, and support app installations.
  - *Note:* QLearn is Queensland’s official online learning platform, replacing legacy LMS systems.

- **Curriculum Software**:
  - 🎨 Includes Adobe Creative Cloud, Autodesk CAD, and specialized education software.
  - 🛠️ Deploy and manage these applications via Microsoft Intune or SCCM.

- **Microsoft Intune**:
  - 📱 Manages school-owned and BYO devices (via the BYOx Link program).
  - 🛠️ Enroll devices, push Wi-Fi profiles, security policies, and software updates.
  - *Note:* Zero-touch provisioning and remote troubleshooting are becoming standard for device management.

- **PaperCut MF**:
  - 🖨️ Manages printing quotas and follow-me printing.
  - 🛠️ Administer print servers, fix queues, and troubleshoot device connection issues.
  - *Note:* PaperCut MF helps schools monitor and control printing costs.

- **NAPLAN Online**:
  - 📝 Requires a lockdown browser for secure student testing.
  - 🛠️ Install, update, and troubleshoot NAPLAN software.
  - 🚀 Utilize bulk deployment tools (Intune, SCCM, Group Policy) for automation.
  - 🌐 Test network readiness to ensure sufficient bandwidth and that content filtering does not block test sites.
  - *Note:* NAPLAN Online ensures secure, standardized assessments across schools.

- **Asset Tracking**:
  - 🏷️ Managed via the OneSchool Asset Register (Agresso-based).
  - 🛠️ Update records, log new devices, and handle warranty claims.
  - 📊 Regular stocktakes of IT assets for budgeting and compliance.
  - ⏳ Track warranties to arrange replacements before devices fail.
  - *Note:* Accurate asset tracking ensures an up-to-date inventory of IT resources for budgeting and compliance.

---

## 🔧 Hardware Infrastructure & Devices

STOs oversee all hardware—from servers to classroom gadgets—ensuring functionality and reliability.

- **Servers**:
  - 🖥️ Windows servers for Active Directory, file shares, and print services (often virtualized with VMware/Hyper-V).
  - 🛠️ Monitor server health, apply updates, and manage backups (transitioning from tape to disk/cloud-based systems).

- **Network Hardware**:
  - 🔌 Switches, routers, and Wi-Fi access points (e.g., Cisco Meraki, Aruba).
  - 🛠️ Check connectivity, reboot devices, and perform basic configurations.
  - 🌐 **Basic networking skills:** setting VLANs, troubleshooting performance, understanding subnetting, DHCP, RADIUS, and firewall rules.
  - ☁️ Some schools use cloud-based management (e.g., Meraki) for remote Wi-Fi monitoring.

- **End-User Devices**:
  - 💻 Includes student PCs, teacher laptops (via Computers for Teachers), iPads, interactive whiteboards, projectors, and printers.
  - 🛠️ Configure, update, and repair these devices.

- **Niche Equipment**:
  - 📸 Covers digital cameras, 3D printers, robotics kits, and science loggers.
  - 🛠️ Ensure integration and functionality of these specialized devices.

- **AV & Networked Systems**:
  - 📢 Manages PA systems, CCTV (on separate networks), and bell controllers.
  - 🛠️ Assist with setup and troubleshooting of audiovisual systems.

STOs unbox and configure new devices, repair or replace faulty equipment, and maintain accurate asset records in OneSchool.

---

## 🔒 Network Security & Safety

STOs enforce cybersecurity measures to protect the school’s digital environment.

- **Content Filtering**:
  - 🌐 Use Symantec/Broadcom WebFilter to block malicious/inappropriate websites.
  - 🛠️ Troubleshoot blocked sites and report bypass attempts.

- **Antivirus & Firewall**:
  - 🛡️ **Microsoft Defender for Endpoint** protects against malware threats.
  - 🛠️ Monitor alerts, isolate infections, and apply patches.

- **User Education**:
  - 📚 Promote safe practices (strong passwords, phishing awareness).
  - 🛠️ Enforce policies like multi-factor authentication (MFA) and updated password guidelines.
  - 🧑‍🏫 **Train staff and students on cyber hygiene**:
    - Spot phishing emails.
    - Avoid reusing passwords.
    - Report suspicious activity.
  - 🌍 Support digital citizenship education to foster cyber safety.

- **Access Controls**:
  - 🔑 Set permissions on servers and OneSchool for appropriate access.
  - 🛠️ Adjust settings based on staff roles or exam security needs.

- **Incident Response**:
  - 🚨 Isolate systems during breaches and report to the Department’s IT security team.
  - 🛠️ Use Intune to remotely wipe lost or compromised devices.
  - 🔑 Enforce MFA and strict access controls.

- **Department Policies & Compliance**:
  - 📜 Adhere to MOE policies, cybersecurity standards, and DoE protocols.
  - 🔐 Enforce software licensing and restrict unauthorized applications.

---

## 🛠️ Common Troubleshooting Scenarios

STOs tackle a variety of issues daily, keeping the school operational. Below is a table summarizing common problems and their solutions:

| Problem                          | Solution                                                                 |
|----------------------------------|--------------------------------------------------------------------------|
| **Login & Account Issues**       | Reset passwords or fix profile errors for network/Office 365 access.     |
| **Printing Problems**            | Clear queues, fix PaperCut errors, or update drivers during peak usage.  |
| **Classroom Tech Glitches**      | Resolve projector/whiteboard issues (e.g., cables, bulbs) under time pressure. |
| **Network Connectivity Outages** | - Check switch uplinks to ensure physical connections are intact. <br>- Test VLAN assignments to confirm correct network segments. <br>- Verify RADIUS authentication for network access issues. <br>- Coordinate with Regional IT for larger issues (e.g., circuit replacements, WAN outages). <br>- Report broader outages and keep staff informed. |
| **Slow or Sluggish Systems**     | Investigate server load, malware issues, or update scheduling conflicts. |
| **Software Installation & Compatibility** | Install approved software and resolve conflicts with MOE standards. |
| **Security Incidents**           | Handle breaches or run virus scans, coordinating with the ICT Service Centre as needed. |

STOs log issues and share knowledge to prevent repeat problems, ensuring smooth daily operations.

---

## 🚧 Challenges & Best Practices

- **Managing Workload**:
  - 🎫 Use the Services Catalogue Online (SCO) ticketing system to track tasks and prioritize urgent issues.
  - 🔄 Schedule maintenance tasks efficiently using tools like Intune.

- **Budget Constraints**:
  - 💰 Extend hardware life through repairs and proper lifecycle management.
  - 📊 Ensure accurate asset tracking via OneSchool for budgeting purposes.

- **Continuous Learning**:
  - 📚 Complete training sessions (e.g., Orange Card) and network with peers.
  - 🤝 Stay updated on evolving tools like QLearn, Intune, and cloud-based device management.

- **Documentation**:
  - 📝 Record network setups and create staff guides to reduce support calls.
  - 📘 Maintain clear documentation for continuity when transitioning roles.

- **Communication & Training**:
  - 🗣️ Run professional development (PD) sessions and mentor student tech teams.
  - 🤝 Collaborate to enhance digital literacy across the school.

- **Improving Digital Learning**:
  - 💡 Recommend tech enhancements (e.g., robotics, VR) and plan strategically.
  - 📈 Audit equipment regularly for future-proofing and sustainability.

- **Security Challenges**:
  - 🔐 Maintain robust defenses (backups, segmentation) and test system restores.
  - 🛡️ Prepare for high-stakes events like NAPLAN by ensuring security and reliability.

---

STOs are vital to Queensland state schools, acting as troubleshooters, administrators, and educators. By managing operations, supporting systems, and overcoming challenges with best practices, they ensure a stable, secure IT environment that empowers teachers and students to thrive in a digital world.
