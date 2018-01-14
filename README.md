# Software projects
**<details><summary>Python</summary><p>**

An example of quality control software written for analyzing nanowire growth on copper cryo-electron microscopy grids.

![](https://github.com/irazinkov/Portfolio/blob/master/grid-qc.PNG)

As part of the manufacturing process of the novel nanowire copper grids, the grids are exposed to a chemical reaction to grow nanowires  directly on the copper surface. Each individual grid is then examined under a light microscope, where the images are taken and automatically processed through this software.

Custom image analysis code provides a individual score for each grid.

Next, a classification algorithm (we call it 'Santa') decides if the grid is "good" or "bad".
</p></details>

**<details><summary>C#</summary><p>**
 
Software package for controlling Spotiton, a robotic liquid dispenser designed for freezing samples for cryo-electron microscopy. The software integrates and automates motion, video processing and logic control to guide the user efficiently through all the necessary steps for preparing a cryo-EM sample.

Link to publication: [A new method for vitrifying samples for cryoEM](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5464370/) 

Authors: **Ivan Razinkov**, Venkat Dandey, Hui Wei, Zhening Zhang, David Melnekoff, William J. Rice, Christoph Wigge, Clinton S. Potter, and Bridget Carragher

![](https://github.com/irazinkov/Portfolio/blob/master/spotiton%20screencap.png)

 - motion control for 6 axies
 - pneumatic control
 - digital I/O
 - image acquisition
 - video analysis(for motion correction)
 - liquid dispenser control and tuning
 </p></details>
 
**<details><summary>Java</summary><p>**
 
Software for control of a device called DAW, a system that dynamically changes fluid pressures inside a microfluidic device. It is used to dynamically expose cells (bacterial, yeast and mammallian) in a microfluidic device to changing chemical environment. For example, cells could be exposed to a metabolite (sugar), hormone (acyl-homoserine lactone) or even an antibiotic.
 
Link to publication: [Microfluidics for Synthetic Biology: From Design to Execution](https://www.ncbi.nlm.nih.gov/pubmed/21601093)

Authors: Michael Ferry, **Ivan Razinkov** and Jeff Hasty

Link to project website: [Dial-A-Wave](http://dialawave.wikispaces.com)

![](https://github.com/irazinkov/Portfolio/blob/master/daw_software.png)

 - capable of running up to 12 individual units simulatenously
 - longterm stable (>90 days)
 - installed in multiple science labs around the world
 - designed for long-term microfluidic experiments for evolution studies in yeast and bacteria
 
 </p></details>

# Hardware Projects
**<details><summary>Spotiton</summary><p>**

A novel sample preparation instrument for cryo-electron microscopy. Current commercial state of the art equipment is a replication of manual process of sample preparation. With Spotiton, the idea is to automate and create a high-throughput machine that would eliminate inconsistencies in sample freezing and speed up time from idea to 3D protein reconstruction. In this project i created the superhydrophilic copper nanowire grid, that allowed small drops of sample to hit the grid and within 100 milliseconds spread out to a thin liquid layer of 20-40 nanometers. This sample was then frozen in liquid ethane to obtain amorphous ice, instead of regular crystalline ice. Designed various components that made the final product as well as worked together with a mechanical engineer to complete everything. The robot has produced amazing results as is now being commercialized by TTP Labtech, a scientific equipment company in the UK.

Link to publication: [A new method for vitrifying samples for cryoEM](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5464370/) 

Authors: **Ivan Razinkov**, Venkat Dandey, Hui Wei, Zhening Zhang, David Melnekoff, William J. Rice, Christoph Wigge, Clinton S. Potter, and Bridget Carragher

 ![](https://github.com/irazinkov/Portfolio/blob/master/792-100-000%20spotiton%20v1.0%20deck%20assembly.jpg)
 
 ![](https://github.com/irazinkov/Portfolio/blob/master/20150529_110051.jpg)
</p></details>

**<details><summary>Fluorescence Sensor (w/ lock-in amplification)</summary><p>**
Although fluorescence sensors are nothing new, for the project algae wastewater treatment project shown below we needed a customizable fluorescence sensor that would be able to work in outdoor conditions. High sensitivity fluorescence microscopes required near-dark rooms for high quality imaging. Unfortunately, dark rooms are hard to find when you are in the middle of a 400-foot-long pond in the desert of Southern California. To bypass this roadblock, I designed a sensor with high-frequency modulation of the excitation source, which modulated the fluorescence output, by only reading the matching frequency you would get the real-time fluorescence signal. 
 
 ![](https://github.com/irazinkov/Portfolio/blob/master/enclosure.PNG)
 
 ![](https://github.com/irazinkov/Portfolio/blob/master/fluor3.png)

 - liquid tight enclosure with customizable emission/excitation filter
 - USB data logging
 - high-sensitivity, signal even in direct sunlight
 - AD630 Lock-in-Amplifier
 
</p></details>

**<details><summary>Bioluminescence Silicon PhotoMultiplier Sensor </summary><p>**
A monitoring system the size of your average shoebox, designed to monitor the health and toxicity of water reservoirs and streams. Genetically engineered bacteria strains would respond to chemicals in the water and produce and bioluminescence signal. We chose to go with a bioluminescence rather than fluorescence to minimize the number of optical components. Furthermore, advent of affordable [Silicon Photomultiplier](http://sensl.com/products/) elements increased the sensitivity of the device many fold, allowing the microfluidic device to be right on top of the sensor, with only a coverslip separating the cells from sensor. I was tasked with making designing the electronics for SiPM integration, logic control, battery charging, communication and peristaltic pump control. Below is a sample of the ARM-based microcontroller circuit design for this device.
 
![](https://github.com/irazinkov/Portfolio/blob/master/simp_due.png)
 
 - Silicon Photomultiplier sensor for detecting single photons emitted by bacteria cultured in microfluidics devices
 - Solar powered 
 - Intended for use in remote water ways for water supply quality testing
 - ARM32 core from ATMEL for control of power supply, peristaltic pump, 54 data I/O ports and data logging
 - Transmits sensor information through long-range WiFi

</p></details>

**<details><summary>Algae-based Dairy Wastewater Remediation Facility</summary><p>**
Clean energy solutions depend highly on the industry and geographic location. In sunny San Diego our approach to wastewater remediation on a dairy farm, was in form of a series of algae ponds. By controlling the geometry of each pond, we could tailor the biological processes to our needs. The diary wastewater is considered is rich in phosphate and nitrates (from manure) is normally stored for 90 days on site to allow the slow conversion of these chemicals. Our system utilized extremely fast-growing algae cultures that would use these chemicals as a food source, effectively cleaning the water. Furthermore, the solid waste from the dairy farm was utilized in the anaerobic digester, which provided bio-gas for electricity production. 
 
![](https://github.com/irazinkov/Portfolio/blob/master/vanO-farm.jpg)

Link to the Google Maps image: [Van Ommering Dairy Farm, Lakeside CA](https://www.google.com/maps/place/Van+Ommering+Dairy+Farm/@32.8840284,-116.8731092,195m/data=!3m1!1e3!4m5!3m4!1s0x80dbe1e7f99ca189:0x3c8ca246074a6110!8m2!3d32.8817067!4d-116.870681)

 - Design and construction of large-scale ponds
 - 2 raceway ponds with 2 large paddlewheels for algae culture agitation
 - 3 settling ponds
 - anaerobic digester (refurbished previous install)
 - worked with numerous construction crews to make sure timely project completion
 
Due to the high cost of large parts, everything was modeled and simulated for stress, deformation and safety factors.

Here is an example of the paddlewheel analysis:

![](https://github.com/irazinkov/Portfolio/blob/master/Result_1_2.png)

The complete report can be view here: [Paddlewheel Stress and Safety Report](https://github.com/irazinkov/Portfolio/blob/master/Stress%20Analysis%20Report.pdf)

</p></details>

**<details><summary>Microfluidics Hardware</summary><p>**

Link to project website: [Dial-A-Wave](http://dialawave.wikispaces.com)

![](https://github.com/irazinkov/Portfolio/blob/master/daw-wikispaces.PNG)

</p></details>
