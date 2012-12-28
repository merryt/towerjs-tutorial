## The Users resource

In this section, we'll implement the users data model in Section 2.1.1, along with a web interface to that model. The combination will constitute a Users resource, which will allow us to think of users as objects that can be created, read, updated, and deleted through the web via the HTTP protocol. As promised in the introduction, our Users resource will be created by a scaffold generator program, which comes standard with each Tower.js project. I urge you not to look too closely at the generated code at this time. It will only add confusion.

Tower.js scaffolding is generated by passing the scaffold command to the tower generate script. The argument of the scaffold command is the singular version of the resource name (in this case, User), together with optional parameters for the data model's attributes: