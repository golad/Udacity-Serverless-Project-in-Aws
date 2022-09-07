# serverless-project
project 4, ALX-T Scholarship, Udacity Cloud Developer Nanodegree project on Serverless Applications on AWS FaaS

### Functionality

The application allows users to create, update, delete TODO items

The application allows users to upload a file.

The application only displays TODO items for a logged in user.

Authentication is implemented and does not allow unauthenticated access.

### Code Base

The code is split into multiple layers separating business logic from I/O related code.

Code is implemented using async/await and Promises without using callbacks.

### Best Practices

All resources in the application are defined in the "serverless.yml" file

Each function has its own set of permissions.

Application has sufficient monitoring.

HTTP requests are validated

### Architecture

Data is stored in a table with a composite key.

TODO items are fetched using the "query()" method and not "scan()" method (which is less efficient on large datasets)