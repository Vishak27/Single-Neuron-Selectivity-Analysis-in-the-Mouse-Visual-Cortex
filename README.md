# Single Neuron Selectivity Analysis in the Mouse Visual Cortex

## Overview
This project analyzes **spatial selectivity in single neurons** from the mouse visual cortex using the **Allen Institute's Neuropixel dataset**. By exploring how individual neurons respond to visual stimuli at different locations in the visual field, the analysis demonstrates fundamental principles of **receptive field organization** in the visual system.

## Key Features
* **Analysis of neuronal responses** to Gabor stimuli across spatial locations
* **Statistical quantification** of spatial selectivity using t-tests and d-prime calculation
* **Visualization of receptive fields** using spatial heatmaps
* **Temporal analysis** via Peri-Stimulus Time Histograms (PSTHs)
* **Comparison of neuronal responses** between preferred and non-preferred spatial locations

## Dataset
* **Source:** Allen Institute for Brain Science's Neuropixel Dataset
* **Data type:** Extracellular electrophysiology recordings
* **Experiment design:** Visual coding with Gabor stimuli presented at various locations
* **Collected parameters:**
  * **Spike timestamps**
  * **Stimulus parameters** (position, orientation, contrast)
  * **Brain area information**

## Implementation
### Data Processing
* **Pre-processing:** Loading neurophysiological data, extracting spike times
* **Analysis approach:** Comparing responses between spatial locations
* **Statistical Analysis:** t-tests for significance of spatial selectivity

### Analysis Pipeline
* **Selection** of single units from primary visual cortex (VISp)
* **Calculation** of firing rates in response to Gabor stimuli
* **Identification** of spatial receptive fields
* **Statistical verification** of spatial tuning
* **Visualization** of neuronal response properties

## Results
* **Neuron specificity:** Unit ID 951061537 from primary visual cortex (VISp)
* **Spatial selectivity:** Significant preference for stimuli at position (-20.0, -20.0)
* **Statistical significance:** p-value of 0.00025 between preferred and non-preferred positions
* **Selectivity index:** d-prime value of 0.811
* **Response characteristics:** Rapid increase in firing rate immediately after stimulus onset at preferred position

## Applications
* **Understanding** fundamental principles of visual processing
* **Mapping** functional organization of visual areas in the mouse brain
* **Characterizing** single neuron response properties
* **Providing** baseline data for studies of visual perception

## Future Work
* **Extend analysis** to compare neurons across different visual areas
* **Investigate** orientation selectivity in addition to spatial tuning
* **Analyze** population coding of visual information
* **Examine** response dynamics in more detail with higher temporal resolution

## Requirements
* **Python 3.6+**
* **allensdk**
* **numpy**
* **pandas**
* **matplotlib**
* **scipy**
