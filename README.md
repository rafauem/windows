<p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Windows_logo_-_2012_%28dark_blue%29.svg/480px-Windows_logo_-_2012_%28dark_blue%29.svg.png" alt="MarkText" width="100" height="100"></p>

<h1 align="center">Windows</h1>

<div align="center">
  <strong>:high_brightness: Some tricks and tips for Windows 10 and 11 :crescent_moon:</strong><br>

  <sub>Available only for Windows.</sub>
</div>

<br>


<div align="center">
  <h3>
    <a href="https://github.com/rafauem/windows/edit/main/README.md#useful-programs">
      Programs
    </a>
    <span> | </span>
    <a href="https://github.com/marktext/marktext#commands">
      Commands
    </a>
    <span> | </span>
    <a href="https://github.com/marktext/marktext#download-and-installation">
      Downloads
    </a>
    <span> | </span>
    <a href="https://github.com/marktext/marktext#development">
      Development
    </a>
    <span> | </span>
    <a href="https://github.com/marktext/marktext#contribution">
      Contribution
    </a>
  </h3>
</div>

<br />

# Useful Programs

- Microsoft PowerToys. You can find it in [github.com/microsoft/PowerToys](https://github.com/microsoft/PowerToys/releases/tag/v0.65.0)

- Bootable Prendrive
	- [Ventoy](https://www.ventoy.net/en/download.html)
	- [Rufus](https://rufus.ie/)
  
- Microsoft Power App. Easily develop mobile and web apps for any business need—even if you have no technical or development experience—with [Power Apps](https://powerapps.microsoft.com/en-us/landing/developer-plan/?&ef_id=Cj0KCQiA45qdBhD-ARIsAOHbVdG-TPjNG-E9sJSG_c_vHON1P1HIFwIJDHK5DOU9-2vr1DK8XnrDeSAaAimfEALw_wcB:G:s&OCID=AIDcmm61zwfh7q_SEM_Cj0KCQiA45qdBhD-ARIsAOHbVdG-TPjNG-E9sJSG_c_vHON1P1HIFwIJDHK5DOU9-2vr1DK8XnrDeSAaAimfEALw_wcB:G:s&gclid=Cj0KCQiA45qdBhD-ARIsAOHbVdG-TPjNG-E9sJSG_c_vHON1P1HIFwIJDHK5DOU9-2vr1DK8XnrDeSAaAimfEALw_wcB).



- Antivirus: [Malwarebytes](https://www.malwarebytes.com/). 14 days free.

- Optimizer. _Use at your own risk_. I checked with [Malwarebytes](https://www.malwarebytes.com/) and no virus was detected: :point_right:[optimizer](https://github.com/hellzerg/optimizer/releases):point_left:

# Commands

- Antivirus Windows Native: <kbd>⊞ Win</kbd>+<kbd>R</kbd>, then type wriete ```MRT``` and press <kbd>OK</kbd>

- Show WI-FI Password
```pwsh
C: > netsh wlan show profile
     name
C: > netsh wlan show profile name key=clear
```

- Virus check: <kbd>⊞ Win</kbd>+<kbd>R</kbd>, then type wriete ```MRT``` and press <kbd>OK</kbd>

Turn off Windows send things

 <kbd>⊞ Win</kbd>+<kbd>R</kbd>, then type wriete ```gpedit.msc``` and press <kbd>OK</kbd>

 - Windows Free
```phsw
C:> bcdedit -set TESTSIGNING OFF
```



