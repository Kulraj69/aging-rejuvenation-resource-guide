# Aging and rejuvenation: an evidence guide

This guide separates aging mechanisms, animal interventions, human cells in vitro, human trials and aging biomarkers. A change in a methylation clock is not by itself proof of better health or longer human life. This is an educational bibliography, not treatment advice or a self-experimentation protocol.

## Questions to carry through the reading

- Is the endpoint lifespan, disease burden, physical function, a molecular marker or a clock score?
- Was the study randomized and controlled? How large was it, and what was the follow-up?
- Are reported analyses prespecified, exploratory or post hoc? What adverse events and null results were reported?
- Does a result in cells or mice support the claim being made about people?

## First useful projects

1. Build a human-trial evidence table from full texts: population, randomization, control, registered endpoint, sample size, follow-up, adverse events and null findings. Mark missing data explicitly.
2. Reproduce an aging-clock analysis with held-out subjects, batch-effect checks and a leakage audit. Keep clock change separate from clinical benefit.
3. Add negative and replication evidence. The RTB101 phase 3 result is deliberately included here so the guide does not read like an intervention advertisement.

## Scope and provenance

Prepared 17 November 2026 from a selected 66-work reading library: 17 mind/emulation, 18 BCI/neurotechnology and 31 aging/rejuvenation works. The underlying selection covers foundational work and selected publications through 2025. This is not an exhaustive, latest or systematic review.

The source library checked journal bibliographic records and abstracts and direct repository abstracts for the six arXiv entries. Reading notes are short original summaries, not full-text critical appraisals. This guide preserves those limits; it does not imply every full text was read. Paper full texts are linked, not redistributed. Source titles and author names remain attributed to their authors.

`papers.json` is the reusable source, `papers.bib` is a citation export, and `validate.py` checks local metadata. Validation is structural, not a scientific peer review or a live link check. No clinical datasets or participant-level records are included.

## Evidence labels

- **Theory / review / philosophy / roadmap:** synthesis or argument, not an experimental demonstration of uploading or rejuvenation.
- **Computational:** simulation or modeling; judge the model's measured validation target, not its name.
- **Animal / tissue:** results for the stated organism or preparation, not proof of a human outcome.
- **Human cells / in vitro:** experiments on cells, not treatment of a person.
- **Human feasibility / pilot:** limited early human evidence; do not infer population-wide effectiveness.
- **Human trial / RCT:** inspect population, controls, sample size, endpoints and harms. A randomized biomarker analysis is still a biomarker analysis.
- **arXiv / report:** repository-hosted work; the label alone does not establish journal peer review.

## Use and improve this guide

```sh
python3 validate.py papers.json
python3 -m unittest -v test_validate.py
```

Keep limitations attached to the result they qualify. See `CONTRIBUTING.md` for the review checklist. Repository documentation and code are private review material at this stage. No license grant is made for third-party papers. Before a wider release, choose terms for the original guide/code separately from rights in cited works.

## Suggested reading path

