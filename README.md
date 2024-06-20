good tree command for removing node modules, starage, vendor and public :

```
tree -L 2 -I 'node_modules|storage|vendor|public' --dirsfirst
```


what if: 
a small repair shop's service writer and tech app, where a client can come in w a repair issue, the service writer creates a client account, a vehicle for them, and on that vehicle creates a ticket quote for the repair service, after the ticket has been approved the service writer assigns the job to a tech where they can clock into each issue and log their hours, and on completion of all their items on the ticket send the ticket to a completion bucket where the service writer can draft an invoice