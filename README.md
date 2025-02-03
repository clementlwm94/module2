#1 
128.3 MB

#2
green_tripdata_2020-04.csv
(Actually I likely can be anything as the variable is set by us)

#3
SELECT 
	COUNT(*) 
FROM 
	yellow_tripdata
WHERE
    filename LIKE '%2020%'
Ans: 24,648,499

#4
SELECT 
	COUNT(*) 
FROM 
	green_tripdata
WHERE
    filename LIKE '%2020%'
Ans: 1734051


#5
SELECT * 
FROM 
	public.yellow_tripdata
WHERE
	filename = 'yellow_tripdata_2021-03.csv'

Ans: 1,925,152
	
#6
Reference
https://kestra.io/plugins/core/triggers/io.kestra.plugin.core.trigger.schedule
