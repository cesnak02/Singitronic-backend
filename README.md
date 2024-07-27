#SINGITRONIC BACKEND

1. Create a .env file in the root directory of the application and add the following line:
   ```
   DATABASE_URL="mysql://username:password@localhost:3306/database_store"
   ```
2. Run npm install in the terminal to install all necessary packages.
3. Run npm install express-fileupload separately.
4. Run npx prisma migrate dev for Prisma.
5. Navigate to the utils folder and execute the command node insertDemoData.js to add data to the database.
6. In the root component, run node app.js.
   
