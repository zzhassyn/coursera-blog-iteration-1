# Blog

A Rails blog application for Coursera's Blog App Iteration 1 assignment. Posts have a title and body; comments belong to a post and have a body. Both resources support create, read, update, and delete operations.

## Run locally

Install Ruby and Bundler, then run:

```sh
bundle install
bin/rails db:migrate
bin/rails server
```

Open `http://localhost:3000/posts` or `http://localhost:3000/comments`. Create a post first, then use its ID when creating a comment.
