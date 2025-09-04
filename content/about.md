---
title: "About"
type: about
description: "Why this Biology digital textbook exists"
---

I developed a systematic, framework-based methodology to transform dense biology textbook content into a series of granular, digestible mini-lessons for a digital learning platform. By analyzing the curriculum's learning standards, cognitive taxonomies, and sample exam questions, I identified five distinct types of biological knowledge and created a unique content template for each. This ensures the material is not only easy for Gen Z learners to understand but is also structured precisely to meet exam requirements.

---
### **Part 1: The Problem & Initial Hypothesis**

The project's goal was to adapt the Malaysian KSSM Form 4 & 5 Biology syllabus for an online Hugo website, specifically targeting Gen Z and Alpha learners. These digital natives respond better to bite-sized, predictable, and easily searchable content, whereas traditional textbooks can cause cognitive overload.

My initial hypothesis was that I could simplify everything using a single, consistent framework I called NCF—**Name, Characteristics, Function**. I tested this on the content from **Chapter 2 on Cell Biology**. While it worked perfectly for descriptive concepts like organelles (e.g., mitochondrion), I immediately ran into problems when I tried to apply it to content from **Chapter 3 on Membrane Transport**. NCF was completely unsuitable for explaining processes like osmosis or comparing active versus passive transport. The single-framework approach was a failure, and I needed a more robust, data-driven solution."

---

### **Part 2: My Analytical Process & How the Files Interconnected**

To find the right solution, I performed a multi-source analysis, treating it like a data problem. My process involved interconnecting several key documents:

1.  **Establishing the Blueprint**: I started with my core technical prompt . This document established the non-negotiable constraints: **one concept per file**, scientific accuracy, adherence to learning standard numbers, and the specific Hugo file structure. This was my foundation.

2.  **Mapping the Curriculum**: I used the `KSSM Biology Learning Standard` file as my source of truth. Instead of just reading the topics, I focused on the **action verbs** used for each standard, like `State`, `Compare and contrast`, `Explain the process`, `Design an experiment`, and `Correlate the effects`. This was the first major clue that the curriculum demanded different cognitive skills for different topics.

3.  **Categorizing Cognitive Skills**: Anderson Taxonomy is cognitive taxonomy that links the verbs from the learning standards to specific thinking skills like **Remembering**, **Understanding**, **Analyzing**, and **Creating**. By cross-referencing the verbs from the learning standards with this taxonomy, I discovered a clear pattern: the curriculum wasn't just a list of facts; it was a structured hierarchy of skills.

4.  **Validating with Content & Assessments**:
    * I then went back to the raw textbook chapters and saw these patterns in the actual content. For example, Chapter 3 contained descriptions of the plasma membrane (facts), the process of active transport (a sequence), a comparison of transport types (analysis), and the effects of tonic solutions on cells (cause-and-effect).
    * Finally, I analyzed the sample exam questions from the. The questions directly mirrored the cognitive skills I had mapped. There were questions asking students to *'compare'*, *'explain the effect'*, and *'describe the process'*, confirming that my analysis was aligned with how students are ultimately assessed.

This interconnected analysis proved that a 'one-size-fits-all' approach was wrong. The type of content, the required cognitive skill, and the assessment method were all intrinsically linked."

---

### **Part 3: The Solution - A Multi-Framework System**

The conclusion from this analysis was to create a suite of five distinct content frameworks, each tailored to a specific type of knowledge I had identified. This became my core methodology:

1.  **Concept Definition (CD) Framework**: An evolution of my original NCF, used for factual recall (**Remembering**).
2.  **Process & Mechanism (PM) Framework**: For explaining sequential events like mitosis or active transport (**Understanding**).
3.  **Comparative Analysis (CA) Framework**: For side-by-side comparisons, like Plant vs. Animal cells (**Analyzing**).
4.  **Cause & Effect (CE) Framework**: For explaining relationships, like why a cell shrinks in a hypertonic solution (**Applying/Understanding**).
5.  **Experimental Protocol (EP) Framework**: For outlining scientific procedures as required by the syllabus (**Creating/Applying**).

To operationalize this, I created a **master prompt for an LLM**. This prompt acts as a detailed set of instructions, telling the AI how to analyze any given piece of textbook content, automatically select the correct framework from the five options, and then restructure the information into the corresponding template.

The end result is a highly efficient and scalable system. It produces content that is **predictable and easy to navigate** for students, **reduces cognitive load** by focusing on one idea at a time in the most logical structure, and is **inherently exam-focused** because the frameworks are built from an analysis of the curriculum's own objectives and assessment patterns."
