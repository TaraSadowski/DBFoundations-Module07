# DBFoundations-Module07
Repository for IT FDN 130 A Wi 21: Foundations Of Databases &amp; SQL Programming

Tara Sadowski

03/03/21

IT FDN 130 A Wi 21: Foundations Of Databases & SQL Programming

Assignment 07

https://github.com/TaraSadowski/DBFoundations-Module07


<p align="center">

## Functions

#### Introduction
</p>
Functions are procedures that return data, whether a single value of a table that are not stored as datapoints, but are derived from the data.  Functions can use parameters that the user can utilize to define what data the table returns.
<p align="center">  


#### When User Defined Functions are Used
</p>
User-defined functions (UDFs) are functions that the user can preform that are not built-in functions in SQL Server.  These would return special values or identifiers that would be useful in a certain query.
<p align="center">  

#### Differences Between Scalar, Inline, and Multi-Statement Functions
</p>
Scalar functions return a single value.  Inline and multi-statement functions can return tables (figure 1).  Multi-Statement functions, however, can have multiple statements – the function is indicated within BEGIN and END operator.
<p align="center">  

![image](https://user-images.githubusercontent.com/79488525/109891622-3c838180-7c3e-11eb-86e4-51dd62390cd2.png)

Figure 1 - Multi-Statement and Inline Function differences

#### Conclusion
</p>
Functions are very useful in  deriving data that is not stored within the database, or returning data based upon user parameters.  Whether simply changing the format, transforming the data, or providing user-defined filters and parameters, functions are a vital part of searches and queries.
