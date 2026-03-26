# Setting Up Homelab In Azure

**This is a thread of me setting up my virtual homelab i Azure to practice Sysadmin tasks.**<br><br>

---
---
---
### Setting up VMs
**Here, I am setting up the server VM using Windows Server 2022. It says I used US East region for my VMs, but I went back later to create the VMs over due to errors that I didn't get to document. You will see in later pictuers.**<br><br>
![Dashboard Screenshot](images/img1.png)
![Dashboard Screenshot](images/img2.png)
![Dashboard Screenshot](images/img3.png)<br><br><br>

---
---
---

## VM is deploying<br><br>
![Dashboard Screenshot](images/img4.png)<br><br><br>

---
---
---

**This is where I created the VM for the client computer using Windows 11 Enterprise. I used zone 2, and I couldn't figure out what it did, but it wouldn't allow to use Zone 1 for the Windows Server VM and in order to connect both VMs to the same vnet it was necessary to add both to the same region and zone.**<br><br>
![Dashboard Screenshot](images/img5.png)<br><br><br>

---
---
---

### VMs are finished
**As you can see the location says West US 2. I was having issues with the last VMs I created in East US and there was an outage in East US (I hear that outages are common in East US 1).** <br><br>
![Dashboard Screenshot](images/img8.png)<br><br><br>

---
---
---

### Resizing virtual machines
**I resized my VMs for more speed and better ease of use. I was using B1s, which only had 2gb of RAM, and I switched to B2s with 4gb RAM and 2 CPU. It was much faster and made setting up my server much easier.**<br><br>
![Dashboard Screenshot](images/img9.png)<br><br><br>

---
---
---

### Setting up server<br><br>
![Dashboard Screenshot](images/img10.png)
![Dashboard Screenshot](images/img11.png)
![Dashboard Screenshot](images/img12.png)<br><br><br>

---
---
---

### Creating users<br><br>
![Dashboard Screenshot](images/img13.png)
![Dashboard Screenshot](images/img14.png)
![Dashboard Screenshot](images/img15.png)
![Dashboard Screenshot](images/img16.png)<br><br><br>

---
---
---

### Connecting Client to Server
**Making sure client computer can reach server and connecting client to the server**<br><br>
![Dashboard Screenshot](images/img17.png)
![Dashboard Screenshot](images/img18.png)
![Dashboard Screenshot](images/img19.png)
![Dashboard Screenshot](images/img20.png)
![Dashboard Screenshot](images/img21.png)<br><br><br>

---
---
---

### Trying different group policies<br><br>
![Dashboard Screenshot](images/img22.png)
![Dashboard Screenshot](images/img23.png)
![Dashboard Screenshot](images/img24.png)
![Dashboard Screenshot](images/img25.png)<br><br><br>
