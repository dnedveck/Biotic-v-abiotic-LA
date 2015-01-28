# Data annotation, local adaptation to biotic and abiotic selective agents

Describes contents of <data.txt>, tab-delimited text file.

## Column names

| Name     | Explanation
|----------|-------------
| OBS      | Observation number
| AUTH     | Paper author
| YR       | Paper pub year
| DOI      | DOI code for source paper
| PARAM    | Response variable (closest proxy to fitness measured)
| UNIT     | PARAM units
| GENUS    | Taxonomy of species studied 
| SPECIES  | Taxonomy of species studied 
| EXPTYPE  | Experiment type: CG (common garden), TR (transplant), or GH (greenhouse)
| XSRC     | F(igure) or T(able) containing estimates of means
| ASRC     | F(igure) or T(able) containing ANOVA interaction terms
| ABIO     | Abiotic treatment variable
| ATYPE    | Abio treatment type: PA (presence/absence), LV (levels)
| BIO      | Bio treatment variable
| BTYPE    | ABio type: PA, LV
| AUTHLA   | Did the authors suggest local adaptation to abio, bio, or both?
| INDF     | Degrees of freedom for interaction term
| INF      | F statistic for interaction term
| INP      | P(> F) for interaction term
| TRTYPE   | Treatment for the contrast
| TRDIST   | Treatment distance -- difference between treatments, standardized 0-1
| Xx       | Mean for group x
| SEx      | SE for group x
| SDx      | SD for group x
| Nx       | N for group x
| ENTERED  | Initials of person who entered data