This shows that `better_errors` is not working on a fresh rails install using rack 2.0.7.

To reproduce:

1. Clone this repo
2. Run `bundle install`
3. Run `rails server`
4. Navigate to `localhost:3000/alsdkjfaldj` (bogus route) and notice that the Routing Error it throws does not render a `better_errors` screen.
