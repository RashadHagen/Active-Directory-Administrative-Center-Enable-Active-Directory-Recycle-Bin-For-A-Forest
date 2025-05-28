<h1>Active Directory Administrative Center – Enable Active Directory Recycle Bin</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to enable Active Directory Recycle Bin using Active Directory Administrative Center (ADRB). When an administrator enables Active Directory Recycle Bin, it serves as a temporary holding area for deleted Active Directory objects and allows them to recover these objects without resorting to system state backups or using complex methods.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>Active Directory Administrative Center</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: This is helpful if you delete something on accident in an Active Directory.</b></span>  
<br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: All domain controllers in the same Forest will need to have their Recycle Bin enabled in Active Administrator Center. Once you enable Recycle Bin, you cannot undue it.n</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/WPGAFDP.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br/><br/>


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: The “Recycle Bin” is called “Deleted Objects” in Active Directory Administrative Center.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/InvgY64.png" height="100%" width="100%" /></td>
    <td><img src=https://imgur.com/yWOskRH.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/QIkxAi1.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Active Directory Administrative Center.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/iJrFoLu.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/9l8YbcD.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: The Domain you want to enable a Recycle Bin (called Deleted Object) (left-side under Overview).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/WNCAjHS.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/gVSWr4y.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>FIRST WAY TO ENABLE: Right-Click: The Domain name (left-hand side under Overview) and Click: Enable Recycle Bin.  Note: it will be black if not enabled and grey if enabled.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/bYRLQjv.png" height="100%" width="100%" /></td>
    <td><img src=https://imgur.com/32CScmM.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/nq8gsOf.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>SECOND WAY TO ENABLE: Click: Enable Recycle Bin (right-side under the Forest name and above New). Note: it will be black if not enabled and grey if enabled.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/0FPNjnB.png" height="100%" width="100%" /></td>
    <td><img src=https://imgur.com/cHZqpG0.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/Di96cbD.png" height="50%" width="50%" /></td>
  </tr>
</table>

<br /><br />
