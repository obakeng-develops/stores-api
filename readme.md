## Stores REST API

## Description

This project uses Flask, Flask-RESTful, Flask-SQLAlchemy, Flask-JWT, uwsgi & psycopg2. It's a REST API that allows to create your own store with each store having specific items.

## Resources

### There are three resources you can make use of

UserRegister
Item
Store

## UserRegister

To register a new user, you can call the https://stores-res-flask.herokuapp.com/register endpoint and pass on two arguments: username and password, with this structure

```
{
    "username": "Mandla",
    "password": "88199288"
}
```

## Store

The store resource will allow you to create, read, and delete a store. There's no updating for a store.
To create/read/delete a store, you need to send data to this endpoint https://stores-res-flask.herokuapp.com/store/[name]
To retrieve a list of stores with their items, you need to send data to this endpoint https://stores-res-flask.herokuapp.com/stores

## Item

The item resource will allow you to create, read, update and delete an item from a specific store.
To create/read/delete/update an item, you need to send data to this endpoint https://stores-res-flask.herokuapp.com/item/<name>
To retrieve a list of items, you need to send data to this endpoint To create/read/delete a store, you need to send data to this endpoint https://stores-res-flask.herokuapp.com/items

### Enjoy!
