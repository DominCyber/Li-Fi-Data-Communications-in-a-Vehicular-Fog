# Li-Fi Data Communications in a Vehicular Fog

## Objective
This Saint Leo University cornerstone project allow undergraduates to explore emerging trends within information technology. Undergraduates are to take any emerging trends of their choosing and examine a potential cross section of such trends that may benefit humanity. 

### Project 
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Li-Fi Data Communications in a Vehicular Fog</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Manuel R. Dominguez II</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Saint Leo University</p>

#### Introduction
<p>&nbsp;Our futures are moving in the direction of the ‘smart city’ environment.  This also means a more complex roadside environment with smart vehicles both man an unmanned. These vehicles are expected to be connected, in a ‘vehicular fog’. Vehicular fog is defined as a total data communications network between vehicles and roadside management systems (Lee et al., 2016). This network is comprised of multi-spectral and spatial smart sensors. However, these systems are susceptible to challenges. To introduce safety through security, it is proposed to introduce Li-Fi data communications between these vehicles and Roadside Devices (Lee et al., 2016). This will present various benefits in a roadside environment that has both automated vehicles and manned vehicles.</p>

#### Brief Component Explanation
<p><i>&nbsp;The Vehicular Fog Model, with emphasis on Autonomous Unmanned Vehicles (AUV’s)</i></p>
<p>&nbsp;At this moment, we employ smart, manned, vehicles, daily. Lee et al. mentions they are a formidable sensor platform (utilizing lidar, radar, EO, sonic, INS, GPS) absorbing information from the environment and feeding it to drivers and infrastructure to assist in safe navigation, pollution control, and traffic management. The next step in this evolution is just around the corner:  Autonomous Unmanned Vehicles. AUV’s interconnected in an Internet of Vehicles of sorts, a vehicular fog (Lee et al., 2016).</p>
<p>&nbsp;Lee et al. continues to explain that when these AUV’s have intentional smart-sensor use, cloud computing-processing, collaborative sharing of this spatial information, and a well-maintained network infrastructure, this will be called vehicular fog. The main goal is to promptly deliver passengers safely to their destinations (Lee et al., 2016).</p>
<p>&nbsp;The AUV’s have a constant receive-request-transmit of spatial data when departing dense urban areas, upwards to several kilometers to have a good course, in order to eventually join a fleet on a highway, where the vehicular fog is at this strength, and in communication with RSU’s on the road (Lee et al., 2016).</p>
<p>&nbsp;Lee, et al. proposes that vehicular fog will be an adhoc network among the vehicles in proximity, due to the vehicles leaving and joining networks frequently. For protocol and addressing functions, a content-naming host is utilized, instead of internet protocol address. Named data networking (NDN) is consider the model architecture for this format. This will theoretically give the AUV’s, within a vehicular fog, certain assignment sensory and data-processing duty among an adhoc fleet. Each AUV will have three categories of resources: data storage (supports data sharing between fog connected vehicles), sensors (all connected to the IoV to be read and controlled), and computing. Depending on proximity to an RSU, either one AUV on the fog can self-organize a local vehicular fog environment and assign roles (like data cache, etc.) to other vehicles around itself. Here, it is proposed to allow Li-Fi usage, so data-sharing clock speeds can be sped up.</p>
<img src="https://i.imgur.com/p84mwyh.png" style="width: 65%;" alt="1">
<p><i>Figure 1: Brief illustration of assets in a vehicular fog network (Lee et al., 2016)</i>i</p>
<p><i>&nbsp;Light Fidelity Data Communications in Brief</i></p>
<p>&nbsp;Light Fidelity, or Li-Fi, is a visible light communications technology. It is a bidirectional and fully networked wireless communications medium which uses light from light-emitting diodes (LEDs) and provides transmission of data through illumination by sending data through a LED light bulb that varies in intensity faster than the human eye can follow (Yeasmin et al., 2016). This varying intensity, in nanoseconds, is how data is transmitted, in a binary format.  The light bandwidth can be measured at multiple tera-hertz, at 10 Gbps (Hernandez-Oregon et al., 2019). Visible light has ten thousand times more real estate on the Electromagnetic Spectrum than radio frequency energy, x-rays, or gamma-rays (Hernandez-Oregon et al., 2019; Islim et al., 2018). The Visible light bandwidth measures in the range of 380-750 nanometers (Hernandez-Oregon et al., 2019).  With a small microchip, and the presence of a receiver, any of the 14 plus billion lightbulbs worldwide could be made in a transmitter (Haas, 2011). The receiver is only interested in subtle data changes, so other light sources won’t affect it much (Haas, 2011). However, in sunlight may pose small amount of interference as ‘shot noise’, but not outright interference (Islim et al., 2018).</p>
<img src="https://i.imgur.com/cEiWoaE.jpg" style="width: 65%;" alt="1">
<p><i>Figure 2:  Li-Fi Working mechanism (Yeasmin et al., 2016).</i></p>
<p>&nbsp; Hernandez-Oregon0 et al. have successful conducted a viable study that used a traffic light server model that then transmits pertinent data to queues of stationary cars, that in turn transmits data from head-to-taillight fashion through said queue (Hernandez-Oregon et al., 2019).</p>

