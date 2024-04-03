# Kaggle project

## TODOs

- [ ] Create two sets of data
  - [ ] Imputation
    - [ ] By mean
    - [ ] By adding 0
    - [ ] Other method? (External data?)
  - [ ] Removing missing values (Might be worse off, since there are not as many observations)
    - [ ] Look into which models might perform better with so many dimensions
      - [ ] PCA?
- [ ] Look at what columns might be irrelevant (e.g.: currency?)
  - If many currencies, might be good idea to translate to one?
  - Or since different countries/regions, could be still valid left as is
- Temporal aspect
  - How to incorporate different time results into the model
  - Are more recent observations more important than latter?
    - Time trend increasing or decreasing, so relevant for sure
  - Do we need to go so far back?
  - How to ensure correct split for model selection?
- Feature engineering
  - Any other columns we can create that could provide value to the model?
