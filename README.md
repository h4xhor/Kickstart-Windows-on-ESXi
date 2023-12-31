



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# Kickstart-Windows-on-ESXi






# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

To clone this project into your own instance of Attune, follow the
[Clone a GIT Project How To Instructions](https://servertribe-attune.readthedocs.io/en/latest/howto/design_workspace/clone_project.html).




## Blueprints

This Project contains the following Blueprints.



### Check ESXi Drivers Installed - Group


### Kickstart Win10 BIOS autounattend Dual ISO on Linux for ESXi


### Kickstart Win10 BIOS autounattend Single ISO on Linux for ESXi

Kickstarts Windows Desktop 10 from a single ISO.

### Kickstart Win10 BIOS autounattend WinPE ISO on Linux for ESXi


### Kickstart Win10 UEFI autounattend Dual ISO on Linux for ESXi


### Kickstart Win10 UEFI autounattend Single ISO on Linux for ESXi


### Kickstart Win10 UEFI autounattend WinPE ISO on Linux for ESXi


### Kickstart Win2016 BIOS autounattend Dual ISO on Linux for ESXi


### Kickstart Win2016 BIOS autounattend Single ISO on Linux for ESXi


### Kickstart Win2016 BIOS autounattend WinPE ISO on Linux for ESXi


### Kickstart Win2016 UEFI autounattend Dual ISO on Linux for ESXi


### Kickstart Win2016 UEFI autounattend Single ISO on Linux for ESXi


### Kickstart Win2016 UEFI autounattend WinPE ISO on Linux for ESXi


### Kickstart Win2019 BIOS autounattend Dual ISO on Linux for ESXi


### Kickstart Win2019 BIOS autounattend Single ISO on Linux for ESXi

Kickstarts Windows Server 2019 from a single ISO.

### Kickstart Win2019 BIOS autounattend WinPE ISO on Linux for ESXi


### Kickstart Win2019 UEFI autounattend Dual ISO on Linux for ESXi


### Kickstart Win2019 UEFI autounattend Single ISO on Linux for ESXi


### Kickstart Win2019 UEFI autounattend WinPE ISO on Linux for ESXi


### Kickstart Win2022 BIOS autounattend Dual ISO on Linux for ESXi


### Kickstart Win2022 BIOS autounattend Single ISO on Linux for ESXi


### Kickstart Win2022 BIOS autounattend WinPE ISO on Linux for ESXi


### Kickstart Win2022 UEFI autounattend Dual ISO on Linux for ESXi


### Kickstart Win2022 UEFI autounattend Single ISO on Linux for ESXi


### Kickstart Win2022 UEFI autounattend WinPE ISO on Linux for ESXi


### WinPE Kickstart Win10+ESXi


### Deploy Plain WinPE ISO (link) - DELETE





## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Attune OS Build Server | Linux/Unix Node | `attuneosbuildserver` |  |
| Drivers Drop Directory | Text | `driversdropdirectory` | Put any extra drivers you want used by WinPE and the Windows installer here.<br><br>This can contain subfolders.<br><br>These are the "*.inf" files.<br><br>WinPE's startnet.cmd will recursively search for the "*.inf" files to install.<br><br>autounattend.xml will do the same.<br><br>This folder path relative to "{ksAttuneBaseDir}/build-{targetServer.fqn}".<br><br>Example: Setting this as "drop_in_drivers" will mean the drivers drop in directory will be at "{ksAttuneBaseDir}/build-{targetServer.fqn}/drop_in_drivers".<br><br>If "drop_in_drivers" exists, it's contents will be copied to "Drivers" folder.<br><br>If "drop_in_drivers" does not exist, it is ignored.<br><br>The contents of the Drivers folder will eventually seen at "X:\attune_drivers" by WinPE and the Windows installer. |
| KS: Attune Base Dir | Text | `ksattunebasedir` |  |
| Linux: Attune User | Linux/Unix Credential | `linuxattuneuser` |  |
| Linux: Root User | Linux/Unix Credential | `linuxrootuser` |  |
| New OS Node | Basic Node | `newosnode` |  |
| New OS Windows Node | Windows Node | `newoswindowsnode` |  |
| New OS Windows User: Administrator | Windows Credential | `newoswindowsuseradministrator` | The windows administrator user |
| Target Server: Win | Windows Node | `targetserverwin` |  |
| Windows Build Server | Windows Node | `windowsbuildserver` |  |
| Windows Build User | Windows Credential | `windowsbuilduser` |  |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**
