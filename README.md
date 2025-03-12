# Fitness Gym Web Application

![Home Page](./screenshots/home-page.png)

## Overview

Welcome to the Fitness Gym Web Application! This project serves as a comprehensive platform for fitness enthusiasts to explore available gym classes, learn about membership plans, and connect with the gym staff. Designed with a user-first approach, the application provides an engaging and intuitive experience for visitors to stay informed and take the first steps towards a healthier lifestyle.

## Purpose

The primary objective of this project is to:

- Simplify the process of discovering fitness classes and their schedules.
- Offer clear membership plans to cater to different fitness goals.
- Provide users with an easy way to contact the gym and get their questions answered.

By addressing these needs, the web application ensures that users can efficiently interact with the gym, discover classes, and make informed decisions about their fitness journey.

## Key Features

### 1. Home Page:

- Highlights the gym's vision and facilities.
- Features a dynamic banner showcasing key offerings.

### 2. Classes Page:

- Displays a detailed table of available fitness classes, including their description, schedule, duration, and instructors.

### 3. Contact Page:

- Allows users to send inquiries through a form.
- Provides essential contact details and a Google Maps integration for location.

### 4. Responsive Design:

- Fully optimized for various devices including desktops, tablets, and mobile phones.

## Deployment Procedure

To deploy this web application, follow these steps:

### 1. Clone the Repository:

```bash
git clone <repository-url>
```

### 2. Navigate to the Project Directory:

```bash
cd fitness-gym-web-app
```

### 3. Open the Project Locally:

- Use a local server (e.g., VS Code Live Server, XAMPP) to serve the HTML files.

### 4. Deploy on a Hosting Platform:

- **GitHub Pages:**
  1.  Push your project to a GitHub repository.
  2.  Go to **Settings > Pages**.
  3.  Select the branch where the project is stored.
  4.  Click "Save" and the site will be live.
- **Netlify:**
  1.  Sign in to Netlify.
  2.  Drag and drop the project folder or connect it to a Git repository.
  3.  Click **Deploy Site**.
- **Vercel:**
  1.  Install Vercel CLI (`npm install -g vercel`).
  2.  Run `vercel` in the project folder and follow the instructions.

## Validation Testing

### 1. Manual Testing:

- Verified responsiveness on various screen sizes (mobile, tablet, desktop).
- Checked all navigation links for proper redirection.
- Ensured form validation works as expected.

### 2. Browser Compatibility:

- Tested on **Google Chrome, Mozilla Firefox, Microsoft Edge, and Safari**.
- Ensured styles and functionality remain consistent across browsers.

### 3. Performance Testing:

- Page load speed tested using Google Lighthouse.
- Optimized images for faster loading.

### 4. Accessibility Testing:

- Checked contrast ratios for readability.
- Used screen readers to ensure accessibility compliance.

### 5. Known Issues:

- **Google Maps iframe may not load on some networks due to restrictions.**
- **Mobile menu may require a fix to close after selection on certain screen sizes.**

## Screenshots

### Home Page

![Home Page](./screenshots/home-page.png)

### Classes Page

![Classes Page](./screenshots/classes-page.png)

### Contact Page

![Contact Page](./screenshots/contact-page.png)

## Code Attribution

### 1. External libraries and tools:

- Font Awesome: Used for social media icons. [Font Awesome](https://fontawesome.com/)

### 2. Code comments in relevant sections:

```html
<!-- Font Awesome CDN for social icons -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.1/css/all.min.css"
  integrity="sha512-5Hs3dF2AEPkpNAR7UiOHba+lRSJNeM2ECkwxUIxC1Q/FLycGTbNapWXB4tP889k5T5Ju8fs4b1P5z/iB4nMfSQ=="
  crossorigin="anonymous"
  referrerpolicy="no-referrer"
/>
```

## Target Audience

This web application is targeted at:

- Individuals seeking structured fitness programs.
- Current gym members looking to explore additional classes.
- Prospective members interested in membership options.

## User Stories

1. "As a user, I want to view available classes so I can decide which ones fit my schedule."
2. "As a prospective member, I want to view membership plans so I can choose one that meets my fitness goals."
3. "As a visitor, I want to contact the gym easily to resolve my inquiries."

## Development Rationale

This project was developed to create an easy-to-navigate, visually appealing platform that bridges the gap between fitness service providers and their clients. By integrating modern web design principles, the application ensures seamless navigation, intuitive UI, and responsive layouts.

## Credits

- Developer: Lloyd
- Icons: [FontAwesome](https://fontawesome.com/)
- Map Integration: [Google Maps Embed API](https://developers.google.com/maps/documentation/embed/get-started)

## License

This project is open-source and available under the [MIT License.](https://choosealicense.com/licenses/mit/)
