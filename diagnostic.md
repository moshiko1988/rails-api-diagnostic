# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
basically how the site works updates and changes this refers to everything the user can’t see in the browser, like databases and servers. ```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
the model
```

Which layer in the MVC pattern communicates with the model?

```md
the controller communicates with the model
```

Why don't we use views in our interpretation of the MVC pattern?

```md
i am not sure -
```

What does C.R.U.D stand for?

```md
CREATE
READ
UPDATE
DELETE

```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
server
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
// your response here
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
request to the server
server ask controller for the id1
controller get the info from model
model give it back to the controller - server - browser
```

What is the command to generate a new rails-api app?

```bash
bin/rails generate scaffold
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
bin/rails db:migrate
bin/rails db:drop
bin/rails db:create:
bin/rails db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
