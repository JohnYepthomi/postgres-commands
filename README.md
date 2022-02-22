# List of common postgress CLI commands

## LIST ALL TABLES:
  1. \dt  
  2. \dt+ -- shows extra info about the tables eg. table size


## CREATE A View
  ``
    CREATE <viewname> AS
    SELECT <required column names seperated by commas>
    FROM <table name>;
  `` 
  
## DROP A VIEW
  ``
    DROP VIEW view_name;
  ``
