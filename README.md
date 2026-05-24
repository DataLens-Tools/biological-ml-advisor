# Biological Tabular Data Advisor

## A Computational Framework for Scientifically Guided Machine Learning Workflow Recommendation in Experimental Biology

Biological Tabular Data Advisor is a biologically informed machine learning workflow recommendation system designed for experimental biological datasets.

Unlike generic AutoML systems, this framework evaluates:

- experimental structure
- repeated measurements
- longitudinal organization
- fluorescence workflows
- imaging-derived features
- dose-response experiments
- batch effects
- interpretability requirements
- biological reproducibility risks

before recommending computational workflows.

The goal is not simply to maximize predictive performance, but to provide scientifically defensible and biologically appropriate analysis guidance.


# Motivation

Modern biological datasets often violate standard machine learning assumptions.

Many experiments contain:

- repeated measurements
- time-series trajectories
- fluorescence drift
- longitudinal structure
- plate/well effects
- non-independent observations
- high-dimensional feature spaces
- small sample sizes

Generic AutoML platforms frequently ignore these biological realities, leading to:

- data leakage
- inflated model performance
- incorrect train/test splitting
- poor reproducibility
- biologically misleading conclusions

This project introduces a computational reasoning layer specifically designed for experimental biology workflows.


# Current Features

## Biological Structure Detection

Automatically detects:

- wide vs long format datasets
- time-series structure
- repeated measurements
- fluorescence-related columns
- morphology features
- dose/concentration columns
- batch/plate metadata
- longitudinal experimental organization


## Scientific Reasoning Engine

Provides biologically informed warnings for:

- data leakage
- repeated measures
- temporal autocorrelation
- fluorescence artifacts
- photobleaching
- inappropriate train/test splitting
- batch effects
- small sample size risks


## Workflow Recommendation

Suggests biologically appropriate methods including:

- Logistic Regression
- Random Forest
- Gradient Boosting / XGBoost
- Linear Mixed-Effects Models
- Functional Data Analysis
- Dynamic Time Warping
- Cross-correlation analysis
- Longitudinal trajectory analysis


## Time-Series / Longitudinal Analysis Mode

Specialized support for:

- fluorescence trajectories
- calcium imaging
- repeated stimulation paradigms
- longitudinal cell-line experiments
- time-course biological assays

Recommendations include:

- baseline correction
- ΔF/F normalization
- ON/OFF phase analysis
- lag-response analysis
- grouped validation
- temporal preservation strategies


# Supported Dataset Types

The framework is designed for:

- fluorescence microscopy datasets
- cell-line assays
- imaging-derived morphology features
- dose-response experiments
- longitudinal biological experiments
- electrophysiology measurements
- behavioral datasets
- experimental tabular biology data


# Architecture

```text
Dataset Upload
      ↓
Biological Structure Detection
      ↓
Scientific Reasoning Engine
      ↓
Workflow Recommendation
      ↓
Validation Guidance
      ↓
Visualization Suggestions
```


# Example Biological Risks Detected

The advisor can automatically identify risks such as:

- repeated measurements
- wide-format trajectory data
- temporal leakage
- inappropriate random splitting
- fluorescence preprocessing requirements
- batch effects
- missing-value structure
- class imbalance


# Example Recommendations

## Preprocessing

- baseline correction
- ΔF/F normalization
- photobleaching inspection
- batch correction
- feature scaling
- biological outlier inspection

## Validation

- grouped cross-validation
- time-aware splitting
- replicate-level validation
- mixed-effects modeling

## Visualization

- PCA
- correlation heatmaps
- fluorescence trajectories
- ON/OFF phase plots
- lag analysis plots
- morphology embeddings


# Tech Stack

- React
- Vite
- Tailwind CSS
- PapaParse
- JavaScript
- Lucide React


# Philosophy

This project is not intended to replace scientists or statisticians.

Instead, it aims to function as:

- a computational biology assistant
- a workflow reasoning engine
- a methodological reviewer
- a biological ML guidance system

The emphasis is on:

- scientific rigor
- interpretability
- reproducibility
- biologically defensible workflows

rather than purely predictive optimization.


# Future Directions

Planned future expansions include:

- microscopy-specific workflow reasoning
- omics-aware workflow modules
- neuroscience analysis modules
- reviewer-risk detection
- publication-readiness assessment
- literature-aware recommendation systems
- RAG-enhanced scientific guidance
- integration with LLM-based reasoning engines


# Repository Status

Current status:

- MVP / research prototype
- active development
- conceptual framework + experimental implementation

# App Link

https://biological-ml-advisor.netlify.app/

# Author

**Taufia Hussain**  
Computational Biology • Experimental Biology • Scientific ML  
CEO & Co-Founder — DataLens.Tools


# License

MIT License
