This integration takes a set of Lead objects from a Mock REST API and inserts them into Salesforce. This project can be repurposed for any data type beyond just Leads. This project supports Upsert functionality, but be sure to clear Salesforce of any Leads that match what is incoming from the REST API before moving the data if you'd like new Leads to appear.

This project requires creating a mock API to pass the data from. This is the site I use to create mock API endpoints: mockapi.io
