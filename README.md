# ActiveDirectoryPowerShellLab
<h1>JWipe - Secure Disk Sanitization Utility</h1>

<h2>Description</h2> **JWipe** is a lightweight, user-friendly PowerShell-based utility for securely sanitizing connected drives by overwriting data ("zeroing out"). This ensures sensitive information is irrecoverable, aligning with industry data protection and compliance standards.
The script guides users through disk selection and customization of overwrite passes. Based on user inputs, JWipe dynamically generates a Diskpart script to perform the sanitization, leveraging the reliability of Windows-native tools.

<h2>Key Features</h2>
Interactive Workflow: Step-by-step prompts to ensure safe disk selection and accurate operations.
Customizable Passes: Choose the number of overwrite passes for enhanced data security.
Data Security Compliance: Designed to align with NIST 800-88 and similar standards for secure data erasure.
Error Prevention: Confirmation steps to mitigate accidental disk erasure.
<h2>Languages and Utilities Used</h2>
PowerShell (script logic, user interaction)
Diskpart (disk wiping utility)
<h2>Environments Used</h2>
Windows 10 (21H2 or later)
<h2>Program Walkthrough</h2> <p align="center"> <b>1. Launch the Utility:</b> <br/> <img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Launch Utility"/> <br /><br />
<b>2. Select the Target Disk:</b> <br/> <img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Select Disk"/> <br /><br />

<b>3. Specify Overwrite Passes:</b> <br/> <img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Specify Passes"/> <br /><br />

<b>4. Confirm Your Selections:</b> <br/> <img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Confirm Selection"/> <br /><br />

<b>5. Process Execution:</b> Wait for the utility to complete the sanitization (this may take some time based on disk size). <br/> <img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Process Execution"/> <br /><br />

<b>6. Sanitization Complete:</b> A confirmation message will indicate successful disk sanitization. <br/> <img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Sanitization Complete"/> <br /><br />

<b>7. Verify the Wiped Disk:</b> Observe the sanitized disk to confirm all data has been erased. <br/> <img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Verify Wiped Disk"/>

</p> <h2>Use Cases</h2>
Device Decommissioning: Securely erase sensitive data before hardware disposal or repurposing.
Regulatory Compliance: Align with data protection standards like GDPR, HIPAA, and SOX.
Incident Response: Safely sanitize drives affected by data breaches or malware.
