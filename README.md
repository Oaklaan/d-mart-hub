# 🛒 D-Mart Hub — Find D-Mart Near Me!

A simple and responsive web application that helps users quickly find the nearest **D-Mart stores** using their current location and Google Maps.

The application uses the browser's **Geolocation API** to detect the user's location and generates Google Maps search links for nearby D-Mart stores.

---

## 📌 About the Project

**D-Mart Hub** is a lightweight location-based grocery store finder built using **HTML, CSS, and JavaScript**.

The main purpose of this project is to provide users with a simple interface where they can:

* 📍 Share their current location
* 🛒 Search for nearby D-Mart stores
* 🗺️ Open D-Mart locations directly in Google Maps
* 🔍 View Google Maps search results
* ⚡ Use the application without installing any software

The project is completely client-side and does not require a backend or database.

---

## ✨ Features

### 📍 Location Detection

Uses the browser's built-in **Geolocation API** to obtain the user's latitude and longitude.

### 🗺️ Google Maps Integration

Automatically generates Google Maps search links based on the user's current location.

### 🔎 Search Fallback

If location access is unavailable or denied, users can still search for:

> D-Mart near me

directly through Google Maps.

### 📱 Responsive Design

The interface is designed to work across:

* 💻 Desktop
* 📱 Mobile
* 📲 Tablet

### 🎨 Clean UI

The application uses a D-Mart-inspired visual theme with:

* Green
* Yellow
* Cream
* White

along with a simple card-based layout.

### 🔐 Privacy Friendly

The application does not store the user's location.

Location information is used only within the browser to generate the Google Maps search URL.

---

## 🛠️ Technologies Used

| Technology      | Purpose                      |
| --------------- | ---------------------------- |
| HTML5           | Structure of the webpage     |
| CSS3            | Styling and responsive UI    |
| JavaScript      | Application logic            |
| Geolocation API | Detecting user's location    |
| Google Maps     | Finding nearby D-Mart stores |

---

## 📂 Project Structure

```text
d-mart-hub/
│
├── mart.html
└── README.md
```

---

## 🚀 How to Run the Project

### Method 1 — Open Directly

1. Clone the repository:

```bash
git clone https://github.com/Oaklaan/d-mart-hub.git
```

2. Open the project folder:

```bash
cd d-mart-hub
```

3. Open `mart.html` in your browser.

---

### Method 2 — Using VS Code

1. Clone the repository.

2. Open the folder in **Visual Studio Code**.

3. Open `mart.html`.

4. Install the **Live Server** extension if you have it.

5. Right-click `mart.html`.

6. Select:

```text
Open with Live Server
```

7. Click:

```text
📍 Find D-Mart Near Me
```

8. Allow location permission when your browser asks.

---

## ⚙️ How It Works

The application follows this flow:

```text
User opens D-Mart Hub
        ↓
Clicks "Find D-Mart Near Me"
        ↓
Browser requests location permission
        ↓
User allows location
        ↓
Geolocation API returns latitude & longitude
        ↓
Application creates Google Maps search URL
        ↓
User opens Google Maps
        ↓
Nearby D-Mart stores are displayed
```

---

## 📍 Geolocation

The application uses:

```javascript
navigator.geolocation.getCurrentPosition()
```

The API provides:

```text
Latitude
Longitude
```

These coordinates are then used to create a Google Maps search URL.

Example:

```text
https://www.google.com/maps/search/D-Mart/@LATITUDE,LONGITUDE,14z
```

---

## 🔗 Google Maps Integration

The application provides two Google Maps options:

### 🗺️ Open in Google Maps

Opens a location-focused D-Mart search using the user's coordinates.

### 🔍 See Search Results List

Opens Google Maps search results for D-Mart based on the user's location.

---

## ❌ Location Permission Handling

If the user:

* Denies location permission
* Has location services disabled
* Uses a browser that does not support geolocation
* Experiences a location detection error

the application displays an error message and provides a fallback Google Maps search.

Fallback search:

```text
D-Mart near me
```

---

## 🔐 Privacy

D-Mart Hub does not have a backend or database.

The application:

* ❌ Does not store user locations
* ❌ Does not send location data to a server
* ❌ Does not require user registration
* ❌ Does not require an account

The location is accessed by the browser and used to generate the Google Maps search link.

---

## 🎨 UI Design

The interface contains:

### Header

```text
Grocery Finder

Find a D-Mart near you
```

### Description

A short explanation informing users that their location will be used to find nearby D-Mart stores.

### Main Button

```text
📍 Find D-Mart Near Me
```

### Result Section

After successful location detection:

```text
🗺️ Open in Google Maps
🔍 See Search Results List
```

---

## 📸 Application Preview

You can add a screenshot of your application here:

```markdown
![D-Mart Hub Preview](screenshot.png)
```

For example, your repository can contain:

```text
d-mart-hub/
│
├── mart.html
├── README.md
└── screenshot.png
```

---

## 🌐 Browser Compatibility

The application works with modern browsers that support the Geolocation API.

Recommended browsers:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

> Location access generally requires a secure context such as HTTPS or localhost.

---

## ⚠️ Important Note About Location

When running the application locally, browsers may restrict geolocation when opening an HTML file directly using:

```text
file:///
```

For reliable location access, use **Live Server** or host the project using a service such as GitHub Pages.

---

## 🚀 Future Improvements

The project can be expanded with additional features such as:

* 📍 Automatic distance calculation
* 🛒 D-Mart store details
* ⭐ Store ratings
* 🕐 Store opening and closing times
* 📞 Store contact information
* 🗺️ Embedded Google Maps
* 📌 List of nearby stores
* 📏 Distance from current location
* 🔄 Real-time location updates
* 🌙 Dark mode
* 📱 Progressive Web App (PWA)
* 🗄️ Backend and database integration
* 🔐 User authentication
* ❤️ Save favorite D-Mart stores

---

## 📚 Learning Outcomes

This project demonstrates practical knowledge of:

* HTML5
* CSS3
* JavaScript
* DOM manipulation
* Browser APIs
* Geolocation API
* Event handling
* Dynamic URL generation
* Google Maps integration
* Responsive web design
* Client-side error handling

---

## 👨‍💻 Author

**Krushna**

Information Technology Student
Bharati Vidyapeeth Deemed University College of Engineering, Pune

### GitHub

[GitHub Profile](https://github.com/Oaklaan)

### Project Repository

[D-Mart Hub](https://github.com/Oaklaan/d-mart-hub)

---

## 📄 License

This project is created for **educational and learning purposes**.

You are free to explore, modify, and improve the project.

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

---

### 🛒 D-Mart Hub

**Find a D-Mart near you — quickly and easily.**
