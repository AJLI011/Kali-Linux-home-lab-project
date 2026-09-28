# Kali-Linux-home-lab-project

A virtual cybersecurity lab built on a Ryzen 5 4650G with 16 GB RAM.

---
I am creating a basic homelab to perform various Cybersecurity and Networking labs that I can use for practicing tools and such. For this project, I am following a video for setting up Kali Linux in my system. I am using a hypervisor, VirtualBox to store this virtual homelab. I can’t perform dual boot yet since I’m scared of bricking my device as it is the only one I have. For now this will do.

# Tools: 
- Oracle VirtualBox
- Kali Linux.iso file
- Browser (for installing the applications,ISO file, etc.)
- QbitTorrent (for getting the ISO file)

# Documentation:
I already have Virtual Box installed but not Kali Linux yet so I headed over to the website and got their torrent file so that I can download the and be able to install the tool. To install Virtual Box though, just head over to their website and select the windows host or whatever OS the device is. My device is Windows so I selected Windows host. I used torrent since I have a torrent app which allows me to download it quickly.

![kali website](/img/kali-website.png)
![oracle website](/img/oracle-website.png)

After I was done installing the file, I took note where it was located as it will be needed when I set it up later on VirtualBox

![finished downloaded file](/img/downloaded-kali-iso.png)

Now for this to work, we just have to mount it to virtual box and set some configurations for the virtual machine. Since my device is a bit low-end, I decided to set the resources to the following. By the way, before that, here are my specs:

![device specs](/img/device-specs.png)

Below are the specifications I’ve allocated to Kali as I configure it on Virtual Box.

![kali resource](/img/kali-resource-alloc.png)

As I continue with the installation, I’ve already created the name of the device as well as the username. I’ve kept everything default (except for the username) so that they are accessible. At this point, I’ve finished partitioning.

![kali resource](/img/kali-resource-alloc.png)

