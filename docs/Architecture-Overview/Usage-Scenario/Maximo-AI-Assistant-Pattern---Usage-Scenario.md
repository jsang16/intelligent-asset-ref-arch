---
tags:
    - AOD-Usage
---

#  Maximo AI Assistant Pattern - Usage Scenario




![Maximo AI Assistant Pattern - Usage Scenario](../../../img/aodusagescenario_4zl9Uh0xBia_BtQWIkjwL.svg)














## Step List

| Name | Description |
| --- | --- | 
 | 1 | <p>The Maximo Skill Service is deployed to a container runtime (podman/docker/kubernetes)</p> |
 | 2 | <p>A new assistant the Maximo AI Assistant is developed using the Watsonx.orchestrate capability</p> |
 | 3 | <p>The actions of the new assistant are configured to forward requests to the newly created Maximo Custom extension</p> |
 | 4 | <p>The Maximo Skill Service OpenApi specification is obtained from the developers of the skill service</p> |
 | 5 | <p>The Maximo Custom Extension is built from the Maximo Skill Service API specification</p> |
 | 6 | <p>The MAS user accesses the Maximo AI Assistant using the code embedded into the UI of the MAximo Suite</p> |
 | 7 | <p>The MAS user interacts with the Maximo AI Assistant to do one of the following:</p><ol><li>Retrieve unhealthy assets</li><li>Check asset for work order</li><li>Create work order for asset</li><li></li></ol> |
 | 8 | <p>The Maximo AI Assistant forwards the requests to the custom extension</p> |
 | 9 | <p>The custom extension forward the requests to the Maximo Skill service</p> |
 | 10 | <p>The skill service invokes the relevant MAS Manage APi's and returns the result to the caller</p> |
 | 11 | <p>The skill service invokes the relevant MAS Health API's and returns the result to the caller</p> |

    

