# anything-salesforce
Types of Report
1. Tabular
  -  Cannot be added to chart or dashboard
2. Summary
  -  Group by Row
3. Matrix
  -  Group by Row and Column
4. Joined
  -  Multiple reports put together

Bucket fields
  -  Values which could be grouped together. For example picklist values or amount

Report Types
  -  Lookup fields option available
  -  Can rename fields displayed in report

Future
- Mixed DML operations
- 
Queueable
- Can pass sobjects
- Can chain jobs
- Can monitor jobs
- 1 job can be chained per job and have unlimited stack depth
- Can delay job execution
- 50 enqueueJob for Synchronous and 1 enququeJob for Asynchronous
- Job Id can been queried with AsyncApexJob object and can be monitored from UI
- AsyncOptions to define depth of the stack as well as delay time
- Database.AllowCallouts for making HTTP and webservice calls

Batch

Triggers

Long running transactions

Event Driven Architecture
- Publish Subscribe - Guarenteed delivery, unique copy
- Fanout - No guarenteed delivery, no unique copy
- Claim Check - Message header and data store - sends only header - guarenteed delivery
- Passed Messages - Router - Transformer - Writer
- Streaming - Similar to pub sub but in stream 
- Queueing - Message queue - low connectivity - buffering
- 10 concurrent jobs which runs more than 5 seconds

Test.LoadData()
- Use this to create test data from Static Resources

