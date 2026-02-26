1. It's a Jupyter Notebook, where I load all the data from TCB and make a pipeline to process it and store it in local storage. Then reload it again and create an individual product file for all the products.
2. After that, each product went through TSA, ACF, PACF, SARIMAX(D=0 and D=1), Validation and Forecasting phase.
3. On each stage this script generates pickle models, plots, aggregated data and all related info and then uploaded to local storage.
