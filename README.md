# SOEN 363: Database Systems
*Phase II: NoSQL Databases (MongoDB)*
![Banner](https://raw.githubusercontent.com/milaroisin/soen363-databasesystems-phase2/master/Banner%20Image.jpg)

Banner image taken from [here](https://safebooru.org/index.php?page=post&s=view&id=1514244).

Contributors:
- Mila Roisin
- Michelle Choi
- Collin Zhou

Software Engineering
Gina Cody School of Engineering
Concordia University 2020

## Database System
We chose MongoDB as our NoSQL database, it is document-based. 

Download the community edition from : [here](https://www.mongodb.com/download-center/community)

## Database
We selected the following dataset from Kaggle:  [Safebooru - Anime Image Metadata](https://www.kaggle.com/alamson/safebooru#all_data.csv)

* Metadata: 2,736,037 rows of tag-based anime image metadata
* Contains 2736034 unique values
* Size: 1.24 GB-9 Columns
* Filetype: .csv (comma separated values)
* No. of files: 1

## Steps

1. Download the `all_data.csv` dataset
2. Make a folder chain called data/db in the hardrive you installed mongodb in
3. Open command line and cd to the bin of your mongodb folder and type execute `mongod`
4. In another command line, cd into the bin as well and run  `mongoimport` command as shown below: 

![image](https://puu.sh/Fy0mc/d3341abc4a.png)


Let this run for a few minutes and you would have now imported all the documents to your collection


__OR__

Install Studio3T GUI to help streamline the queries and importing

__Documentation__ : [Studio3T GUI](https://studio3t.com/knowledge-base/articles/visual-query-builder/)

For how to execute the queries and the queries themselves, 
__please look at the documentation report [`ProjectPhase2-29575774_40033295_26307647.pdf`](https://github.com/milaroisin/soen363-databasesystems-phase2/blob/master/ProjectPhase2-29575774_40033295_26307647.pdf)__
