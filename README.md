# Round Robin
Round Robin is a custom application for ServiceNow that allows easy configuration of task auto-assignments for specific assignment groups.


##### How it Works
Create a rule that specifies the table and group for round robin assignments. If a task is inserted or updated on that table with the specified assignment group then tickets will be auto-assigned to users in that group that are currently logged into the system.


##### Future Enhancements:
- Add different types of round Robin
    - Based on schedule selected on the user record
    - Based on a schedule selected for the grouo on the RR Rule
- Move code to script include vs everything in BR


##### Contribute
Feel free to file bugs/enhancements on github, or fork the project and do pull requests.

If you found this app useful and would like to tip me you can do so here: [paypal.me/timharris777](https://www.paypal.me/timharris777)
