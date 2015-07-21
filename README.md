# Outline

### Intro
  
### Eight schools example
- Data description
- Model description
- Stan code for naive (centered parameterization) model
- Problems with naive model and motivation for NCP
- n_eff plot
- acf plot
- Show DAG of CP vs DAG of NCP 
- Better diagnostics from NCP

### Weakly informative priors and scaling (Sleep study example)
- Data description
- Model description
- Fit/problems
- Stan's estimates very different from lme4
- shinyStan parameters plot (interval estimates)
- Change priors

### Finding M.B.'s bug 
2-level hierarchical model
- Data model
- Stan model and fit
- PPCs look bad 
- Interval plots of regression coefs
- Fix coding error 
- PPCs and intervals look good
