---
tags:
    - AOD-Ent
---

#  Intelligent Asset Reference Architecture




![Intelligent Asset Reference Architecture](../../../img/aodenterprise_3T35EJcGRGw_S1LsE5rUo.svg)






### Reference(s)

    
        
[Intelligent Asset Inspection](https://w3.ibm.com/tools/cogarch/architectures/Collaboration/arch_BJPQhnWzh/itsystem/artifacttype_355f72be-6566-3f48-8b15-c30f671d7c8f/aoditsystem_3T7yfIgjHIh/w)
        
    




## Element(s)




### Actor(s)

| Name | Description | Type | GenericGroup |
| --- | --- | --- | --- |
| ADVANTECH | <p>Advantech IoT Edge Gateways help bridge data from edge devices to the cloud, acting as protocol converters, data collectors, or data loggers.</p> | IT System |  |
| Aviation Asset | <p>Assets from the Aviation Facilities</p> | IT System |  |
| Building Asset | <p>Assets from the Commercial and Industrial Buildings</p> | IT System |  |
| CISCO | <p>CISCO edge device collects and processes data from sensors and other IoT devices at the network's edge before transmitting that data to a central system for analysis and processing.</p> | IT System |  |
| Civil & Infrastructure Asset | <p>Assets from the Cil and Infrastructure Facilities</p> | IT System |  |
| Control System | <p>A control system uses sensors and actuators to monitor and control the operation of a system or process. Control systems also can be used to automatically adjust the operation of a system based on predetermined set points, as well as to respond to changes in the environment or to commands from operators.</p> | IT System | <div><strong>SubSystem,Maximo Application Suite Core</strong>[Auto-Generated]</div><div>This group is derived from SubSystem named Maximo Application Suite Core.</div> |
| Energy & Utility Asset | <p>Assets from the Energy &amp; Utility Facilities</p> | IT System |  |
| FLUKE | <p>Fluke enables its devices to connect to the internet and transmit data to the cloud or on-premise systems for analysis and processing.</p> | IT System |  |
| HARTING | <p>HARTING edge devices collect and process data from sensors and other IoT devices at the edge of a network before transmitting that data to a central system for analysis and processing.</p> | IT System |  |
| HILSCHER | <p>HILSCHER gateways help aggregate, process, or transmit IoT information of your production process completely autonomously to a central system for analysis and processing.</p> | IT System |  |
| Life Science Asset | <p>Assets from the Life Science Facilities</p> | IT System |  |
| Manufacturing Asset | <p>Assets from the Manufacturing Facilities</p> | IT System |  |
| Oil & Gas Asset | <p>Assets from the Oil and Gas Facilities</p> | IT System |  |
| Omnio | <p>Omnio Edge is a middleware application that runs on gateways connected to your gateways.</p> | IT System |  |
| OSISOFT | <p>OSIsoft provides lightweight data collection, storage, and access to edge devices and other IoT devices at the edge of a network before transmitting that data to a central system for analysis and processing.</p> | IT System |  |
| Sensors | <p>IoT sensors are pieces of hardware that detect changes in an environment and collect data.  The type of IoT sensors include:  temperature sensors, proximity sensors, pressure sensors, water quality sensors, chemical and gas sensors, infrared sensors, smoke sensors, motion sensors, and optical sensors to name a few.</p> | IT System | <div><strong>SubSystem,Maximo Application Suite Core</strong>[Auto-Generated]</div><div>This group is derived from SubSystem named Maximo Application Suite Core.</div> |
| TELIT | <p>TELIT edge devices collect and process data from sensors and other IoT devices at the edge of a network before transmitting that data to a central system for analysis and processing.</p> | IT System |  |
| Transportation Asset | <p>Assets from the Transportation Facilities</p> | IT System |  |





### Subsystem(s)

| Name | Description | Sub-Diagram |
| --- | --- | --- |
| AI & Analytics Services | The AI &amp; Analytics layer allows customers to sift through their asset data points and extract valuable insights.<br> |  |
| Application Suite | A comprehensive set of software applications designed to help organizations manage their physical assets, optimize operations, and improve productivity and efficiency. |  |
| Asset | Physical items or equipment that are essential to the operations of the facility. |  |
| Control System | A control system monitors and controls a system's operation or process using sensors and actuators.  |  |
| Data | The data layer will help to store, standardize and normalize data in a meaningful way that asset management applications can consume. |  |
| Edge | Edge devices collect and process and transmit data from sensors and other IoT devices. |  |
| Integration | The integration layer enables the exchange of data and information to optimize asset management.  |  |
| Sensors | A device measures physical or environmental conditions in a building or facility.  |  |






### Logical Component(s)



<details markdown=1>
<summary markdown="span">Analytics Engine</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Analytics Engine</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Analytics engines analyze data from various systems to optimize overall asset performance and management.</p></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Analytics Studio</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Analytics Studio</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Templates for detecting anomalies and predicting asset failures of assets</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>analytic & ai</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Application Connection Services</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Application Connection Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Connect applications and data with prebuilt smart connectors.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>api management</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Assist</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Assist</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Provide technicians with AI-powered guidance through a knowledge base of equipment maintenance data and gives them remote access to experts for assistance. Using an intuitive mobile interface, technicians can diagnose equipment problems, find recommended solutions, and collaborate with experts to resolve problems.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Data Dictionary</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Data Dictionary</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Catalog and communicate the structure and content of data, and provides meaningful descriptions for individually named data objects.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>metastore</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Data Lake Services</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Data Lake Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Centralized repository that allows you to store all structured and unstructured data at any scale.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>data lake</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Data Synchronization</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Data Synchronization</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Synchronizing organization, site, asset, and location data from Maximo Manage to the data dictionary</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>data</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Device Connection Services</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Device Connection Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>IoT device message broker for device registration, IoT data management, and IoT device management. Connect and control IoT devices. Provides secure communication to and from your devices by using MQTT and TLS.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>integration</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Health</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Health</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Manage the health of your assets using IoT data from asset sensors, asset records and work history to increase asset availability and improve replacement planning. Get a true view of asset health via dashboard displays to provide evidence to base operational decisions.</p></td>
    </tr>
    <tr>
        <td> <strong>Functional Requirement</strong> </td>
        <td><div>MAS Health - Maximo Application Suite: Health Functional Requirement</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Industries</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Industries</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Industry applications include:  (1) Energy and Utilities: Create efficient, reliable, sustainable utility operations. Learn how you can calculate potential impacts to the grid, monitor asset health, anticipate failures and better plan maintenance procedures. (2) Oil and gas: Create safer, more efficient and reliable operations. Learn how you can improve maintenance practices and plans, enhance HSE practices and rise above the commoditization of products. (3) Manufacturing: Jumpstart your Industry 4.0 transformation, get peak performance from your manufacturing assets, and reduce defects and downtime. Learn how you can create more sustainable operations. (4) Travel and Transportation: Keep everyone and everything moving by improving the productivity of your assets. Learn how you can manage assets and maintenance to meet safety, regulatory and customer demands. (5) Government:  Improve safety and better monitor critical infrastructure. Learn how you can manage assets, make faster, smarter decisions and balance citizen expectation with leaner operations.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Information Management Services</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Information Management Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Information management service that supports transaction processing.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>data</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">IoT Platform & Data Pipelines</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>IoT Platform & Data Pipelines</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Provides device connectivity, data filtering and mapping, and device management.  Add metric data that IoT monitoring systems gather from sensor devices to meters.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>information model</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Manage</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Manage</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Reduce downtime and costs by optimizing asset management and maintenance processes to improve operational performance. Leverage embedded industry expertise with best-practice data models and workflows to accelerate your industry transformation. Unify asset management processes using role-based workspaces to help teams across your enterprise. Unify robust asset life cycle and maintenance management activities, providing insight into all enterprise assets, their conditions and work processes to achieve better planning<br>and control.</p></td>
    </tr>
    <tr>
        <td> <strong>Functional Requirement</strong> </td>
        <td><div>MAS Manage - Maximo Application Suite: Manage Functioanl Requirement</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Message Services</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Message Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>The message services provides the configuration of the Java Message Serve resources for scalability and the configuration of  the messaging engines for highly availability.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>messaging</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Mobile</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Mobile</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Manage any asset, anytime, any place. Built on next generation mobile technology, Maximo Mobile boosts productivity by giving field technicians the power to easily navigate a single, intuitive platform and find the right asset history and operational data —even in the most remote locations, online or offline—all in the palm of their hand.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Monitor</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Monitor</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Improve asset and operational availability with advanced AI-powered remote asset monitoring at scale. Collect data from your existing OT systems, an converge your IT systems and operational systems in a single data lake to detect anomalies.</p></td>
    </tr>
    <tr>
        <td> <strong>Functional Requirement</strong> </td>
        <td><div>MAS Monitor - Maximo Application Suite: Monitor Functional Requirements</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Partner or Enterprise-developed</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Partner or Enterprise-developed</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Highly customizable and extensible Maximo applications developed by business partners will provide new capabilities and integrations to meet customer-specific business needs.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Predict</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Predict</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Go beyond time-scheduled maintenance to condition-based action to predict the likelihood of future failures by applying machine learning and data analytics to reduce cost and asset failures. Build on the power of other Maximo capabilities and Watson Studio to make data-driven decisions and build predictive models.</p></td>
    </tr>
    <tr>
        <td> <strong>Functional Requirement</strong> </td>
        <td><div>MAS Predict - Maximo Application Suite: Predict Functional Requirement</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Rules & Alerts</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Rules & Alerts</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Rules and alerts engine helps customers identify and address potential issues with their assets on time, reducing downtime and maintenance costs.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>analytic & ai</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Safety</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Safety</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Transform business models by integrating work, asset management, and health and safety functions. Help businesses improve operational efficiency and effectiveness, and help businesses meet their safety requirements and regulatory and compliance standards.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Schedule</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Schedule</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Transform business models by integrating work, asset management, and health and safety functions. Help businesses improve operational efficiency and effectiveness, and help businesses meet their safety requirements and regulatory and compliance standards.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Secure Integration</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Secure Integration</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>The integration layer consists of adapters, enterprise services, and publish channels. Use adapters to group enterprise services and publish channels to meet your transaction needs. With enterprise services and publish channels, you can receive data from and send data to multiple external systems and applications.</p></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Visual Inspection</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Visual Inspection</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Perform a visual inspection of the line or asset using commercial, off-the-shelf iOS devices to get immediate, actionable notifications of any emerging issue. Scale easily to view multiple points 24/7 including global views of all plants and geographies. Integrate with maintenance and quality workflows for a fast and prescriptive response.</p></td>
    </tr>
    <tr>
        <td> <strong>Functional Requirement</strong> </td>
        <td><div>MAS Visual Inspection - Maximo Application Suite: Visual Inspection Functional Requirements</div></td>
    </tr>
</table>
</details>
    








