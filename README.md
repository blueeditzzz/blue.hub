# BLUE HUB

A service directory where people can list what they offer and find services from others.

**Live Website:** https://blueeditzzz.github.io/blue.hub/  
**Repository:** https://github.com/blueeditzzz/blue.hub

## About

BLUE HUB is a service discovery platform built as part of my web development project.

Users can browse service listings, search for specific services, and publish their own listings after signing in. Each listing includes information such as its description, category, starting price and contact details.

The goal is to make it easier for service providers and potential clients to find each other.

## Features

### Service Listings
- Browse published services.
- Search by service name, description or category.
- Filter by category and currency.
- Filter by availability and price range.
- Sort listings by newest or price.
- View individual service providers and their listings.

### User Accounts
- Sign up and sign in.
- Shared authentication between the main website and BLUE HUB.
- Password recovery.
- Persistent login sessions.
- Profile management.

### Dashboard
- View your published listings.
- See listing statistics.
- Create new service listings.
- Edit existing listings.
- Delete your listings.

### Publishing Services
Users can add:
- Service title and description.
- Category and skills.
- Starting price in INR or USD.
- Availability status.
- Contact information.
- Optional service images.

### Design
- Responsive layout for desktop and mobile.
- Category-based browsing.
- Search and filtering interface.
- Simple navigation and interactive elements.

## Integrations

| Service | Purpose |
|---|---|
| Supabase Auth | User registration, login and sessions |
| Supabase Database | Stores user profiles and service listings |
| Supabase Storage | Stores uploaded images |
| GitHub Pages | Hosts the website |
| GitHub | Source code and version control |

## Technologies

- **HTML5** – Page structure.
- **CSS3** – Styling, layouts and responsive design.
- **JavaScript** – Application logic and interactive features.
- **Supabase JavaScript SDK** – Communication with Supabase services.
- **Git & GitHub** – Version control and project hosting.

## Project Structure

```text
blue.hub/
│
├── index.html       # Main website
├── hub.html         # BLUE HUB service directory
├── messages.html    # Messages page
└── README.md        # Project documentation
```

## Run Locally

You can run the project locally without installing a build system.

1. Clone the repository:

```bash
git clone https://github.com/blueeditzzz/blue.hub.git
```

2. Open the project folder:

```bash
cd blue.hub
```

3. Open `index.html` in your browser.

You can also use the Live Server extension in VS Code.

**Note:** Features that use Supabase require an internet connection and the configured Supabase project.

## Developer

**BLUE**

GitHub: https://github.com/blueeditzzz
