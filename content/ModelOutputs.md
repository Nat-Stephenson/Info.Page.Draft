+++
# date = '2025-07-29T12:09:58+01:00'
draft = false
title = 'Model Outputs'
description = 'The key outputs of the model are estimates of the future hospital activity which can be viewed as high-level summaries or at an individual-level of granularity.'
+++

## Key Outputs of the Model ##

The key outputs of the model are estimates of future hospital activity which can be viewed as high-level summaries or at an individual-level of granularity.

High-level summary statistics include:

- Counts of inpatient admissions
- Bed-days
- Outpatient and A&E attendances
- Impact of activity mitigation assumptions

Because the model runs hundreds of simulations to generate a range of possible futures, the outputs are presented as distributions rather than point estimates. Some key visualisations of the outputs include:

- **Beeswarm Plots**: These plots show the distribution of activity for each type of hospital service, allowing users to see the range of possible future activity levels.

- **S-Curve Charts**: These charts display the cumulative distribution of activity over time, helping users understand the timing and scale of potential future demand.

**note**: Where point estimates of demand are required by the user, these are generated from the average of all the simulations. This is known as the principle projection.