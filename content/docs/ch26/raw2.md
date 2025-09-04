---
title: "[26] Medellian Genetics (RAW)"
weight: 260000
---


## File 1: Chromosomal Disorders
**Framework Chosen**: **Concept Definition (CD) Framework** because the content defines different types of chromosomal disorders and their characteristics.

---

```markdown
---
title: "Chromosomal Disorders from Nondisjunction"
prev: /docs/ch26/26-human-genetics/05-human-karyotypes/
next: /docs/ch26/26-human-genetics/07-abo-blood-groups/
weight: 2660
---

# Chromosomal Disorders from Nondisjunction <sub>[26.4.2]</sub>

## What is it?
Chromosomal disorders are genetic conditions caused by **nondisjunction** - the failure of homologous chromosomes to separate during anaphase I or sister chromatids to separate during anaphase II of meiosis.

## Key Characteristics
- **Abnormal chromosome number**: Results in gametes with 22 or 24 chromosomes instead of normal 23
- **Trisomy conditions**: When fertilization produces zygotes with 47 chromosomes (one extra chromosome)
- **Monosomy conditions**: When fertilization produces zygotes with 45 chromosomes (one missing chromosome)
- **Affects both autosomes and sex chromosomes**: Can occur in any chromosome pair

## Primary Functions
- **Down Syndrome (Trisomy 21)**: Extra chromosome 21 affects intellectual development and physical characteristics
- **Turner Syndrome (45,X)**: Missing X chromosome in females affects growth and sexual development  
- **Klinefelter Syndrome (47,XXY)**: Extra X chromosome in males affects sexual development

{{< tabs items="Down Syndrome,Turner Syndrome,Klinefelter Syndrome" >}}
  {{< tab >}}**Karyotype**: 47 chromosomes (45 + XY or XX)
  - Extra chromosome at position 21
  - Affects both males and females
  - Intellectual disability and distinctive facial features{{< /tab >}}
  {{< tab >}}**Karyotype**: 45 chromosomes (44 + XO)
  - Missing X chromosome
  - Only affects females
  - Short stature, infertility{{< /tab >}}
  {{< tab >}}**Karyotype**: 47 chromosomes (44 + XXY)
  - Extra X chromosome
  - Only affects males
  - Underdeveloped secondary sex characteristics{{< /tab >}}
{{< /tabs >}}

✅ **Quick Check**: What causes chromosomal disorders like Down syndrome?
💡 **Analogy**: Like a deck of cards being dealt incorrectly - instead of getting the right number of cards (chromosomes), some hands get too many or too few.
```

---

## File 2: ABO Blood Groups
**Framework Chosen**: **Concept Definition (CD) Framework** because the content defines the ABO blood group system and its genetic basis.

---

```markdown
---
title: "ABO Blood Group System"
prev: /docs/ch26/26-human-genetics/06-chromosomal-disorders/
next: /docs/ch26/26-human-genetics/08-rhesus-factor/
weight: 2670
---

# ABO Blood Group System <sub>[26.4.5]</sub>

## What is it?
The ABO blood group system classifies human blood into four types (A, B, AB, O) based on the presence of specific antigens on red blood cell surfaces, controlled by **multiple alleles**.

## Key Characteristics
- **Three alleles control the system**: I^A, I^B, and I^O
- **I^A and I^B are dominant**: Both express their respective antigens
- **I^O is recessive**: Only expresses when paired with another I^O
- **Codominance occurs**: I^A and I^B together produce AB blood type
- **Each person has only two alleles**: One from each parent

## Primary Functions
- **Blood group A**: Genotypes I^A I^A or I^A I^O - produces antigen A
- **Blood group B**: Genotypes I^B I^B or I^B I^O - produces antigen B  
- **Blood group AB**: Genotype I^A I^B - produces both antigens A and B
- **Blood group O**: Genotype I^O I^O - produces no antigens

{{< tabs items="Genotype Table,Inheritance Example" >}}
  {{< tab >}}
| Blood Group | Genotype | Antigens Present |
|-------------|----------|------------------|
| A | I^A I^A, I^A I^O | Antigen A |
| B | I^B I^B, I^B I^O | Antigen B |
| AB | I^A I^B | Antigens A and B |
| O | I^O I^O | No antigens |
  {{< /tab >}}
  {{< tab >}}**Parents**: A blood (I^A I^O) × B blood (I^B I^O)
  **Possible children**: AB, A, B, O
  **Ratio**: 1:1:1:1
  **Probability of O child**: 25%{{< /tab >}}
{{< /tabs >}}

✅ **Quick Check**: How can parents with A and B blood types have a child with O blood type?
💡 **Analogy**: Like having a color-mixing gene where some colors are strong (dominant) and some are weak (recessive), and sometimes two strong colors mix to create a new combination.
```

---

