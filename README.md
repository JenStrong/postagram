# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


<h1>Welcome to Postagram</h1>

    <% @posts.each do |post| %>
      <div class="card" style="width: 18rem;">
        <div class="card-header"> **Avatar/User Here </div>
        <img class="card-img-top" <%= image_tag(post.image, style: "width: 100%") %>
        <div class="card-body">
          <p class="card-text"><%= post.description %></p>
          <div class="card-text"><%= link_to 'Edit', edit_post_path(post) %></div>
          <div class="card-text"><%= link_to 'Delete', post, method: :delete, data: { confirm: 'Are you sure?' } %></div>
        </div>
      </div>
<% end %>
