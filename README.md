# List of common postgress CLI commands

1. ## LIST ALL TABLES:
  1. \dt  
  2. \dt+ -- shows extra info about the tables eg. table size

2. ## CREATE A View
  ``
    CREATE <viewname> AS
    SELECT <required column names seperated by commas>
    FROM <table name>;
  `` 
  
3. ## DROP A VIEW
  ``
    DROP VIEW view_name;
  ``
