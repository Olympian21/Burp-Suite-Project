<h1>Qualys Vulnerability Management Home Lab</h1>


<h2>Description</h2>
Installed and deployed Qualys Virtual Scanner Appliance and accessed it through the Qualys Cloud Platform to indentify and remediate vulnerabilites found on a Windows 10 machine. You can enlarge the images by clicking on them.
<br />

<h2>Software & Environments Used </h2>

- <b>VirtualBox</b>
- <b>Windows 10</b>
- <b>VLC (outdated version)</b>
- <b>Firefox (older version)<b/>
- <b>Qualys Cloud Platform</b>


<h2>Project Walk-Through:</h2>

<p align="center">
Setting up authenticated scan and entering the IP adress of the Windows 10 virtual machine: <br/>
<img src="https://i.imgur.com/nnAV0nF.png" height="80%" width="80%" alt="Vulnerability Scan Steps"/>
<br />
  <br />
<img src="https://i.imgur.com/JUqiYQ6.png" height="80%" width="80%" alt="Vulnerability Scan Steps"/>
<br />
  <br />
  <img src="https://i.imgur.com/t0MrnSJ.png" height="80%" width="80%" alt="Vulnerability Scan Steps"/>
<br />
<br/>
<br />
Launched the scan: <br/>
<img src="https://i.imgur.com/QBVSwkz.png" height="80%" width="80%" alt="Vulnerability Scan Steps"/>
<br />
<br />
Found 117 Vulnerabilities:  <br/>
<img src="https://i.imgur.com/HstRJxs.png" height="80%" width="80%" alt="Vulnerability Scan Steps"/>
<br />
<br />
Each vulnerability has a risk score ranking from 1-5. The higher the risk score the more potential it has to do harm to your machine. The report shows vulnerablities for VLC media player as well as Microsoft Edge. The report also gives the solution for remediating these vulnerabilities. For example, the solution to remediate the vulnerability for Microsoft Edge is to upgrade it to a higher version. Most of the vulnerabilities in the report can be remediated by uninstalling outdated software. <br/>
<img src="https://i.imgur.com/8yafqUy.png" height="80%" width="80%" alt="Vulnerability Scan Steps"/>
<br />
<br />
Remediated vulnerabilities by uninstallilng the outdated versions of VLC and Firefox:  <br/>
<img src="https://i.imgur.com/nQP5XWd.png" height="80%" width="80%" alt="Vulnerability Scan Steps"/>
<br />
<br />
Reduced the vulnerabilities to 27 remaining (77% reduction). All vulnerabilities with a risk score of 5 have been remediated.  <br/>
<img src="https://i.imgur.com/LVnx8Gs.png" height="80%" width="80%" alt="Vulnerability Scan Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
