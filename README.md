# Create simple REST API to get list of authors. 

# Entities:

## AUTHOR
 - ID
 - NAME

## BOOK
 - ID
 - AUTHOR_ID
 - NAME
 
# Create following REST endpoints

 1. Get single Author with a list books
 2. Get all Authors with their list of books
 3. Create Author together with list of books
 
 
#Notes

Use H2 in memory database. Populate tables with couple of rows on startup. 

Don't need to handle any exceptions, like row doesn't exist etc. Don't need to validate values for creation. 

You can use any documentation, forums, existing code etc as a reference. You can use any IDE and pick either Maven or Gradle. 
