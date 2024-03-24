============================ PHONE PAY PROJECT ========================

step 1) Create three tables
1)PHONEPAY 2)PHONEPAY_BACKUP 3)TRANSACTION

step 2) Create a trigger to insert record. The record which you are are inserting in PHONEPAY table same should be insert in PHONEPAY_BACKUP table, Hence Create Trigger to insert the same record into PHONEPAY_BACKUP table.

step 3) Insert record into PHONEPAY table , check whether same record is present in PHONEPAY_BACKUP table.

step 4) Create Sequence to get the unique sequence in TRANSACTION table For transaction id(TID) column.

step 5) Create trigger to update record. if any record updated in PHONEPAY table then that updated record must be insert in the TRANSACTION table. for this I have created a trigger which will insert the , Updated/modified record into Transaction table.

step 6) Update the record and check whether it is isert in the TRANSACTION table or not.

step 7) Create one Stored Procedure to upadate the balance of User using their name and that record also insert in TRANSACTION table.
