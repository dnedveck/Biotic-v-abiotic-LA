# Project notes

## 2014.09.15

Initial reading of [Hembry *et al*. (2014; *Am Nat*)](http://dx.doi.org/10.1086/677928), which reviews the evidence that coevolutionary selection directly causes the formation of new species. Highlights of discussion:

- Not many good cases are found; 
- Those that are pretty well understood may be too extreme to be generally informative;
- Coevolution may promote diversity within species without promoting speciation;
- Higher within-population diversity may even reduce the relative amount of variation that assorts between populations.

Established [shared Google spreadsheet](https://docs.google.com/spreadsheets/d/1xlDhX4D_L3mvzZgfQYNdb6INZFq39RPimZ1lAL_aR-A/edit?usp=sharing) to coordinate plans for the rest of the semester. Ryan will kick off next week with [Afkhami *et al*. (2014; *Ecol. Lett.*)](http://dx.doi.org/10.1111/ele.12332).

## 2014.12.15

At the end of the semester, we think we have a basis to move forward. A [preliminary literature search](https://docs.google.com/a/umn.edu/spreadsheets/d/1QySxIow48qv6M6ef4s8mCbsuMbh_sZCcZj8aCOiCCb8) for papers containing

- tests for local adaptation
- to at least one biotic interaction AND one abiotic environmental variable
- in a fully factorial design

... has so far yielded 38 papers. We need to establish a more formal plan of action, particularly to conduct a more replication-friendly literature search (establish terms, record results count, then filter), and to determine what specific statistics we will synthesize and how, per [Harrison (2011)](http://dx.doi.org/10.1111/j.2041-210X.2010.00056.x), [Koricheva and Gurevitch (2014)](http://dx.doi.org/10.1111/1365-2745.12224), and citations therein. For that purpose, I've asked people to e-mail me requests for inclusion in a new e-mail list, which will organize group meetings starting in the spring semester. E-mail addresses for members are in the file [`contact_list.txt`](./contact_list.txt).

## 2015.01.28

Preparations for first planning meeting this afternoon, in conversation with RBR. 

### What will we meta-analyze?

We're looking for fully factorial experiments testing effects of at least one biotic factor and one abiotic factor, but we also want to try to capture the "crossing slopes" of interactions, which really suggest local adaptation. So what we've come up with is to calculate each possible contrast using the standard (X1 - X2)/sp contrast metric, but then calculate a slope using the treatment levels, standardized on a 0-1 scale: for a 2 x 2 factorial design, this should give us 2 contrasts for each treatment type, each divided by 1 (because whatever the treatment levels are, they're standardized). We also want to know the degrees of freedom, F stat, and p-value for the interaction term between treatment types, to identify cases when (1) the slopes cross and (2) that interaction is significant.

So, for a paper to be included, it must report, or tell us where to find

- a fully factorial experiment testing effects of at least one abiotic and one biotic factor on some proxy of fitness
- mean, standard error (or deviation) and sample size for each treatment group (usually bar plots)
- an ANOVA table reporting df, F, and P(>F), or F(df1,df2), which can give us P.

*Or* the paper must link to archived data allowing us to calculate all these things. We'll also record whether the paper's authors describe the factors tested as sources of local adaptation, and what kind of factors we're dealing with. These are covered in the file [`data_annot.md`](./data/data_annot.md), which explains each column of the data table.


### How will we handle this?

The data pipeline will be roughly 

1. Literature search (set terms in specific search engines/indices) (record total hits)
2. Selection of papers from the search meeting the above criteria (track total number kept)
3. Extraction of data from selected papers (track final number included)

The data table will be an Excel spreadsheet, with one line for each contrast. We'll export to tab-delimited text for analysis and eventual archiving. Data extraction will use XYScan or DataThief or some equivalent; the extraction team will walk through examples together, and perform replicate extractions to ensure consistency.


### How will we apportion credit?

Coauthors must contribute substantively to at least one of 

1. Literature searching and paper selection 
2. Data extraction
3. Data analysis
4. Literature reviewing and writing

RBR and JBY will be first and senior authors (we'll decide between ourselves who gets which as we get closer to completion and can judge relative contributions). How shall we place other coauthors?