# # create a new Bitcoin address
$ curl https://block.io/api/v2/get_new_address/?api_key={API KEY}
{
  "status": "success",
  "data": {
    "network": "BTC",
    "user_id": 1,
    "address": "3EL5SKSjEzFQDBmXA5JFbsZu48vKnNSdDH",
    "label": "random"
  }
}
