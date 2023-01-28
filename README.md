# No-Reference quality assessment of tone mapped high dynamic range (HDR) images using transfer learning

## Getting Started
This GitHub repository contains code for [this](https://ieeexplore.ieee.org/document/7965668) paper. This work is motivated by the observation that quality assessment database in general, and HDR image database in particular are "small" relative to the typical requirements for training deep neural networks. Transfer learning based approaches have been successful in such scenarios where learning from a related but larger database is transferred to the smaller database. Specifically, we propose a framework where transfer learning and Principal Component Analysis (PCA) are used to reduce the dimensionality and fit a regression model to get Mean Opinion Scores (MOS). We demonstrate state-of-the-art performance of the proposed approach on the ESPL-LIVE database.


## Requirement
- MATLAB

## File Structure
- ``espllinearwithregularization.m`` to train the model.
- **bestresultsext.mat** best trained model.