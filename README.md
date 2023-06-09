# serverless-api

## Author: Coriana Williams

### Problem Domain
Create a serverless REST API.

### Collaborators
Help from Ryan, Kenya Womack, Kao Saelor, Resse

1. What is the root URL to your API? 
- ![Api Gateway](https://jvglyfwxui.execute-api.us-east-1.amazonaws.com/people)

2. What are the routes? What inputs do they require? What output do they return?
  - POST /people - Inserts a record into the database.
      Input: JSON body containing the data for the record.
      Output: An object representing the inserted record, including its ID.
  - GET /people - Retrieves an array of objects representing all the records in the database.
    Input: No input required.
    Output: An array of objects representing the records in the database.

GET /people/{id} - Retrieves an object representing a specific record by its ID.
    Input: The ID of the record in the URL path.
    Output: An object representing the requested record.

PUT /people/{id} - Updates a record in the database with new data.
    Input: JSON body containing the updated data for the record, and the ID of the record in the URL path.
    Output: An object representing the updated record.

DELETE /people/{id} - Removes a record from the database.
    Input: The ID of the record in the URL path.
    Output: An empty object indicating the successful deletion of the record.

### Links and Resources

- ![UML](serverlessAPIWhiteboard.png)
