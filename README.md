Community Service

Step1: Installing all dependencies
>pip install -r requirement.txt

Step2: Migrate Data model(migrating postgre database)
>python migrate.py

Step3: To test and validate community service
>python main.py
1 - /addCategory
    This is to add category record in table which has following parameters to pass for posting:-
    {
        "CategoryName": "string",
        "CategoryDescription": "string",
        "CategoryMedia": "string",
        "CategoryStatus": true,
        "LastUpdated": "2019-11-04T09:55:41.249Z",
        "CreatedOn": "2019-11-04T09:55:41.249Z"
    }
2 - /deleteCategory/{id}/
    This is to delete Category record by specifying CategoryID which id in our case
    **CategoryID = id
3 - /categoryDetail/{id}/
    This is to get category Detail of specific CategoryID
4 - /categoryUpdate/{id}/
    This is to Update category Details of specified category record
5 - /getCategory
    This is to get whole table information