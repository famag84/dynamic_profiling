# Dynamic Profiling
This project effectively implements a diverse range of clustering techniques, assisting analysts in segmenting customers into distinct categories.


### Pre-processing:
1. Input data has some transformation / feature renaming process. That should be avoided.
    - Feature names should not be changed (just translation to upper case probably)

2. A feature dictionary should be provided in order to get descriptions of the features (to be implemented). 
    - Feature filters (custom queries) should apply over feature description and NOT over feature names. 


### Plots

Cluster visualization

Feature importance: Where are categories defined? 
- Socio-Demographic
- Geographic & Ethnic data 
- Psychographic
- Affinites


### Custom Queries subitem:

- A knowledge of the feature's names is needed. Add some feature list and/or feature description from dictionary.
- If not features found errors are printed (show nothing instead) (In Feature importance doesnt work in Audience Profiling wors properly.)
- We should use a feature dictionary instead of feature's names.
- Custom queries overwrite Categry selected (add "custom query" categry?)


### Technical references

 - clustering_tools.py
 - new_variable_definition.py
 - query_tools.py