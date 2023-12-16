## Credentials

- *Guest:*
  - Username: guest
  - Password: guest

- *Admin:*
  - Username: admin
  - Password: admin

## Steps

1. *Clone the repository:*
    bash
    git clone https://github.com/your-username/library-management-system.git
    

2. *Navigate to the project directory:*
    bash
    cd frontend
    cd backend
    

3. *Install dependencies:*
    bash
    npm install
    

4. *Set up environment variables:*
    - Create a .env file in the root directory and add the following:
        env
        PORT=3000
        DB_URI=your-mongodb-atlas-url
        SECRET_KEY=mysecret-key
        
        Replace your-mongodb-atlas-url with the connection URL from your MongoDB Atlas account.

5. *Run the application:*
    bash
    npm start
    

6. The application will be accessible at [http://localhost:3000](http://localhost:3000).
