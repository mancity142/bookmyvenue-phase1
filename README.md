About the project the applications it covers 

<img width="992" height="555" alt="image" src="https://github.com/user-attachments/assets/d95efdbb-4ef0-41d7-8c6b-c51e77db0043" />

Problems faced: no central platform, no digital place for events to be booked

Our solution: <img width="998" height="553" alt="image" src="https://github.com/user-attachments/assets/6618d3b4-8a0a-4b41-b8ab-7c42ea66955a" />

For : Families, community groups,professionals,event organizers,venue owners

WORKING OF THE PLATFORM

<img width="1000" height="562" alt="image" src="https://github.com/user-attachments/assets/7d4199c0-52a3-4e5a-a098-3f76dd4da33a" />

ROLES AND ACTOR INVOLVEMENTS:

<img width="1000" height="555" alt="image" src="https://github.com/user-attachments/assets/2f606c47-c58d-4d81-94b8-8271ed8ee8ff" />

PROJECT STRUCTURE


bookmyvenue/                # Root directory
├── manage.py               # Django entry point
├── requirements.txt        # Dependencies (Django, DRF, Celery, etc.)
├── .env                    # Environment variables (Sensitive keys)
├── Dockerfile              # Containerization for easy community setup
├── docker-compose.yml      # Service orchestration
├── docs/                   # Documentation for contributors
│
├── core/                   # Project configuration
│   ├── settings.py
│   ├── urls.py             # Main router
│   └── wsgi.py
│
├── apps/                   # Everything is neatly organized here
│   ├── accounts/           # User/Role management
│   ├── venues/             # Venue, Amenities, Geo-location
│   ├── bookings/           # Availability, State Machine, Prices
│   ├── notifications/      # Celery tasks, Email templates
│   └── reviews/            # Peer-review system
│
└── media/                  # User uploads (Photos of venues)