#### Possible Benefits of Li-Fi in Vehicular Fog
<p>&nbsp;According to Hernandez-Oregon et al., Li-Fi in vehicular communications could be a low-cost, high-data-rate, and provide efficient-bandwidth usage solution.  The study provided in the next section, make note that diverse information can be downloaded to vehicles like traffic infractions enforcements can be transmit a vehicle users’ average speed or traffic violations in previous streets and other types of situational information pertaining to parking spaces, cultural events, weather conditions (rain, fog, or ice), city driving conditions, traffic jams, roads in construction, weather, pollution, relevant news and even commercial sales in specific points of the city that can affect driving (Hernandez-Oregon et al., 2019).</p>
<p>&nbsp;Lastly, a small research effort conducted by Yeasmin et al. (2016) explained there are traffic law enforcement benefits, in the form of an installed system, that communicates through Li-Fi-enabled headlights, consisting of arduino microcontrollers, photo interrupters and optical sensors to capture manned vehicle speeds, process a speeding infraction and promptly slow said vehicle down . They also mention that speed controls can be facilitated in the ‘fleet model’ as well.  With ultrasonic sensors for detecting proximation, offending vehicles can be sent a slowdown command if too close (Yeasmin et al., 2016).</p>

#### Study
<p>&nbsp;The study conducted by Hernandez-Oregon et al. focused exclusively on resting traffic at traffic lights, were the traffic light will act like a server. Here, the first vehicles in the resting queue with receive data packets from traffic lights, through the headlights, and transfer thereafter into a computer and data transfer bus to the taillights to the vehicles behind itself, until the last vehicle in the queue, or the queue starts to move again. The Data transferred is intended for both vehicles and passengers (Hernandez-Oregon et al., 2019).</p>
<p>&nbsp; Angle of influence of vehicle-related Li-Fi LEDs are as follows: Traffic lights were estimated to irradiate targets in the tens of watts with a range of 30 meters in a cone coverage of 10 meters. Headlights were estimated to transfer data over a 300-meter range, in a cone coverage of 20 meters (Hernandez-Oregon et al., 2019).</p>
<p>&nbsp; The study’s computational data is as follows; Li-Fi system has OOK modulation and Manchester codification with a clock speed of 200 kHz that would provide 24.44 kbps. The study considered two data packet sizes: Ethernet packets at 1500 bytes and Jumbo frame packets at 9000 bytes. Successful downloading of data packets data rate transmission is 11.67 kbs, where 16 ethernet packet frames would cover all vehicles in a queue (Hernandez-Oregon et al., 2019).</p>
<p>&nbsp; The study proposes that longer waiting periods would benefit data transfer at a red-light traffic scenario. Though that would very well lead to traffic jams (Hernandez-Oregon et al., 2019).</p>
<p><i>&nbsp;Limitation of Study</i></p>
<p>&nbsp;This study conducted by Hernandez-Oregon et al. had rational limitations, focusing on static is the worst-case scenario of data transfer, thus focus on the traffic light server model. The study was assumed an error-free communication environment with vehicles perfectly aligned, spaced and not moving. Other limitations included not considering moving vehicles in green-traffic light crossing, or U turn situations, which the researcher will assess in future studies (Hernandez-Oregon et al., 2019).</p>

