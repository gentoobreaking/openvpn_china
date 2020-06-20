---
title: 'Configuration for openvpn with DD-WRT.'
disqus: hackmd
---

Configuration for openvpn with DD-WRT.
===
![downloads](https://img.shields.io/github/downloads/atom/atom/total.svg)
![build](https://img.shields.io/appveyor/ci/:user/:repo.svg)
![chat](https://img.shields.io/discord/:serverId.svg)

## Table of Contents

[TOC]

## Operator Guide

User story
---

Step.1 Preparing tftp server with Tranfer app.

![image Info](screenshots/tftp_server.png "tftp_server")
---

Step.2 Download dd-wrt firmware.

![image Info](screenshots/dd-wrt_download.png "dd-wrt_download")
---

Step.3 Update firmware with dd-wrt version.
       a.config pc ip with 192.168.0.66
       b.startup tftp with dd-wrt firmware.
       c.push reset button when power on within 7 ~ 10 secs.
       d.ensure the device get firmware in tftp gui.
       e.waitting for 5 mins. and then restart ap device. (please config pc ip with dhcp.)

![image Info](screenshots/dd-wrt_version.png "dd-wrt_version")
---

Step.4 Configuration for openvpn client.

![image Info](screenshots/openvpn_client_1.png "openvpn_client_1")
![image Info](screenshots/openvpn_client_2.png "openvpn_client_2")
![image Info](screenshots/openvpn_client_3.png "openvpn_client_3")
![image Info](screenshots/openvpn_client_status.png "openvpn_client_status")
---

Step.5 Verify result.

![image Info](screenshots/verify_result.png "verify_result")
---


