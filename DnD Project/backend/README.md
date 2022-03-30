# Backend

## Before Running

Make sure to run `npm install -D` so that you install of the packages including the dev dependencies.

After doing that, you will need to create a file titled `.env` in the same folder that you have the `package-lock.json` file.

Here's what must be put in the file (check discord for the actual details):

```
USERNAME={db_username}
PASSWORD={password_to_db}
ADDRESS={address_of_db}
DATABASE={db_name}
ACCESS_TOKEN={token}
REFRESH_TOKEN={token}
```

For the Access and Refresh tokens in the env file, you can put whatever as there will be an official one later in development or when we push to production.

This will allow for the backend application to use those variables custom variables when connecting to the database.

## Running

Run the command `npm run dev` to run the server in development mode.
You should see it say this for the backend application to be working:

```
Server running on port 8080
Mongodb connected
```
