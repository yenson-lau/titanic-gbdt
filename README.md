# Titanic-GBDT

This is a simple toy project using gradient boosted decision trees (GBDT) to model the [Titanic dataset](https://www.kaggle.com/competitions/titanic/data).

The goal here is to familiarize with GBDTs (more specifically using LightGBM) rather than to maximize performance. For such a study, see [RutvijBhutaiya/The-Famous-Titanic-Study](https://github.com/RutvijBhutaiya/The-Famous-Titanic-Study), which achieves >98% accuracy on the test set.


## Setup

The project is managed using [uv](https://docs.astral.sh/uv/) with `Python=3.11`. To install the required packages, activate a virtual environment and run:

```sh
uv lock
uv sync
```
