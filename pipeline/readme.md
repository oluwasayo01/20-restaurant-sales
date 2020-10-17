# Running the pipeline
In case the code breaks in the first run within your kubeflow cluster, try to run the following command in the pipeline notebook `restaurant_prediction_pipeline.ipynb`
```notebook
!pip install pandas scikit-learn --user
```

Restart  the kernel then run the notebook again and everything should work.
A link to a running experiment is present in the last cell in the notebook.
