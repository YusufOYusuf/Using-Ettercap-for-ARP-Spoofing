<h1>Using Ettercap for ARP Spoofing</h1>


<h2>Description</h2>
In this lab, I learned to use ettercap for ARP spoofing. Ettercap is an open-source network security tool. It can be used for a security audit and can also be used for ARP (address resolution protocol) spoofing.
<br />



<h2>Environments Used </h2>

- <b>Windows 10 Pro</b> 
- <b>Windows 10 VM</b>
- <b>Kali VM</b>

<h2>Program walk-through:</h2>

<p align="center">
From the Desktop double-click Hyper-V Manager: <br/>
<img src="https://i.postimg.cc/Fzv3926L/Screen-Shot-2022-08-30-at-4-13-42-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In the Hyper-V Manager window, from the middle pane select "Kali"  <br/>
<img src="https://i.postimg.cc/wxF7yyyP/Screen-Shot-2022-08-30-at-4-18-11-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
<br />
enter the username, and password then click ok:  <br/>
<img src="https://i.postimg.cc/6pVsqRT4/Screen-Shot-2022-08-30-at-4-23-25-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
Minimize the kali VM and then in the Hyper-V Manager window click Windows 10 machine and click start: <br/>
<img src="https://i.postimg.cc/Vsbz1J9n/Screen-Shot-2022-08-30-at-4-26-14-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





  

<br />
Enter in the Username and Password in the Windows 10 VM <br/>
<img src="https://i.postimg.cc/SsgdvQRK/Screen-Shot-2022-08-30-at-4-31-45-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





<br />
Minimize the Windows 10 VM and go to the Kali VM. Once in Kali VM click the Kali logo in the top left then go to 09 then click Ettercap-graphical  <br/>
<img src="https://i.postimg.cc/q7xcYBq3/Screen-Shot-2022-08-30-at-4-39-18-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />






<br />
Enter in the Password  <br/>
<img src="https://i.postimg.cc/GpKgWnmH/Screen-Shot-2022-08-30-at-4-43-15-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />








<br />
In ther Ettercap window mae sure that the primary interface is selected as eth0 and click accept  <br/>
<img src="https://i.postimg.cc/xd7QwmCk/Screen-Shot-2022-08-30-at-4-47-04-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





<br />
Click the menu then select "hosts" then select "Hosts list"  <br/>
<img src="https://i.postimg.cc/KvgMw78T/Screen-Shot-2022-08-30-at-4-49-52-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





<br />
Select your 1st target as 192.168.1.101 and 2nd target as 192.168.1.1 <br/>
<img src="https://i.postimg.cc/PqmGRRB7/Screen-Shot-2022-08-30-at-4-54-26-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





<br />
Click the MITM icon and then click ARP Poisoning and then verify that the Sniff remote connections checkbox is checked then click ok <br/>
<img src="https://i.postimg.cc/0jv7Cb73/Screen-Shot-2022-08-30-at-4-57-28-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
<img src="https://i.postimg.cc/Fs3H4T5j/Screen-Shot-2022-08-30-at-4-59-53-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





<br />
Minimize the Kali VM and then open the Windows VM. From here, go to "http://testphp.vulnweb.com/login.php" and enter in the username and password  <br/>
<img src="https://i.postimg.cc/4NmF70N9/Screen-Shot-2022-08-30-at-5-03-49-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
Go back to the Kali VM and you will observe the Username and password typed in the Windows 10 VM <br/>
<img src="https://i.postimg.cc/KzhC2DnH/Screen-Shot-2022-08-30-at-5-05-11-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
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
