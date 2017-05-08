# Framgia Booking Tours

## Admin

- Manage User
- Manage Tour
- Manage booking requests
- Manage user reviews
- Manage revenue
- Manage category

## Guess
- View tour
- View review about place, food, news 
- Search tour
- Register account

## User
- View tour
- Booking tour
- Payment tour by internet banking
- Sign in, sign out
- Can authenticate via Facebook, Twitter, Google
- Manage user bank account
- View review about place, food, news 
- Search tour
- Manage profile
- Manage review of themself
- Comment a review, Comment a comment
- Like review
- Rating a tour

## Activity
- Booking tour
- Cancel tour
- Create new review
- User pay tour

## User
- can sign-up
- can sign-in/sign-out
- can create a post (display title, body, date)
- can make a comment on a post (of owner and followed user) (display comment, name and date)
- can follow other users
- can see the latest posts which are posted by following users (with pagination)

## Everyone (including no sign-in user)
- can read all posts and their comments (with pagination)
- can search post by keyword
- cannot make a comment

## Admin

* can manage all data

----------

# Step by step

1. Design database
2. Add task on redmine + estimate time
3. Static page
4. Init model + relationship
5. Login logout
6. Other pulls

> Notice: Trừ pull về init model, còn lại các pull khác không nhiều hơn 15 files


----------


# Step to update task on redmine

1. Change Status to "In Progress", "Due date"
2. Update  "Spent time", "% Done (100)",  before send pull request to trainer 
3. if trainer COMMENT, change "% Done (80)", after that continue to fix comment else move to step 4
4. after MERGED, update task infomation "spent time", "% Done (100)", Status to "Resolved"
