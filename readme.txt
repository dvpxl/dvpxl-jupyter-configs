# reference documentation
https://jupyter-notebook.readthedocs.io/en/stable/config.html

# performance for heavy visualization
jupyter notebook --NotebookApp.iopub_data_rate_limit = 10000000
see pr: https://github.com/jupyter/notebook/issues/2287

# run with exposed ip & port (note running safely below)
jupyter notebook --ip ip --port 8888
see reference doc regarding secure

# create jupyter config
jupyter notebook --generate-config

# jupyter config location
~/.jupyter

# max buffer
jupyter notebook --NotebookApp.max_buffer_size=xxx
