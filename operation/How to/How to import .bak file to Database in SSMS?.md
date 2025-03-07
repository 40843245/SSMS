# How to import .bak file to Database in SSMS?
Step 1:

Right click on Database you want to import to.

Then select `Job` -> `Restore` -> `Database`.

<img width="637" alt="image" src="https://github.com/user-attachments/assets/025dc6b1-68e9-462b-a5ac-1cdb752d2841" />

Step 2:

In `Restore Database` dialog, under source section, click `from device` radio button and select the .bak file as source.

<img width="431" alt="image" src="https://github.com/user-attachments/assets/a39a38cb-5ad6-449d-849c-58668a31df61" />

Step 3:

In `choose backup device` dialog,

+ If your source is placed in local device, in `backup source type` drop-down list, select `from file` and then click `Add` button.
+ Otherwise, in `backup source type` drop-down list, select `from url` and then click `Add` button.

Finally click `OK` button.

<img width="366" alt="image" src="https://github.com/user-attachments/assets/10ce247a-f68f-4864-8218-92c7b39d228c" />

Step 4:

In `Restore Database` dialog, click `OK` button.

Step 5: 

Restart the connection to make change effect.
