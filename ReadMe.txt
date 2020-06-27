/** As per instruction create the Pets module **/

/** Please consider below points ::
    1. applied logs and unit test and functional test, but can do in more better way 
    2. tried totally modular way with routes/service/bo/dao, but c also apply ORM and related models to make it more proper way 
    3. Code base easily maintainable and enhancement friendly,  Please consider as MVP module, can do more better way with some more time.
**/

1. Use Sql scripts form sql folder to create the table (can put more constraints like unique and all, but for now not much applied)
2. npm install
3. npn run test (for now, do the unit test for one file (business logic file) only with mocking, if time permits then can do for dao and all other)
3. npm run functional (for now, use the same port and database, if time permits then can do with another "unit_test" database)
4. npm run start
========================================
Run below apis 

Get Pets :: http://locahost:3000/api/v1/pets
Create Pet :: method:POST :: http://locahost:3000/api/v1/pet (for now, limited validation applied, if time permits then can apply more like lendth, lessthan, greate than and all)
Update Pet :: method:PUT  :: http://locahost:3000/api/v1/pet (for now, do update for whole object with PUT, if time permits then can do for individual/dynamically for single properties with PATCH request)
Delete Pet :: method:DELETE :: http://localhost:3000/api/v1/pet
