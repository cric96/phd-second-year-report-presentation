 
+++

title = "Guide for writing markdown slides"
description = "A Hugo theme for creating Reveal.js presentations"
outputs = ["Reveal"]
aliases = [
    "/guide/"
]

+++


## A Language-based Software Engineering Approach for Cyber-Physical Swarms
**PhD second year report**

🎤 *Gianluca Aguzzi*, supervisior **Mirko Viroli**

📧 [gianluca.aguzzi@unibo.it](mailto:gianluca.aguzzi@unibo.it)

---

{{% slide auto-animate=true %}}
## Context {.highlight}
### Cyber-Physical Swarms (*CPSW*) {.accent}
{{% row %}}
{{% fragment class="col" %}} 
#### Many Networked Agents
{{< image height="30" src="/network.png" >}} 
{{% /fragment %}}
{{% fragment class="col" %}} 
#### Cyber-Physical Systems
{{< image height="30" src="/cps.png" >}} 
{{% /fragment %}}
{{% fragment class="col" %}} 
#### Collective Behaviour  
{{< image height="30" src="/ci.png" >}} 
{{% /fragment %}}
{{% /row %}}


---
{{% slide auto-animate=true %}}
## Context {.highlight}
### Cyber-Physical Swarms (*CPSW*) {.accent}
{{% row %}}
{{% col %}}
#### Many Networked Agents
{{< image height="30" src="/network.png" >}} 
{{% /col %}}
{{% col %}}
#### Cyber-Physical Systems
{{< image height="30" src="/cps.png" >}} 
{{% /col %}}
{{% col %}}
#### Collective Behaviour  
{{< image height="30" src="/ci.png" >}}
{{% /col %}}
{{% /row %}}

{{% row %}}
{{% col %}}
### Applications {.ok}
- Swarm robotics
- Crowd of (augmented) people
- Smart Cities
- Large-scale IoT systems
{{% /col %}}
{{% /row %}}

---

{{% slide auto-animate=true %}}

## Context {.highlight}
### Cyber-Physical Swarms (*CPSW*) {.accent}
{{% row %}}
{{% col %}}
#### Many Networked Agents
{{< image height="30" src="/network.png" >}} 
{{% /col %}}
{{% col %}}
#### Cyber-Physical Systems
{{< image height="30" src="/cps.png" >}} 
{{% /col %}}
{{% col %}}
#### Collective Behaviour  
{{< image height="30" src="/ci.png" >}}
{{% /col %}}
{{% /row %}}

{{% row %}}
{{% col %}}
### Applications {.ok}
- Swarm robotics
- Crowd of (augmented) people
- Smart Cities
- Large-scale IoT systems
{{% /col %}}
{{% col %}}
### Challenges {.bad}
- Complex & Layered IT networks
- Distributed Control
- Scale
- (Unwanted) Emergents
- Green Computing
{{% /col %}}
{{% /row %}}

---

## Engineering Applications for CPSWs
### Goals
- Collective Behaviour Decoupled from IT networks (**generalization**, focus on *functional* aspects)
    - State-of-the art, macro-programming approaches {{< fa arrow-right >}} **Aggregate Computing**
- Adaptive & Robust behaviour against environmental changes
  - Machine Learning  {{< fa arrow-right >}} Multi Agent Reinforcement Learning Approaches
