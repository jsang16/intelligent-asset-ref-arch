---
tags:
    - AOD-ITS
---

#  Deployment Overview




![Deployment Overview](../../../img/aoditsystem_3TjRTod70HB_S1LsE5rUo.svg)











## Element(s)




### Actor(s)

| Name | Description | Type | GenericGroup |
| --- | --- | --- | --- |
| 3rd Party System | <p>Third party applications external to Maximo Application Suite Core</p> | IT System |  |
| Weather System | <p>The weather system provides weather information, tracks patterns, and predicts trends.</p> | IT System |  |





### Subsystem(s)


| Name | Description | Sub-Diagram |
| --- | --- | --- |
| Applications | IBM Maximo Safety enables companies to establish safer working environments by providing safety insights for proactive protection with personalized risk assessment and near real-time protection. These insights and protection can minimize workplace hazards. |  |
| Cloud Pak 4 Data | <div>One prerequisite, which must run in the Red Hat OpenShift cluster is the Cloud Pak for Data. </div><div><br></div><div>Cloud Pak for Data consists of a control plane, which has its own user interface and its own set of authorized users. After you install Cloud Pak for Data into Red Hat OpenShift cluster and you log in as an administrator, you can install one or more Cloud Pak for Data services into the Red Hat OpenShift cluster. In particular, you can use it to install the DB2 Warehouse that is used by the Maximo Monitor and IoT applications. </div><div><br></div><div>The Maximo Application Suite license entitles you to install and use a number of theCloud Pak for Data services, provided you are using them with Maximo Application Suite applications.</div><br> |  |
| Maximo Application Suite Core | Start by installing a control plane, Maximo Application Suite core, into Red Hat OpenShift cluster. Use Maximo Application Suite core to install and manage the Maximo Application Suite applications, industry solutions, and add-ons that you want to use. Maximo Application Suite core maintains a registry of users. You can specify which users are to be permitted to access which Maximo Application Suite applications. |  |
| Maximo Application Suite Prerequisites | Maximo Application Suite applications have several dependencies or prerequisites. Some of these are required regardless of which applications you use, others are use by specific applications. Choose whether to deploy prerequisites in the Red Hat OpenShift cluster or run them externally,either in a separate Red Hat OpenShift cluster, or by using an external service provider. |  |
| OpenShift | The Red Hat OpenShift Container Platform cluster is managed by a set of master nodes. These master nodes run the Kubernetes cluster control software, managing what runs on the other nodes in the cluster (the worker nodes). The master nodes also maintain an internal database (etcd) of containing the Kubernetes resource definitions. To ensure continuous and high availability of the Red Hat OpenShift Container Platform cluster uses a minimum of three master nodes. <br> |  |






### Location(s)

| Name | Description |
| --- | --- | 
 | Client Network |  |
 | Platform | cloud or on-prem |
 | Public Network |  |








### Logical Connection(s)






All connections are not named.

    




### Logical Node(s)

    