1. [The hallmarks of aging](https://doi.org/10.1016/j.cell.2013.05.039) (2013) - Review. The original nine-hallmark framework organizes mechanisms of mammalian aging. Limitation: Read with the 2023 update; neither is a clinical treatment protocol.
2. [Hallmarks of aging: An expanding universe](https://doi.org/10.1016/j.cell.2022.11.001) (2023) - Review. Updates the hallmarks framework to twelve interacting aging mechanisms. Limitation: A framework for research, not a proven anti-aging treatment list.
3. [In Vivo Amelioration of Age-Associated Hallmarks by Partial Reprogramming](https://doi.org/10.1016/j.cell.2016.11.052) (2016) - Animal / intervention. Cyclic partial reprogramming improves aging-related phenotypes and survival in progeroid mice. Limitation: Premature-aging model survival does not establish normal human lifespan extension.
4. [Multi-omic rejuvenation of human cells by maturation phase transient reprogramming](https://doi.org/10.7554/elife.71624) (2022) - Human cells / in vitro. Transient reprogramming shifts several aging-related measures in cultured fibroblasts. Limitation: Human cells in a dish, not rejuvenated people; clock changes are surrogate outcomes.
5. [Senolytics in idiopathic pulmonary fibrosis: Results from a first-in-human, open-label, pilot study](https://doi.org/10.1016/j.ebiom.2018.12.052) (2019) - Human / pilot. An open-label senolytic pilot tests feasibility in idiopathic pulmonary fibrosis. Limitation: 14 participants, no placebo control, adverse events; not healthy-person longevity evidence.
6. [mTOR inhibition improves immune function in the elderly](https://doi.org/10.1126/scitranslmed.3009892) (2014) - Human / trial. Tests an mTOR inhibitor against age-related vaccine-response impairment. Limitation: Immune-response endpoint, not human lifespan or whole-body rejuvenation.
7. [Targeting the biology of ageing with mTOR inhibitors to improve immune function in older adults: phase 2b and phase 3 randomised trials](https://doi.org/10.1016/S2666-7568(21)00062-3) (2021) - Human / RCT. Reports phase 2b and phase 3 RTB101 trials, including a negative phase 3 primary endpoint. Limitation: Promising immune-gene signals did not translate into fewer clinically symptomatic respiratory illnesses in phase 3.
8. [Effect of long-term caloric restriction on DNA methylation measures of biological aging in healthy adults from the CALERIE trial](https://doi.org/10.1038/s43587-022-00357-y) (2023) - Human / RCT analysis. CALERIE analysis finds a small change in DunedinPACE after calorie restriction. Limitation: Post hoc biomarker analysis; other age clocks did not significantly change; not mortality evidence.

## Annotated bibliography

### P36. Hallmarks of aging: An expanding universe

López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. (2023). *Cell*.

**Evidence:** Review.

**Why read:** Updates the hallmarks framework to twelve interacting aging mechanisms.

**Limit:** A framework for research, not a proven anti-aging treatment list.

[Primary record](https://doi.org/10.1016/j.cell.2022.11.001)

Verification: Bibliographic record and abstract checked.

### P37. In Vivo Amelioration of Age-Associated Hallmarks by Partial Reprogramming

Ocampo A, Reddy P, Martinez-Redondo P, Platero-Luengo A, Hatanaka F, Hishida T, Li M, Lam D, Kurita M, Beyret E, Araoka T, Vazquez-Ferrer E, Donoso D, Roman JL, Xu J, Rodriguez Esteban C, Nuñez G, Nuñez Delicado E, Campistol JM, Guillen I, Guillen P, Izpisua Belmonte JC. (2016). *Cell*.

**Evidence:** Animal / intervention.

**Why read:** Cyclic partial reprogramming improves aging-related phenotypes and survival in progeroid mice.

**Limit:** Premature-aging model survival does not establish normal human lifespan extension.

[Primary record](https://doi.org/10.1016/j.cell.2016.11.052) | [Open-text link](https://europepmc.org/articles/PMC5679279)

Verification: Bibliographic record and abstract checked.

### P38. Reprogramming to recover youthful epigenetic information and restore vision

Lu Y, Brommer B, Tian X, Krishnan A, Meer M, Wang C, Vera DL, Zeng Q, Yu D, Bonkowski MS, Yang JH, Zhou S, Hoffmann EM, Karg MM, Schultz MB, Kane AE, Davidsohn N, Korobkina E, Chwalek K, Rajman LA, Church GM, Church GM, Hochedlinger K, Gladyshev VN, Horvath S, Levine ME, Gregory-Ksander MS, Ksander BR, He Z, Sinclair DA. (2020). *Nature*.

**Evidence:** Animal / intervention.

**Why read:** OSK reprogramming restores regenerative and visual functions in mouse eyes.

**Limit:** Tissue-specific mouse outcomes, not whole-person age reversal.

[Primary record](https://doi.org/10.1038/s41586-020-2975-4) | [Open-text link](https://europepmc.org/articles/PMC7752134)

Verification: Bibliographic record and abstract checked.

### P39. Cellular reprogramming and epigenetic rejuvenation

Simpson DJ, Olova NN, Chandra T. (2021). *Clinical epigenetics*.

**Evidence:** Review.

**Why read:** Explains how epigenetic rejuvenation might be separated from loss of cell identity.

**Limit:** Translational strategy and review, not human efficacy evidence.

[Primary record](https://doi.org/10.1186/s13148-021-01158-7) | [Open-text link](https://europepmc.org/articles/PMC8419998)

Verification: Bibliographic record and abstract checked.

### P40. In vivo partial reprogramming alters age-associated molecular changes during physiological aging in mice

Browder KC, Reddy P, Yamamoto M, Haghani A, Guillen IG, Sahu S, Wang C, Luque Y, Prieto J, Shi L, Shojima K, Hishida T, Lai Z, Li Q, Choudhury FK, Wong WR, Liang Y, Sangaraju D, Sandoval W, Esteban CR, Delicado EN, Garcia PG, Pawlak M, Vander Heiden JA, Horvath S, Jasper H, Izpisua Belmonte JC. (2022). *Nature aging*.

**Evidence:** Animal / intervention.

**Why read:** Studies longer-term partial reprogramming during normal aging in mice.

**Limit:** Molecular/tissue improvements do not establish safe human systemic reprogramming.

[Primary record](https://doi.org/10.1038/s43587-022-00183-2)

Verification: Bibliographic record and abstract checked.

### P41. Multi-omic rejuvenation of human cells by maturation phase transient reprogramming

Gill D, Parry A, Santos F, Okkenhaug H, Todd CD, Hernando-Herraez I, Stubbs TM, Milagre I, Reik W. (2022). *eLife*.

**Evidence:** Human cells / in vitro.

**Why read:** Transient reprogramming shifts several aging-related measures in cultured fibroblasts.

**Limit:** Human cells in a dish, not rejuvenated people; clock changes are surrogate outcomes.

[Primary record](https://doi.org/10.7554/elife.71624) | [Open-text link](https://europepmc.org/articles/PMC9023058)

Verification: Bibliographic record and abstract checked.

### P42. Chemically induced reprogramming to reverse cellular aging

Yang JH, Petty CA, Dixon-McDougall T, Lopez MV, Tyshkovskiy A, Maybury-Lewis S, Tian X, Ibrahim N, Chen Z, Griffin PT, Arnold M, Li J, Martinez OA, Behn A, Rogers-Hammond R, Angeli S, Gladyshev VN, Sinclair DA. (2023). *Aging*.

**Evidence:** Human cells / in vitro.

**Why read:** Screens chemical cocktails that shift cellular aging signatures.

**Limit:** Cell assays do not prove human safety, durable rejuvenation or longer life.

[Primary record](https://doi.org/10.18632/aging.204896) | [Open-text link](https://europepmc.org/articles/PMC10373966)

Verification: Bibliographic record and abstract checked.

### P43. Clearance of p16Ink4a-positive senescent cells delays ageing-associated disorders

Baker DJ, Wijshake T, Tchkonia T, LeBrasseur NK, Childs BG, van de Sluis B, Kirkland JL, van Deursen JM. (2011). *Nature*.

**Evidence:** Animal / intervention.

**Why read:** Genetically clearing senescent cells delays selected disorders in progeroid mice.

**Limit:** Engineered premature-aging mice; not a supplement trial.

[Primary record](https://doi.org/10.1038/nature10600) | [Open-text link](https://europepmc.org/articles/PMC3468323)

Verification: Bibliographic record and abstract checked.

### P44. Naturally occurring p16(Ink4a)-positive cells shorten healthy lifespan

Baker DJ, Childs BG, Durik M, Wijers ME, Sieben CJ, Zhong J, Saltness RA, Jeganathan KB, Verzosa GC, Pezeshki A, Khazaie K, Miller JD, van Deursen JM. (2016). *Nature*.

**Evidence:** Animal / intervention.

**Why read:** Clearing p16-positive cells extends median lifespan in mouse cohorts.

**Limit:** Genetic cell-clearance system, not direct evidence for a human drug regimen.

[Primary record](https://doi.org/10.1038/nature16932) | [Open-text link](https://europepmc.org/articles/PMC4845101)

Verification: Bibliographic record and abstract checked.

### P45. Senolytics improve physical function and increase lifespan in old age

Xu M, Pirtskhalava T, Farr JN, Weigand BM, Palmer AK, Weivoda MM, Inman CL, Ogrodnik MB, Hachfeld CM, Fraser DG, Onken JL, Johnson KO, Verzosa GC, Langhi LGP, Weigl M, Giorgadze N, LeBrasseur NK, Miller JD, Jurk D, Singh RJ, Allison DB, Ejima K, Hubbard GB, Ikeno Y, Cubro H, Garovic VD, Hou X, Weroha SJ, Robbins PD, Niedernhofer LJ, Khosla S, Tchkonia T, Kirkland JL. (2018). *Nature medicine*.

**Evidence:** Animal / intervention.

**Why read:** Senolytic treatment improves function and remaining survival in old mice.

**Limit:** Includes human tissue experiments, but the lifespan evidence is in mice.

[Primary record](https://doi.org/10.1038/s41591-018-0092-9) | [Open-text link](https://europepmc.org/articles/PMC6082705)

Verification: Bibliographic record and abstract checked.

### P46. Fisetin is a senotherapeutic that extends health and lifespan

Yousefzadeh MJ, Zhu Y, McGowan SJ, Angelini L, Fuhrmann-Stroissnigg H, Xu M, Ling YY, Melos KI, Pirtskhalava T, Inman CL, McGuckian C, Wade EA, Kato JI, Grassi D, Wentworth M, Burd CE, Arriaga EA, Ladiges WL, Tchkonia T, Kirkland JL, Robbins PD, Niedernhofer LJ. (2018). *EBioMedicine*.

**Evidence:** Animal / intervention.

**Why read:** Tests fisetin for senescence-related tissue and lifespan effects in mice.

**Limit:** Human tissue work does not establish that taking fisetin extends human life.

[Primary record](https://doi.org/10.1016/j.ebiom.2018.09.015) | [Open-text link](https://europepmc.org/articles/PMC6197652)

Verification: Bibliographic record and abstract checked.

### P47. Senolytics in idiopathic pulmonary fibrosis: Results from a first-in-human, open-label, pilot study

Justice JN, Nambiar AM, Tchkonia T, LeBrasseur NK, Pascual R, Hashmi SK, Prata L, Masternak MM, Kritchevsky SB, Musi N, Kirkland JL. (2019). *EBioMedicine*.

**Evidence:** Human / pilot.

**Why read:** An open-label senolytic pilot tests feasibility in idiopathic pulmonary fibrosis.

**Limit:** 14 participants, no placebo control, adverse events; not healthy-person longevity evidence.

[Primary record](https://doi.org/10.1016/j.ebiom.2018.12.052) | [Open-text link](https://europepmc.org/articles/PMC6412088)

Verification: Bibliographic record and abstract checked.

### P48. Senolytics decrease senescent cells in humans: Preliminary report from a clinical trial of Dasatinib plus Quercetin in individuals with diabetic kidney disease

Hickson LJ, Langhi Prata LGP, Bobart SA, Evans TK, Giorgadze N, Hashmi SK, Herrmann SM, Jensen MD, Jia Q, Jordan KL, Kellogg TA, Khosla S, Koerber DM, Lagnado AB, Lawson DK, LeBrasseur NK, Lerman LO, McDonald KM, McKenzie TJ, Passos JF, Pignolo RJ, Pirtskhalava T, Saadiq IM, Schaefer KK, Textor SC, Victorelli SG, Volkman TL, Xue A, Wentworth MA, Wissler Gerdes EO, Zhu Y, Tchkonia T, Kirkland JL. (2019). *EBioMedicine*.

**Evidence:** Human / pilot.

**Why read:** A small senolytic study measures changes in senescence markers in diabetic kidney disease.

**Limit:** Nine participants, open label and short follow-up; biomarker change is not lifespan extension.

[Primary record](https://doi.org/10.1016/j.ebiom.2019.08.069) | [Open-text link](https://europepmc.org/articles/PMC6796530)

Verification: Bibliographic record and abstract checked.

### P49. Rapamycin fed late in life extends lifespan in genetically heterogeneous mice

Harrison DE, Strong R, Sharp ZD, Nelson JF, Astle CM, Flurkey K, Nadon NL, Wilkinson JE, Frenkel K, Carter CS, Pahor M, Javors MA, Fernandez E, Miller RA. (2009). *Nature*.

**Evidence:** Animal / intervention.

**Why read:** Late-life rapamycin extends survival in genetically heterogeneous mice.

**Limit:** Mouse results do not establish a safe or effective human longevity regimen.

[Primary record](https://doi.org/10.1038/nature08221) | [Open-text link](https://europepmc.org/articles/PMC2786175)

Verification: Bibliographic record and abstract checked.

### P50. mTOR inhibition improves immune function in the elderly

Mannick JB, Del Giudice G, Lattanzi M, Valiante NM, Praestgaard J, Huang B, Lonetto MA, Maecker HT, Kovarik J, Carson S, Glass DJ, Klickstein LB. (2014). *Science translational medicine*.

**Evidence:** Human / trial.

**Why read:** Tests an mTOR inhibitor against age-related vaccine-response impairment.

**Limit:** Immune-response endpoint, not human lifespan or whole-body rejuvenation.

[Primary record](https://doi.org/10.1126/scitranslmed.3009892)

Verification: Bibliographic record and abstract checked.

### P51. TORC1 inhibition enhances immune function and reduces infections in the elderly

Mannick JB, Morris M, Hockey HP, Roma G, Beibel M, Kulmatycki K, Watkins M, Shavlakadze T, Zhou W, Quinn D, Glass DJ, Klickstein LB. (2018). *Science translational medicine*.

**Evidence:** Human / RCT.

**Why read:** A phase 2a trial tests TORC1 inhibition, immune responses and infections in older adults.

**Limit:** Read alongside the later phase 2b/3 report with a negative phase 3 primary endpoint.

[Primary record](https://doi.org/10.1126/scitranslmed.aaq1564)

Verification: Bibliographic record and abstract checked.

### P52. Effect of long-term caloric restriction on DNA methylation measures of biological aging in healthy adults from the CALERIE trial

Waziry R, Ryan CP, Corcoran DL, Huffman KM, Kobor MS, Kothari M, Graf GH, Kraus VB, Kraus WE, Lin DTS, Pieper CF, Ramaker ME, Bhapkar M, Das SK, Ferrucci L, Hastings WJ, Kebbe M, Parker DC, Racette SB, Shalev I, Schilling B, Belsky DW. (2023). *Nature aging*.

**Evidence:** Human / RCT analysis.

**Why read:** CALERIE analysis finds a small change in DunedinPACE after calorie restriction.

**Limit:** Post hoc biomarker analysis; other age clocks did not significantly change; not mortality evidence.

[Primary record](https://doi.org/10.1038/s43587-022-00357-y) | [Open-text link](https://europepmc.org/articles/PMC10148951)

Verification: Bibliographic record and abstract checked.

### P53. Fasting-mimicking diet and markers/risk factors for aging, diabetes, cancer, and cardiovascular disease

Wei M, Brandhorst S, Shelehchi M, Mirzaei H, Cheng CW, Budniak J, Groshen S, Mack WJ, Guen E, Di Biase S, Cohen P, Morgan TE, Dorff T, Hong K, Michalsen A, Laviano A, Longo VD. (2017). *Science translational medicine*.

**Evidence:** Human / RCT.

**Why read:** Tests cycles of a fasting-mimicking diet against metabolic and disease-risk markers.

**Limit:** Short-term risk-marker changes, not proof of longer life or cancer prevention.

[Primary record](https://doi.org/10.1126/scitranslmed.aai8700) | [Open-text link](https://europepmc.org/articles/PMC6816332)

Verification: Bibliographic record and abstract checked.

### P54. Nicotinamide riboside is uniquely and orally bioavailable in mice and humans

Trammell SA, Schmidt MS, Weidemann BJ, Redpath P, Jaksch F, Dellinger RW, Li Z, Abel ED, Migaud ME, Brenner C. (2016). *Nature communications*.

**Evidence:** Human + animal / pharmacokinetics.

**Why read:** Shows oral nicotinamide riboside can increase NAD-related metabolites.

**Limit:** Bioavailability is not proof of anti-aging benefit.

[Primary record](https://doi.org/10.1038/ncomms12948) | [Open-text link](https://europepmc.org/articles/PMC5062546)

Verification: Bibliographic record and abstract checked.

### P55. Chronic nicotinamide riboside supplementation is well-tolerated and elevates NAD+ in healthy middle-aged and older adults

Martens CR, Denman BA, Mazzo MR, Armstrong ML, Reisdorph N, McQueen MB, Chonchol M, Seals DR. (2018). *Nature communications*.

**Evidence:** Human / RCT.

**Why read:** A short randomized crossover trial tests NR tolerability and NAD metabolism.

**Limit:** Short-term target engagement; no demonstrated human lifespan extension.

[Primary record](https://doi.org/10.1038/s41467-018-03421-7) | [Open-text link](https://europepmc.org/articles/PMC5876407)

Verification: Bibliographic record and abstract checked.

### P56. Long-Term Administration of Nicotinamide Mononucleotide Mitigates Age-Associated Physiological Decline in Mice

Mills KF, Yoshida S, Stein LR, Grozio A, Kubota S, Sasaki Y, Redpath P, Migaud ME, Apte RS, Uchida K, Yoshino J, Imai SI. (2016). *Cell metabolism*.

**Evidence:** Animal / intervention.

**Why read:** Long-term NMN treatment mitigates several age-related physiological changes in mice.

**Limit:** Mouse physiology, not established human rejuvenation.

[Primary record](https://doi.org/10.1016/j.cmet.2016.09.013) | [Open-text link](https://europepmc.org/articles/PMC5668137)

Verification: Bibliographic record and abstract checked.

### P57. Nicotinamide mononucleotide increases muscle insulin sensitivity in prediabetic women

Yoshino M, Yoshino J, Kayser BD, Patti GJ, Franczyk MP, Mills KF, Sindelar M, Pietka T, Patterson BW, Imai SI, Klein S. (2021). *Science (New York, N.Y.)*.

**Evidence:** Human / RCT.

**Why read:** Tests NMN against muscle insulin sensitivity in prediabetic postmenopausal women.

**Limit:** A specific metabolic endpoint and population, not general age reversal.

[Primary record](https://doi.org/10.1126/science.abe9985) | [Open-text link](https://europepmc.org/articles/PMC8550608)

Verification: Bibliographic record and abstract checked.

### P58. DNA methylation age of human tissues and cell types

Horvath S. (2013). *Genome biology*.

**Evidence:** Human / biomarker.

**Why read:** Introduces a multi-tissue DNA-methylation clock for age estimation.

**Limit:** Prediction of age is not validation of a treatment or a direct measure of remaining life.

[Primary record](https://doi.org/10.1186/gb-2013-14-10-r115) | [Open-text link](https://europepmc.org/articles/PMC4015143)

Verification: Bibliographic record and abstract checked.

### P59. An epigenetic biomarker of aging for lifespan and healthspan

Levine ME, Lu AT, Quach A, Chen BH, Assimes TL, Bandinelli S, Hou L, Baccarelli AA, Stewart JD, Li Y, Whitsel EA, Wilson JG, Reiner AP, Aviv A, Lohman K, Liu Y, Ferrucci L, Horvath S. (2018). *Aging*.

**Evidence:** Human / biomarker.

**Why read:** Develops PhenoAge using clinical-risk and DNA-methylation information.

**Limit:** Predictive associations do not show that changing the clock improves survival.

[Primary record](https://doi.org/10.18632/aging.101414) | [Open-text link](https://europepmc.org/articles/PMC5940111)

Verification: Bibliographic record and abstract checked.

### P60. DNA methylation GrimAge strongly predicts lifespan and healthspan

Lu AT, Quach A, Wilson JG, Reiner AP, Aviv A, Raj K, Hou L, Baccarelli AA, Li Y, Stewart JD, Whitsel EA, Assimes TL, Ferrucci L, Horvath S. (2019). *Aging*.

**Evidence:** Human / biomarker.

**Why read:** Develops GrimAge to predict mortality-related and healthspan-related outcomes.

**Limit:** Risk prediction is not a causal test of rejuvenation.

[Primary record](https://doi.org/10.18632/aging.101684)

Verification: Bibliographic record and abstract checked.

### P61. DunedinPACE, a DNA methylation biomarker of the pace of aging

Belsky DW, Caspi A, Corcoran DL, Sugden K, Poulton R, Arseneault L, Baccarelli A, Chamarti K, Gao X, Hannon E, Harrington HL, Houts R, Kothari M, Kwon D, Mill J, Schwartz J, Vokonas P, Wang C, Williams BS, Moffitt TE. (2022). *eLife*.

**Evidence:** Human / biomarker.

**Why read:** Develops DunedinPACE as a blood-based estimate of the pace of aging.

**Limit:** Useful research surrogate; changes need validation against clinical outcomes.

[Primary record](https://doi.org/10.7554/elife.73420) | [Open-text link](https://europepmc.org/articles/PMC8853656)

Verification: Bibliographic record and abstract checked.

### P62. Reversal of epigenetic aging and immunosenescent trends in humans

Fahy GM, Brooke RT, Watson JP, Good Z, Vasanawala SS, Maecker H, Leipold MD, Lin DTS, Kobor MS, Horvath S. (2019). *Aging cell*.

**Evidence:** Human / uncontrolled pilot.

**Why read:** Reports immune and epigenetic-clock changes after a thymus-focused intervention.

**Limit:** Small uncontrolled pilot; predicted lifespan is not observed lifespan extension.

[Primary record](https://doi.org/10.1111/acel.13028) | [Open-text link](https://europepmc.org/articles/PMC6826138)

Verification: Bibliographic record and abstract checked.

### P63. Partial cellular reprogramming: A deep dive into an emerging rejuvenation technology

Paine PT, Nguyen A, Ocampo A. (2024). *Aging cell*.

**Evidence:** Review.

**Why read:** Reviews partial cellular reprogramming, translation challenges and commercial interest.

**Limit:** A field overview, not evidence that systemic rejuvenation is ready for patients.

[Primary record](https://doi.org/10.1111/acel.14039) | [Open-text link](https://europepmc.org/articles/PMC10861195)

Verification: Bibliographic record and abstract checked.

### P64. The hallmarks of aging

López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G. (2013). *Cell*.

**Evidence:** Review.

**Why read:** The original nine-hallmark framework organizes mechanisms of mammalian aging.

**Limit:** Read with the 2023 update; neither is a clinical treatment protocol.

[Primary record](https://doi.org/10.1016/j.cell.2013.05.039) | [Open-text link](https://europepmc.org/articles/PMC3836174)

Verification: Bibliographic record and abstract checked.

### P65. Individual and additive effects of vitamin D, omega-3 and exercise on DNA methylation clocks of biological aging in older adults from the DO-HEALTH trial

Bischoff-Ferrari HA, Gängler S, Wieczorek M, Belsky DW, Ryan J, Kressig RW, Stähelin HB, Theiler R, Dawson-Hughes B, Rizzoli R, Vellas B, Rouch L, Guyonnet S, Egli A, Orav EJ, Willett W, Horvath S. (2025). *Nature aging*.

**Evidence:** Human / RCT analysis.

**Why read:** DO-HEALTH analysis reports small methylation-clock changes with omega-3 and some combinations.

**Limit:** Post hoc biomarker analysis, not demonstrated clinical age reversal or extra years of life.

[Primary record](https://doi.org/10.1038/s43587-024-00793-y) | [Open-text link](https://europepmc.org/articles/PMC11922767)

Verification: Bibliographic record and abstract checked.

### P66. Targeting the biology of ageing with mTOR inhibitors to improve immune function in older adults: phase 2b and phase 3 randomised trials

Mannick JB, Teo G, Bernardo P, Quinn D, Russell K, Klickstein L, Marshall W, Shergill S. (2021). *The lancet. Healthy longevity*.

**Evidence:** Human / RCT.

**Why read:** Reports phase 2b and phase 3 RTB101 trials, including a negative phase 3 primary endpoint.

**Limit:** Promising immune-gene signals did not translate into fewer clinically symptomatic respiratory illnesses in phase 3.

[Primary record](https://doi.org/10.1016/S2666-7568(21)00062-3) | [Open-text link](https://europepmc.org/articles/PMC8102040)

Verification: Bibliographic record and abstract checked.
