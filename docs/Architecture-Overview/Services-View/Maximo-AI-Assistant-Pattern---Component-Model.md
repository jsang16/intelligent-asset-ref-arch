---
tags:
    - AOD-Svc
---

#  Maximo AI Assistant Pattern - Component Model




![Maximo AI Assistant Pattern - Component Model](../../../img/aodservices_4zkPguMTpkU_BtQWIkjwL.svg)








## Element(s)




### Actor(s)

| Name | Description | Type | GenericGroup |
| --- | --- | --- | --- |
| MAS User-uploaded | <p>The Maximo Application Suite allows users to sign on to a single, integrated platform to access key monitoring, maintenance, and reliability applications across the business. Not only does it help remove data silos, it enhances data sharing with integrated user experience and shared administrative controls for enterprise-scale execution. With a new Committed Term License, businesses can access the entire suite with one single entitlement. Users in the organization will have a pool of AppPoints that will allow them to seamlessly move from one application to another, as needed. This enables organizations to pay for only what they use. You can try and deploy new applications without substantial license and administration costs. It also allows your team to deploy new capabilities and grow as well as share industry specific Digital Twin assets and modules.</p> | Human | <div><strong>SubSystem,Maximo Application Suite Core</strong>[Auto-Generated]</div><div>This group is derived from SubSystem named Maximo Application Suite Core.</div> |





### Subsystem(s)

| Name | Description | Sub-Diagram |
| --- | --- | --- |
| Container Runtime |  |  |
| Maximo Application Suite |  |  |
| Watsonx |  |  |





### Logical Component(s)

    

<details markdown=1>
<summary markdown="span">Actions</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Actions</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Provides the functionality to react to cretain actions within the AI Assistant</p></td>
    </tr>
</table>
</details>


    

<details markdown=1>
<summary markdown="span">Health-uploaded</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Health-uploaded</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Manage the health of your assets using IoT data from asset sensors, asset records and work history to increase asset availability and improve replacement planning. Get a true view of asset health via dashboard displays to provide evidence to base operational decisions.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Functional Requirement</strong> </td>
        <td><div>MAS Health-uploaded - Maximo Application Suite: Health Functional Requirement-uploaded</div></td>
    </tr>
</table>
</details>


    

<details markdown=1>
<summary markdown="span">Manage-uploaded</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Manage-uploaded</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Reduce downtime and costs by optimizing asset management and maintenance processes to improve operational performance. Leverage embedded industry expertise with best-practice data models and workflows to accelerate your industry transformation. Unify asset management processes using role-based workspaces to help teams across your enterprise. Unify robust asset life cycle and maintenance management activities, providing insight into all enterprise assets, their conditions and work processes to achieve better planning<br>and control.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
    <tr>
        <td> <strong>Functional Requirement</strong> </td>
        <td><div>MAS Manage WOI - AI: Work Order Intelligence</div><div>MAS Manage-uploaded - Maximo Application Suite: Manage Functioanl Requirement-uploaded</div></td>
    </tr>
</table>
</details>


    

<details markdown=1>
<summary markdown="span">MAS User Interface</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>MAS User Interface</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>USer Interface for the MAS suite of applications</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
</table>
</details>


    

<details markdown=1>
<summary markdown="span">Maximo AI Assistant</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Maximo AI Assistant</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Maximo AI Assistant Provides capabilities to allow for determining asset health, examining the work orders for the asset and the creation of work orders for remedying unhealthy assets all through a natural language interface</p></td>
    </tr>
</table>
</details>


    

<details markdown=1>
<summary markdown="span">Maximo Assistant Embedding Code</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Maximo Assistant Embedding Code</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Code to embed the MAximo AI Assistant into the Maximo Application Suite User Interfaces</p></td>
    </tr>
</table>
</details>


    

<details markdown=1>
<summary markdown="span">Maximo Custon Extension</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Maximo Custon Extension</td>
    </tr> 
</table>
</details>


    

<details markdown=1>
<summary markdown="span">Maximo Skill Service</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Maximo Skill Service</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>Provides the capability to interact with the manage and health applications via the OSLC service that they provide</p></td>
    </tr>
</table>
</details>


    

<details markdown=1>
<summary markdown="span">Maximo Skill Service OpenAPI specification</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Maximo Skill Service OpenAPI specification</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>The OpenAPI Specification for the servceis provided by the Maximo Skill Service component</p></td>
    </tr>
</table>
</details>


    

<details markdown=1>
<summary markdown="span">Watsonx.orchestrate</summary>

<table>
    <caption></caption>
    <tr>
        <td> <strong>Name</strong> </td>
        <td>Watsonx.orchestrate</td>
    </tr> 
    <tr>
        <td> <strong>Description</strong> </td>
        <td><p>IBM watsonx Orchestrate, powered by LLMs, is here to help by bringing generative AI and automation to every business domain across the enterprise.</p><ul><li>Delivers conversational AI and automation capabilities to transform how work gets done while increasing productivity, lowering costs and improving agility.</li><li>It's personalized with the skills to support the work of your teams, using the tools they already use.</li><li>Use purpose-built AI assistants for quick and easy task completion and complex processes facilitated  by engaging natural language experience</li><li>Empower domain experts to create customized AI assistants with a low-code builder, supporting diverse enterprise functions like HR, Finance, Sales, and Procurement.</li></ul><p>Build your AI assistant with Orchestrate to streamline your team's efforts and reclaim your day.</p></td>
    </tr>
    <tr>
        <td> <strong>Primary Capability</strong> </td>
        <td><div>application</div></td>
    </tr>
</table>
</details>


    




### Logical Connector(s)






All connectors are not named.

    




