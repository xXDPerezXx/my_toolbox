numeric_dist_comparison:
Here is the list of the five metrics the function is using to evaluate if the distributions are similar, along with a quick reminder of what each one specializes in:

Kolmogorov-Smirnov (K-S) Test: A good all-purpose test that compares the entire shape of the two distributions. It's particularly sensitive to differences in the center (like the median) of the distributions.

Mann-Whitney U Test: A non-parametric test that checks if one distribution tends to have consistently higher or lower values than the other. It's excellent for determining if the central tendency of the two groups is different.

Anderson-Darling Test: A very powerful and rigorous test that is especially sensitive to differences in the tails of the distributions. It's great for catching differences in outliers or extreme values.

Cramér-von Mises Test: Similar to the Anderson-Darling test, it gives more weight to the entire distribution, including the tails, than the K-S test does.

Wasserstein Distance: Instead of a statistical test with a p-value, this is a direct measurement of the "distance" between the two distributions. It represents the minimum "cost" or effort required to transform one distribution into the other. A smaller distance means more similarity.
