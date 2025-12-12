# The NUAST Fullstack app

## Modules:
Each module is stored in its own directory

### Database:
- Mongo DB
- ORM
### Flask `./flask`:
- CRUD Restful API
- Serve the frontend
- Interact with the DB
    - `/read`
    - `/update`
    - `/list`
    - `/delete`
### Frontend:
- Jinja
- Bootstrap

## Plan
For now we only need to take a `Name` and `Email` from a user in the frontend code,  
Store it in a database through the Flask API  
Which then interacts with the database to store it
