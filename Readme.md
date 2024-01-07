
step1 : https://www.liquibase.com/download
step2 : download mysql
step3 : add mysql jar in lib folder of liquibase
step4 : commands
D:\GIT-REPO\liquibase_mssql>liquibase --defaultsFile=liquibase.properties  --changeLogFile=changelog_1.0.xml update
D:\GIT-REPO\liquibase_mssql>liquibase --defaultsFile=liquibase.properties  --changeLogFile=changelog_2.0.sql update
D:\GIT-REPO\liquibase_mssql>liquibase --defaultsFile=liquibase.properties  --changeLogFile=changelog_3.0.sql update