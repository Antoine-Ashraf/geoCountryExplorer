# Geolocation-Based Country Data Explorer
A dynamic web application that leverages the **Geolocation API** and **RestCountries API** to display real-time country information based on the user's location. Built with modern JavaScript (ES6+), this project demonstrates:  
- **Reverse geocoding** to convert latitude/longitude into country/city names  
- **Async/await workflows** for efficient API integration (geocode.xyz + RestCountries)  
- **DOM manipulation** to dynamically render country statistics (population, currency, language)  
- **Error handling** for geolocation permissions and API failures  
- **Responsive UI** with clean data visualization  

Key technical features:  
✅ Promise chaining & error propagation  
✅ Modular code architecture with reusable `renderCountry`/`renderError` functions  
✅ RESTful API consumption using `fetch`  
✅ Geolocation permission handling  
