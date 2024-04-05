# Use a base image with Apache Spark and Jupyter installed
FROM jupyter/pyspark-notebook:latest

# Install JIndo SDK
RUN pip install --upgrade pip && \
    pip install jindo-sdk
	


# Expose necessary ports for Jupyter notebook server
EXPOSE 8888
