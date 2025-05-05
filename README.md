# 🚀 Ansible Network Automation Challenges

Welcome to my **Ansible Challenges Repository**!  
This project showcases hands-on network automation using **Ansible** on Cisco IOS devices, built in **GNS3**.

🔧 Each challenge demonstrates a practical use case, from basic device connectivity to advanced automation patterns like error handling and compliance checks.

---

## 🟢 Beginner Challenges

1. **Basic Connectivity Check**
   - Playbook to test Ansible reachability using `ansible.builtin.ping`.

2. **Gather and Save Facts**
   - Collects device facts (hostname, interfaces, OS, uptime) and saves them to a file.

3. **Configure Hostnames**
   - Dynamically sets hostnames based on inventory names.

---

## 🟡 Intermediate Challenges

4. **VLAN Automation**
   - Creates VLANs 10, 20, and 30 with idempotent playbooks.

5. **Backup Device Configurations**
   - Saves running configurations locally on the control node.

6. **Deploy NTP Settings**
   - Pushes NTP server configuration and verifies status.

---

## 🔴 Advanced Challenges

7. **Dynamic Inventory from GNS3**
   - Builds dynamic inventory scripts to reflect the live topology.

8. **Rolling Update with Confirmation**
   - Batch updates device configs with human approval steps.

9. **Compliance Checker**
   - Verifies hostname standards, SSH, and SNMP settings. Reports non-compliant devices.

10. **Error Handling with Rescue/Always**
    - Uses `block`, `rescue`, and `always` to roll back on configuration errors.

---

## 📁 Repo Structure

Each folder includes:
- ✅ Ansible playbook
- 📸 Example output (with comments)
- 📝 Notes or verification commands used

---

## 💡 Why I Built This

To reinforce real-world automation skills and prepare for infrastructure-as-code roles. It’s also part of my learning path toward advanced Ansible, NetDevOps, and DevNet certifications.

---

Feel free to fork, adapt, or suggest improvements.  
Happy Automating! 🤖📡
