# hello-workd
just an example

##### create table space #####
 create tablespace SIMS_CORE_OPERATION_D01   
 logging datafile '/db/iut11gee/oradata/SIMS_CORE_OPERATION_D01_f01.dbf'  
 size 500M autoextend on  
 next 10M maxsize 500M extent management local;

 create tablespace SIMS_CORE_OPERATION_X01   
 logging datafile '/db/iut11gee/oradata/SIMS_CORE_OPERATION_X01_f01.dbf'  
 size 500M autoextend on  
 next 10M maxsize 500M extent management local;
 
 ###########
