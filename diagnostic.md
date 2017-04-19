# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The purpose of a back end is to connect clients to servers and store data.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The model is used by the controller to fetch data.
```

Which layer in the MVC pattern communicates with the model?

```md
The controller, which contains the business logic communicates with the model.
```

Why don't we use views in our interpretation of the MVC pattern?

```md
We don't use views because we have single page applications with only one piece of markup.
```

What does C.R.U.D stand for?

```md
CRUD stands for create, read, update destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
CRUD actions are done in the model and controller sections.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Index, show, create, update, destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
The get request is handled by:
1. The controller which gets the request
2. The controller passes the request to the model
3. The model looks in the database to see if there is a person with an id of one
4. The model returns the response of whether there is or isn't to the controller
5. THe client displays the result.
```

What is the command to generate a new rails-api app?

```bash
rails new
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
1. db:create
2. db:drop
3. db:migrate
4. db:examples
5. db:seed
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails generate scaffold Pet name:string age:integer
```