<details markdown=1>
<summary markdown="span">Enterprise Assets</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Enterprise Assets</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Enterprise Assets are a company's physical capital investments used for production.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>iot</div>
                <div>IoT</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">App Connect</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>App Connect</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Use App Connect to connect your different applications and make your business more efficient. Set up flows that define how data is moved fromone application to one or more other applications. App Connect supports a range of skill levels and interfaces, giving you the flexibility to create integrations without writing a single line of code. You can use a web user interface or drop resources into a toolkit that gives a broader range of configuration options. Your entire organization can make smarter business decisions by providing rapid access, visibility, and control over data as it flows through your business applications and systems from a single place - App Connect.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>api management</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Maximo Application Suite Prerequisites</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Maximo Application Suite Prerequisites.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
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
        <td><p>Maximo Assist helps to reduce the time that is required to diagnose and repair equipment problems, improves first-time fix rates, improves diagnosis accuracy, and drives higher levels of technician productivity.  </p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Applications</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Applications.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">CAD Files</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>CAD Files</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>CAD (computer-aided design) files are digital files that house 3D &amp; 2D designs as well as information regarding materials, processes, tolerances, and other data.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>source</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">CouchDb</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>CouchDb</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>CouchDB is embedded and automatically deployed with Maximo Assist. You do not have to manually install it.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>NOSQL</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Maximo Application Suite Prerequisites</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Maximo Application Suite Prerequisites.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Database</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Database</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Asset data</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>data</div></td>
    </tr>
    <tr>
        <td> <strong>Implementation</strong> </td>
        <td>
                <div><a href="">DB2 Warehouse</a></div>
                <div><a href="">Oracle</a></div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,MAS</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named MAS.</div>
                <div><strong>SubSystem,Maximo Application Suite Core</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Maximo Application Suite Core.</div>
                <div><strong>SubSystem,Maximo Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Maximo Application Suite.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
        <tr>
        <td> <strong>Related Elements</strong> </td>
        <td>
                <div>SYS_DU_3V0vmL2m4je</div>
                <div>SYS_DU_3V0vmL0r2yw</div>
        </td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">DB2 Warehouse</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>DB2 Warehouse</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>IBM Db2 Warehouse is an analytics data warehouse that features in-memory data processing and in-database analytics. The Cloud Pak for Data control plane is not required to install Db2; alternatively, the Db2U operator can be installed standalone. For  					Maximo Application Suite users that require Maximo Predict or Maximo Assist applications Cloud Pak for Data is required to install the Watson Studio or Watson Discovery dependencies.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>warehouse</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Cloud Pak 4 Data</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Cloud Pak 4 Data.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Discovery</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Discovery</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Watson Discovery for Cloud Pak for Data is an award-winning AI-powered intelligent search and text-analytics platform that helps you find valuable information that is buried in your enterprise data. Discovery uses innovative, market-leading natural language processing to uncover meaningful insights from complex business documents.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>discovery</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Cloud Pak 4 Data</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Cloud Pak 4 Data.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
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
        <td><p>With Maximo Health, you can review your assets’ performance and condition indicators, such as the last failure date and the maintenance-to-replacement ratio (MRR),and take action by creating work orders and service requests. You can use work queues to improve the quality of your asset’s details and related data. You can also configure scoring for assets’ health,criticality, and risk.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Applications</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Applications.</div>
                <div><strong>SubSystem,Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Application Suite.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Integration & Connection Services</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Integration & Connection Services</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Most applications require access to data or computations that are provided by another system, or applications need to respond to requests from other systems for data or computations. The approaches, technologies, and facilities that support accessing data are collectively known as integration and connection services.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>integration</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Kafka</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Kafka</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Apache Kafka provides a buffer for messages sent to and received from externalinterfaces. Apache Kafka is not required if the IBM® Maximo® Manage software is notinterfacing with external systems.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>event streaming</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Maximo Application Suite Prerequisites</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Maximo Application Suite Prerequisites.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Location Files</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Location Files</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>The location of files is where digital files [for example, documents, drawings, images, videos, maintenance records, etc.] related to the assets are stored.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>source</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
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
        <td><p>Maximo Manage provides a comprehensive view of all asset types, their conditions and locations, and the work processes that support them, to provide you with optimal planning, control, audit, and compliance capability.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Application Suite.</div>
                <div><strong>SubSystem,Applications</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Applications.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">ML</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>ML</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Watson Machine Learning provides a full range of tools and services so that you can build, train, and deploy Machine Learning models. Choose the tool with the level of automation or autonomy that matches your needs, from a fully automated process to writing your own code.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>machine learning</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Cloud Pak 4 Data</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Cloud Pak 4 Data.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
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
        <td><p>IBM Maximo mobile solutions deliver remote and AI-based expert assistance, real-time asset history and operational data from wearables, safety sensors and diagnostic interfaces to the digital twin.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Applications</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Applications.</div>
                <div><strong>SubSystem,Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Application Suite.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">MongoDB</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>MongoDB</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Maximo® Application Suite uses MongoDB for its data dictionary and local user management. Your MongoDB instance can run in the Red Hat® OpenShift® cluster or external toit.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>NOSQL</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Maximo Application Suite Prerequisites</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Maximo Application Suite Prerequisites.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
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
        <td><p>By using Maximo® Monitor, business users can visualize current and historical trend data for their devices and assets in customizable dashboards. Users can drill down through layers from a system-wide view to individual assets and devices. Analytic functions are applied to input data, and the output is displayed on value cards, tables,images, line graphs, and alert tables.<br>Anomaly detectors run on the input data to detect outliers, gaps, and flat lines in the data and fire alerts. The anomalous data points are highlighted on line graphs.<br><br><br><br><br></p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Application Suite.</div>
                <div><strong>SubSystem,Applications</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Applications.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Operational Conditions</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Operational Conditions</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>External data sources can be synchronized with a Data Lake for access by the Analytics Services to create models for asset monitoring, health analysis, optimization and prediction of operational issues.<br></p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>information governance</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
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
        <td><p>Maximo Predict uses historical and near real-time asset performance data, maintenance records, inspection reports, and environmental data to correlate performance factors that predict asset degradation or failure. Maximo Predict uses artificial intelligence to optimize predictive model accuracy.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Application Suite.</div>
                <div><strong>SubSystem,Applications</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Applications.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
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
        <td><p>IBM Maximo Safety enables companies to establish safer working environments by providing safety insights for proactive protection with personalized risk assessment and near real-time protection. These insights and protection can minimize workplace hazards.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Applications</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Applications.</div>
                <div><strong>SubSystem,Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Application Suite.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Studio</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Studio</td>
    </tr>
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Watson Studio provides the environment and tools for you to collaboratively work on data to solve your business problems. You can choose the tools you need to analyze and visualize data, to cleanse and shape data, to ingest streaming data, or to create and train machine learning models.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>analytic & ai</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Cloud Pak 4 Data</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Cloud Pak 4 Data.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    

<details markdown=1>
<summary markdown="span">Train Model</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Train Model</td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>machine learning</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,MAS</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named MAS.</div>
                <div><strong>SubSystem,Maximo Application Suite Core</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Maximo Application Suite Core.</div>
                <div><strong>SubSystem,Maximo Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Maximo Application Suite.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
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
        <td><p>IBM® Maximo Visual Inspection is a machine-learning application for video and image analysis. IBM Maximo Visual Inspection offers built-in deep learning models that learn to analyze images and video streams for classification and object detection.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td>
                <div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Generic Group</strong> </td>
        <td>
                <div><strong>SubSystem,Application Suite</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Application Suite.</div>
                <div><strong>SubSystem,Applications</strong>[Auto-Generated]</div>
                <div>This group is derived from SubSystem named Applications.</div></td>
    </tr>
    <tr>
        <td> <strong>Related Diagrams</strong> </td>
        <td>
                <div><a href="../../../Architecture-Overview/IT-System-View/Deployment-Overview">Deployment Overview</a></div></td>
    </tr>
</table>
</details>
    





