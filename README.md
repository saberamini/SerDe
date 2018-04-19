
CREATE EXTERNAL TABLE movies (id STRING, title STRING, year DOUBLE, genre STRING, summary STRING, country STRING, direct STRUCT<id:STRING, last_name:STRING, first_name:STRING, year_of_birth:STRING>, actors array<STRUCT<id:STRING,role:STRING>>)
