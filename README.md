# InvestigatingSuspiciousFileHash
In this project, I analyze an artifact using VirusTotal and capture details about its related indicators of compromise using the Pyramid of Pain. 

<h2>Scenario:</h2>
You are a level one security operations center (SOC) analyst at a financial services company. You have received an alert about a suspicious file being downloaded on an employee's computer. 

You investigate this alert and discover that the employee received an email containing an attachment. The attachment was a password-protected spreadsheet file. The spreadsheet's password was provided in the email. The employee downloaded the file, then entered the password to open the file. When the employee opened the file, a malicious payload was then executed on their computer. 

You retrieve the malicious file and create a SHA256 hash of the file. You might recall from a previous course that a hash function is an algorithm that produces a code that can't be decrypted. Hashing is a cryptographic method used to uniquely identify malware, acting as the file's unique fingerprint. 

<br />
<br />

<h2>Review Details of the Alert</h2>
<br />

SHA256 file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

Timeline of events leading up to alert:
  - 1:11 p.m.: An employee receives an email containing a file attachment.
  - 1:13 p.m.: An employee receives an email containing a file attachment.
  - 1:15 p.m.: Multiple unauthorized executable files are created on the employee's computer.
  - 1:20 p.m.: An intrusion detection system detects the executable files and sends out an alert to the SOC.

<h4>Enter the File Hash Into VirusTotal</h4>

<img src="https://i.imgur.com/sjRGGZE.png" height="80%" alt="Enter File Hash"/> <br />
<br />
<br />

<h2>Analyze the VirusTotal Report</h2>
<img src="https://i.imgur.com/yZPLFKh.png" height="80%" alt="Analyze VirusTotal Report1"/> <br />
<img src="https://i.imgur.com/Q7m1T7t.png" height="80%" alt="Analyze VirusTotal Report2"/> <br />
<br />
<br />

<h2>Determine Whether the File is Malicious</h2>

<img src="https://i.imgur.com/VCeYYGt.png" height="80%" alt="Determine Whether the File is Malicious"/> <br />

<h4>Reference (Pyramid of Pain):</h4>
<img src="https://i.imgur.com/5J7ypg2.png" height="80%" alt="Pyramid of Pain"/> <br />

<br />
<br />

<h4>End of Project</h4>
