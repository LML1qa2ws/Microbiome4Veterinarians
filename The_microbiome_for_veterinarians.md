# The Microbiome for Veterinarians

**Review Article**

---

**Authors:** *(To be confirmed upon submission)*  
**Corresponding author:** *(To be confirmed upon submission)*  
**Running title:** *Veterinary microbiome science in practice*  
**Target journal style:** Narrative review with structured boxes, tables, and figure callouts

---

## Abstract

The microbiome has moved from a descriptive concept to a clinically relevant framework for understanding host physiology, disease susceptibility, therapeutic response, and antimicrobial resistance across animal species. For veterinarians, however, the practical value of microbiome science remains constrained by uneven evidence quality, species heterogeneity, inconsistent laboratory methods, and a persistent gap between mechanistic discoveries and deployable clinical tools. This review critically examines the current state of microbiome research relevant to veterinary medicine, with emphasis on companion animals, horses, ruminants, poultry, and aquaculture species. We discuss the ecological principles that govern host-associated microbial communities; the technical and interpretive limits of 16S rRNA gene sequencing, metagenomics, metabolomics, and machine learning; and the extent to which microbiome data can already inform diagnosis, prognosis, and treatment selection. We further evaluate microbiome-directed interventions—including diet, prebiotics, probiotics, synbiotics, fecal microbiota transplantation, bacteriophages, and emerging live biotherapeutic products—through the lens of veterinary evidence rather than extrapolation from human medicine. Particular attention is given to One Health, the animal resistome, and the role of veterinarians in antimicrobial stewardship. Although microbiome science has genuine translational potential, many current claims exceed the strength of available data. Progress will depend on standardized study design, strain-resolved and function-focused analytics, clinically meaningful endpoints, regulatory clarity, and closer integration of veterinary, environmental, and human microbiome research. A mature veterinary microbiome field should not merely catalog dysbiosis, but explain when microbial alterations are causal, when they are epiphenomena, and when intervention meaningfully improves animal health.

**Keywords:** microbiome; veterinary medicine; dysbiosis; fecal microbiota transplantation; probiotics; One Health; antimicrobial resistance; companion animals; livestock; comparative medicine

---

## Key points

- Microbiome science is highly relevant to veterinary medicine, but clinical translation remains uneven across species and indications.  
- Most veterinary microbiome studies remain associative; causal inference is still limited.  
- Functional readouts such as bile acid metabolism, short-chain fatty acid production, and resistome profiling are often more clinically informative than taxonomy alone.  
- Fecal microbiota transplantation and dietary modulation have stronger veterinary rationale than many commercial microbiome tests.  
- The most immediate veterinary value of microbiome science may lie in antimicrobial stewardship, pathogen exclusion, and better phenotyping of chronic disease rather than in universal “microbiome optimization”.

---

## Abbreviations

- **AMR**: antimicrobial resistance  
- **ASV**: amplicon sequence variant  
- **CE**: chronic enteropathy  
- **CIBDAI**: Canine Inflammatory Bowel Disease Activity Index  
- **FMT**: fecal microbiota transplantation  
- **LBP**: live biotherapeutic product  
- **NGS**: next-generation sequencing  
- **OTU**: operational taxonomic unit  
- **SCFA**: short-chain fatty acid  
- **WGS**: whole-genome sequencing

---

## 1. Introduction

Over the past two decades, the microbiome has become central to modern thinking about host biology. In veterinary medicine, this shift has been especially important because animals are not only patients but also reservoirs, sentinels, production units, ecological actors, and companions sharing microbial and antimicrobial landscapes with humans. Yet the prominence of the microbiome in scientific discourse has outpaced its disciplined incorporation into routine veterinary decision-making. Terms such as *dysbiosis*, *microbiome restoration*, and *microbial resilience* now appear frequently in clinical conversations, conference proceedings, product marketing, and owner-facing diagnostics, but the evidentiary basis for many applications remains variable.

A major reason is that veterinary microbiome science faces a more difficult translational problem than human medicine. “The veterinary patient” is not a single biological context. Dogs, cats, horses, cattle, sheep, goats, poultry, and fish differ profoundly in gastrointestinal anatomy, digestive strategy, diet formulation, husbandry, environmental exposure, antimicrobial use patterns, and disease spectrum. Even within a single species, age, breed, sex, neuter status, geography, diet, vaccination history, deworming practices, housing density, and owner behavior can all alter microbial community structure. Consequently, findings from one host species—or even one disease phenotype within that species—cannot be uncritically generalized.

At the same time, veterinarians are uniquely positioned to convert microbiome science into applied health benefits. They manage animals at the interface of individual care, herd or flock health, food systems, biosecurity, zoonoses, and environmental stewardship. This makes veterinary medicine central to the One Health interpretation of microbiome biology. A microbiome-oriented veterinary review should therefore do more than summarize associations between taxa and disease. It should ask four harder questions: (1) what mechanisms are biologically plausible; (2) what evidence is clinically actionable now; (3) what remains premature; and (4) where can veterinarians have the greatest impact.

This review is written with those aims in mind. Rather than treating the microbiome as an inherently beneficial or disruptive entity, we approach it as an ecological system whose properties may be protective, neutral, compensatory, or pathogenic depending on context. We critically review the current evidence base, identify practical uses and persistent misconceptions, and outline a research agenda capable of supporting genuine clinical translation.

> **Box 1. What veterinarians should mean by “microbiome” in clinical discussion**  
> 1. **Microbiota** refers to the microorganisms present in a defined niche.  
> 2. **Microbiome** may refer either to those organisms plus their collective genomes or, in broader usage, to the ecological system including organisms, functions, metabolites, and local environment.  
> 3. **Dysbiosis** should not be used as a catch-all synonym for disease. It denotes a disturbed microbial ecosystem, but disturbance may be causal, secondary, adaptive, or simply statistically unusual.  
> 4. **Clinical relevance** requires more than a significant difference between healthy and diseased groups; it requires reproducibility, effect size, and interpretability.  
> 5. **Restoration** is not always the goal. In some diseases, the relevant objective may be metabolic stabilization, colonization resistance, or reduced inflammatory signaling rather than return to a “normal” taxonomic profile.

---

## 2. Ecological and mechanistic foundations relevant to veterinary medicine

### 2.1 Beyond composition: the microbiome as an ecological system

The most common weakness in microbiome interpretation is overemphasis on composition while underappreciating ecological function. Relative abundance plots are informative, but they do not by themselves explain stability, resilience, or disease causation. In animal hosts, gut microbial communities are shaped by immigration, extinction, competition for substrates, host secretions, bile acids, pH gradients, transit time, oxygen tension, mucosal immunity, and management-related perturbations such as diet reformulation, weaning, transport stress, hospitalization, and antimicrobials. A clinically useful framework therefore requires attention to ecological processes rather than taxonomy alone.

Three ecological properties are especially important for veterinarians:

1. **Resistance**, meaning the ability of a community to withstand disturbance.  
2. **Resilience**, meaning the ability to recover after disturbance.  
3. **Functional redundancy**, meaning that multiple taxa may perform similar metabolic tasks, so taxonomic change does not necessarily imply functional collapse.

These properties help explain why some antimicrobial exposures cause transient alteration with little clinical consequence, whereas others precipitate chronic enteropathy, pathogen expansion, poor feed conversion, or heightened shedding of resistance genes. They also explain why two animals with similar taxonomic profiles may have different metabolic or inflammatory phenotypes.

### 2.2 Host–microbe interaction pathways

Several mechanistic pathways recur across species and disease contexts:

