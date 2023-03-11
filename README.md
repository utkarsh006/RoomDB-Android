- [Why RoomDB over SqLite?](https://medium.com/mindorks/sqlite-made-easy-room-persistence-library-ecd1a5bb0a2c)


### 3 components of RoomDb

- **Database class :** It holds the database and serves as the main access point for your app persisted or stored data.

- **Entity :** Represents tables in your app database.
- **Data Access Object (DAO) :** Provides methods to perform operations on the database.

### STEPS

1. Create the data class that will denote the object we are going to put inside our table.
2. Create DAO for writing the queries.
3. Create Appdatabase class which would be creating the actual database.
4. Write your CRUD operations in MainActivity.