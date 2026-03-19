<h1>Microsoft Deployment Toolkit Adding Google Chrome application: </h1>


<p>
 <ul>
   <li>adksetup</li>
   <li>adkwinpesetup</li>
   <li>Microsoft Deployment Toolkit</li>
  <li>Microosft Deployment Service (from Windows Server 2022)</li>
 </ul>

</p>


<h2>Introduction</h2>

<p>
Microsoft Deployment Toolkit is a software that deploys auomtatically WIM file (Windows 11 OS version) on desktops, laptops, and servers.
In my IT homelab, I actually did a IT class in-person project when I was at Utah Valley University. I knew how to create a boot image and setup DHCP server on the Domain Controller (Windows Server 2022 VM).
Here is screenshot I took. Firstly, I downloaded adksetup, adkwinpesetup, and Microsoft Deployment Toolkit (Workbench application) from the official Microsot website. Also, I have to download Microsoft Deployment Service
 on my domain controller, so it is for PXE network when I creat a Client Virtualmachine and it find the Ip address after setup DHCP scope.
</p>

<br>


<img width="1358" height="738" alt="image" src="https://github.com/user-attachments/assets/454ec0ab-acf5-497b-8b78-f65057ef772a" />



<br>
<p>In this stage of my homelab development, I am leveraging the Microsoft Deployment Toolkit (MDT) to streamline and automate software distribution across my virtual environment. The image shows the New Application Wizard within the Deployment Workbench, where I am configuring a new "Application with source files." By importing these installers directly into the MDT Deployment Share, I can create a standardized repository of essential tools and runtimes. This setup is a critical step in building a "zero-touch" or "lite-touch" deployment strategy, allowing me to PXE boot new virtual machines and have them fully provisioned with a custom OS image and pre-configured software suites without manual intervention.</p>

<br>

<h1>Details</h1>
<img width="1371" height="725" alt="image" src="https://github.com/user-attachments/assets/ee3b83c6-2551-4e49-918c-4ed832a41dc4" />

<br>

<p>
 
</p>

<br>

<h1>Source</h1>
<img width="1363" height="722" alt="image" src="https://github.com/user-attachments/assets/ac1ede57-d56d-42b0-993f-5b882e8615dd" />

<br>

<p>
 
</p>

<br>

<h1>Command Details</h1>

<img width="1382" height="725" alt="image" src="https://github.com/user-attachments/assets/18c87a5c-5f7e-4a3e-ae97-d21a456de5f7" />


<p></p>

<img width="1377" height="721" alt="image" src="https://github.com/user-attachments/assets/068f0e7e-b108-4d73-afe5-ad6b62bfbee9" />
