# Exchange Rooms

PowerShell scrips for managing rooms and room lists in Exchange Online.

The script is supporting synchronization of rooms from a CSV file to Exchange Online. The script is using the following CSV file format:

```csv
RoomName,DisplayName,EmailAddress,RoomList
Room1,Room 1,
Room2,Room 2,
Room3,Room 3,
```

The script is using the following parameters:

```powershell
.\Sync-ExchangeRooms.ps1 -CsvFile .\Rooms.csv 
```

## 365admin ready

This packages is 365admin ready. This means that you can install the package in your
tenant and be sure that there has been made a proper peer review of the code.

## What is 365admin?

365admin is a platform which makes life easier for Administrators. 

[ ] todo: add link to 365admin website - https://365adm.in

