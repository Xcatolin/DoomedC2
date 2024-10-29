# DoomedC2
*A command and control tool born doomed.*

> DoomedC2 is a work in progress and still in an early stage of development. Source code should be published as Doomed matures and becomes more robust and stable.
___
#### Design and Features
**Slayer**
- Implant written in C, supports UNIX and Windows

**Doomed**
- Back-end and CLI written in Python3

**Core Features**
- Customizable sleep mask and jitter functionalities
- Authentication checks
- Supports multiple victims
    - Individual command queue
- Anti-analysis/emulation/sandbox checks
- Multiple methods for command execution
- HTTP traffic with support for SSL/TLS, encoding and obfuscation
- Evasive features, capable of running against major endpoint protection solutions without triggering alerts

#### Implant/Server Interaction
![FlowDigaram](https://raw.githubusercontent.com/Xcatolin/DoomedC2/refs/heads/main/img/diagram.png)


#### Screenshots

Doomed's Command-Line Interface
<img src="https://raw.githubusercontent.com/Xcatolin/DoomedC2/refs/heads/main/img/cli.png" width="900">
