# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
To store, manage and protect data and to allow communication between users.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The controller layer
```

Which layer in the MVC pattern communicates with the model?

```bash
The Model layer
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Because modern dev tools are capable of iterpretting returned data without a need for the View layer
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Destroy. More porgrammatically: Post, Get, Patch, Delete.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
In the Controller layer.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
Post, Get, Patch, Delete, and index.
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
The routes file picks up on 'GET' and calls the 'Index 'function in the 'people controler' for the index '1'. The controller then returns the values under the 'people model' associated with the instance of people (possibly an index of Person) with an 'id' of 1.
```

What is the command to generate a new rails-api app?

```bash
bundle exec rails bd:create |I must have this wrong|
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
bundle exec rake db:drop db:create db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails g model pet name:string age:integer
```
