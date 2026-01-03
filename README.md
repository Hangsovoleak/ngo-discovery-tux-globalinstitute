# NGO Discovery Playform

This is a desktop-first MVP for a Donation & NGO Discovery Plarform.
It includes public and admin screens, interactive maps, and mock data for demonstration.

## Project Structure

```
ngo-discovery/
├── assets/
│ ├── images/
│ │ ├── ngos/ # NGO logos & profile images
│ │ ├── qr/ # QR codes for donations
│ │ └── placeholders/ # Default images
│ │
│ └── icons/
│ ├── map-pin.svg
│ ├── verified.svg
│ ├── edit.svg
│ └── delete.svg
│
├── css/
│ └── style.css # Global styles, layout, colors, typography
│
├── js/
│ ├── auth.js # Admin login, logout, session handling
│ ├── data.js # Mock NGO, category, beneficiary, location data
│ ├── main.js # Page switching, rendering UI, routing logic
│ └── map.js # Map rendering, distance calculation
│
├── index.html # Main HTML shell (all screens rendered here)
└── README.md # Project overview & instructions
```

## Features

- Browse and filter NGOs by category, city, or beneficiaries
- View detailed NGO profiles with maps and contact info
- Interactive map showing donation locations
- Admin panel to manage NGOs and locations
- Modular frontend structure with HTML, CSS and JS