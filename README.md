Code files:

In this reposityory data and code of the paper "Social-circle enhanced Fashion Recommendations System" is available:
The calculation and results for three different ranking measures are provided by three different notebooks:
"diff_calc_ktau.ipynb" comes up with experiemts referring to kendall's tau ranking measure.
"diff_calc_spearman.ipynb" provides experiemtal results based on spearman's ranking measure.
"diff_calc_wtau.ipynb" gives results about empirical analysis with respect to weighted tau ranking measure.

-------------------------

Data files:

"without_prefer_a" is the data file includes rankings of the users for different shopping intents without incorporating user preferences.

"with_prefer_a" is the data file includes rankings of the users for different shopping intents along with incorporation of user preferences.


---------------------------

Intermediary files:

The intermediary results are stored in separate files:
"score_ktau", "scores_spearman", "scores_wtau" provides the ranking measures scores for different shopping intents with and without user preferences.

"norm_data_ktau", "norm_data_wtau", "norm_data_spearman" give the normalized score of ranking measures

"results_for_t_test_after_sampling_kendall_tau.text", "results_for_t_test_after_sampling_spearman.text", "results_for_t_test_after_sampling_wtau.text" give results after sampling the users for t-test measure.