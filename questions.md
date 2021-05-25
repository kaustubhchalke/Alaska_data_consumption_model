### Questions
* How are we generating recommendation for a flight search ?
* Are we capturing search event in transcational db ?
* Do you have any thing provisioned to maintain historical data ?
* How the system is tracing non loged-in user ?
* How the travelling fare for flight recommendation is being generated ?
* Do we have any data pipeline provisioned for flight recommendation system ?

### Our Assumptions
* Assuming we have a transactional data to store and capture search events and results based on search event.
* Also assumning we will be having a dedicated server where we can install 3rd party libraries and modules to generate real-time streams of data.
* Assuming we'll be dealing with big data in real-time to generate reports and analytics.
* Data and system will be scaled up in near future.
* Historical data is being used for initial one time data dump process.
* Assumning current transactional systems are not serverless.

