## 1. According to the default Rails page, what is the version of Ruby on your system? Confirm by running ruby -v at the command line.

`ruby 2.6.3p62 (2019-04-16 revision 67580) [x86_64-darwin19]`

## 2. What is the version of Rails? Confirm that it matches the version installed in Listing 1.2.

`6.0.3.2`

## 3. Change the content of the hello action in Listing 1.9 to read “hola, mundo!” instead of “hello, world!”.

👋🌎

## 4. Show that Rails supports non-ASCII characters by including an inverted exclamation point, as in “¡Hola, mundo!”

¡👋🌎!

## 5. By following the example of the `hello` action in Listing 1.9, add a second action called `goodbye` that renders the text “goodbye, world!”. Edit the routes file from Listing 1.11 so that the root route goes to goodbye instead of to hello

🌎👋

## 6. Arrange for your production app to display “hola, mundo!”.

👍

## 7. Arrange for the root route to display the result of the goodbye action.

👍

## 8. Run `heroku help` to see a list of Heroku commands. What is the command to display logs for an app?

`heroku logs`

## 9. Use the command identified in the previous exercise to inspect the activity on your application. What was the most recent event?

`2020-07-04T12:48:10.100211+00:00 heroku[router]: at=info method=GET path="/favicon.ico" host=tranquil-capitol-reef-63850.herokuapp.com request_id=40b8bb89-583f-4cfd-9633-a4ce79459d3a fwd="67.83.196.95" dyno=web.1 connect=1ms service=9ms status=200 bytes=143 protocol=https`