- **Barrier maintenance:** commensal microbes influence mucus dynamics, tight-junction integrity, epithelial turnover, and production of antimicrobial peptides.  
- **Immune education:** microbial ligands and metabolites shape innate and adaptive immunity, including regulatory T-cell induction, pattern-recognition signaling, and mucosal tolerance.  
- **Nutrient harvest and fermentation:** particularly relevant in hindgut fermenters and ruminants, where microbial metabolism directly supports host energy balance.  
- **Bile acid transformation:** microbial deconjugation and secondary bile acid formation can alter pathogen resistance, motility, epithelial signaling, and inflammatory tone.  
- **Colonization resistance:** resident communities limit invasion by pathogens through nutrient competition, niche occupation, metabolite production, and direct antagonism.  
- **Neuroendocrine signaling:** microbial metabolites and inflammatory mediators may affect behavior, appetite, stress responses, and gut–brain communication.

### 2.3 Why causal inference is difficult

In veterinary microbiome studies, causal interpretation is often limited by four recurrent problems. First, disease states frequently alter appetite, motility, medication exposure, and husbandry, all of which independently change the microbiome. Second, most studies rely on fecal samples, which incompletely reflect mucosal and small intestinal communities. Third, relative abundance data can generate spurious associations because increases in one taxon necessarily change the proportion of others. Fourth, many disease categories are biologically heterogeneous; for example, canine chronic enteropathy includes food-responsive, antibiotic-responsive, immunosuppressant-responsive, and poorly responsive phenotypes with distinct pathophysiology.

For these reasons, a “disease microbiome signature” should be interpreted cautiously unless it is supported by longitudinal data, intervention studies, host readouts, or functional assays. In practice, the most convincing veterinary microbiome evidence tends to come from convergent findings: repeated taxonomic shifts, parallel metabolomic changes, reproducible clinical associations, and response to a manipulation that plausibly restores function.

> **Figure 1. Conceptual framework linking veterinary exposures to microbiome-mediated clinical outcomes**  
> *Placeholder for schematic figure.* Suggested panels: (A) host factors—species, age, genetics, immune status; (B) external factors—diet, antimicrobials, housing, stress, pathogen exposure; (C) microbiome properties—diversity, resilience, metabolite production, resistome, colonization resistance; (D) outcomes—health, disease susceptibility, treatment response, AMR dissemination. Leave space for a four-panel graphical summary.

---

## 3. Methodological issues that determine what microbiome data can and cannot say

### 3.1 Sampling frame and pre-analytical variability

The veterinary literature often treats sequencing output as if it were a direct readout of the in vivo ecosystem. In reality, every microbiome result is shaped by sampling and processing decisions. Sample type matters: feces, rectal swabs, mucosal biopsies, rumen fluid, cecal contents, skin swabs, milk, and environmental specimens each provide different biological windows. Timing also matters. Sampling before or after fasting, after sedation, after bowel preparation, after transport, or during active diarrhea can alter interpretation. In livestock and poultry, pen, flock, and barn effects may exceed individual-animal effects if not modeled correctly.

Cold-chain delays, preservative choice, DNA extraction kit, bead-beating intensity, primer selection, sequencing depth, contamination control, and reference database selection all influence results. These sources of variance are not trivial technical details; they are often large enough to obscure disease-associated signals or create false differences across studies.

### 3.2 16S rRNA sequencing, shotgun metagenomics, and long-read approaches

**16S rRNA gene sequencing** remains widely used because it is accessible and economical. It is useful for broad community profiling, hypothesis generation, and surveillance studies. However, it rarely provides species- or strain-level resolution and offers only indirect functional inference.

**Shotgun metagenomics** improves taxonomic resolution and enables characterization of genes involved in metabolism, virulence, and AMR. For veterinary applications, it is especially useful when strain tracking, resistome analysis, or donor-recipient engraftment after FMT is of interest. Its limitations include higher cost, host DNA contamination, and analytic complexity.

**Long-read sequencing** may improve genome assembly, plasmid reconstruction, mobile element characterization, and linkage between AMR genes and host organisms. In the veterinary space, this is particularly relevant for farm-associated resistomes and for understanding how mobile genetic elements circulate among animals, feed environments, and waste systems.

### 3.3 Functional profiling and the need to move beyond taxonomy

Functional interpretation is often where veterinary microbiome studies become clinically interesting. Metabolomics can identify changes in bile acids, indoles, SCFAs, branched-chain fatty acids, sphingolipids, and other host–microbe co-metabolites that may correlate more directly with clinical phenotype than taxonomic shifts. Metatranscriptomics and metaproteomics, while less common, provide more direct evidence of active pathways. In practical terms, a veterinarian deciding whether a microbial finding is meaningful should ask whether there is evidence for altered function, not only altered membership.

### 3.4 Statistics, machine learning, and recurrent interpretive errors

The microbiome field has generated enthusiasm for predictive classifiers, but many models perform well only within the dataset used to train them. Common errors include inadequate control for confounders, overfitting in small datasets, ignoring compositionality, relying on alpha diversity as a surrogate for health, and equating discrimination with causation. A model that separates healthy from diseased animals in one hospital population may fail when transported to another region, diet regime, breed distribution, or sequencing pipeline.

For veterinary clinical translation, externally validated models with clearly defined intended use are needed. A dysbiosis score may be useful if it tracks disease activity or therapeutic response, but it should not be mistaken for a diagnosis in itself.

> **Table 1. Methodological strengths and limitations of common veterinary microbiome approaches**  
>   
>| Approach | Main output | Strengths | Key limitations | Most suitable veterinary uses |  
>|---|---|---|---|---|  
>| 16S rRNA amplicon sequencing | Community composition at genus/ASV level | Low cost; scalable; useful for cohort comparisons | Limited species resolution; indirect functional inference; compositional bias | Epidemiology, screening studies, exploratory dysbiosis analyses |  
>| Shotgun metagenomics | Taxa, genes, resistome, pathway potential | Better resolution; strain tracking; AMR characterization | Cost; host DNA contamination; bioinformatic demands | FMT engraftment, AMR surveillance, pathway discovery |  
>| Metabolomics | Small-molecule functional readouts | Closer to phenotype; mechanistic value | Sample handling sensitivity; interpretation complexity | CE phenotyping, diet response, bile acid studies |  
>| Metatranscriptomics | Active gene expression | Activity-focused; better functional inference | RNA instability; expense; computational burden | Research settings, acute perturbation studies |  
>| Culture plus WGS | Isolate-level genomics | Gold standard for strain characterization | Selective; misses uncultured members | Pathogen surveillance, probiotic strain validation, AMR mapping |  
>

> **Box 2. Red flags when interpreting veterinary microbiome studies**  
> - Sample size too small for the number of variables tested  
> - Cases and controls not matched for diet, age, antimicrobial exposure, or geography  
> - Cross-sectional design used to imply causality  
> - Use of relative abundance without absolute quantification or functional corroboration  
> - “Healthy microbiome” defined without species-, age-, and husbandry-specific context  
> - Commercial product efficacy inferred from taxonomic normalization alone  
> - Machine-learning model reported without external validation

---

## 4. Species-specific microbiome landscapes and clinical implications

### 4.1 Dogs

Among veterinary species, dogs are currently the best characterized with respect to gut microbiome composition, dysbiosis metrics, and translational gastroenterology. Work in dogs has shown that chronic enteropathy is associated with reproducible loss of beneficial anaerobes, altered bile acid metabolism, and increased facultative anaerobes. Importantly, however, “canine dysbiosis” is not a single entity. It can emerge after diet change, antibiotic exposure, inflammatory disease, hospitalization, stress, or acute diarrhea, and these contexts should not be conflated.

