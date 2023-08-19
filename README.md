# Ambula-Java-Developer-Task-Solution-2024
The task to perform :
                                                              Included User Location Problem
                                       Create a spring boot project using Gradle with the following requirements
                                             1. There will be 2 users (ADMIN, READER).
                                             2. ADMIN can perform CRUDE operations like POST, DELETE, PATCH, etc.
                                             3. READER can perform only GET operation.
                                             4. Create a REST API called create_data which creates a table in the database with the name 'user_location'.
                                             5. user_location will have three fields NAME, Latitude, Longitude and excluded.
                                             6. user can update the user_location table using another REST API called update_data
                                             7. READER can call the get_users/N which returns the nearest N users from the location (0,0).
                                             E.g GET http://base_url/get_users/5 will return the nearest 5 users from (0,0) which are not excluded;
                                             You need to create 3 rest API
                                                  a) create_data b) update_data c) get_users/N
                                                   Evaluation will be done on the following criteria
                                                   1. Unit Test
                                                   2. Checkstyle issues
                                                   3. Working functionality
                                                   4. Clean and readable code with proper Javadoc with minimal code smell
                                                   Note: Use HSQL in-memory database for the database work. Your code should be able to create a table with no manual script required.
