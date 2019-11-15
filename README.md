# GoStack Challenge 03 

![GymPoint](https://raw.githubusercontent.com/Rocketseat/bootcamp-gostack-desafio-03/master/.github/logo.png)

![GitHub language count](https://img.shields.io/github/languages/count/GiovaniCuenca/GoStack-Challenge03)    ![GitHub issues](https://img.shields.io/github/issues/GiovaniCuenca/GoStack-Challenge03)          ![GitHub](https://img.shields.io/github/license/GiovaniCuenca/GoStack-Challenge03)


## About the Challenge

Develop the application backend which will be used for the Bootcamp certification final challenge.
[Oficial challenge README](https://github.com/Rocketseat/bootcamp-gostack-desafio-03/blob/master/README.md#desafio-03-continuando-aplica%C3%A7%C3%A3o)
## Technologies

 - **Engine**: NodeJS
 - **Microservices**: Express
 - **Utility**: Sucrase / Nodemon / 
 - **DB**: Docker / Sequelize / Postgres SQL / Redis
 - **Authentication**: JWT (Jason Web Token) / bcrypt
 - **Mail**: Nodemailer / Bee Queue / Express Handlebars
 - **Package Manager**: Yarn
 - **Programs**: VScode / Insomnia / Postbird

## Features

 - API development
 - Queues for sending e-mails and dealing with jobs

## Installation
Requirements:
Docker;
Node.JS v10.15 or higher,
Yarn v1.12 or higher,

Clone or download the zip file. At the project folder run the following at your terminal:

    # Install Dependencies:
    $ yarn
    
    # Start Postgres:
    $ docker run --name postgresgympoint -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres:11
    
    # Start Redis:
    $ docker run --name redisgympoint -p 6379:6379 -d -t redis:alpine
    
    # Create a new Database named 'gympoint' and run the following:
    $ yarn sequelize db:migrate 
    $ yarn sequelize db:seed:all
    
    # Run the Server:
    $ yarn dev
    
    # Run Nodemailer:
    $ yarn queue
    

## License
This project is under the MIT license. See the [LICENSE](https://github.com/GiovaniCuenca/GoStack-Challenge03/blob/master/LICENSE) for more information.
