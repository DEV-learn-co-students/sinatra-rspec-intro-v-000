

# Sinatra, RSpec, and Rack::Test

In the specs, you'll find tests to make sure that your Sinatra application responds to the expected routes, and that your route handlers respond with the expected information.

Start with `route_spec.rb` and write the code in `app.rb` that makes the tests pass.

After all your tests pass, use `rackup` to run your app, and then make sure it works in the browser as well.

How do you get the /hello path to work with a name? Hint: you need [query string parameters](http://en.wikipedia.org/wiki/Query_string).

## Resources
* [Thoughtbot](http://robots.thoughtbot.com/) - [How to Test Sinatra-Based Web Applications](http://robots.thoughtbot.com/how-to-test-sinatra-based-web-services)
* [Sinatra Docs](http://www.sinatrarb.com/) - [Testing Sinatra with Rack::Test](http://www.sinatrarb.com/testing.html)
* [Optional parameters in Sinatra](http://stackoverflow.com/questions/21847105/several-optional-parameters-in-sinatra-route)

<a href='https://learn.co/lessons/sinatra-rspec-intro' data-visibility='hidden'>View this lesson on Learn.co</a>
