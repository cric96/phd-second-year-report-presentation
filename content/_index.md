 
+++

title = "Second Year PhD report"
description = "A Language-based Software Engineering Approach for Cyber-Physical Swarms"
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

{{% slide auto-animate=true %}}
## Engineering Applications for CPSWs {.highlight}

Find a **systematic** methodology to synthesise and deploy *self-organising* behaviours of
predictable outcomes for CPSW

---

{{% slide auto-animate=true %}}
## Engineering Applications for CPSWs {.highlight}

Find a **systematic** methodology to synthesise and deploy *self-organising* behaviours of
predictable outcomes for CPSW

### Multi-faceted scientific problem {.accent}
- Algorithms & Methodologies (*how* to express collective behaviours)
- Middleware Dinamycs (*how* to execute collective specifications)
- Deployment in Complex IT networks

---

{{% slide auto-animate=true %}}
## Engineering Applications for CPSWs {.highlight}

Find a **systematic** methodology to synthesise and deploy *self-organising* behaviours of
predictable outcomes for CPSW

### Multi-faceted scientific problem {.accent}
- Algorithms & Methodologies (*how* to express collective behaviours)
- Middleware Dinamycs (*how* to execute collective specifications)
- Deployment in Complex IT networks

### Current Approaches 
- Nature-inspired algorithms (e.g., Automatic Desing)
    - simple and robust
    - hardly scale with application complexity
- Macro-programming appraoches (e.g., Aggregate Computing)
    - top-down approches
    - reduce the abstraction gap
    - limited adaptivity against non-stationary environment (no learning)
- Machine Learning (e.g., Multi-Agent Reinforcement Learning)
    - learn complex collective dynamics
    - tipically they are application specific

---

## Proposed Approach
### Language-based engineering
**Models**, **tools**, **algorithms** are built around a *programming language*
### Aggregate Computing
- target/reference model
- best match for CPSWs
    - decouple the collective specification from the IT networks
    - scale naturally with nodes in the systems
    - high-level abstraction to devise applications
### Directions
- Develop algorithms & methodologies for CPSWs engineering
    - Swarm-Based clustering
    - DCEps
    - other
- Integrate machine learning with Aggregate Computing stack
    - Language-level (program sketching)
    - Middleware-level (distributed schedulers learning)
    - Deployment level (pulverisation) 

---

## Hybrid collective programming
### Aggregate Computing + Machine Learning
#### Roadmap

---

## Learn collective building block
### Program sketching

--- 

## Distributed Schedulers


---
