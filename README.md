Dr Keith S. Reid 1 2
keithreid@nhs.net
1. Department of Health and Life Sciences, University of Northumbria at Newcastle
2. Positive and Safe Care team, Cumbria Northumberland Tyne and Wear
NHS Foundation Trust, Newcastle

The author gratefully acknowledges Aji Lewis MBE, Peter McMeekin and Mick Hill.

Abstract
Mann-Whitney U test, a canonical test of the order of two groups, does not handle
ties. Typical implementations use approximations fragile to small samples. These
problems are troublesome in certain clinical situations where a small range of possible
values necessarily forces either small samples or ties. This paper presents Napkin, an
exact computationally feasible superset of Mann-Whitney U which handles ties. Call
sets S and T. Let q be length in steps of a path across an adapted Young diagram
where sloped steps are ties. Generate all pairs of binary numbers of variable length
q ∈ [1 : n = s+t] which write, with 1, the places where elements are present. Binary
pairs must meet bitwise OR and binary representations of untied pairs also meet XOR.
Partitioning elements over the 1s generates all paths prior to conflating isomorphic
paths. Tied elements follow discrete distributions in similar data and deterministically
shorten paths. Thus the distribution of tied elements informs likelihood of path
lengths. Paths derived from binary pairs of each length have deterministically exact
relative likelihoods. In a clinical application the exact test is more sensitive than the
approximation. Benefits include exactness, visual beauty and shorter experiments.
Keywords: Mann-Whitney Wilcoxon Young Ties Napkin
