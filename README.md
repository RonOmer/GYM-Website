# SharkGYM

A responsive, five-page gym website created as part of the **AI-Assisted Front End Development Practicum**. The project uses semantic HTML and shared CSS to present training programs, trainers, membership plans, and contact information.

## Technologies

- HTML5
- CSS3, including Flexbox and responsive media queries
- Roboto from Google Fonts, with a system sans-serif fallback

No JavaScript, build tools, or package installation is required.

## Pages

| Page | Description |
| --- | --- |
| Home | Gym introduction, benefits, motivational quote, and membership links |
| Programs | Strength, cardio, functional training, and group fitness |
| Trainers | Illustrative trainer profiles and a membership link |
| Subscriptions | Example membership plans with links to Contact |
| Contact | Placeholder contact details and a labeled demonstration form |

## Project structure

```text
GYM-website/
├── Index.HTML
├── Pages/
│   ├── Programs.HTML
│   ├── Trainers.html
│   ├── Subscriptions.HTML
│   └── Contacts.HTML
├── CSS/
│   ├── shared.css
│   ├── Index.css
│   ├── Programs.css
│   ├── Trainers.css
│   ├── Subscriptions.css
│   └── Contacts.css
├── Images/
└── README.md
```

## Run locally

Open `Index.HTML` in a browser. Alternatively, from the project root, run the following command if Python is installed:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000/Index.HTML`. Use the explicit filename because its capitalization may prevent a server from treating it as the default index page. Preserve filename capitalization when hosting on a case-sensitive server.

The navigation collapses into a menu on smaller screens. Check both desktop and mobile layouts when editing styles.

## Project scope

Trainer profiles, membership prices, and contact details are illustrative. Membership links lead to the Contact page; there is no registration or payment backend. The contact form is intentionally disabled and does not send or store messages. An internet connection is only needed to load Google Fonts.

The repository does not include the assignment document, so exact visual compliance with its reference design must be checked separately.