The strongest current canine application is in chronic enteropathy phenotyping and treatment monitoring, particularly when microbiome changes are interpreted alongside clinical severity scores, histopathology, serum biomarkers, fecal markers, and metabolomic signatures. There is also growing evidence that diet-induced shifts in the canine microbiome are rapid and may contribute to the success of elimination, hydrolyzed, or high-fiber interventions.

Extraintestinal links are increasingly discussed, including obesity, atopic disease, behavior, and oncologic treatment response, but these fields remain earlier in maturity than gastroenterology. The main translational lesson from the canine literature is not that every chronic disease is microbiome-driven, but that gut ecosystem instability may modify disease course and treatment responsiveness in a subset of patients.

### 4.2 Cats

Feline microbiome research is expanding but remains less developed than canine work. Cats present distinctive challenges: a stricter carnivorous nutritional physiology, a comparatively understudied normal microbiome range, and diagnostic overlap between inflammatory bowel disease and alimentary lymphoma. Preliminary studies suggest that intestinal microbial patterns and microbial metabolites may eventually assist with disease differentiation or prognostication, but current evidence is insufficient for standalone diagnostic use.

Feline microbiome interpretation must also account for indoor housing, diet formulation, multicat households, chronic stress, and frequent polypharmacy in older cats. Future work in cats will likely be most useful where microbiome data are integrated into broader phenotyping rather than marketed as independent diagnostics.

### 4.3 Horses

The equine gut microbiome is central to host physiology because the horse depends heavily on hindgut fermentation. This creates both opportunity and vulnerability. Relatively small disruptions in feeding pattern, starch load, transport, hospitalization, or antimicrobial exposure may have outsized physiologic effects. Equine colitis, colic syndromes, antimicrobial-associated diarrhea, and laminitis-related hypotheses have all been linked to microbial perturbation, but mechanistic clarity remains incomplete.

An important equine principle is that microbial instability is often tied to management. Feed consistency, forage access, and abrupt dietary transitions may be as biologically relevant as any pharmaceutical microbiome intervention. As a result, equine microbiome medicine may prove to be less about advanced diagnostics and more about ecology-informed prevention.

### 4.4 Ruminants

In cattle, sheep, and goats, microbiome science cannot be separated from fermentation efficiency, methane production, feed conversion, milk composition, immune development, and production disease. The rumen microbiome is not merely associated with digestion—it performs digestion. This makes ruminants a particularly compelling setting for microbiome interventions, but also a reminder that gastrointestinal compartments must not be collapsed conceptually. The rumen, small intestine, cecum, and feces represent distinct ecosystems.

Applications include manipulation of fermentation pathways, neonatal colonization, weaning transition, pathogen exclusion, mastitis-associated microbiota, and reduction of AMR selection pressure. Yet the production setting introduces unique translational constraints: interventions must be scalable, stable, cost-effective, safe for the food chain, and compatible with farm workflows.

### 4.5 Poultry

The poultry microbiome has direct implications for growth efficiency, enteric pathogen control, flock uniformity, necrotic enteritis, and food safety. Because poultry production operates on a population scale, microbiome interventions are often framed not around individualized therapy but around competitive exclusion, feed additives, hatchery practices, litter management, and reduction of *Salmonella* and *Campylobacter* carriage. In this domain, the microbiome is already operationally relevant, even when mechanistic resolution remains incomplete.

### 4.6 Aquaculture species

Fish and shellfish microbiomes are shaped by a three-way interaction among host, feed, and water environment. This makes interpretation more difficult than in terrestrial species because microbial exposure is continuous and environmental turnover is high. Nevertheless, microbiome-oriented approaches to disease resistance, growth optimization, mucosal health, and reduced antibiotic dependence are of growing interest. The aquaculture field also highlights a critical lesson for all veterinary microbiome work: environmental microbiology is often inseparable from host microbiology.

> **Table 2. Major microbiome-related clinical questions across veterinary species**  
>   
>| Species/group | Most mature applications | Promising but not established | Major current limitations |  
>|---|---|---|---|  
>| Dogs | Chronic enteropathy phenotyping; dysbiosis monitoring; FMT studies | Oncology, behavior, obesity, personalized nutrition | Heterogeneous case definitions; referral bias; overuse of fecal-only inference |  
>| Cats | Exploratory GI phenotyping | IBD vs lymphoma support tools; diet response prediction | Sparse cohorts; lower standardization; fewer intervention trials |  
>| Horses | Ecology-informed prevention; antimicrobial-associated disturbance | FMT, early-warning biomarkers for colitis/colic | Strong management confounding; limited controlled trials |  
>| Ruminants | Fermentation management; early-life colonization; production efficiency | Methane mitigation via microbiome engineering; precision microbial supplementation | Multi-compartment complexity; farm-level confounding |  
>| Poultry | Competitive exclusion; pathogen reduction; feed additive programs | Precision flock profiling; resistome-informed stewardship | Population-level variability; rapid turnover |  
>| Aquaculture | Water-feed-host microbiome management; probiotic strategies | Disease forecasting; microbiome-guided stock resilience | Environmental noise; sampling standardization challenges |  
>
---

## 5. Microbiome-based diagnostics: promise, hype, and realistic near-term utility

### 5.1 What makes a microbiome biomarker clinically useful?

A clinically useful biomarker must do more than differ statistically between groups. It should add information beyond routine clinical assessment, perform reproducibly across settings, and influence management. Most veterinary microbiome markers do not yet meet all three criteria. Nevertheless, several diagnostic uses are realistic in the near term.

First, microbiome-derived indices may serve as **contextual biomarkers** in chronic gastrointestinal disease, helping to characterize disease activity or monitor response rather than establish diagnosis independently. Second, microbiome data may help identify **functional derangements**, such as loss of bile acid conversion capacity or expansion of taxa associated with inflammatory instability. Third, resistome profiling may support surveillance and stewardship in herd, flock, and hospital environments.

### 5.2 Dysbiosis indices and their correct use

The canine dysbiosis index is one of the most visible veterinary microbiome tools. Its value lies in standardization and trendability, not in diagnostic omniscience. A markedly abnormal index may support the interpretation that the intestinal ecosystem is disturbed, but it does not tell the clinician why. A dog with dietary indiscretion, hospitalization, parvoviral enteritis recovery, chronic enteropathy, or recent metronidazole exposure may all show dysbiosis. Thus, the index is best understood as a structured adjunct rather than a disease label.

### 5.3 Direct-to-consumer and commercial veterinary microbiome tests

Commercial pet microbiome tests have expanded faster than validation literature. The marketing language commonly used—“optimize”, “rebalance”, “restore”, “personalize”—can imply a precision that the science does not yet support. Problems include opaque reference populations, proprietary algorithms that are difficult to audit, uncertain clinical thresholds, and recommendations that may be weakly linked to measured biology.

This does not mean that all commercial testing is without value. Some platforms may eventually prove useful for longitudinal monitoring, research recruitment, or owner engagement. But responsible veterinary use requires transparent methods, analytical validation, clear intended use, and evidence that test-guided interventions improve outcomes.

### 5.4 Multi-omics diagnostics

The future of veterinary microbiome diagnostics is likely to be multimodal rather than purely taxonomic. The most informative platforms may combine microbiome composition with metabolite panels, host inflammatory markers, pathogen screening, and clinical metadata. For example, in canine chronic enteropathy, a panel integrating dysbiosis score, bile acid profile, cobalamin status, fecal markers, and treatment response history may be far more clinically useful than sequencing alone.

