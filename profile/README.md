# RADIUSdesk
RADIUSdesk is a powerful and user-friendly RADIUS management platform designed to simplify the administration of network authentication and accounting.

# Features
* **User Management:** Easy user management with a comprehensive web interface.
* **Real-time Monitoring:** Monitor user sessions and access logs in real-time.
* **Multi-language Support:** Available in multiple languages.
* **Customizable:** Highly customizable to fit your specific needs.

# MESHdesk
MESHdesk allows you to create and manage mesh networks with ease. It is designed to enhance network coverage and reliability by connecting multiple access points (APs) in a seamless mesh.

* **Automatic Configuration:** MESHdesk automatically configures and optimizes your mesh network for optimal performance.
* **Self-healing Networks:** If an AP goes offline, the network automatically re-routes traffic to ensure continuous connectivity.
* **Scalability:** Easily add or remove APs to scale your network as needed. We use **Batman-adv** which can potentially scale to hundreds of nodes in a single mesh network.
* **Centralized Management:** Manage all your mesh nodes from a single, user-friendly interface.
* **Firmware Management:** Remotely update and manage firmware across all APs.
* **Network Visualization:** Visualize the mesh network topology and monitor the health of each node.

![Mesh Nodes Mobile](https://radiusdesk.com/wiki24/_media/homepages/mobile_mesh.png "Mesh Nodes Mobile")

# APdesk
APdesk provides powerful tools for managing individual access points (APs). It simplifies the process of configuring, monitoring, and maintaining APs to ensure a high-quality network experience.

* **Intuitive Interface:** User-friendly interface for configuring and managing APs.
* **Performance Monitoring:** Real-time monitoring of AP performance metrics such as signal strength, bandwidth usage, and client connections.
* **Configuration Profiles:** Create and apply configuration profiles to multiple APs for consistent setup.
* **Security Management:** Configure security settings including encryption, firewall rules, and access controls.
* **Client Management:** Monitor and manage clients connected to each AP.
* **Reporting and Analytics:** Generate detailed reports on AP performance, client activity, and network usage.

![LTE Sginal](https://radiusdesk.com/wiki24/_media/network/lte_tooltip.png "LTE Signal")

# Flexible and Cost-Effective Deployment with MESHdesk and APdesk
One of the standout benefits of MESHdesk and APdesk is the flexibility to use a wide range of hardware, from current off-the-shelf models to repurposed devices. This includes:
* **Using Current Off-the-Shelf Hardware:** Deploy modern, off-the-shelf hardware like the Cudy X6, available on Amazon. These devices can be easily flashed with OpenWrt, providing a powerful and customizable networking solution.
* **Repurposing Pre-owned Hardware:** Utilize cost-effective, pre-owned devices like Meraki MR24s, which are affordable and readily available on platforms like eBay. This significantly reduces the initial investment required to set up your network.
 ## Key Advantages
* **Cost Savings:** Save on hardware costs by leveraging both pre-owned and affordable new devices.
* **Sustainability:** Repurpose existing hardware to reduce electronic waste and promote environmental sustainability.
* **Flexibility:** Choose from a wide range of compatible devices to suit your specific needs and budget.
* **Accessibility:** Make advanced networking solutions attainable for everyone, regardless of budget constraints.

With MESHdesk and APdesk, you can deploy powerful, reliable networks using a mix of repurposed and new hardware, ensuring high-quality connectivity without breaking the bank.

![picture alt](https://raw.githubusercontent.com/RADIUSdesk/RADIUSdesk.github.io/main/images/pr/pr5.png "RADIUSdesk Screenshot") 

# Our Goals
We aim to provide a centralized management system for your Internet users and hardware that is:
* **User-Friendly:** Intuitive and easy to use, even for those with minimal technical expertise.
* **Fully Controlled:** Empowering you with complete control over your network.
* **Open Source:** Entirely open source, ensuring transparency and community-driven development.

# Getting Started
Below, you will find pinned repositories, each with its own comprehensive wiki page providing detailed instructions:
* [rdcore:](https://github.com/RADIUSdesk/rdcore)  Instructions for installing the central administration system.
* [openwrt-meshdesk:](https://github.com/RADIUSdesk/openwrt-meshdesk) Guidelines for compiling the OpenWrt firmware with the MESHdesk package.

# History
RADIUSdesk has a rich history spanning over a decade.
* **2012:** The project was launched on SourceForge, marking the beginning of our journey.
* **2022:** We transitioned to GitHub, embracing modern development workflows.

## Initial Setup
When we first started, our technology stack included:

* **Operating System:** Ubuntu 10.04
* **RADIUS Server:** FreeRADIUS 2.x
* **JavaScript Framework:** ExtJS 4.0
* **PHP Framework:** CakePHP 2.x
* **Router Firmware:** OpenWrt Attitude Adjustment (12.09)
* **Hardware:** Single radio devices for mesh networks using 802.11n (Wi-Fi 4)

## Current Setup
Today, RADIUSdesk utilizes a more advanced and robust stack:

* **Operating System:** Ubuntu 24.04
* **RADIUS Server:** FreeRADIUS 3.x
* **JavaScript Framework:** ExtJS 7.0
* **PHP Framework:** CakePHP 4.x
* **Router Firmware:** OpenWrt 23.05.x
* **Hardware:** Devices with up to three radios supporting 802.11n/ac/ax (Wi-Fi 4/5/6)


# Licensing
* All the code is published under the **GNU General Public License v3.0**.<br/>
* This means that you may make modifications and changes.

# Funding

This project also received funding through [NGI0 Entrust](https://nlnet.nl/entrust), a fund established by [NLnet](https://nlnet.nl) with financial support from the European Commission's [Next Generation Internet](https://ngi.eu) program.<br/>
Learn more at the [NLnet project page](https://nlnet.nl/project/RADIUSdesk-Multiwan).<br/>
<br/>
[<img src="https://nlnet.nl/logo/banner.png" alt="NLnet foundation logo" width="20%" />](https://nlnet.nl)<br/>
[<img src="https://nlnet.nl/image/logos/NGI0_tag.svg" alt="NGI Zero Logo" width="20%" />](https://nlnet.nl/entrust)<br/>