## File 3: Sex-Linked Inheritance
**Framework Chosen**: **Process & Mechanism (PM) Framework** because the content explains how traits are inherited differently based on sex chromosome location.

---

```markdown
---
title: "Sex-Linked Inheritance Patterns"
prev: /docs/ch26/26-human-genetics/09-thalassemia/
next: /docs/ch26/26-human-genetics/11-family-pedigree-analysis/
weight: 2690
---

# Sex-Linked Inheritance Patterns <sub>[26.4.5]</sub>

## What's the Goal?
Sex-linked inheritance explains why certain genetic conditions (like color blindness and hemophilia) appear more frequently in males and follow specific inheritance patterns through families.

## The Breakdown
{{% steps %}}
### Step 1: Gene Location
**Sex-linked genes** are located on the X chromosome but not on the Y chromosome. The Y chromosome is shorter and lacks many corresponding alleles.
### Step 2: Male Expression Pattern  
Males (XY) need only **one recessive allele** on their X chromosome to express the trait, since they have no second X chromosome to mask it.
### Step 3: Female Expression Pattern
Females (XX) need **two recessive alleles** (one on each X chromosome) to express the trait. With one recessive allele, they become carriers.
### Step 4: Inheritance Pattern
**Affected fathers** pass the trait to ALL daughters (as carriers) but NO sons. **Carrier mothers** pass the trait to 50% of sons (affected) and 50% of daughters (carriers).
{{% /steps %}}

## Visual Summary

### Color Blindness Example
| Individual | Genotype | Phenotype |
|------------|----------|-----------|
| Normal male | X^B Y | Normal vision |
| Color blind male | X^b Y | Color blind |
| Normal female | X^B X^B | Normal vision |
| Carrier female | X^B X^b | Normal vision (carrier) |
| Color blind female | X^b X^b | Color blind |

**Key**: X^B = dominant (normal), X^b = recessive (color blind)

### Inheritance Pattern: Normal male × Carrier female
- **Parents**: X^B Y × X^B X^b
- **Children**: 25% normal girls, 25% carrier girls, 25% normal boys, 25% color blind boys

✅ **Quick Check**: Why are males more likely to be color blind than females?
💡 **Real-World Link**: This explains why hemophilia affected European royal families - carrier queens passed the condition to their sons, who then couldn't pass it to their own sons.
```

---

## File 4: Family Pedigree Analysis
**Framework Chosen**: **Experimental Protocol (EP) Framework** because pedigree analysis is a systematic method for investigating inheritance patterns.

---

```markdown
---
title: "Family Pedigree Analysis Method"
prev: /docs/ch26/26-human-genetics/10-sex-linked-inheritance/
next: /docs/ch26/26-human-genetics/12-summary/
weight: 2700
---

# Family Pedigree Analysis Method <sub>[26.4.6]</sub>

## Research Question
How can we trace the inheritance pattern of genetic traits through multiple generations of a family to predict future occurrences and identify carrier individuals?

## Hypothesis
By systematically mapping trait appearance across generations using standardized symbols, we can determine whether a trait follows dominant, recessive, or sex-linked inheritance patterns.

## Key Variables
- **Individuals studied**: Family members across multiple generations
- **Trait expression**: Present or absent in each individual
- **Inheritance pattern**: Dominant, recessive, or sex-linked mode of inheritance
- **Fixed factors**: Genetic makeup of each individual, family relationships

## Procedure Summary
{{% steps %}}
### Step 1: Symbol Assignment
Use standard pedigree symbols:
- □ = Normal male
- ○ = Normal female  
- ■ = Affected male
- ● = Affected female
- ◐ = Carrier female (for recessive traits)
### Step 2: Generation Mapping
- Number each generation with Roman numerals (I, II, III)
- Connect parents with horizontal lines
- Connect children with vertical lines from parents
### Step 3: Pattern Analysis
Track trait appearance across generations to identify inheritance type:
- **Dominant**: Appears in every generation
- **Recessive**: May skip generations
- **Sex-linked**: Affects more males, passes from carrier mothers
{{% /steps %}}

## Interpreting the Results
- **Dominant Pattern**: If trait appears in consecutive generations and affects both sexes equally
- **Recessive Pattern**: If trait skips generations and appears when both parents are carriers
- **X-linked Pattern**: If more males affected and trait passes from affected grandfather through carrier daughter to affected grandson

{{< callout type="info" >}}
**Analysis Tip**: Look for the "knight's move" pattern in X-linked traits - the condition jumps from affected male to his daughter's son.
{{< /callout >}}

✅ **Quick Check**: What inheritance pattern would you suspect if a trait affects only males and passes from mother to son?
💡 **Real-World Application**: Genetic counselors use pedigree analysis to assess risk for couples planning families, especially when genetic disorders run in their families.
```

This breakdown transforms the dense textbook content into digestible, framework-driven mini-lessons that maintain scientific accuracy while improving accessibility for students.