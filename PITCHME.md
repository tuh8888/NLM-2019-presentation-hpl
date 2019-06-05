#### Semi-supervised relation extraction using word vectors and syntax patterns

**Presenter:** Harrison Pielke-Lombardo

**Advisor:** Lawrence Hunter

**Institution:** University of Colorado, Anschutz Medical Campus

---
@title[Background]

## Background

@snap[west span-50]
- Relation extraction lets us go beyond just using mentions in text
- Previous approaches
  - Regular expressions/pattern based approaches. High precision, low recall. Time consuming to construct. Hard to generalize.
  - Supervised methods. Very little gold standard data available
  - One-shot learning language models. Have yet to try this
@snapend

@snap[east span-50]
![](https://github.com/tuh8888/Dep2Rel/blob/master/resources/dep_example.png)
@snapend

---
@title[Method]
## Method

@snap[west span-50]
- Dependency path between two entities -> context path
- Combine word vectors -> context vectors
- Bootstrapping
  - Seeds
  - Clustering -> patterns
  - Context similarity
@snapend

@snap[east span-50]
![](https://github.com/tuh8888/Dep2Rel/blob/master/resources/algorithm.png)
@snapend

---
@title[Results]
## Results

@snap[west span-50]

@snapend

@snap[east span-50]
![]()
@snapend

---
@title[Conclusion]
## Conclusion

@snap[west span-50]
### Contact
- Email: Harrison.Pielke-Lombardo@ucdenver.edu
- GitHub: https://github.com/tuh8888
- Project: https://github.com/tuh8888/Dep2Rel
@snapend