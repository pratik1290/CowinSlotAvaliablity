# CowinSlotAvaliablity

The scripts call the COWIN public API every 30 seconds(which is configurable value in milliseconds) to get the slots by dictrict code for next 7 days - https://cdn-api.co-vin.in/api/v2/appointment/sessions/public/calendarByDistrict?district_id=337&date=08-05-2021 and parse the JSON to check the slot avaliablity on the basis of age.

Configurable values -
var timeInMillis = 30000;
var age = 45;
var slotSizeGreaterThan = 0;
