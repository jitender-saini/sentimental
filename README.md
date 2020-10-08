# text-sentiment
API Curls

curl --location --request POST 'http://localhost:5000/api/v1/sentiment' \
--header 'accept: application/json' \
--header 'Content-Type: application/json' \
--data-raw '{"text": "i am so happy"}'

curl --location --request POST 'http://localhost:5000/api/v1/sentiments' \
--header 'accept: application/json' \
--header 'Content-Type: application/json' \
--data-raw '{ "texts": [ { "text": "i am so happy" }, { "text": "I am so SAD" }, { "text": "today is a Good day" } ]}'
