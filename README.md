# Ruby On Rails Blog App

I made this project to learn Ruby and Rails so I could be better prepared for interviews at companies that use this program stack

### Install Dependencies

Make sure you have Ruby and Rails installed on your machine. Once you do, you can use *gem* in your 

1. Run this in terminal/command prompt: *gem install bundler*
2. Run this in terminal/command prompt: *bundle install*

### Hot Module Repacement

To enable hot module replacement, run this command in the terminal/command prompt

1. Run this in terminal/command prompt: *bundle exec guard*

### To Run This Project

1. Clone the reop
2. Run this in terminal/command prompt: *rails s*
3. Go to *http://localhost:3000/* in your browser

### To Get All Project Routes

1. Run this in terminal/command prompt: *rake routes*

***

## Useful Rails Tips

To generate a controller called post_controller.rb run this in terminal/command prompt: *rails g controller posts*

To generate a model called Post with fields title and content run this in terminal/command prompt: *rails g model Post title:string content:text*

To migrate the rails database run this in terminal/command prompt: *rails db:migrate*

To generate your own migration run this in terminal/command prompt: *rails g migration AddPostIdToComments*

### Accessing Our Rails Database Using Rails Console

1. To access rails console run this in terminal/command prompt: *rails console*

2. Then to access individual models like Post by running: *@post = Post*

3. Then connect to that models data by running: *@post.connection*

4. Then view all the records of that model by running: *@post.all*

5. To create a reference to an individual record by its Id run: *Post.find(8)*

6. Now running *@post* should return that individual post which you can now edit the values of like this: *@post.title "New title"*, and then run this to save the changes: *@post.save*

