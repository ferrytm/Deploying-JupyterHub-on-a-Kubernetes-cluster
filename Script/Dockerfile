FROM jupyter/pyspark-notebook:latest

# Set environment variables
ENV JINDO_SDK_VERSION=2.1.0
ENV JINDO_SDK_URL=https://github.com/aliyun/aliyun-emapreduce-datasources/blob/main/jars/datasources/2.1.0/emr-datasources_shaded_2.11-2.1.0.jar

# Download and copy the JIndo SDK JAR file
ADD ${JINDO_SDK_URL} /usr/local/spark/jars/

# Install any additional dependencies if needed
# RUN pip install ...

# Expose necessary ports if needed
 EXPOSE 8888

# Set any additional configurations if needed
# ENV ...

# Start Jupyter Notebook
CMD ["start-notebook.sh"]
