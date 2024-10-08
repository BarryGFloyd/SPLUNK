# SPLUNK
Demonstration with screenshots showing Splunk experience

I installed Windows Server 2022 on a VM and downloaded the SIEM Splunk, to demonstrate working knowledge.

##### Utilities Used
 
 - Windows Server 2022

 - Splunk
 
 ##### Environments Used
 - VMWare
 - Windows 10


# Program Walk Through

 ![Alt text](https://private-user-images.githubusercontent.com/177887327/358888699-1af58d95-58c5-472e-8a3a-307b2020d087.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjM5NjM1NzAsIm5iZiI6MTcyMzk2MzI3MCwicGF0aCI6Ii8xNzc4ODczMjcvMzU4ODg4Njk5LTFhZjU4ZDk1LTU4YzUtNDcyZS04YTNhLTMwN2IyMDIwZDA4Ny5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwODE4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDgxOFQwNjQxMTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02YjA4ZWQyMWIyZjdlZmNlZTI1YzFlZjAyYWI5YWM2MTc4MTA3NTRhMWJmNWU5MGY1ODhjNDQwZWExYjFhYjQ4JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.mbEzNsJ9AqmNZsYcPBTBXxMjY5xS5j5Xb_PnAL0v3yA)

 ### Installing Splunk on the VM

  ![Alt text](https://private-user-images.githubusercontent.com/177887327/358888846-5da82620-ed00-49aa-a71e-d33a06172b5f.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjM5NjM4MDksIm5iZiI6MTcyMzk2MzUwOSwicGF0aCI6Ii8xNzc4ODczMjcvMzU4ODg4ODQ2LTVkYTgyNjIwLWVkMDAtNDlhYS1hNzFlLWQzM2EwNjE3MmI1Zi5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwODE4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDgxOFQwNjQ1MDlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kN2E0MDFmZWQ2Y2MwY2E5NjhkNzgwNDUwYjdlNjUwMDVkZGNlNjRmOWZmMzFjZGM2Njk4NjRhNTdiZGY5YTQxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.5VfQjtIuK9NYb6H3qJ2MSBc6ooeQjh7bmiN-ZvsbIsU)



  ### LOGIN TO SPLUNK


  ![Alt text](https://github.com/user-attachments/assets/43dd874a-ffb8-4025-a59c-1912a53d4e2b)


  ### Here I will configure the type of logs to analyze

  ![Alt text](https://github.com/user-attachments/assets/4bd07223-0f6a-4c3c-8808-2458c40219ca)

  ### Here I will select local logs.  However you can also do more by selecting remote as well.  For the demonstration, I will keep it simple.

  ![Alt text](https://github.com/user-attachments/assets/5807c7d6-28dc-435b-ba03-b306f0a1c4d1)

  ### I now selected the local logs to ingest.

  ![Alt text](https://github.com/user-attachments/assets/9cf5d17a-4b54-4ab4-a565-2f85c3a9a746)


  ### I clicked on search and reporting and put in an * in the search box to yield all the results/events. You can also get more advanced with filters, queries and parameters
 


  ![Alt text](https://github.com/user-attachments/assets/647c9697-61b3-4d17-ab40-d57ef5cd5494)

  ### I opened up the event viewer in Windows and went under Windows logs and security, than I right clicked to clear the security logs

  ![Alt text](https://private-user-images.githubusercontent.com/177887327/358889589-46c176f4-c2a3-4ee6-af43-f8642ed71fef.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjM5NjUxNDAsIm5iZiI6MTcyMzk2NDg0MCwicGF0aCI6Ii8xNzc4ODczMjcvMzU4ODg5NTg5LTQ2YzE3NmY0LWMyYTMtNGVlNi1hZjQzLWY4NjQyZWQ3MWZlZi5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwODE4JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDgxOFQwNzA3MjBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xMGM4ZDM5OTg3ODE4NWNjOWZhYjkzYWNkMjg0NWRjOGQwNzUzMGNhZDk1NzU3MWMzZTkwYzkzYjA5MjJkZWMxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.KewJBXT_lyRdC6jm3KoxNJ0n3lx-keqg3VbiKu3JWO8)

  ![Alt text](https://github.com/user-attachments/assets/dbf040ea-9ec1-49e7-a910-8c7b32375c8f)

  ### I narrowed down the search by adding the host WIN-9U6SIS2QUSF, source WinEventLog:Security and EventCode = 1102
  
  ![Alt text](https://github.com/user-attachments/assets/eb30080f-31dc-4314-8802-45df249701fb)

  ![Alt text](https://github.com/user-attachments/assets/eb7c8cce-0e54-4137-babc-85fb2a8b54ba)

  ### Now it shows everything cleared

  ![Alt text](https://github.com/user-attachments/assets/133536b7-6656-4f46-8fee-b67674663594)

  ### Now I copied the filtered info and will create a table view

  ![Alt text](https://github.com/user-attachments/assets/2bc758af-7c37-4ef8-bb82-129b9aab72d6)

  ### Now it shows the logs in a table view

  ![Alt text](https://github.com/user-attachments/assets/44a3eae8-aa1c-41cd-9c55-b7e7fb37fd46)

  ### Now I created a new Dashboard to demonstrate a different view.

  ![Alt text](https://github.com/user-attachments/assets/e9a66b98-693a-4596-9be4-43153eb3d585)

  ###  I added a table and pasted query WIN-9U6SIS2QUSF, source WinEventLog:Security and EventCode = 1102 in the search SPL

  ![Alt text](https://github.com/user-attachments/assets/048413c5-e5d5-40fb-81e7-a169a6becf07)
  
  ![Alt text](https://github.com/user-attachments/assets/670dbf6e-6ae2-4072-8ed7-d037681b8ee8)

  ### Now I named the data source and demonstrated how to add/remove fields in the table by typing a pipe | - fields _bkt, _cd

  ### now it shows the fields are removed

  ![Alt text](https://github.com/user-attachments/assets/b16310f1-5dff-45ad-8c17-70308c21a49e)

  ### The saved Dashboard now appears and we can set it for easy view

  ![Alt text](https://github.com/user-attachments/assets/ad05e14d-147a-4b1e-ad95-2667aa0ce977)

  ### I set the new Dashboard as a home dashboard which will now appear as the main viewing screen

  ![Alt text](https://github.com/user-attachments/assets/6c6b2e50-7ddd-496a-8de0-57fe1401c9c6)

  




  

