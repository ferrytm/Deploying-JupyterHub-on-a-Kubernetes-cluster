FROM jupyter/pyspark-notebook

# Install JIndo SDK dependencies
RUN pip install --upgrade pip
RUN pip install jindofs

# Expose port for Jupyter notebook
EXPOSE 8888

COPY ../Source/* .