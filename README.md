# RESTful Blog

A RESTful blog app to practise RESTful Routing

| Name | Path | HTTP Verb | Purpose | Mongoose Method
| ------ | ------ | ------ | ------ | ------ |
| Index | /blogs | GET | List all blogs | Blog.find()
| New |  /blogs/new | GET |Show new blog form | N/A
| Create | /blogs | POST | Create a new blog post, then redirect somewhere | Blog.create()
| Show | /blogs/:id | GET | Show info about one specific blog post | Blog.findById()
| Edit | /blogs/:id/edit | GET | Show edit form for one blog post | Blog.findById()
| Update | /blogs/:id | PUT | Update a particular blog post, then redirect somewhere | Blog.findByIdAndUpdate()
| Destroy | /blogs/:id | DELETE | Delete a particular blog post, then redirect somewhere | Blog.findByIdAndRemove()