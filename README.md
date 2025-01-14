# Dissertation_Longitudinal_Analysis_Of_Farm_Animal_Development

Description:

Background
A local (Leeds) farm has been collecting data on new-born lambs over several
years. After each lamb is weaned there is a series of measurements which record
the weight, and the month of the recording. Each lamb will belong to a sin-
gle/twin/triplet, and its feeding may be assisted. Interest may lie in how the
growth curves
(a) differ according to the number in the litter
(b) are affected by the date of birth and/or sex
(c) change according to bottle-feeding, or fostering
(d) depend on the age of the ewe (female parent).
The lamb data exists in electronic data files for the seasons 2016–2022 (and – if
desired – may be keyed in for 2023). An initial part of the project is to carry out
an exploratory data analysis, with checking of unusual values. Analyzing growth
curves can take several forms. Starting points include longitudinal data analysis
and fitting of parametric models. When the data are dense, then functional data
analysis may also be appropriate.

MATH5872M: Dissertation in DSA Proposed dissertation topics 2023/24

Objectives - 
1. How do gender, breed, and litter size affect the growth trajectories of lambs?
2. What are the effective statistical and machine learning models for predicting lamb weight at various
 stages of growth?
3. How can these models be used to improve farm management practices, particularly in terms of opti
mizing breeding strategies and maximizing meat production?

## Observations
 • Gender-Based Weight Differences: Male lambs consistently achieved higher weights from early ages
 compared to female lambs.
 
 • WeightDifferences by Breed: Commercial lambs, regardless of gender, typically have higher weights
 than pedigree lambs. This difference often led to commercial lambs being sold primarily for meat,
 while pedigree lambs were typically reserved for breeding purposes.
 
 • Growth Patterns: The growth trajectories of commercial and pedigree lambs differed significantly,
 with commercial lambs having higher initial weights and continuously increasing thereafter. Pedigree
 lambs have lower weights in their early ages but grow faster later on. Regardless of breed, both types
 of lambs’ growth rates slowed between 200 and 250 days of age before growing again.
 
 • Impact of Litter Size on Male Lambs: The growth curve of male lambs showed a noticeable down
ward shift in trajectory as litter size increased, particularly in pedigree lambs. This indicates that lambs
 from larger litters are born with lower weights and maintain this lower weight pattern throughout their
 growth. In commercial lambs, the trajectory moves downward with bigger litter sizes, but the weight
 differential at later stages remains less evident. Litter sizes 3 and 4 almost have the same growth trend,
 with minor variations.
 
 • Impact of Litter Size on Female Lambs: Female lambs also displayed a similar pattern where litter
 size affected growth trajectory. However, the impact was less significant in pedigree lambs with litter
 sizes of 3 and 4 compared to those from smaller litters. It also shows that the initial weights of litter
 size 4 were higher but thereafter fell when compared to smaller litters, indicating a general pattern of
 lower weights as litter size increases. In commercial lambs, except for the data for litter size 4, the
 growth curves showed significant differences in growth trajectories, highlighting the impact of litter
 size on weight development.
 
 ## Conclusion
 The analysis demonstrated the effectiveness of non-parametric methods in providing accurate estimates of
 lamb weights. These methods proved particularly flexible, allowing for the modeling of growth curves with 
 out the need for predefined assumptions about the relationship between age and weight. However, while
 highly effective for lambs with similar characteristics, the accuracy of these methods may decrease when
 applied to lambs with varying traits, as their performance is closely tied to the specific data used.
 The study provides valuable insights into optimizing farm management practices by enabling precise
 prediction of lamb growth trajectories. By leveraging these predictive tools, farmers can enhance breeding
 strategies and efficiently allocate resources to maximize meat production, ultimately improving overall farm
 productivity.

Code for the above Project is given in the file - Dissertation_Updated.iypnb
Data can be found from the Data folder in the repository.
