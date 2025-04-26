# Ansible Challenges Repository

Welcome to my repository of Ansible challenges! Here, I have documented and resolved various challenges related to network automation and configuration management. These challenges are grouped into three categories: Beginner, Intermediate, and Advanced.

---

## 🟢 Beginner Challenges

### 1. Basic Connectivity Check
- **Objective:** Create a playbook that:
  - Pings all devices in your inventory.
  - Uses the `ansible.builtin.ping` module.

### 2. Gather and Save Facts
- **Objective:** Create a playbook that:
  - Gathers facts from all devices.
  - Writes a summary (`hostname`, `interfaces`, `OS`, `uptime`) to a file.

### 3. Configure Hostnames
- **Objective:** Push a hostname config to all your routers/switches.
  - Make the hostname dynamic using the inventory name.

---

## 🟡 Intermediate Challenges

### 4. VLAN Automation
- **Objective:** On your switches:
  - Create VLANs 10, 20, and 30.
  - Assign names to each VLAN.
  - Ensure the playbook is idempotent.

### 5. Backup Device Configurations
- **Objective:** Create a playbook to SSH into devices and save the running config to a local file on your Ansible control node.

### 6. Deploy NTP Settings
- **Objective:** Push NTP server settings to all routers and switches.
  - Verify with a command that NTP is working.

---

## 🔴 Advanced Challenges

### 7. Dynamic Inventory from GNS3
- **Objective:** Instead of a static hosts file, generate inventory dynamically based on GNS3 topology using a script or API.

### 8. Rolling Update with Confirmation
- **Objective:** Create a playbook that updates device configs in batches.
  - After each batch, pause and wait for user confirmation to proceed.

### 9. Compliance Checker
- **Objective:** Write a playbook that checks if all routers have:
  - A specific hostname format.
  - SSH enabled.
  - Specific SNMP community strings.
  - Report non-compliant devices.

### 10. Error Handling with Rescue/Always
- **Objective:** Simulate failure (e.g., bad config on a device).
  - Use `block`, `rescue`, and `always` to handle the error gracefully and restore the last known good config.

---

Feel free to explore the individual challenge folders to see how each of these problems was solved. Each challenge comes with a detailed explanation and the Ansible playbook used to solve it.

Happy automating! 🚀
