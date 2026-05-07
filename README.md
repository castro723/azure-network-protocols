
<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- NSG Overview / Rules
- VM-to-VM Traffic Testing
- Blocking Traffic With NSG
- Connection Failure Evidence

<h2>Actions and Observations</h2>

<p>
<img width="1087" height="471" alt="Screenshot 2026-05-07 at 11 06 09 AM" src="https://github.com/user-attachments/assets/c4c86135-679a-483b-bdd7-040791666151" />


</p>
<p>
This screenshot shows the Network Security Group configuration and security rules applied to the virtual machine.
</p>
<br />

<p>
<img width="1056" height="601" alt="Screenshot 2026-05-07 at 11 05 01 AM" src="https://github.com/user-attachments/assets/96d884b8-e974-4713-9bac-d8f77bbcd25e" />

</p>
<p>
This screenshot demonstrates traffic inspection between Azure virtual machines by testing connectivity after modifying NSG rules.
</p>
<br />

<p>
<img width="1084" height="464" alt="Screenshot 2026-05-07 at 10 58 56 AM" src="https://github.com/user-attachments/assets/8b505e52-d82b-4868-9797-b82950e739f5" />

</p>
<p>
This screenshot shows a custom NSG rule configured to block specific inbound traffic between Azure virtual machines.
</p>
<br />

<img width="1245" height="734" alt="Screenshot 2026-05-07 at 11 02 53 AM" src="https://github.com/user-attachments/assets/cb8c5590-c0df-48f5-a2cb-e932783e9234" />

This screenshot confirms that the NSG rule successfully blocked network traffic between the virtual machines.