#### Challenges
<p>&nbsp; Lee et al. addresses that smart vehicles on the road during natural catastrophes sudden like an earthquake, must be able to coordinate the evacuation of critical areas in a rapid and orderly manner.  If a vehicular fog model holds true, then loss of communications among vehicles to RSU’s would prompt an immediate localization of data management duties and eventual slowdown of traffic. Its suggested to have protocols to allowing emergency response vehicles access to an AUV dense road (Lee et al., 2016).</p>
<p>&nbsp;Cybersecurity concerns are ever present with AUV’s in a vehicular fog. Where normal concerns like disabling of the steering or the brake system, its proposed that an AUV’s network and computer systems exercise common cybersecurity requirements: confidentiality, integrity, privacy, and authentication in the face of adversity.  Loss of control for an AUVs OS would be disastrous, because there is no driver on instant standby. Protection from attacks both external (from access points or from conventional vehicles) as well as internal (from other AUVs) must be designed with stricter standards (Lee et al., 2016), even in the presence of Li-Fi. Accessing to internal mechanism and possibly to on-board diagnostics (OBD) and CAN bus must be allowed when the AUV is out of control because of either internal malfunctioning or malicious attack. proper enforcement of access control emerges as a first-line protection strategy in the vehicular fog.  Botnet IoT, Denial of Service, RF jamming of wireless mediums are just a few challenges facing AUV’s in a vehicular fog. Moreover, the communications must be secure to prevent malicious attacks that in the case of AUVs could be literally deadly since there is no standby control and split-second chance of intervention by the driver (who may be surfing the web) (Lee et al., 2016).  A dedicated army of transparent and highly skilled cybersecurity specialists, software engineers, and system administers can be employed to combat these issues with constant IoV system-software and cloud computing upgrades.</p>
<p>&nbsp;Li-Fi systems in the presence of solar irradiance ‘shot noise’ reduces the data rate of Li-Fi systems. However, optical bandpass blue filters can limit the degradation caused by solar irradiance. Data rates above 1 Gb/s were experimentally achieved in the presence of solar irradiance without optical filtering. Simulation results have shown that an improvement of at least 6.47 dB can be achieved for SNR using off-the-shelf blue filters (Islim et al., 2018).</p>

#### Conclusion
<p>&nbsp;In this report, the proposal to add Light Fidelity data communications into the plans of vehicle grid conversion to a vehicular fog was explored, and proven very possible, at least if implemented to queues’ of traffic at rest, at a traffic light, where it has been converted into a Li-Fi server. Here, pertinent and diverse data can be displayed to drivers on the road. Applications for AUV’s in a vehicular fog environment, were heavily considered.</p>
<p>&nbsp;Benefits, challenges and their possible mitigation were explored as well. This addressed just about every general roadside issue that may cause issues to any component in the vehicular fog architecture.</p>
<p>&nbsp;Future studies will include the use of Li-Fi data communications, in the vehicular fog, for moving vehicles, with an emphasis on ‘fleets’ AUV’s and vehicles in a motion in and around a traffic light server.</p>

#### Citations
<p>Annotated Bibliography</p>
<p>1) Haas, H. (2011, Aug. 2) Wireless data from every lightbulb. Retrieved from https://www.youtube.com/watch?v=NaoSp4NpkGg </p>
<p>2) Hernandez-Oregon, G., Rivero-Angeles, M., Chimal-Eguía J., Campos-Fentanes, A.,  Jimenez-Gallardo, J., Estevez-Alva, U., Juarez-Gonzalez, O., Rosas-Calderon, P., Sandoval-Reyes, S., Menchaca-Mendez, R., (2019, Aug. 23) Performance Analysis of V2V and V2I LiFi Communication Systems in Traffic Lights 
Retrieved form https://www.hindawi.com/journals/wcmc/2019/4279683/</p>
<p>3) Yeasmin, N., Zaman, R., Mouri, I., (2016, Aug.) Traffic Control Management and Road Safety Using Vehicle To Vehicle Data Transmission Based on Li-Fi. Retrieved from http://aircconline.com/ijcseit/V6N4/6416ijcseit01.pdf</p>
<p>4) Lee, E., Gerla, M., Rau, G., Lee, U., Lim, J., (2016, Sep. 6) Internet of Vehicles: From intelligent grid to autonomous cars and vehicular fogs. Retrieved from https://journals.sagepub.com/doi/10.1177/1550147716665500</p>
<p>5) Islim, M., Videv, S., Safari, M., Xie, E., McKendry, J., Gu, E., Dawson, M., Haas, H., (2018, Jun. 15) The Impact of Solar Irradiance on Visible Light Communications
Retrieved from https://ieeexplore.ieee.org/document/8309381
</p>
