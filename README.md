# Loadsmart BI Challenge

This is a test for a job opportunity, the scripts and dashboards are working fine, however, a production environment solution would require additional features such as, Log, Validations prior loading the data, build a class to hold functions that help ETL and so on. 


Please consider these assumptions when evaluating my solution:
1. No SCD Type 2 was created as the data did not have a proper key to allow that;
2. For the Fact table, I considered that no changes would be applied in a record once the data is loaded into BI (no reprocessing of old records, only full reprocessment);
3. Incremental load was considered for the Fact table;
4. Carrier Rating and Vip Carrier could be loaded into Dim Carrier. For this exercise I kept in the fact as it could change along the time, but this would be a good candidate for SCD Type 2;
5. I noticed that has_mobile_app_tracking was duplicated, but I decided not to drop one of them as it would need further investigation.
