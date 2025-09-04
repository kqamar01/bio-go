---
title: "Golgi Apparatus"
type: docs
prev: docs/ch02/components/03-ribosome.md
next: docs/ch02/components/05-mitochondrion.md
weight : 21304

---

{{< tabs items="Micrographs,Exam Diagram,3D Render" >}}
  {{< tab >}}
  ![Golgi Micrograph](/cell/golgi-micrograph.gif) 
  *Golgi stack.*
  {{< /tab >}}
  {{< tab >}}
  ![Golgi Diagram](/cell/golgi-diagram-spm2013.png)
  *Golgi apparatus in red outline*
  {{< /tab >}}
  {{< tab >}}
  ![Golgi 3D](/cell/golgi-3d.png)
  *3D rendering of Golgi Apparatus.*
  {{< /tab >}}
{{< /tabs >}}

**NAME**: Golgi Apparatus  

**CHARACTERISTICS**:
- Stack of parallel flattened sacs  
- Single membrane coating  
- Vesicles bud off from one end  

**FUNCTION**:
- Processes proteins and carbohydrates  
- Modifies and packages chemicals  
- Transports glycoproteins  


**Function between Nucleus, ER, Ribosome & Golgi Apparatus**:
```mermaid
sequenceDiagram
    participant Nucleus
    participant Ribosome
    participant Rough_ER
    participant Golgi_Apparatus
    
    Nucleus->>Ribosome: mRNA (instructions to synthesize protein)
    Ribosome->>Rough_ER: Synthesized proteins
    Rough_ER->>Golgi_Apparatus: Transports proteins
    Golgi_Apparatus->>Cell: Processes and packages protein ready to use
```