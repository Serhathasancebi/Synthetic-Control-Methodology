# Synthetic-Control-Methodology
SCM as a case study measuring the causal impact of the Islamic Revolution on Iranian Economy


The SCM illustrates a hypothetical counterfactual unit by taking the weighted average of pre-intervention outcomes from selected donor units. The donor units that are combined to form the synthetic control are selected from a pool of potential candidates. Predictor
variables that affect the outcome, and the outcome variable itself before the intervention is enacted, determine the selection of donor units and weights.

The following describes the SCM in comparative case studies. Suppose that we observe J + 1 units. Without loss of generality, suppose also that only the first unit is exposed to the intervention of interest, so that we have J remaining units as potential controls.
Borrowing from the statistical matching literature, we refer to the set of potential controls as the “donor pool”.

Let Y^0_it be the outcome that would be observed for the unit i at time t in the absence of the intervention, for units i = 1,…, J + 1, and time periods t = 1,…, T. Let T0 be the number of the pre-intervention periods, with t = 1,…, T0. Let Y^1_it be the outcome that would be observed for unit i at time t if unit i were exposed to the intervention periods T0 + 1 to T. We assume that the intervention has no effect on the outcome before implementation period so, for t = 1,…, T0 and all i = 1,…, J + 1, we have that Y^1_it = Y^0_it Abadie et al. (2010, 2015), and Echevarría and García-Enríquez (2019a, 2019b).

In practice, interventions may have an impact prior to their implementation (e.g., via anticipation effects). In these cases, T0 could be interpreted as the first period in which the outcome may possibly react to the intervention. Implicit in our notation is the usual assumption of no interference between units. That is, we assume that outcomes of the untreated units are not affected by the intervention implemented in the treated unit.

The treatment effect for the treated unit in period t is given by:

α1t ≡ Y^1_1t - Y^0_1t.

Note that in this application the synthetic control estimator has been applied with the Multivariate Synthetic Control Method Using Time Series (MSCMT) package, see for details  (Becker and Klößner, 2017, 2018).

For the article where we implement the SCM with different optimization techniques and software packages, see https://www.worldscientific.com/doi/abs/10.1142/S0217590820420072.

Further information, serhat.hasancebi@gmail.com.

Enjoy.
