# KingModelOE 2026

Computational models accompanying King et al. 2026, investigating clonal dynamics in the oesophageal epithelium.

## Repository structure

### LogicalModel

A logical gene regulatory network (GRN) model of oesophageal epithelial cell fate, built for [BioModelAnalyzer](https://biomodelanalyzer.org). The model encodes interactions between Notch1, Notch2, Trp53, and cellular fitness.

Open `OE GRN v1.json` directly in the BioModelAnalyzer web tool.

### EvolutionaryModel

A Jupyter notebook (`Digital oesophagus.ipynb`) that simulates clonal competition in the oesophagus using a Wright-Fisher 2D spatial model. It models the fitness effects and epistatic interactions of Notch1 (het/hom), Notch2, and Trp53 mutations across a population of oesophageal cells.

**Dependencies:** Requires the `clone-competition-simulation` package, available at [https://github.com/michaelhall28/clone-competition-simulation](https://github.com/michaelhall28/clone-competition-simulation), along with standard scientific Python packages (`numpy`, `matplotlib`, `pandas`, `scikit-learn`, `pingouin`).

## License

MIT
