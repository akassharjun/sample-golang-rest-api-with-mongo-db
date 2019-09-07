# sample-golang-rest-api-with-mongo-db

Basic RESTful API to save the first name & last name of a person. 

### Requirements

* Local instance of MongoDB
* Go

### API Endpoints

#### getPerson

```
URL
http://localhost:9323/person/{id}
```


#### createPerson

```
URL
http://localhost:9323/person/

Body
{ 
  "firstname" : "FIRST NAME",
  "lastname" : "LAST NAME" 
}
```

#### get People

```
URL
http://localhost:9323/people/
```