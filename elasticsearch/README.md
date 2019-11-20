### Elastic Search Demo

This is a super simple demo of elastic search - using the most very basic settings. 

To run the demo:

1. Create a new stack in AWS using the yaml template ('aws/cloudformation-template.yml'). Easiest way is just to import as new stack using web console

2. Load postman collection & environment into Postman. Will need to update the {{hostname}} environment variable with the newly created Elastic search domain endpoint (can find from the AWS Management Console).

3. Load some indexes with test data - there is a bulk upload operation in the postman collection.

4. Run some searches - again, see examples in postman collection.