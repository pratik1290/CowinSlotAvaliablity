# CowinSlotAvaliablity

The Java script call the COWIN public API every 30 seconds(which is configurable value in milliseconds) to get the slots by dictrict code for next 7 days - https://cdn-api.co-vin.in/api/v2/appointment/sessions/public/calendarByDistrict?district_id=337&date=08-05-2021 and parse the JSON to check the slot avaliablity on the basis of age.

Configurable values - </br>
districtId = 365 (Nagpur District Id)</br>
timeInMillis = 30000 </br>
age = 45 </br>
slotSizeGreaterThan = 0 </br></br>

To get the State Id hit the following API directly in the browser URL - https://cdn-api.co-vin.in/api/v2/admin/location/states</br>
TO get the District Id with the help of State Id - https://cdn-api.co-vin.in/api/v2/admin/location/districts/<State-Id></br>
(Replace <State-Id> with actual id)
  
<h1>Run</h1>  
To run the java script. Download the HTML and double click should open it in default browser.
