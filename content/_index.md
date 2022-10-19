 
+++
title = "Second Year PhD report"
description = "A Language-based Software Engineering Approach for Cyber-Physical Swarms"
outputs = ["Reveal"]
aliases = [
    "/guide/"
]

+++
{{% slide preload=true background-iframe="boids.html" transition="zoom" %}}

## A Language-based Software Engineering Approach for Cyber-Physical Swarms
**PhD second year report**

🎤 *Gianluca Aguzzi*, supervisor **Mirko Viroli**

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
- COMMunity-OrieNted WEARrable Computing Systems 
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
- COMMunity-OrieNted WEARrable Computing Systems
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
## Context {.highlight}


#### Engineering Applications for CPSWs {.accent}

Find a **systematic** methodology to synthesise and deploy *self-organising* behaviours of
predictable outcomes for CPSW

---

{{% slide auto-animate=true %}}
## Context {.highlight}


#### Engineering Applications for CPSWs {.accent}

Find a **systematic** methodology to synthesise and deploy *self-organising* behaviours of
predictable outcomes for CPSW

#### Multi-faceted scientific problem {.accent}
- Algorithms & Methodologies (*how* to express collective behaviours)
- Middleware Dynamics (*how* to execute collective specifications)
- Deployment in Complex IT networks (*how* to collocate the computation *smartly*)

---

{{% slide auto-animate=true %}}

## Context {.highlight}


#### Engineering Applications for CPSWs {.accent}

Find a **systematic** methodology to synthesise and deploy *self-organising* behaviours of
predictable outcomes for CPSW

#### Multi-faceted scientific problem {.accent}
- Algorithms & Methodologies (*how* to express collective behaviours)
- Middleware Dynamics (*how* to execute collective specifications)
- Deployment in Complex IT networks (*how* to collocate the computation *smartly*)

#### Current Approaches {.highlight}
- Nature-inspired algorithms (e.g., Automatic Desing)
    - Simple and robust
    - {{< fa thumbs-down >}} {{% bad c="Hardly scale with application complexity" %}}
- Macro-programming approaches (e.g., Aggregate Computing)
    - **Top-down** approaches (reduce the *abstraction* gap)
    - {{< fa thumbs-down >}} {{% bad c="Limited adaptivity against non-stationary environment" %}}
- Machine Learning (e.g., Multi-Agent Reinforcement Learning)
    - Learn complex collective dynamics
    - {{< fa thumbs-down >}} {{% bad c="Typically are application specific" %}}

---

{{% slide auto-animate=true %}}
## Proposed Approach {.accent}
#### Language-based engineering {.highlight}
**Models**, **tools**, and **algorithms** are built around a *programming language*

---

{{% slide auto-animate=true %}}
## Proposed Approach {.accent}
#### Language-based engineering {.highlight}
**Models**, **tools**, and **algorithms** are built around a *programming language*
#### Aggregate Computing {.highlight}
- Target/reference model
- Best match for CPSWs
    - Decouple the collective specification from the IT networks
    - Scale naturally with nodes in the systems
    - High-level abstractions to devise applications

---

{{% slide auto-animate=true %}}
## Proposed Approach {.accent}
#### Language-based engineering {.highlight}
**Models**, **tools**, and **algorithms** are built around a *programming language*
#### Aggregate Computing {.highlight}
- Target/reference model
- Best match for CPSWs
    - Decouple the collective specification from the IT networks
    - Scale naturally with nodes in the systems
    - High-level abstractions to devise applications
#### Directions (Activities overview) {.highlight}
- Integrate machine learning with Aggregate Computing stack
    - **Language**-level (program sketching)
    - **Middleware**-level (distributed schedulers learning)
    - **Deployment**-level (pulverisation) 
- Develop *algorithms* & *methodologies* for CPSWs engineering
    - *Swarm-based* API (e.g., Swarm-Based sensing-driven clustering)
    - Engineering methodologies (e.g., Dynamic Decentralization Domains)

---

## Hybrid collective programming {.highlight}
### Aggregate Computing + Machine Learning {.accent}
#### Roadmap {.highlight}
{{< image height="25" src="/roadmap-step-5.png" >}} 

**Reference**: G. Aguzzi et al, *Machine Learning for Aggregate Computing: a Research Roadmap*, in workshop {{% good c="DISCOLI 2022" %}}

---

## Hybrid collective programming {.highlight}
### Learn collective building block {.accent}
#### Program sketching {.highlight}
#### High-Level idea {.accent}

{{%row%}}
{{%fragment%}}
{{< image height=30 src="/synthesis-1.png"  >}}
#### Aggregate Program
{{%/fragment%}}

{{%fragment%}}
{{< image height=30 src="/synthesis-2.png"  >}}
#### System-Dynamic Specific Part {{%accent c="(Hole)" %}}
{{%/fragment%}}

{{%fragment%}}

{{< image height=30 src="/synthesis-3.png"  >}}
#### Fill the Hole through {{%accent c="Experience" %}}
{{%/fragment%}}
{{%/row%}}

**Reference**: G. Aguzzi et al, *Towards Reinforcement Learning-based Aggregate Computing*, in conference {{% good c="COORDINATION 2022" %}}

