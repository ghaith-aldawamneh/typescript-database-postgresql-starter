<h1 base starter kit for making Node.js + Express.js API with TypeScript 🛠</h1>
<h1 align="center">Notes to be taken from this project 🎗:</h1>
<h6 align="center">keep in mind that this project has been taken just in order to take notes from it.
 

 
# About
# in case of an unsuccess connection: 
![typescript-database-1](https://user-images.githubusercontent.com/101610105/209463842-39c8c231-1cfd-4110-9085-9845f1405132.png)
# in case of a success connection:
![typescript-database-2](https://user-images.githubusercontent.com/101610105/209463845-53c43389-98df-4568-aa71-aa42988f666a.png)
This project is a base starter kit for making Node.js + Express.js API with TypeScript and [typescript-rest](https://github.com/thiagobustamante/typescript-rest).
It is structured to be fully configured with DB using [TypeORM](https://github.com/typeorm/typeorm), which is going to be fully usable as a go to Kit to get started with your
next or existing API project.
## what i learned from this project:
  - a new smart way for importing and exporting the ts modules from the inner files inside the src file.
  - using the ready typescript-rest library that facilitates the responding issue with basic responing messages.
  - Server.buildServices(app) from the server.d.ts.
  - when connection we must handle the connection by, getConnection(), connection.connect().
