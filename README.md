# DAL NETWORK SNIFFER

**Author:** HuzaifaDal  
**License:** MIT  
**Type:** Lightweight Bash-based Network Sniffer

---

## 📌 Description

**DAL NETWORK SNIFFER** is a simple and lightweight Bash script built using `tcpdump` to capture live network traffic from a specified network interface. It is designed for quick packet capture operations and security testing purposes.

---

## ⚙️ Features

- Capture packets on any interface.
- Save captured traffic to `.pcap` file.
- Lightweight, requires only Bash and `tcpdump`.

---

## 🧰 Requirements

- Linux/Unix OS
- `tcpdump` installed
- Root privileges to run

Install `tcpdump` if not installed:
```bash
sudo apt install tcpdump  # Debian/Ubuntu
sudo yum install tcpdump  # RHEL/CentOS
🚀 Installation & Usage

    Clone the Repository:

git clone https://github.com/YourUsername/dal-network-sniffer.git
cd dal-network-sniffer

    Make the script executable:

chmod +x dal_sniffer.sh

    Run the tool:

./dal_sniffer.sh

Follow the on-screen prompts to select the interface and duration.
📂 Output

The captured traffic will be saved in:

dal_sniffer_capture.pcap

You can analyze it later using Wireshark or any packet analysis tool.
🧑‍💻 Author

Made with ❤️ by HuzaifaDal
