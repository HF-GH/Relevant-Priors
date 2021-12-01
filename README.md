# Relevant-Priors
Dataset

Full details of this project can be found in: 
** Feigin, H., Baror, S., Bar, M., & Zaidel, A. (2021). Perceptual decisions are biased toward relevant prior choices. Scientific reports, 11(1), 1-16.**

The dataset includes data from 6 experimental conditions, each in its own repository (the first condition has two variants – A and B, each in its own repository). Each table contains data of a single participant, and includes the following fields: 
1. loc_deg - stimulus location in degrees.
2. prior_type - priors' type, such that right priors are coded as "1" and left priors as "-1" (condition 1A also included an unbiased priors’ type, coded as “0”).
3. stim_num - stimulus number within a specific trial; the test stimulus is coded as "0", the preceding prior as "1", the one before that as "2", etc.
4. test_stim - test stim are coded as "1" and priors are coded as "0".
5. ans - participant's response; "right" is coded as "1" and "left" is % coded as "-1".
6. rt - response time in seconds. 
Conditions 3,5 and 6 also include an additional field:
7. prior_color - priors were either green or purple, coded as "1" and "2", counterbalanced between participants. Test circles were always white, and their color is coded as "0".
