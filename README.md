# Pat's Personal Training Website

## Description
A professional website for a personal trainer that helps showcase services, client testimonials, and booking options. The site aims to make it easy for clients to get to know the trainer, view training videos, and book sessions directly online.

## Features
- Eye-catching landing page with visuals and video highlights.
- Testimonials section for client reviews and success stories.
- About the trainer page with bio and credentials.
- Booking calendar integrated with Google Calendar (future update to Alignify module).
- Video gallery of workout routines and fitness tips.
- Contact form for inquiries and discovery calls.

## Tech Stack
- **Frontend**: React JS, Tailwind CSS, Next.js
- **Backend**: Node.js, Express, MongoDB, Firebase (optional)
- **Deployment**: Vercel for frontend, DigitalOcean/AWS for backend
- **Authentication**: Auth0 or Firebase Authentication
- **Additional Tools**: Google Calendar API, Stripe for payments, Contentful or Sanity for content management

## Directory Structure
```
Pat_Personal_Training/
├── public/                      # Public assets (images, favicons, etc.)
├── src/                         # Source files for the project
│   ├── assets/                  # Images, videos, and other media assets
│   ├── components/              # Reusable components (e.g., Navbar, Footer, LandingPage)
│   ├── pages/                   # Page components (e.g., Home, About, Testimonials, Booking)
│   ├── services/                # API service calls (e.g., Google Calendar, Stripe)
│   ├── styles/                  # Global and component-specific stylesheets
│   ├── utils/                   # Utility functions (e.g., formatters, helper functions)
│   ├── App.js                   # Main app component
│   └── index.js                 # Entry point for React application
├── backend/                     # Backend files
│   ├── controllers/             # Request handlers for different routes
│   ├── models/                  # Database models (e.g., User, Booking, Testimonial)
│   ├── routes/                  # Route definitions (e.g., booking, testimonials)
│   ├── config/                  # Configuration files (e.g., database, authentication)
│   ├── server.js                # Entry point for the Node.js server
│   └── utils/                   # Utility functions for backend (e.g., validation, middleware)
├── .env                         # Environment variables
├── .gitignore                   # Git ignore file
├── package.json                 # Project metadata and dependencies
├── README.md                    # Project documentation
└── LICENSE                      # License information
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Pat_Personal_Training.git
   ```
2. Navigate into the project directory:
   ```bash
   cd Pat_Personal_Training
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Usage
- Access the website locally via `http://localhost:3000`.
- View the landing page, about section, testimonials, and booking options.

## Roadmap
- **Phase 1**: Set up landing page, about section, and testimonials.
- **Phase 2**: Integrate booking calendar with Google Calendar API.
- **Phase 3**: Implement backend APIs for managing client data and bookings.
- **Phase 4**: Upgrade booking to Alignify time module.

## Contributing
Feel free to fork this repository and create pull requests for any enhancements or bug fixes.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact
For questions or support, reach out to [trainer@example.com](mailto:trainer@example.com).