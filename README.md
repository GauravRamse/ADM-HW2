# ADM-HW2

## Teammates
* Gaurav Ramse
* Mirko Lozzi 
* Tran Luong Bang 

![alt text](https://camo.githubusercontent.com/52d83042699755a6287b8aa0e5ada1567fdc4bb890b7dcdf27d4eaaa664546a7/68747470733a2f2f7777772e6e65787472652e69742f77702d636f6e74656e742f75706c6f6164732f323032302f30392f452d636f6d6d657263652d7765622d646576656c6f706d656e742e706e67)

## Data 
1) We have performed data analysis on data Oct-2019 and Nov-2019, downloaded from the https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store?select=2019-Oct.csv
2) Unzip downloaded file from kaggle, and put both files in directory of code.

We decide to perform our analysis with Dask library( Which uses pandas in backend). We choose Dask because it can enable efficient parallel computing on a single machines by leveraging their multi-core CPUs and streaming data efficiently from disk, preventing us to load the entire dataset on RAM. We also convert our data in Apache Parquet file in order to save memory. We also worked with pandas alongside with dask.

<!--
#### Why we have use Dask
* Dask helps to load huge amount of data in RAM (like lazy loading).
* Eneable parallel computing on a single machine

-->
<!--
#### Folder structure
      We have created main.ipynb file where you can find code to solve research question

-->