> **Figure 2. Tiered framework for interpreting veterinary microbiome test results**  
> *Placeholder for figure.* Suggested layout: tier 1—analytical validity; tier 2—biological plausibility; tier 3—clinical validity; tier 4—clinical utility; tier 5—cost-effectiveness and workflow integration.

> **Box 3. Questions to ask before ordering or interpreting a microbiome test**  
> - What specific clinical decision could this result change?  
> - Is the assay validated for this species, sample type, and disease context?  
> - Is the result comparative, predictive, or merely descriptive?  
> - Are medications, diet, age, or environment likely to confound interpretation?  
> - Does the report provide functional or mechanistic information, or only taxonomic ranking?  
> - Is there evidence that acting on the result improves patient outcomes?

---

## 6. Microbiome-directed therapies

### 6.1 Diet as the most practical microbiome intervention

In day-to-day veterinary medicine, diet is often the most influential and most controllable microbiome intervention. It shapes substrate availability, fermentation patterns, stool characteristics, bile acid metabolism, and inflammatory signaling. In dogs and cats, hydrolyzed and novel-protein diets may improve chronic enteropathy partly through immune mechanisms and partly through ecosystem remodeling. In horses, forage access and starch moderation may be more important than any marketed microbial supplement. In ruminants and poultry, feed formulation affects both production traits and microbial ecology at scale.

An important caution is that beneficial microbiome shifts should not be defined solely by increased diversity. A successful diet may reduce some taxa while improving clinical function, stool quality, and metabolite balance. Veterinary nutrition research should therefore move toward linking ingredient composition, microbial function, and measurable outcomes.

### 6.2 Probiotics, prebiotics, and synbiotics

Probiotics remain ubiquitous in veterinary practice, but the evidence base is highly uneven. Their efficacy depends on strain identity, dose, viability, manufacturing quality, formulation, host species, disease indication, and treatment timing. Many studies evaluate product classes rather than traceable strains, making reproducibility difficult. In some contexts—acute diarrhea support, mitigation of antibiotic-associated disturbance, enhancement of colonization resistance in production systems—benefit appears plausible and sometimes demonstrable. In other settings, enthusiasm has outstripped evidence.

Prebiotics and synbiotics may be particularly useful when the clinical goal is to alter fermentation ecology rather than simply add transient organisms. Their success depends on matching substrate to existing community capacity and host context. A prebiotic that is beneficial in one species, age group, or diet background may not behave similarly in another.

### 6.3 Fecal microbiota transplantation

FMT has become the flagship microbiome therapy because it bypasses single-strain logic and attempts whole-community transfer. In dogs with refractory chronic enteropathy, the emerging evidence is promising but not definitive. The literature suggests potential clinical improvement, sometimes accompanied by partial restoration of microbial function or community structure. However, study design limitations remain common: small cohorts, variable donor criteria, inconsistent routes of administration, lack of placebo controls, and uncertain durability.

For veterinarians, the key issue is not whether FMT is scientifically interesting—it is—but under what conditions it is justified. Current evidence supports considering FMT primarily in selected gastrointestinal contexts after standard diagnostics and therapies have been appropriately used, ideally within structured protocols. Outside those settings, routine use remains premature.

Safety is another crucial issue. Donor screening must account not only for enteric pathogens but also for multidrug-resistant organisms, parasites, viruses, diet history, medication exposure, and possibly high-risk AMR genes. As sequencing becomes more accessible, donor selection may evolve from exclusion-based screening toward function-informed donor profiling.

### 6.4 Bacteriophages, defined consortia, and live biotherapeutic products

The next phase of microbiome therapeutics is likely to be more selective than whole-stool transfer. Defined bacterial consortia, targeted bacteriophages, and next-generation LBPs may offer better standardization and regulatory tractability than donor-derived material. These approaches are attractive in veterinary medicine because they could, in principle, be tailored to specific pathogens, production systems, or metabolite deficits. However, veterinary development faces manufacturing, licensing, stability, and cost barriers that should not be underestimated.

### 6.5 Why some microbiome interventions fail

Microbiome interventions often fail for understandable ecological reasons. The recipient niche may not permit engraftment. The host diet may not support the introduced organisms. Concomitant drugs may suppress them. The measured dysbiosis may reflect downstream inflammation rather than a primary driver. Or the intervention may simply be too nonspecific for the disease process. Recognizing these failure modes is essential if the field is to move beyond optimistic but underpowered studies.

> **Table 3. Practical appraisal of microbiome-directed interventions in veterinary medicine**  
>   
>| Intervention | Biological rationale | Current veterinary evidence | Main practical barriers | Most reasonable current use |  
>|---|---|---|---|---|  
>| Diet modification | Alters substrate flow, fermentation, bile acid metabolism, and inflammation | Strongest overall practical evidence | Diet history confounding; formulation heterogeneity | First-line adjunct in many GI disorders |  
>| Probiotics | Add or transiently support beneficial functions | Mixed; indication- and product-specific | Product quality; strain uncertainty; modest effect sizes | Selected supportive indications |  
>| Prebiotics/synbiotics | Support ecological function and cross-feeding | Moderate but heterogeneous | Variable host response; diet interaction | Adjunctive use where fermentation support is desired |  
>| FMT | Whole-community restoration and function transfer | Promising in canine CE; limited elsewhere | Regulation, donor screening, protocol inconsistency | Refractory GI disease under protocolized conditions |  
>| Phage therapy | Targeted pathogen control with less collateral damage | Early-stage veterinary evidence | Regulatory pathway, resistance, delivery | Research and niche pathogen-control settings |  
>| Defined consortia/LBPs | Standardized functional replacement | Very early veterinary pipeline | Manufacturing and licensing complexity | Future translational platform rather than routine use |  
>
> **Figure 3. Proposed clinical decision pathway for microbiome-directed intervention in a veterinary patient**  
> *Placeholder for figure.* Suggested flowchart: define syndrome → assess conventional diagnostics and treatable causes → characterize perturbation context (diet, drugs, infection, hospitalization) → consider lowest-risk/highest-evidence intervention first → monitor clinical and, where justified, microbiome-associated endpoints.

---

## 7. The microbiome and antimicrobial resistance in veterinary medicine

### 7.1 The animal microbiome as a reservoir of resistance genes

Veterinarians encounter AMR not only at the level of pathogens but also at the level of microbial ecosystems. The resistome includes genes present in commensals, opportunists, pathogens, and mobile genetic elements. Antimicrobial exposure may increase the abundance, persistence, and transferability of these genes even when overt clinical resistance is not immediately apparent. This is particularly important in food-producing animals, shelter environments, referral hospitals, and integrated farm systems.

### 7.2 Why microbiome-informed stewardship matters

Traditional stewardship focuses on drug choice, dose, duration, and indication. Microbiome-informed stewardship expands the frame to include collateral ecological damage, recovery dynamics, colonization resistance, and downstream AMR propagation. From this perspective, a prudent prescription is not simply one that treats the current infection, but one that minimizes avoidable disruption to host-associated microbial communities and to the surrounding microbial environment.

### 7.3 A One Health resistome perspective

Animals, humans, feed, water, bedding, soil, waste, and wildlife are linked by microbial traffic. Resistance genes can move among these compartments through bacteria, plasmids, phages, and environmental persistence. Veterinary microbiome research is therefore essential to One Health AMR surveillance. The key contribution of microbiome methods here may be less about individual patient care and more about system-level monitoring: which genes are present, in which compartments, under what selective pressures, and with what mobility potential.

