## GiftWise
A web based gift tracking application built on Ruby 3.3.8 with Rails 7

---

### Summary
Giftwise is a gift tracking app that keeps all details of gift giving all in one place. You can create an event, invite friends & family to the event, and then get helpful gift information regarding each user! Once a user accepts an event invite, you get access to their interests, profile bios, and wish list. You can also chat with a gift giving assistant that will generate gift ideas personalized to each event user. 

### Live Demo

Production: https://test-heroku-gift-d2da158a293e.herokuapp.com

### Local Setup

1. Requirements: Ruby 3.3.8 and Bundler
2. Install gems: `bundle install`
3. Prepare DB: `bin/rails db:setup` (or `db:create db:migrate`)
    - In the future, may want seed data via `bin/rails db:seed`
4. Run tests:
    - Unit: `bundle exec rspec`
    - BDD: `bundle exec cucumber`
5. Start server: `bin/rails server` then open `http://localhost:3000`

### Status

Active development. Main branch tracks the latest stable code. Feature branches hold in progress stories and tasks. 

### Preview

<img width="1861" height="870" alt="image" src="https://github.com/user-attachments/assets/63a66194-ac5f-4680-ad11-382e72d7ae6a" />
<img width="1861" height="874" alt="image" src="https://github.com/user-attachments/assets/e794ea54-f50e-4f6e-b4e6-85620cc66fb6" />
<img width="1859" height="870" alt="image" src="https://github.com/user-attachments/assets/2ec8eba1-82a4-45f5-b176-724ad6039887" />


