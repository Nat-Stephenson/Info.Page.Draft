+++
# date = '2025-07-29T12:09:44+01:00'
draft = false
title = 'Model Inputs'
Description = 'This page provides details on the inputs required for the healthcare demand model.'
+++

## Key Inputs for the Model ##

Over 100 adjustable parameters are incorporated into the model, covering the key factors influencing healthcare demand.

Many of these parameters allow the user to provide their forecasts as ranges rather than point estimates and they thereby quantify the level of uncertainty behind the input assumption. 

## Unmet Needs ##

Not all healthcare are currently met. The model allows the users to correct for imbalances which is not considered, would be built into the modelled future. In the model, we distinguish between 'demand-supply' and 'need-supply' imbalances.

### Demand-Supply Imbalance ###
1. Waiting lists management
2. Reparatriation/expatriation
3. Private funding dynamics

### Need-Supply Imbalance ###
1. Unmet needs
2. Inequalities
3. Treatment thresholds

## Population Changes ##

Hospital activity arises from the needs of its catchment population. As the size, age/sex structure, and age specific needs of the population change, so will the levels of demand for healthcare. The model incorporates these population changes by allowing users to input different demographic scenarios and their potential impact on healthcare demand.

- **Population Growth**: Users can select from ONS population projection variants, or opt to use their own custom population projections.
- **Health Status**: This parameter adjust age-specific utilisation rates account for future changes in population health status. 

## Non-demographic changes ##

This element of the model accounts for anticipated changes in activity which are NOT due to changes in the size and age-sex structure of the population over time. These changes may include factors such as advancements in medical technology, changes in treatment protocols, and shifts in patient preferences.

- As medical technologies develop, medical conditions become more treatable, and the technology becomes available to a wider set of patients. 
- Clincial standards may chnage what is acceptable or best-practice care. 
- Patient expectation may rise, increasing demand for a particular service or intervention.

The non-demographic assumptions currently used in the model are based on detailed analysis and the results of an expert elicitation exercise with clinical experts.

## Activity Mitigation ##

Here 'Mitigation' refers to the reduction in demand for hospital treatments through deliberate actions. This may be achieved by mechanisms such as:
- Preventative care
- Early intervention
- Improved management of chronic conditions
- Substitution of care
- Enhanced community care
- System efficiency improvements

Using a suite of methods grounded in published research, we identified over 90 categories of hospital activity that could be potentially reduced.

For each of these categories, users can forecast how much activity they believe will be mitigated by the model horizon year. Supporting information is provided to users' consideration when making forecasts about activity mitigation including data for benchmarking against nationla trends, peers, and expert opinions. 

In the model outputs, the scale of the impact of these activity mitigation assumptions can be viewed. 

For further information on the activity mitigation assumptions, please refer to the [Activity Mitigators](connect.strategyunitwm.nhs/nhp/project_information/modelling_methodology/activity_mitigators/inpatient_activity-mitigators.html) page.
