# timezone-information-using-geo-coordinates
Retrieve Timezone Information using Geographical Coordinates and Address

# Task: Retrieve Timezone Information using Geographical Coordinates and Address

Step 1: API Documentation
Refer to the Geoapify API documentation to understand how to fetch timezone information using latitude and longitude.

Step 2: User Interface (UI)
Create a web page with the following elements:

1. Display area to show the user's current timezone using their latitude and longitude (obtained using the Geolocation API)
2. Input field for the user to enter an address
3. Button to trigger the timezone retrieval based on the entered address
4. Display area to show the timezone corresponding to the entered address


Step 3: Fetch User's Current Timezone
Use the Geolocation API (e.g., HTML5 Geolocation API) to retrieve the user's latitude and longitude automatically when they visit the web page. Use these coordinates to fetch and display their current timezone.

Step 4: Retrieve Timezone by Address
When the user enters an address and clicks the button, perform the following steps:

Validate the entered address.
Use a geocoding API (e.g., [Geoapify Geocoding API](https://www.geoapify.com/geocoding-api)) to convert the address into latitude and longitude coordinates.
If the geocoding API returns valid coordinates, use them to fetch the corresponding timezone using the Geoapify Timezone API.
Display the retrieved timezone in the designated area.

## Relevant Links
Figma Link- https://www.figma.com/file/CSwRxPkdiFzE0H9hqbZiOm/Untitled?node-id=0%3A1&t=PGLrcIv4Ch80kUit-1
