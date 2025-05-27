# NetworkSubspaceRegression

This is the data set used in the paper:  Linear regression and its inference on noisy network-linked data. Journal of the Royal Statistical Society: Series B, 2022.

It is a data set about a school conflict study as introduced in 
Paluck, E.L., Shepherd, H. & Aronow, P.M. (2016) Changing climates of conflict: a social network experiment in56 schools. Proceedings of the National Academy of Sciences, 113, 566–571.

The data set contains students' social relations (spending time together, or best friend), as well as hundreds of attributes based on questionnaires. The raw data set is available from the journal website of the original paper. The one we attached here is a processed version.

ProcessedData.Rda: this is the processed data. It is stored as two lists: raw.list and lcc.list. 
The raw.list contains the full data set (60 schools) and each of them has the following items:

df: the attribute data, each row is a student and the columns are the variables from the questionnaires. 

A2: Wave 2 "spend-time" network (undirected)

A1: Wave 1 "spend-time" network (undirected)

DA: Wave 2 "spend-time" network (directed)

DA1: Wave 1 "spend-time" network (directed)

B: Wave 2 "best-friend" network (directed)

B1: Wave 1 "best-friend" network (directed)

A: union of four (symmetrized) networks of Wave 1-1, "spend-time" and "best-friend"

The lcc.list contains the 60 schools as the raw.list, but each of them focuses only on the largest connected component, extracted on the A network



37070-0001-Data.rda: the original raw data provided by the authors

37070-0001-Codebook-ICPSR.pdf: the questionnaire and codebook for the attributes