--- 
## Hybrid collective programming {.highlight}
### Learn collective building block {.accent}
#### Program sketching {.highlight}
```scala
rep((s0, a0, o0)) { // s0, a0 context dependent 
  case (sTMinusOne, aTMinusOne, _) => {
    val Q = sense("Q") // global during training, local during execution
    val oT = update(oTMinusOne, aTMinusOne) // local action
    // state from the neighbourhood field program output
    val sT = state(nbr(oT))
    val aT = branch(learn) { // actions depends on learn condition
      val rTMinusOne = oracle.reward(oT)
      learning.updateQ(Q, sTMinusOne, aTMinusOne, rTMinusOne, sT) // Q update
      sampleFrom(policyBehavioural(sT) // sample from a probabilistic distribution
    } {
      policyTarget(sT) // greedy policy, no sampling is needed
    }
  }
  (sT, aT, oT) 
}
```

---

## Hybrid collective programming {.highlight}
### Distributed Reinforcement-Based Schedulers {.accent}
#### Adjust local scheduling following environment condition {.highlight}
{{% frag-list kind="ul" %}}
{{% frag-li "fade-in" "0" %}} The Aggregate Computing model {{%accent c="does not"%}} enforce a global-synchronization {{% /frag-li %}}
{{% frag-li "fade-in" "1" %}} Current Implementation {{% highlight c="{{% fa solid arrow-right %}}" %}} Periodic possibly async execution {{% /frag-li %}}
{{% frag-li "fade-in" "2" %}} Frontier: {{% accent c="Time-Fluid Field-Based Coordination through Programmable Distributed Schedulers" %}}   {{% /frag-li %}}
{{% frag-li "fade-in" "3" %}} **{{% accent c="Reinforcement Learning"%}}** agent tunes the local node schedulers {{% /frag-li %}}
{{% /frag-list %}}

**Reference**: G.Aguzzi et al, *Addressing Collective Computations Efficiency through Reinforcement Learning*, in conference {{% good c="ACSOS 2022" %}}

---

## Hybrid collective programming {.highlight}
### Distributed Reinforcement-Based Schedulers {.accent}
#### Learning Schema {.highlight}

{{< image height="40" src="/algorithm-learning-5.png" >}}

---


## Hybrid collective programming {.highlight}
### What we learn so far {.accent}
#### Broad Impact {.highlight}

{{% frag-list kind="ul" %}}
{{% frag-li %}} Engineering **{{% accent c="Collective Intelligence" %}}** {{% /frag-li %}}
{{% frag-li %}} **{{% accent c="Green" %}}** Computing{{% /frag-li %}}
{{% frag-li %}} **{{% accent c="Multi-Agent" %}}** Reinforcement Learning {{% /frag-li %}}
{{% frag-li %}} **{{% accent c="Hybrid" %}}** Programming Paradigm {{% /frag-li %}}
{{% /frag-list %}}

#### Challenges {.highlight}

{{%frag-list kind="ul"%}}
{{%frag-li%}} Multi-agent credit assignment problem {{%/frag-li%}}
{{%frag-li%}} Multi-objective goals {{%/frag-li%}}
{{%frag-li%}} Hand-crafted state encoding are inadequate (variable neighborhood) {{%/frag-li%}}
{{%frag-li%}} Environment partial observability {{%/frag-li%}}

{{%/frag-list%}}

---

## Hybrid collective programming {.highlight}
### Ongoing (and Future) Works {.accent}
- *Spatio-temporal* forecasting & tracking leveraging Graph Neural Networks and Aggregate Computing (**Period abroad activity**)
- *Automatic deployment* collective application leveraging Pulverised architecture and Machine Learning
- **Deep** Reinforced-Distributed Schedulers

---

## Swarm-based API {.highlight}
### Sensing-driven Clustering {.accent}
{{% row %}}
{{% col %}}
- A useful Collective pattern for CPSWs applications
  - detected zones in danger (e.g., wildfires in forests)
  - act following zone-level pattern (e.g., use pesticides in an agriculture field)
- Contribution
  - distributed & fault-tollerent sensing based clustering
  - evaluation in several use cases
{{% /col %}}
{{% col %}}
{{< image height="40" src="/gaussian.gif" >}}
{{% /col %}}
{{% /row %}}

**Reference**: G.Aguzzi et al, *A field-based computing approach to sensing-driven clustering in robot swarms* in journal {{% good c="Swarm Intelligence" %}}

---

## Swarm-based API {.highlight}
### Abstractions for Complex Decentralised Application {.accent}
#### Dynamic Decentralization Domains {.highlight}
Distributed *regions* formed for supporting *collective* sensing & acting process
- Contribution
  - API (in Scala) for managing decentralised domains lifecycle
  - Tested in a simulated environment

{{%row%}}
{{%col%}}
{{%/col%}}
{{%col%}}
{{< youtube id=nWLaglM0EkY >}}
{{%/col%}}
{{%col%}}
{{%/col%}}
{{%/row%}}


**Reference**: G.Aguzzi et al, *Dynamic Decentralization Domains for the Internet of Things*, in journal {{% good c="Internet Computing" %}}

---
## Tools and Methodologies {.hightlight}
### Contribution {.accent}
- **Reference** R.Casadei et al, *ScaFI: A Scala DSL and Toolkit for Aggregate Programming*, in journal {{% good c="SSRN"%}}
  - Presentation of ScaFi -- Framework for Aggregate Computing definition
- **Reference** R.Casadei et al, *Towards Automated Engineering for Collective Adaptive Systems: Vision and Research Directions*, in workshop {{% good c="COMMON-WEARS 2022" %}}
  - Discussion in the current engineering process (error-prone)
  - Vision for an automated collective application design
---


{{% slide preload=true background-iframe="waves-thanks.html" transition="zoom" background-color="black" %}}

# Thank you! {.white-text }