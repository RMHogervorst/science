Multiple search strategies to use for instance in webofscience
Use AND to connect different parts.
---
title: "Search strategies"
output:
  html_document:
    toc: true
    theme: united
---

#Including
##Stress
(stress* OR distress OR anxiety OR depression)

##Training
( training OR therapy OR exercise)

##Stroop
(cognitive-conflict OR stroop)

##meditation, yoga and other alternative / complementary therapies.
(taiji OR tai-chi OR meditation* OR "qi gong" OR qi-gong OR mindfulnes* OR MBSR OR MBCT OR "breathing exercises" pranayama OR nishino )


##TRIER
("Trier social stress" OR TSST)

##PASAT
("paced auditory serial addition" OR PASAT)

##Immunesystem
(cytokin* OR antibod* OR immun*   OR IL-* OR interleuk* OR "acute phase respon*" OR inflammat* OR monocytes OR   leucocytes OR endotoxemia OR "natural   killer" OR interferon OR lymphocyt* OR LPS   or "sickness behav*" )
###inflammation
(inflamm*)
###cytokines
(cytokin* OR immun* OR IL-*)
###wound healing methods
((punch OR biopsy OR wound OR ulcer OR "transepidermal water loss") AND skin AND healing )
###LPS in vivo
(LPS or endotoxin) AND ( invitro OR "in vitro" OR in-vitro))

###LPS in vitro (ex-vivo)
(LPS or endotoxin) AND ("ex vivo" OR ex-vivo OR exvivo)

###typhoid fever injection
("typhoid fever" OR salmonella-typhi OR "s.typhi" OR "S. typhi")
###influenza
(influenza AND (vaccine OR injection))

##Physical tests
(ergometer OR bruce OR treadmill OR astrand OR "YMCA cycle" OR "walk test" OR "walk distance")
###six minute walking test
(6MWT OR "six-minute walk distance" OR 6MWD OR "six-minute walk test")

##cognitive behavioral therapies.
((psychologic* OR cognitiv* OR behavioral* OR CBT) AND (therap* OR task*))

##meta-analyses
("systematic review" OR meta-analys* OR "meta analysis" OR Cochrane)

##systems biology
(network* OR chaoti* OR "non-linear" or "non linear" OR "systems biology" OR *ommics)

##multilevel models
(multi-level OR "random effects" or "mixed model" or "random coefficient" or hierarchical or multilevel OR "covariance components models" OR "variance components models" )

##menstrual cycle
((hormon* AND female) OR menstruat* OR contraceptiv* OR ((follicl* OR luteal) AND phase) OR ovulation OR pregnan*)

#Excluding

##Just in humans, no animals
 human NOT (avian OR murine OR animal* OR monkey OR ferret OR horse OR equin* OR swine OR pig OR mice OR mouse OR rat)


##exclude technical papers.
NOT (device OR techni* OR pharmacol*) 

##diseases
NOT ( hepatit* OR cancer OR carcinom* OR dysplasia OR tumor OR HIV* OR "multiple scleros*" OR  leukemi* OR anemia OR chemotherapy OR pneumon* OR disease OR pathogenesis OR "organ dysfunction" OR mortality OR autoimmun* OR MSC OR "multipotent mesenchymal" OR human-immunodeficiency* OR immunodeficienc* OR asthma  OR diabetes OR apoptos* OR acne OR oncolog*  OR melanom* OR myelom*  OR lymphoma OR monoclonal-antibod* OR cateract* OR myasthenia* OR cystic* OR lupus* OR vasculit* OR colitis OR  myocard* OR *arthritic OR arthrit* OR psorias* OR rabies OR aneurys*   OR encephalitis OR mastitis OR "immunoglobin replacement therapy" OR diabet* OR mesoangioblast* OR anaphylactic* OR helicobacter OR leprosy OR fibromyalgia  OR tuberculos* OR MRSA OR "scarlet fever"OR poliomyelitis OR endocarditis OR meningitis  OR smallpox OR ulcers OR sarcoidosis OR cholera OR "tropical medicine" OR syphilis OR herpes OR malaria OR BRUCELLOSIS OR "influenza infection")

##other classifiers
OR guidelines
OR elderly OR *athletes OR neonates OR infants OR pediatric*
OR recombinant* OR transplantation OR receptors OR senescence OR telomerase OR "clinical   response" OR definition OR   drug* OR purification OR mutation OR pluripotency OR pharmacology OR   "therapeutic use" "vaccine design" OR artificial* OR "tissue engineer*"

OR aviation* OR forensic* OR emergency OR undersea
