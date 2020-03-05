## The Guestbook Coding Challenge V1 Requirements

**Billboard Voting**

At some point in the future we'd like to run a contest where we'll buy a billboard and ask people to submit designs, then put up the one that gets the most votes. This challenge is a very simplistic version of that with a slight change: users will vote on billboards instead of design assets.

Here's an outline of what your application should do:
- [ ] Your app should ingest `hotel_billboards_seed.csv` as seed data. It contains a list of images of billboards with accompanying names.
- [ ] When a user visits the homepage, it should ask them to create an account. After creating an account, a user should be signed in. You do not need to add a separate login page. Auth can be very simple.
- [ ] After creating an account, the user should see a list of billboards in rank order along with their photos, names, score, and a way to vote the billboard up or down.
- [ ] Voting should happen via AJAX. Reordering after voting is not required, but a bonus (i.e. it's fine if reordering only happens on page refresh).
- [ ] The score for each billboard can be as simple as upvotes minus downvotes.
- [ ] After voting, the user should see a success message.
- [ ] A user should be able to see how they voted, and change their vote. They shoud only be able to assign 1 vote per board.
- [ ] The app should look and feel good, as if it real users would actually use it. It should be responsive.

The application should have a README that explains clearly how to set it up and run it. We will attempt to run the application ourselves of course, so do us a favor by making it easy.
