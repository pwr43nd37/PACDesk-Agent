# PACDesk-Agent

PACDesk-Agent is a lightweight and robust agent designed for the PACDesk system, provided as a static binary for simplified installation on Linux environments.

## 🚀 Quick Installation

To install PACDesk-Agent, execute the following commands directly in your Linux terminal:

```bash
curl -LO https://github.com/pwr43nd37/PACDesk-Agent/releases/download/v1.8/pacdesk-agent-v1.8.tar.gz
tar -xzf pacdesk-agent-v1.8.tar.gz
cd PACDesk-Agent/
bash install.sh
```

The installation script will prompt you for the installation directory, offering `/opt/pacdesk-agent` as the default. Press Enter to accept or enter a custom directory.

## 📌 Service Management

After installation, manage PACDesk-Agent using `systemctl` commands:

```bash
sudo systemctl start pacdesk-agent     # Start service
sudo systemctl stop pacdesk-agent      # Stop service
sudo systemctl restart pacdesk-agent   # Restart service
sudo systemctl status pacdesk-agent    # Check status
```

## 🔧 Post-Installation Structure

After installation, the file structure will look like this:

```
/opt/pacdesk-agent/
└── agent_pacdesk
```

## 💡 Updates

To update the agent, repeat the installation process above with the new release.

## ⚙️ Requirements

- Linux distribution with Systemd
- Curl or wget installed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
