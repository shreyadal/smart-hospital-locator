# 🏥 Smart Hospital Locator System

This project is a location-based hospital discovery system built using Django. It helps users find nearby hospitals and clinics within a specified radius using real-time geolocation and mapping APIs.

The system is especially useful for users who are new to an area and need quick access to nearby healthcare facilities.

---

## 🚀 Features

* 📍 Detect user location using geolocation APIs
* 🏥 Find nearby hospitals and clinics
* 📏 Search within a 5 km radius
* 🗺️ Route generation for navigation
* 🔗 Integration with real-world APIs
* ⚙️ Backend powered by Django

---

## 🔗 APIs Used

* **OpenRouteService API**
  → Used for route generation and navigation

* **Overpass API (OpenStreetMap)**
  → Fetches hospital and clinic locations

* **Nominatim API**
  → Converts location names into geographic coordinates (geocoding)

---

## ⚙️ How It Works

1. User enters or shares their location
2. Nominatim API converts location into latitude & longitude
3. Overpass API fetches nearby hospitals and clinics
4. System filters results within a 5 km radius
5. OpenRouteService generates route for navigation

---

## 🏗️ Project Structure

```id="7mb7vb"
hospital_project/
│
├── hospital/              # Django project
│   ├── settings.py
│   ├── urls.py
│
├── home/                  # Main app
│   ├── views.py           # API logic
│   ├── models.py
│   ├── urls.py
│   ├── templates/
│
├── manage.py
```

---

## 🛠️ Tech Stack

* Python
* Django
* OpenRouteService API
* Overpass API
* Nominatim API
* HTML/CSS

---

## ▶️ How to Run

```id="v1qf4g"
python manage.py runserver
```

Then open:

```id="r9h2k3"
http://127.0.0.1:8000/
```

---

## 🎯 Use Case

* Helps users find nearby hospitals quickly
* Useful in emergencies or unfamiliar locations
* Can be extended into a full healthcare navigation system

---

## ⚠️ Future Improvements

* Add real-time ambulance tracking
* Integrate user authentication
* Add hospital ratings & reviews
* AI-based recommendation system

---

## 👩‍💻 Author

Shreya
