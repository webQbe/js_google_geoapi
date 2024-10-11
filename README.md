# JavaScript with Google Geocoding API

- Axios library is used 
- Send requests to Google Geocoding API with street addresses 
- Get latitude & longtitude, country, and any associated information with that address
- We need to register for an API key. ([See documentation](https://developers.google.com/maps/documentation/geocoding/start))

    1. Go to [console.developers.google.com](console.developers.google.com)
    2. Create project 
    3. Enable APIs & services 
    4. Select Maps > Geocoding API > Enable
    5. Copy API Key
    6. Open Postman web app > New HTTP request > GET > 
       > https://maps.googleapis.com/maps/api/geocode/json?address=1600+Amphitheatre+Parkway,+Mountain+View,+CA&key=YOUR_API_KEY
    7. See Response

    