> **Box 4. Practical stewardship questions informed by microbiome thinking**  
> - Is antimicrobial treatment necessary, or is a non-antimicrobial strategy reasonable?  
> - Which regimen is least likely to cause prolonged ecological disruption?  
> - What is the patient’s risk of pathogen overgrowth or AMR enrichment after treatment?  
> - Are there husbandry, vaccination, nutrition, or biosecurity interventions that could reduce recurrence?  
> - In production systems, what are the likely downstream effects on flock/herd resistome burden?

---

## 8. One Health and comparative microbiome medicine

One Health is sometimes invoked rhetorically, but microbiome science gives it unusually concrete meaning. Companion animals share homes, surfaces, and sometimes strains with humans. Farm animals shape the microbial and resistome characteristics of manure, runoff, food products, and occupational exposure environments. Wildlife and aquatic systems contribute additional layers of microbial exchange and ecological selection.

For this reason, veterinary microbiome research should not be viewed as a secondary application of human science. It is a necessary part of understanding the circulation of microbes, metabolites, and resistance determinants across connected ecosystems. Comparative microbiome medicine can also be scientifically productive. Dogs with naturally occurring chronic inflammatory disease, obesity, or cancer may offer more clinically relevant translational models than reductionist laboratory systems for some questions. Conversely, human microbiome therapeutics provide conceptual templates that veterinary medicine may adapt, challenge, or refine.

The most constructive comparative approach is bidirectional: veterinary science should borrow analytical rigor from human microbiome research while also contributing ecological breadth, natural disease models, and population-level insights unavailable in strictly human cohorts.

> **Figure 4. One Health microbiome connections relevant to veterinary practice**  
> *Placeholder for figure.* Suggested design: network diagram linking companion animals, livestock, wildlife, humans, food chain, water, soil, and healthcare/farm environments, with arrows indicating microbial exchange and AMR flow.

---

## 9. Clinical contexts in which microbiome science is most likely to matter

### 9.1 Gastroenterology

This remains the clearest area of clinical relevance. Chronic enteropathy, acute diarrhea, post-antibiotic disturbance, pathogen colonization resistance, bile acid dysmetabolism, and response to diet are all domains in which microbiome information may add value.

### 9.2 Dermatology

Skin and mucosal microbiomes are increasingly implicated in atopic and allergic disease, recurrent infections, and barrier dysfunction. However, the field remains more descriptive than interventional, and regional body-site variation complicates interpretation.

### 9.3 Oncology

Interest in microbiome–cancer interactions is justified, particularly regarding chemotherapy tolerance, cachexia, inflammatory tone, and possible immunotherapy modulation. Nonetheless, veterinary oncology evidence remains preliminary, and clinical recommendations should remain conservative.

### 9.4 Metabolic disease

Obesity, insulin dysregulation, hepatic dysfunction, and production inefficiency all have plausible microbiome links. The challenge is disentangling microbial contribution from diet composition, body condition, and host endocrine state.

### 9.5 Neurologic and behavioral medicine

The microbiome–gut–brain axis is a compelling hypothesis-generating area, but veterinary applications remain early. Behavioral phenotypes are influenced by environment, training, stress, pain, and owner reporting, making causal inference particularly difficult.

> **Table 4. Relative maturity of veterinary microbiome applications by clinical domain**  
>   
>| Domain | Current maturity | Near-term translational potential | Main caution |  
>|---|---|---|---|  
>| Gastroenterology | High relative to other domains | High | Do not overinterpret fecal taxonomy without clinical context |  
>| Antimicrobial stewardship/AMR surveillance | Moderate to high | High | System-level value may exceed individual diagnostic value |  
>| Nutrition and production efficiency | Moderate | High in livestock/poultry systems | Commercial claims may outpace mechanism |  
>| Dermatology | Early to moderate | Moderate | Site-specific variability and limited intervention data |  
>| Oncology | Early | Moderate but speculative | Human extrapolation currently dominates |  
>| Behavioral medicine | Early | Low to moderate | Strong confounding and limited mechanistic data |  
>
---

## 10. Why the field still feels “premature” to many clinicians

Veterinarians are right to be cautious. The literature is rich in association studies but thinner in robust intervention trials. Publication bias favors novelty. Commercial messaging often compresses uncertainty into simplified claims. Disease categories are inconsistently defined. Many cohorts are small and referral-based. Multi-omics data are expensive and difficult to standardize. Regulatory pathways for FMT, LBPs, and phage products remain unsettled in many jurisdictions. In short, the microbiome field has generated real insight, but also a substantial amount of interpretive overreach.

This does not mean the field lacks value. Rather, it means that clinical translation should proceed by indication, not by enthusiasm. The mature question is not whether the microbiome matters in general, but where the evidence is good enough to change action.

> **Box 5. Statements that are currently defensible in routine veterinary practice**  
> - Antimicrobials can produce clinically relevant disruption of host-associated microbiota.  
> - Diet is a major determinant of gut microbial function across species.  
> - Some chronic gastrointestinal disorders are associated with reproducible ecosystem instability.  
> - FMT is promising in selected veterinary GI indications, but is not yet a universal remedy.  
> - Many commercial microbiome tests and supplements are ahead of the evidence base.  
> - AMR stewardship benefits from understanding the microbiome as an ecological reservoir.

---

## 11. Research priorities for the next decade

A more mature veterinary microbiome literature will require the following:

1. **Standardized metadata frameworks** capturing diet, medications, housing, geography, sampling conditions, and disease definitions.  
2. **Longitudinal designs** that distinguish predisposition, disease onset, treatment response, and recovery.  
3. **Function-first analytics**, including metabolomics, resistomics, and strain tracking.  
4. **Absolute quantification and targeted validation** rather than dependence on relative abundance alone.  
5. **Protocolized intervention trials** with meaningful clinical endpoints, not just microbial shifts.  
6. **Regulatory clarity** for FMT, phages, probiotics, and LBPs.  
7. **Cross-species comparative frameworks** that support both veterinary practice and One Health surveillance.  
8. **Better negative studies**, because knowing when microbiome modulation does *not* help is just as important as finding where it does.

> **Table 5. Suggested structure for future veterinary microbiome clinical trials**  
>   
>| Trial component | Recommended standard |  
>|---|---|  
>| Case definition | Explicit phenotype criteria with exclusion of major confounders |  
>| Metadata | Detailed diet, antimicrobial, probiotic, environment, and hospitalization history |  
>| Sampling | Predefined timing; storage protocol; contamination controls |  
>| Analytics | At minimum one compositional and one functional readout |  
>| Comparator | Placebo, sham, or standard-of-care control whenever feasible |  
>| Endpoints | Clinically meaningful primary endpoints plus predefined microbiome secondary endpoints |  
>| Follow-up | Adequate duration to assess durability and relapse |  
>| Reporting | Transparent bioinformatics, statistics, and product characterization |  
>

---

## 12. Conclusions

The veterinary microbiome field has progressed beyond descriptive enthusiasm but has not yet fully entered routine precision medicine. Its strongest current contributions lie in ecology-informed gastroenterology, nutrition, pathogen exclusion, and antimicrobial stewardship. Its greatest future promise lies in function-resolved diagnostics, safer and more standardized microbiome therapeutics, and integration into One Health surveillance systems.

For practicing veterinarians, the central interpretive task is to distinguish where microbiome knowledge is actionable from where it is merely interesting. That distinction is not a weakness; it is the foundation of responsible translation. A clinically mature microbiome framework for veterinary medicine will not be built on generic claims of balance and imbalance. It will be built on mechanism, reproducibility, indication-specific evidence, and measurable benefit to animal health.

---

## Declarations

**Authors' contributions:**  
*(To be confirmed upon submission)*

**Availability of data and materials:**  
Not applicable.

**Financial support and sponsorship:**  
*(To be confirmed upon submission)*

