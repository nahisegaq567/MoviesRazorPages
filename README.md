This project uses Entity Framework Core for the architecture, Razor Pages for the development of the 
webpages, and SQLite for the storage of data entered by the user. The webpage also features a search
option using the required bind property for HTTP GET requests.

Movie data can be entered by the user, such as the movie rating or price, and this is stored in the 
SQLite database. A model class contains seeded data, which can also be manipulated from Visual Studio 
(for this project, it contains example ratings. The database context is registered with the Dependency 
Injection container in the Program class.

Validation attributes are implemented in order to reduce the chances of the user entering incorrect 
data, such as a non-compliant price value. 
