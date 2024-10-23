<h1 align="center">
  <br>
  <img src="https://github.com/Torrex123/Netmand/blob/main/public/assets/Logo.png" alt="Markdownify" width="200">
  <br>
  Netmand
  <br>
</h1>

<h4 align="center">An easy-to-use solution for configuring network devices efficiently and effectively.</h4>

<p align="center">
    <img src="https://img.shields.io/badge/contributions-welcome-orange.svg" alt="Contributions welcome">
    <img src="https://img.shields.io/github/contributors-anon/Torrex123/Netmand?color=yellow&style=flat-square" alt="contributors" style="height: 20px;">
</p>

![screenshot](https://github.com/Torrex123/Netmand/blob/main/public/assets/demo.gif)

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#justification">Justification</a> •
  <a href="#usage">Usage</a> •
  <a href="#development">Development</a> •
  <a href="#want-to-contribute">Want to Contribute?</a> •
  <a href="#credits">Credits</a>
</p>

## Disclaimer

This repository is a copy of the original project **Netmand**, which I transferred from my personal GitHub account to my university's project repository. 
- You can find the original repository by clicking [here](https://github.com/proyectosingenieriauninorte/Netmand.git).

## Overview

`Netmand` is a user-friendly platform that simplifies the configuration of network devices such as PCs, switches, and routers. Users can create comprehensive network designs by selecting and configuring each device's options. Based on these configurations, Netmand generates the necessary commands to set up each device, streamlining the process of network deployment and management.

## Justification

The motivation behind creating Netmand stems from the challenges and repetitiveness associated with learning and managing network configurations, particularly in academic settings. Network configuration commands, which are fundamental in networking classes, often tend to be repetitive and easily forgotten, especially when they are not frequently practiced. This can lead to confusion and a steep learning curve for students and newcomers to the field.

Netmand aims to serve as a comprehensive tool that compiles all essential network commands taught in networking courses. By providing an intuitive interface that allows users to design networks and generate configuration commands, Netmand helps in reinforcing learning through practical application. This hands-on approach makes it easier for students to grasp complex concepts and retain critical information.

Additionally, Netmand addresses the issue of consistency in network configuration. By automating the command generation process based on user-selected options, it minimizes errors and ensures that configurations adhere to best practices. This not only aids students but also assists network administrators in quickly setting up and managing network devices, enhancing productivity and reducing the likelihood of misconfigurations.

## Development

Alternatively, instead of using the hosted version of the product, Netmand can be run locally for contribution purposes.

<details open>
<summary>
Pre-requisites
</summary> <br />
To be able to start development on Netmand, make sure that you have the following prerequisites installed:

- **Node.js**: You can download and install it from [nodejs.org](https://nodejs.org/).
- **Docker**: You can download and install it from [docker.com](https://www.docker.com/).
- **Git**: You can download and install it from [git-scm.com](https://git-scm.com/).
</details>

### Running the Project with Docker

If you have Docker installed, you can easily set up and run the project using Docker Compose. Follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/netmand.git
   cd netmand
   ```

2. **Start the Docker containers**:
   ```sh
   docker compose up
   ```

3. **Access the application**:
   Open your browser and go to [http://localhost:8080](http://localhost:8080/).

### Running the Project without Docker

If you don't have Docker, you can run the project using Node.js. Follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/Torrex123/Netmand
   cd netmand
   ```

2. **Install the dependencies**:
   ```sh
   npm install
   ```

3. **Run the application**:
   ```sh
   npm run dev
   ```

4. **Access the application**:
   Open your browser and go to [http://localhost:8080](http://localhost:8080/).
</details>

## Want to Contribute?

This project can still be expanded to include many more functionalities. Here are some potential features that could be added to Netmand:

- **Serial Port Configuration**: 
  Add options to configure serial ports on routers and switches for WAN connections.

- **New Routing Protocols**: 
  Implement support for additional routing protocols such as Static Routes, BGP (Border Gateway Protocol), and OSPF (Open Shortest Path First).

- **Default Gateways**: 
  Allow configuration of default gateways on network devices to ensure proper routing of traffic.

- **IP Calculators**: 
  Integrate IP calculators to help users determine network and broadcast addresses, usable IP ranges, and subnet masks.

- **Network Simulations**: 
  Develop simulation features to test network configurations by sending PDUs (Protocol Data Units) and verifying connectivity between devices.

## Credits

The initial version of Netmand has been developed by:

- Edgar Andres Torres Pérez: [Torrex123](https://github.com/Torrex123)
- Juan Pablo Vargas Rodríguez: [VargasJuanP](https://github.com/VargasJuanP)
- Joseph Venegas Banda: [venegasbjf](https://github.com/venegasbjf)
- Omar Cifuentes Laverde: [OmarCifuentes](https://github.com/OmarCifuentes)
