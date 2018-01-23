# Nosso Amigo Secreto

Nosso Amigo Secreto is a software to help people at the end of the year Secret Santa's party.
Members of a group or community are randomly assigned a person to whom they give a gift. The identity of the gift giver is a secret not to be revealed.
Go party with us!

## Demo
[Nosso Amigo Secreto](http://104.236.242.252/)

## Screenshots

![Home](http://res.cloudinary.com/alteodoro/image/upload/v1516733935/secret_friend/create_campaign.png)
![Login](http://res.cloudinary.com/alteodoro/image/upload/v1516733935/secret_friend/login.png)
![Campaigns](http://res.cloudinary.com/alteodoro/image/upload/v1516733935/secret_friend/create_campaign.png)
![Create Campaign](http://res.cloudinary.com/alteodoro/image/upload/v1516733935/secret_friend/create_campaign.png)

## Getting Started

This instructions will give you a copy of the project on your local machine for development and testing.

### Installing

#### Using Docker
```
git clone https://github.com/andreteodoro/secret_friend.git
cd secret_friend
docker-compose up --build
```

#### Localhost
```
git clone https://github.com/andreteodoro/secret_friend.git
cd secret_friend
bundle install
rails s
```

### Testing

#### Using Docker
```
docker-compose run --rm website rspec
```

#### Localhost
```
rspec
```