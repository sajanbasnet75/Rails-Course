## Rails Basics

### Ruby On Rails Basics

### INTRODUCTION (3 hours)

| Title            | Key Concepts                     | Resources                                                    | Assignment                                                   |
| ---------------- | -------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
|                  | Road-map for Backend Development | [Roadmap for Backend Development](https://github.com/kamranahmedse/developer-roadmap/blob/master/img/backend.png?year-2021-2) |                                                              |
|                  | Rails for web development        | [Rails for web development](https://blog.engineyard.com/ruby-on-rails-web-development) |                                                              |
| **Introduction** | What and Why use Ruby on Rails   | [What and Why use Ruby on Rails](https://careerfoundry.com/en/blog/web-development/should-i-learn-ruby-on-rails/) |                                                              |
|                  |                                  |                                                              |                                                              |
|                  | Understanding How Web Works      | [HTTP and Web Server](https://code.tutsplus.com/tutorials/how-the-web-works-http-and-the-web-server--cms-25971) | *Give an real world example of how the communication between host and a client is done in your own words* |
|                  |                                  | [HTTP protocal every web developer must know](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177) |                                                              |
|                  |                                  |                                                              |                                                              |

### RAILS BASICS 1.0 (5 hours)

| Title                | Key Concepts                                                 | Resources                                                    | Assignment                                                   |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|                      | Install Ruby and RVM if not installed already. What is version control manager and why its needed ? | [RVM as ruby VCM](https://rvm.io/rvm/install)                |                                                              |
|                      |                                                              |                                                              |                                                              |
|                      | **Creating out First Rails application with**                | [Official site](https://guides.rubyonrails.org/getting_started.html#creating-a-new-rails-project) |                                                              |
|                      | Installing Node js and npm                                   | [Installing Node JS](https://guides.rubyonrails.org/v5.0/getting_started.html#installing-rails) |                                                              |
| **Rails Basics 1.0** | Installing Yarn                                              | [Installing Yarn](https://classic.yarnpkg.com/en/docs/install#windows-stable) |                                                              |
|                      | Installing Rails with `gem install rails`                    | [Installing Rails](https://guides.rubyonrails.org/v5.0/getting_started.html#installing-rails) | *Create a new rails app and start the server.*               |
|                      |                                                              |                                                              |                                                              |
|                      | Install Database (sqlite/postgres/mysql)                     |                                                              |                                                              |
|                      |                                                              |                                                              |                                                              |
|                      | Understanding Rails project structure                        | [Understanding your rails application Structure](https://hackernoon.com/understanding-your-rails-application-structure-r8w32xj) | 1. What is a gem and Gemfile in rails ? 2. [Add a Rubocop gem to our rails app](https://developerblogs.github.io/blogs/rails/01#2-setup-robocop-gem) |
|                      |                                                              | [Rails 6 and above application structure](https://dev.to/femolacaster/journey-on-rails-ror-6-s-file-structure-12jk) | 3. Add bootstrap in your rails app with webpacker            |
|                      |                                                              | [Assesset Pipeline](https://www.youtube.com/watch?v=kgEcdBGpr54) |                                                              |
|                      |                                                              | [Understanding Webpacker](https://prathamesh.tech/2019/08/26/understanding-webpacker-in-rails-6/) |                                                              |
|                      |                                                              | [Sp rockets and Webpacker](https://rossta.net/blog/why-does-rails-install-both-webpacker-and-sprockets.html) |                                                              |
|                      | Understanding MVC architecture                               | [MVC architecture](https://www.youtube.com/watch?v=DUg2SWWK18I&ab_channel=WebDevSimplified) | *Write a short introduction about MVC architecture with some real world example in your own words.* |
|                      |                                                              |                                                              |                                                              |

## Rails Basics 1.1 (16 hours)

| Title                | Key Concepts                         | Resources                                                    | Assignment                                                   |
| -------------------- | ------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
|                      | Rails Controllers                    | [Action Controller Official Guide](https://guides.rubyonrails.org/action_controller_overview.html) | 1. In your project generate a new User controller using `rails generator` |
|                      |                                      | [Rails Controller](https://www.theodinproject.com/courses/ruby-on-rails/lessons/controllers) | 2. The controller should have new, index, show, create, update, delete actions/methods. |
|                      |                                      |                                                              | 3. Check all the files that are generated in this process.   |
|                      |                                      |                                                              |                                                              |
|                      | Rails Routes                         | [Blog Post](https://medium.com/podiihq/understanding-rails-routes-and-restful-design-a192d64cbbb5) | 1. Convert the generated routes to rails way of writing Restful Routes (using resources) |
|                      |                                      | [Official Guide](https://guides.rubyonrails.org/routing.html) | 2. Find the difference in the route paths using `rails routes` in console, after using the `resources` and without using `resources` |
|                      |                                      | [Rails Routes](https://www.theodinproject.com/courses/ruby-on-rails/lessons/routing) | 3. Replace the "Yay! You're on Rails" page with index view of your pages controller. (using root route) |
| **Rails Basics 1.1** |                                      |                                                              |                                                              |
|                      |                                      |                                                              |                                                              |
|                      |                                      |                                                              |                                                              |
|                      | Rails Models                         | [Active Record Basics](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby-on-rails/lessons/active-record-basics-ruby-on-rails) | 1. Create a User model with different attributes such as full_name, email, age etc 2. Perform the required migration. |
|                      |                                      | [Active Record Basics official guide](https://guides.rubyonrails.org/active_record_basics.html) | 3. Add some model validations                                |
|                      |                                      | [Active Record Migrations](https://guides.rubyonrails.org/active_record_migrations.html) | 4. Use `rake seed` to generate some fake users. [Blog post](https://ninjadevel.com/seeding-database-ruby-on-rails/) |
|                      |                                      | [Active Record Validations](https://guides.rubyonrails.org/active_record_validations.html) | 5. Create another model and associate it with the User model. For eg: User can have many types of Contacts |
|                      |                                      | [Active Record Associations](https://guides.rubyonrails.org/association_basics.html) |                                                              |
|                      |                                      | [Active Record Query Interface](https://guides.rubyonrails.org/active_record_querying.html) |                                                              |
|                      |                                      |                                                              |                                                              |
|                      | Rails Views                          | [Rails Views](https://www.theodinproject.com/courses/ruby-on-rails/lessons/views) | 1. **Display/Read** the list of all Users in the index views of pages |
|                      |                                      | [Action View Official Guide](https://guides.rubyonrails.org/action_view_overview.html) | 2. Create a **Form** so that we can **create** new Users to the list. |
|                      |                                      | [Layouts and Rendering Official Guide](https://guides.rubyonrails.org/layouts_and_rendering.html) | 3. Add a feature to **edit** the existing user               |
|                      |                                      |                                                              | 4. Add a feature to **delete** the user from the list.       |
|                      |                                      |                                                              |                                                              |
|                      | Uploading Files with active storage. | [Official guide](https://edgeguides.rubyonrails.org/active_storage_overview.html) [Using Active Storage in Rails 6](https://pragmaticstudio.com/tutorials/using-active-storage-in-rails) | 1. Add a feature so that user can upload files.              |