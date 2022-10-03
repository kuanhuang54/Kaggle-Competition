### AMEX Default Prediction using XGBoost
This notebook trained an XGBoost model using the dataset from [AMEX data - integer dtypes - parquet format](https://www.kaggle.com/datasets/raddar/amex-data-integer-dtypes-parquet-format), which provides a data file format designed for efficient data storage and retrieval and can help to solve the memory problem. Also, this notebook used [CuPy](https://cupy.dev/), which utilizes CUDA Toolkit to accelerate computing. Then used feature engineering methods provided by [Amex Agg Data How It Created](https://www.kaggle.com/code/huseyincot/amex-agg-data-how-it-created).

This XGB model achieved LB 0.792.
