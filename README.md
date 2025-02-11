# AskIT

Creating a space where developers can quickly find accurate, reliable answers to their coding questions. What sets it apart is the community-driven approach, where users contribute their expertise, and the platform's voting and reputation system rewards quality contributions. We hope to create a self-sustaining cycle of knowledge.

# Project Components

* [ER: Requirements Specification](docs/Requirements.pdf)

* [EBD : Database Specification](docs/Database.pdf)

* [EAP : Architecture Specification and Prototype](docs/Architecture.pdf)

* [PA : Product and Presentation](docs/FinalProduct.pdf)

### Installation

Here is the docker command to start the image:
docker run -d --name lbaw24141 -p 8001:80 gitlab.up.pt:5050/lbaw/lbaw2425/lbaw24141

To run locally: 

- docker compose build
- docker compose up
- php artisan db:seed
- php artisan serve


### Usage

#### Administration Credentials


| Email | Password |
|----------|----------|
| admin@example.com | 1234 |

#### User Credentials

| Type | email | Password |
|------|----------|----------|
| basic account with some notifications | alice.santos@example.com | 1234 |
| banned user | pedro.oliveira@example.com  | 1234 |


#### Mailtrap Credentials

| Email | Password |
|----------|----------|
| lbaw2024g1@gmail.com | lbaw2024t14g1 |

Maybe, need to log in to Google, because we signed up with Google in mailtrap website.

With that, can also try log in with google feature.


Finally a video to explain the main features of our project:

https://github.com/user-attachments/assets/b79a0bfa-47be-4ca0-9514-67254568ae14



# Team
* Diogo Salazar Ramos, up202207954@up.pt
* Rafael Filipe Barbosa da Costa, up202205013@up.pt
* Daniel Gomes Silva, up201909935@up.pt
* Tiago Miguel Alves Pires, up202208910@up.pt