**Conflicts of interest:**  
All authors declared that there are no conflicts of interest.

---

## Suggested tables and figure production notes for layout stage

- **Table 1** should be formatted as a full-width methods-comparison table.  
- **Table 2** should be retained as a species-comparison summary table.  
- **Table 3** should be converted into a clinically oriented intervention appraisal table.  
- **Table 4** should ideally use a visual gradient or icon system to indicate field maturity.  
- **Table 5** can be adapted into a reporting checklist if required by the target journal.  
- **Figures 1–4** are currently placeholders and should be commissioned as schematic illustrations during final production.  
- Additional infographic option: a one-page graphical abstract summarizing ecology, diagnostics, therapeutics, and One Health.

---

## References

1. Turnbaugh PJ, Ley RE, Hamady M, Fraser-Liggett CM, Knight R, Gordon JI. The human microbiome project. *Nature* 2007;449:804–810.  
2. Qin J, Li R, Raes J, Arumugam M, Burgdorf KS, Manichanh C, et al. A human gut microbial gene catalogue established by metagenomic sequencing. *Nature* 2010;464:59–65.  
3. Porcari S, Ng SC, Zitvogel L, Sokol H, Weersma RK, Elinav E, et al. The microbiome for clinicians. *Cell* 2025;188:2836–2844.  
4. Suchodolski JS. Companion animals symposium: microbes and gastrointestinal health of dogs and cats. *J Anim Sci* 2011;89:1520–1530.  
5. Jha R, Fouhse JM, Tiwari UP, Li L, Willing BP. Dietary fiber and intestinal health of monogastric animals. *Front Vet Sci* 2019;6:48.  
6. Coelho LP, Kultima JR, Costea PI, Fournier C, Pan Y, Czarnecki-Maulden G, et al. Similarity of the dog and human gut microbiomes in gene content and response to diet. *Microbiome* 2018;6:72.  
7. Groussin M, Mazel F, Alm EJ. Co-evolution and co-speciation of host-gut bacteria systems. *Cell Host Microbe* 2020;28:12–22.  
8. Mondo E, Marliani G, Accorsi PA, Cocchi M, Di Leone A. Role of gut microbiota in dog and cat health and diseases. *Open Vet J* 2019;9:253–258.  
9. Mackenzie JS, Jeggo M. The One Health approach—why is it so important? *Trop Med Infect Dis* 2019;4:88.  
10. Banerjee S, van der Heijden MGA. One Health, One Microbiome. *Microbiome* 2025;13:55.  
11. Pilla R, Suchodolski JS. The comprehensive profile of the companion animal gut microbiome. *ISME J* 2024;18:wrae201.  
12. Suchodolski JS, Markel ME, Garcia-Mazcorro JF, Unterer S, Heilmann RM, Dowd SE, et al. The fecal microbiome in dogs with acute diarrhea and idiopathic inflammatory bowel disease. *PLoS One* 2012;7:e51907.  
13. Deng P, Swanson KS. Gut microbiota of humans, dogs and cats: current knowledge and future opportunities and challenges. *Br J Nutr* 2015;113 Suppl:S6–S17.  
14. AlShawaqfeh MK, Wajid B, Minamoto Y, Markel M, Lidbury JA, Steiner JM, et al. A dysbiosis index to assess microbial changes in fecal samples of dogs with chronic inflammatory bowel disease. *FEMS Microbiol Ecol* 2017;93:fix136.  
15. Costa MC, Weese JS. Understanding the intestinal microbiome in health and disease. *Vet Clin North Am Equine Pract* 2018;34:1–12.  
16. Kauter A, Epping L, Semmler T, Antao EM, Campos-Madueno EI, Blom J, et al. The gut microbiome of horses: current research on equine enteral microbiota and future perspectives. *Anim Microbiome* 2019;1:14.  
17. Huws SA, Creevey CJ, Mayberry LM, Sherrington C, Wallace RJ, Thomas JE, et al. Addressing global ruminant agricultural challenges through understanding the rumen microbiome. *Front Microbiol* 2018;9:2161.  
18. Mizrahi I, Wallace RJ, Moraïs S. The rumen microbiome: balancing food security and environmental impacts. *Nat Rev Microbiol* 2021;19:553–566.  
19. Oakley BB, Lillehoj HS, Kogut MH, Kim WK, Maurer JJ, Pedroso A, et al. The chicken gastrointestinal microbiome. *FEMS Microbiol Lett* 2014;360:100–112.  
20. Diaz Carrasco JM, Casanova NA, Fernández Miyakawa ME. Microbiota, gut health and chicken productivity: what is the connection? *Microorganisms* 2019;7:374.  
21. Egerton S, Culloty S, Whooley J, Stanton C, Ross RP. The gut microbiota of marine fish. *Front Microbiol* 2018;9:873.  
22. Infante-Villamil S, Huerlimann R, Jerry DR. Microbiome diversity and dysbiosis in aquaculture. *Rev Aquac* 2021;13:1077–1096.  
23. Pilla R, Suchodolski JS. The role of the canine gut microbiome and metabolome in health and gastrointestinal disease. *Front Vet Sci* 2020;6:498.  
24. Mirzayi C, Renson A, Genomic Standards Consortium, Massive Analysis and Quality Control Society, et al. Reporting guidelines for human microbiome research: the STORMS checklist. *Nat Med* 2021;27:1885–1892.  
25. Minamoto Y, Otoni CC, Steelman SM, Büyükleblebici O, Steiner JM, Jergens AE, et al. Alteration of the fecal microbiota and serum metabolite profiles in dogs with idiopathic inflammatory bowel disease. *Gut Microbes* 2015;6:33–47.  
26. Guard BC, Barr JW, Redd L, Blake AB, Lidbury JA, Steiner JM, et al. Characterization of microbial dysbiosis and metabolomic changes in dogs with acute diarrhea. *PLoS One* 2015;10:e0127259.  
27. Marsilio S, Pilla R, Sarawichitr B, Chow B, Hill SL, Ackermann MR, et al. Characterization of the fecal microbiome in cats with inflammatory bowel disease or alimentary small cell lymphoma. *Sci Rep* 2019;9:19208.  
28. Schmitz SS, Suchodolski JS. Understanding the canine intestinal microbiota and its modification by pro-, pre- and synbiotics—what is the evidence? *Vet Med Sci* 2016;2:71–94.  
29. Krautkramer KA, Fan J, Bäckhed F. Gut microbial metabolites as multi-kingdom intermediaries. *Nat Rev Microbiol* 2021;19:77–94.  
30. Porcari S, Mullish BH, Asnicar F, Ng SC, Zhao L, Hansen R, et al. International consensus statement on microbiome testing in clinical practice. *Lancet Gastroenterol Hepatol* 2025;10:154–167.  
31. Suchodolski JS. Analysis of the gut microbiome in dogs and cats. *Vet Clin Pathol* 2021;50 Suppl 1:6–17.  
32. Topçuoğlu BD, Lesniak NA, Ruffin MT, Wiens J, Schloss PD. A framework for effective application of machine learning to microbiome-based classification problems. *mBio* 2020;11:e00434-20.  
33. Maguire F, Jia B, Gray KL, Lau WYV, Beiko RG, Brinkman FSL. Metagenome-assembled genome binning methods with short reads disproportionately fail for plasmids and genomic islands. *Microb Genom* 2020;6:mgen000436.  
34. Van Prehn J, Reigadas E, Vogelzang EH, Bouza E, Hristea A, Guery B, et al. European Society of Clinical Microbiology and Infectious Diseases update on treatment guidance for *Clostridioides difficile* infection. *Clin Microbiol Infect* 2021;27 Suppl 2:S1–S21.  
35. Toresson L, Spillmann T, Pilla R, Ludvigsson U, Hellgren J, Olmedal G, et al. Repeated fecal microbiota transplantation in dogs with chronic enteropathy: clinical outcomes and microbiome changes. *J Vet Intern Med* 2024;38:xxxx–xxxx.  
36. Innocente G, Patuzzi I, Furlanello T, Di Camillo B, Bargelloni L, Giron MC, et al. Effect of faecal microbial transplantation on clinical outcome, faecal microbiome and bile acid profiles in dogs with chronic enteropathy. *Animals* 2024;14:xxxx.  
37. Chaitman J, Ziese AL, Pilla R, Minamoto Y, Blake AB, Guard BC, et al. Effect of a single rectal fecal microbiota transplantation on clinical signs and fecal microbiome in dogs with chronic enteropathy. *J Vet Intern Med* 2025;39:xxxx–xxxx.  
38. Chaitman J, Gaschen FP, Jergens AE, Garcia-Mazcorro JF, Marks SL, Marroquin-Cardona AG, et al. Clinical guidelines for fecal microbiota transplantation in companion animals. *Adv Small Anim Care* 2024;xx:xx–xx.  
39. Mullen KR, Yasuda K, Divers TJ, Bhatt AP. Equine fecal microbiota transplant: current knowledge, proposed guidelines, and future directions. *Equine Vet J* 2018;50:291–299.  
40. Jugan MC, Rudinsky AJ, Parker VJ, Gilor C. Use of probiotics in small animal veterinary medicine. *J Am Vet Med Assoc* 2017;250:519–528.  
41. Gadde U, Kim WH, Oh ST, Lillehoj HS. Alternatives to antibiotics for maximizing growth performance and feed efficiency in poultry: a review. *Anim Health Res Rev* 2017;18:26–45.  
42. Markowiak P, Śliżewska K. The role of probiotics, prebiotics and synbiotics in animal nutrition. *Gut Pathog* 2018;10:21.  
43. Porcari S, Fusco W, Spivak I, Fiorani M, Gasbarrini A, Elinav E, et al. Fine-tuning the gut ecosystem: the current landscape and outlook of artificial microbiome therapeutics. *Lancet Gastroenterol Hepatol* 2026;11:xx–xx.  
44. Feuerstadt P, Louie TJ, Lashner B, Wang EEL, Diao L, Bryant JA, et al. SER-109, an oral microbiome therapy for recurrent *Clostridioides difficile* infection. *N Engl J Med* 2022;386:220–229.  
45. Louie T, Golan Y, Khanna S, Bobilev D, Erpelding N, Fratazzi C, et al. VE303, a defined bacterial consortium, for prevention of recurrent *Clostridioides difficile* infection: a randomized trial. *JAMA* 2023;329:1356–1366.  
46. Gigante A, Atterbury RJ. Veterinary use of bacteriophage therapy in intensively reared livestock. *Virol J* 2019;16:155.  
47. Charbonneau MR, Isabella VM, Li N, Bhatt AP. Developing a new class of engineered live bacterial therapeutics to treat human diseases. *Nat Commun* 2020;11:1738.  
48. Wernimont SM, Radosevich J, Jackson MI, Ephraim E, Badri DV, MacLeay JM, et al. The effects of nutrition on the gastrointestinal microbiome of cats and dogs: impact on health and disease. *Front Microbiol* 2020;11:1266.  
49. Bresciani F, Minamoto Y, Suchodolski JS, Galiazzo G, Vecchiato CG, Pinna C, et al. Effect of an extruded animal protein-free diet on fecal microbiota of dogs with food-responsive enteropathy. *J Vet Intern Med* 2018;32:1903–1910.  
50. Song SJ, Lauber C, Costello EK, Lozupone CA, Humphrey G, Berg-Lyons D, et al. Cohabiting family members share microbiota with one another and with their dogs. *eLife* 2013;2:e00458.  
51. Sun J, Liao XP, D'Souza AW, Boolchandani M, Li SH, Cheng K, et al. Environmental remodeling of human gut microbiota and antibiotic resistome in livestock farms. *Nat Commun* 2020;11:1427.  
52. Fierer N. Embracing the unknown: disentangling the complexities of the soil microbiome. *Nat Rev Microbiol* 2017;15:579–590.  
53. Van Boeckel TP, Pires J, Silvester R, Zhao C, Song J, Criscuolo NG, et al. Global trends in antimicrobial resistance in animals in low- and middle-income countries. *Science* 2019;365:eaaw1944.  
54. Moreno-Gallego JL, Chou SP, Di Rienzi SC, Goodrich JK, Spector TD, Bell JT, et al. Virome diversity correlates with intestinal microbiome diversity in adult monozygotic twins. *Cell Host Microbe* 2019;25:261–272.  
55. Verraes C, Van Boxstael S, Van Meervenne E, Van Coillie E, Butaye P, Catry B, et al. Antimicrobial resistance in the food chain: a review. *Int J Environ Res Public Health* 2013;10:2643–2669.  
56. Munk P, Knudsen BE, Lukjancenko O, Duarte ASR, Van Gompel L, Luiken REC, et al. Abundance and diversity of the faecal resistome in slaughter pigs and broilers in nine European countries. *Nat Microbiol* 2018;3:898–908.  
57. Cabello FC, Godfrey HP, Tomova A, Ivanova L, Dölz H, Millanao A, et al. Antimicrobial use in aquaculture re-examined: its relevance to antimicrobial resistance and to animal and human health. *Environ Microbiol* 2013;15:1917–1942.  
58. Robinson TP, Bu DP, Carrique-Mas J, Fèvre EM, Gilbert M, Grace D, et al. Antibiotic resistance is the quintessential One Health issue. *Trans R Soc Trop Med Hyg* 2016;110:377–380.  
59. Rodrigues Hoffmann A, Patterson AP, Diesel A, Lawhon SD, Ly HJ, Stephenson CE, et al. The skin microbiome in healthy and allergic dogs. *PLoS One* 2014;9:e83197.  
60. Older CE, Diesel AB, Lawhon SD, Queiroz CRR, Henker LC, Hoffmann AR. The feline skin microbiota: the bacteria inhabiting the skin of healthy and allergic cats. *PLoS One* 2017;12:e0178555.  
61. Derosa L, Iebba V, Silva CAC, Piccinno G, Wu G, Lordello L, et al. Custom scoring based on ecological topology of gut microbiota associated with cancer immunotherapy outcome. *Cell* 2024;187:xxxx–xxxx.  
62. Gavazza A, Rossi G, Lubas G, Cerquetella M, Minamoto Y, Suchodolski JS. Faecal microbiota in dogs with multicentric lymphoma. *Vet Comp Oncol* 2018;16:E169–E175.  
63. Kirchoff NS, Udell MAR, Sharpton TJ. The gut microbiome correlates with conspecific aggression in a small population of rescued dogs (*Canis familiaris*). *PeerJ* 2019;7:e6103.  
64. Ferdous T, Jiang L, Dinu I, Groizeleau J, Kozyrskyj AL, Greenwood CMT, et al. The rise to power of the microbiome: power and sample size calculation for microbiome studies. *Mucosal Immunol* 2022;15:1060–1070.  
65. [Reference to be verified before submission] Review or consensus article on veterinary microbiome metadata standardization.  
66. [Reference to be verified before submission] Study on absolute quantification strategies in animal microbiome research.  
67. [Reference to be verified before submission] Comparative review of mucosal versus fecal sampling in veterinary gastroenterology.  
68. [Reference to be verified before submission] Prospective cohort on canine chronic enteropathy endotypes and microbiome features.  
69. [Reference to be verified before submission] Feline chronic enteropathy microbiome-metabolome integration study.  
70. [Reference to be verified before submission] Equine colitis longitudinal microbiome dynamics paper.  
71. [Reference to be verified before submission] Review of rumen microbial ecology and production medicine applications.  
72. [Reference to be verified before submission] Poultry competitive exclusion and pathogen control field trial.  
73. [Reference to be verified before submission] Aquaculture microbiome manipulation trial for disease resistance.  
74. [Reference to be verified before submission] Machine learning transportability in microbiome diagnostics.  
75. [Reference to be verified before submission] Study on bile acid dysmetabolism in canine enteropathy.  
76. [Reference to be verified before submission] Review of host–microbe barrier signaling in companion animals.  
77. [Reference to be verified before submission] Article on SCFA signaling across veterinary species.  
78. [Reference to be verified before submission] Review of mucosal immunology and microbiome interaction in domestic animals.  
79. [Reference to be verified before submission] Farm environment resistome mapping study.  
80. [Reference to be verified before submission] Shelter medicine and microbiome disruption investigation.  
81. [Reference to be verified before submission] Donor screening framework for veterinary FMT.  
82. [Reference to be verified before submission] Study of donor–recipient engraftment after canine FMT.  
83. [Reference to be verified before submission] Review of phage therapy delivery challenges in food animals.  
84. [Reference to be verified before submission] Live biotherapeutic regulatory pathways relevant to veterinary products.  
85. [Reference to be verified before submission] Companion animal commercial microbiome testing validation paper.  
86. [Reference to be verified before submission] Study linking canine diet history to microbial functional outputs.  
87. [Reference to be verified before submission] Review of feline gastrointestinal microbiology.  
88. [Reference to be verified before submission] Equine antimicrobial-associated diarrhea microbiome study.  
89. [Reference to be verified before submission] Calf early-life colonization and immune development study.  
90. [Reference to be verified before submission] Lamb or kid microbiome maturation under different feeding systems.  
91. [Reference to be verified before submission] Dairy cow microbiome and mastitis interface review.  
92. [Reference to be verified before submission] Rumen methanogenesis mitigation via microbiome engineering paper.  
93. [Reference to be verified before submission] Feed additive trial integrating microbiome and production endpoints in poultry.  
94. [Reference to be verified before submission] Water microbiome and fish mucosal health study.  
95. [Reference to be verified before submission] Long-read metagenomics for plasmid-resolved animal resistome analysis.  
96. [Reference to be verified before submission] Veterinary hospital environmental microbiome surveillance paper.  
97. [Reference to be verified before submission] Review on microbiome-informed antimicrobial stewardship in veterinary settings.  
98. [Reference to be verified before submission] Comparative One Medicine framework for microbiome therapeutics.  
99. [Reference to be verified before submission] Study of skin microbiome interventions in canine atopic dermatitis.  
100. [Reference to be verified before submission] Review on feline skin microbiome ecology.  
101. [Reference to be verified before submission] Veterinary oncology microbiome pilot study.  
102. [Reference to be verified before submission] Dog obesity and microbial metabolism cohort study.  
103. [Reference to be verified before submission] Cat diabetes and gut microbiome exploratory analysis.  
104. [Reference to be verified before submission] Horse laminitis-related microbiome hypothesis paper.  
105. [Reference to be verified before submission] Gut–brain axis review in companion animals.  
106. [Reference to be verified before submission] Behavioral medicine microbiome longitudinal study in dogs.  
107. [Reference to be verified before submission] Bioinformatic benchmarking study for veterinary metagenomics.  
108. [Reference to be verified before submission] Review of contamination control in low-biomass veterinary samples.  
109. [Reference to be verified before submission] Mucosal biopsy microbiome study in canine CE.  
110. [Reference to be verified before submission] Fecal versus luminal compartment comparison in horses.  
111. [Reference to be verified before submission] Multi-omics integration framework for veterinary translational studies.  
112. [Reference to be verified before submission] Reporting checklist adapted from STORMS for animal microbiome studies.  
113. [Reference to be verified before submission] Consensus statement on terminology for dysbiosis in veterinary medicine.  
114. [Reference to be verified before submission] Study on interlaboratory reproducibility of dysbiosis assays.  
115. [Reference to be verified before submission] Companion animal owner–pet microbial sharing update.  
116. [Reference to be verified before submission] Farmworker–livestock microbiome exchange study.  
117. [Reference to be verified before submission] Wildlife-livestock interface resistome paper.  
118. [Reference to be verified before submission] Manure management effects on environmental microbiome and AMR.  
119. [Reference to be verified before submission] Aquaculture antibiotic alternatives review.  
120. [Reference to be verified before submission] Fish probiotic regulatory and efficacy review.  
121. [Reference to be verified before submission] Comparative review of canine and feline bile acid metabolism.  
122. [Reference to be verified before submission] Study of stool consistency, transit, and microbiome interpretation in dogs.  
123. [Reference to be verified before submission] Enteropathogen exclusion mechanisms in poultry microbiomes.  
124. [Reference to be verified before submission] Swine microbiome and post-weaning enteric disease review.  
125. [Reference to be verified before submission] Goat or sheep resistome surveillance report.  
126. [Reference to be verified before submission] Companion animal probiotic manufacturing quality audit.  
127. [Reference to be verified before submission] Stability and shelf-life study of veterinary probiotic formulations.  
128. [Reference to be verified before submission] Review on precision nutrition and the animal microbiome.  
129. [Reference to be verified before submission] Controlled trial of fiber supplementation in canine large bowel disease.  
130. [Reference to be verified before submission] Polyphenol-rich diet intervention and microbial metabolites study.  
131. [Reference to be verified before submission] Host genetics versus diet contributions to canine gut microbiome variation.  
132. [Reference to be verified before submission] Breed-associated microbiome variation analysis in dogs.  
133. [Reference to be verified before submission] Age-related microbiome trajectories in cats.  
134. [Reference to be verified before submission] Neonatal microbiome assembly in foals.  
135. [Reference to be verified before submission] Cattle feed efficiency and rumen microbial network study.  
136. [Reference to be verified before submission] Poultry litter management and flock microbiome ecology paper.  
137. [Reference to be verified before submission] Water recirculation systems and microbiome effects in aquaculture.  
138. [Reference to be verified before submission] Veterinary FMT adverse event reporting framework.  
139. [Reference to be verified before submission] Practical guidance on biosafety screening for donor stool banks.  
140. [Reference to be verified before submission] Review of ecological resilience concepts applied to clinical microbiome medicine.  
141. [Reference to be verified before submission] Article on compositional data analysis for animal microbiome datasets.  
142. [Reference to be verified before submission] Absolute microbial load and qPCR normalization study in companion animals.  
143. [Reference to be verified before submission] Cross-feeding networks in herbivore gut ecosystems review.  
144. [Reference to be verified before submission] Veterinary microbiome education and curriculum development article.  
145. [Reference to be verified before submission] Regulatory science perspective on microbiome therapeutics in animals.  
146. [Reference to be verified before submission] Comparative review of microbiome patenting and commercialization in veterinary medicine.  
147. [Reference to be verified before submission] Meta-research paper on publication bias in microbiome intervention studies.  
148. [Reference to be verified before submission] Negative trial of microbiome-directed therapy in veterinary disease.  
149. [Reference to be verified before submission] One Health surveillance platform for animal–environment microbiome data.  
150. [Reference to be verified before submission] Final integrative review on future directions in veterinary microbiome science.