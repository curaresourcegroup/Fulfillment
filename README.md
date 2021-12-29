# Fulfillment
#Shipedge to Airtable Automations
POST /orders/createlabelfororder HTTP/1.1
Host: ssapi.shipstation.com
Authorization: __YOUR_AUTH_HERE__
Content-Type: application/json

{
  "orderId": 93348442,
  "carrierCode": "fedex",
  "serviceCode": "fedex_2day",
  "packageCode": "package",
  "confirmation": null,
  "shipDate": "2014-04-03",
  "weight": {
    "value": 2,
    "units": "pounds"
  },
  "dimensions": null,
  "insuranceOptions": null,
  "internationalOptions": null,
  "advancedOptions": null,
  "testLabel": false
}
