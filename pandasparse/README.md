python-experiments
## Setup 
// setting up pandas with virtualenv and profiling the code 
https://www.dataquest.io/blog/a-complete-guide-to-python-virtual-environments/

// Using pandas at scale
https://pandas.pydata.org/docs/user_guide/scale.html

  pandas chunksize specifies a certain number of rows
  assumption is that the file is on local machine

## Use Cases 
// using pandas to stream Dataframe to CSV format
https://towardsdatascience.com/reading-and-writing-files-from-to-amazon-s3-with-pandas-ccaf90bfe86c
https://stackoverflow.com/questions/48021280/how-to-upload-a-pandas-dataframe-as-a-csv-stream-without-saving-on-disk
1. Can we stream pandas.io.parsers.TextFileReader in the same manner??
2. Are we using the smallest possible numerical data types? 


// streaming-pandas module (new dependency)
http://www.xavierdupre.fr/app/pandas_streaming/helpsphinx/index.html

// Pandas Dataframe attributes
https://www.w3schools.com/python/pandas/pandas_ref_dataframe.asp

https://medium.com/analytics-vidhya/optimized-ways-to-read-large-csvs-in-python-ab2b36a7914e

// native approaches (no new dependencies)
https://stackoverflow.com/questions/23569771/maximum-size-of-pandas-dataframe

// Aws S3 Select 
https://dev.to/idrisrampurawala/efficiently-streaming-a-large-aws-s3-file-via-s3-select-4on

// pandas and large files 
https://farisology.medium.com/the-easier-way-to-handling-large-files-in-pandas-ad66c68d9936

// AWS parallelization 
https://pragmaticnotes.com/2021/03/09/an-efficient-way-to-download-upload-large-files-with-aws-s3-library-on-client-side-with-blazing-fast-speed/

// pandas in parallel + wrapper script
https://medium.com/@vasista/parallel-processing-with-pandas-c76f88963005

// straight from airflow to GCP  (no python)
https://medium.com/towards-data-science/postgres-bigquery-airflow-e857e3c6aa7a
