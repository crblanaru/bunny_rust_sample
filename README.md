# bunny_rust
Rust app for Bunnyshell demo


To add data:

curl --location --request POST 'https://domain.com/holodeck' \
--header 'Content-Type: application/json' \
--header 'Content-Type: text/plain' \
--data-raw '{
    "id": 2,
    "name": "Electric!"
}'

To see the data navigate to: https://domain.com/holodeck