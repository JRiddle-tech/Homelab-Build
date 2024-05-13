<h1>Homelab PC Build</h1>

<p>A homelab is a personal computing environment that I've set up at home, which serves as my own laboratory for learning, experimenting, and testing various technologies, using virtualization.
The reasons for having a homelab can vary, but for me, it's a valuable tool for several purposes: </p>

<ul> <li><strong>Learning and skill development:</strong> My homelab provides a hands-on environment where I can learn new technologies and system administration skills. It's a great way to gain practical experience and improve my knowledge in these areas.</li> 
<li><strong>Backup and data storage:</strong> My homelab serves as a centralized backup and storage solution for my personal data, documents, and media files. It gives me peace of mind knowing that my important files are safe and easily accessible.</li> 
<li><strong>Networking and security:</strong> My homelab offers an opportunity to learn about networking protocols, configure firewalls, and network segmentation with VLANs.</li> 
<li><strong>Hobby and passion:</strong> For me, a homelab is a way to pursue my passion for technology, tinker with hardware, and stay up-to-date with the latest trends and developments in the field. It's a fun and rewarding hobby that also has practical benefits.</li></ul>


<h2>Hardware Used in this Build</h2> 
<p>The hardware that is used in this build was already purchased by a friend of mine, who was unable to assemble the machine as his circumstances had changed and needed the money to put towards his wedding.</p>

<ul><li><strong>Case:</strong> Cooler Master NR200P</li>
<li><strong>Motherboard:</strong> Asus ROG Strix Z590-I LGA 1200 <em>BIOS version: 2002 (10/03/2023)</em></li> 
<li><strong>Power Supply:</strong> ASUS ROG Loki SFX-L 850W Platinum</li> 
<li><strong>CPU:</strong> Intel Core i7-10700K 3.8GHz, 8-cores (10th Gen)</li>
<li><strong>CPU Cooler:</strong> Noctua NH-L9i Low Profile CPU Fan</li> 
<li><strong>Memory:</strong> G.Skill Trident Z, 32GB DDR4 @ 2933MHz</li>
<li><strong>Storage:</strong> 1TB SSD 980 PRO PCle 4.0 NVMe M.2</li>
<li><strong>GPU:</strong> NVIDIA GeForce RTX 3080</li> </ul>



<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/> <h2>Parts and Product</h2></p>
    <img src="https://i.imgur.com/wfBU9eM.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>


<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/> <h2>CPU</h2> </p>
    <img src="https://i.imgur.com/w0CFTWS.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/> <h2>NVME Storage</h2></p>
    <img src="https://i.imgur.com/TTRtKNb.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>
<p>Unfortunately, the motherboard used in this build only lets you use one of the two M.2 slots if you are not using an 11th gen Intel CPU. This is my biggest regret with this build, as I didn't identify that the 10th gen Intel CPU that my friend purchased wouldn't provide this functionality. In a small form factor build like this one, storage can be limited, and I had originally planned to have two M.2 drives for a mirrored RAID pool.</p>

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/> <h2>RAM</h2> </p>
    <img src="https://i.imgur.com/2DdPKVQ.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>
<p>Additionally, it's worth noting that the 10th gen CPU used in this build has some limitations when it comes to RAM frequency. Specifically, the RAM frequency is limited unless an 11th gen CPU is installed. For this reason, the RAM used in this build, which is rated for 3600MHz, isn't able to be utilized to its full speeds due to incompatibility with the motherboard.</p> 
<p>However, it's still possible to use the RAM at a lower frequency, and in this build, the RAM is running at 2933MHz, which is still faster than the default speed of 2133MHz for DDR4 RAM.</p>

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/><h2>Cooler</h2></p>
    <img src="https://i.imgur.com/yOdXpEG.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>

<p>The original plan for this build was to use the Kraken X63 AIO cooler that came with the parts package. However, after attempting to install it, I found that the 280mm radiator was too large to fit anywhere in the NR200p case, even without a GPU installed. For this reason, I had to swap it out for a 240mm AIO that I had on another machine.</p> 

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/> <h2>Cooler Change</h2></p>
    <img src="https://i.imgur.com/HUa42if.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>
<p>I wasn't too pleased with the options for placing the radiator, as mounting it on the bottom of the case with the tubes going up to the CPU reportedly leads to reduced AIO efficiency. Additionally, the AIO cooler setup in this case ultimately wasn't an effective solution, as I needed more space to put HDDs, and the machine isn't going to be getting too hot given its role.</p> <p>For this reason, I purchased a low-profile CPU fan from Noctua and have been happy with the result. The Noctua NH-L9i is a high-quality, low-profile cooler that provides excellent cooling performance while taking up minimal space in the case. It's also very quiet, which is an added bonus for a small form factor build like this one.</p>


<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/> <h2>GPU</h2></p>
    <img src="https://i.imgur.com/zaesDam.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>
<p>Initially, my use-case for this build was to use the integrated graphics with the Intel CPU and not use a dedicated GPU. However, I was curious to see how it would fit with the PCIe riser cable and explore using an NVIDIA GPU in Proxmox (I had used AMD in a previous build and it was challenging).</p> <p>The placement of the AIO cooler meant that a GPU wouldn't be able to fit without a riser and a vertical mount. This is another reason that the AIO cooler wasn't a good long-term solution for my build.</p> <p>After experimenting with a GPU in the build, I ultimately removed it. </p>


<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/> <h2>Adding Additional Storage</h2></p>
    <img src="https://i.imgur.com/U53jE9z.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>


<p>For storage, I have purchased two Seagate IronWolf 12TB NAS Internal Hard Drive HDDs which I am planning to use in a mirrored zfs pool in Proxmox. This will provide redundancy and ensure that my data is safe in the event of a drive failure.</p> 
<p>Since the NR200p case doesn't have a lot of room for hard drives, I have a friend with a 3D printer, and together we created a custom mounting solution. This allowed me to mount the drives securely and efficiently in the case.</p> 

<div style="display: flex; align-items: center;">
  <div style="flex: 1;">
    <p align="center"> <br/> </p>
    <img src="https://i.imgur.com/kNNoEr0.png" style="height: 70%; width: auto;/>
  </div>
  <div style="flex: 1; padding-left: 20px;">
  </div>
</div>

<p>This is the current working configuration, next I am planning to add a quad port intel NIC.</p>
