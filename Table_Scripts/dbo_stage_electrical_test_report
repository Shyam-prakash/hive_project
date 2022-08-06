CREATE TABLE dbo.stage_electrical_test_report(
data_time string,
data_Date string,
Lot_No string,
Serial_No string,
Test_1_Status string,
F1 string,
F2 string,
F3 string,
F4 string,
F5 string,
F6 string,
F7 string,
F8 string,
F9 string,
F10 string,
Test_2_Status string,
F11 string,
F12 string,
F13 string,
Test_3_Status string,
F14 string,
F15 string,
F16 string,
F17 string,
Test_4_Status string,
F18 string,
F19 string,
Result string)
ROW FORMAT SERDE 'org.apache.hadoop.hive.serde2.OpenCSVSerde'
WITH SERDEPROPERTIES ("separatorChar" = ",", "quoteChar" = '\"',"skip.header.line.count"="1")
STORED AS TEXTFILE 
LOCATION '/dbo/staging_zone/stage_electrical_test_report'