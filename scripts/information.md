bronze bucket fpr kaggle dataset -> aws-de-pipeline-bronze
silver bucket -> aws-de-pipeline-silver 
gold bucket -> aws-de-pipeline-gold

scripts -> aws-de-pipeline-scripts

so we can either add versioning to this buckets if we want to 
if the data is sensitive we can also add encryption
the bronze data can be moved to s3 glacier storage class which is cheaper class compared to the normal stanadard class after it has already been used and transformed in silver and gold
we need to maintain this for say auditing
