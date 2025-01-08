# Winter Clothing Donation Website ❄️

A web application designed to connect donors with volunteers to provide warm clothing to those in need during winter in Bangladesh.

## 🌟 Live URL

[Winter_Clothing_Donation](https://winter-clothing-donation-a09d4.web.app/)

---

## 📖 Project Purpose

During the cold winter months, vulnerable people in rural and low-income areas struggle to stay warm due to the lack of adequate clothing. This platform helps donors contribute winter clothing and provides an easy way for volunteers to organize donations effectively.

---

## 🔑 Key Features

### 🌐 Public Features

- **Home Page**:

  - Winter-themed slider showcasing donation campaigns.
  - About section detailing the mission and vision of the project.
  - "How It Works" section with clear instructions for donors.
  - Two additional sections to engage users.

- **Donation Campaigns Page**:
  - Displays a list of ongoing donation campaigns.
  - Includes an image, title, description, division, and a "Donate Now" button.

### 🔒 Private Features (Requires Login)

- **Donation Details Page**:

  - Displays detailed information about the campaign.
  - Donation form to submit item details (e.g., quantity, item type, pickup location).
  - Toast message upon successful submission.

- **Dashboard**:
  - Displays user profile information.
  - Update profile option for users to edit their name and profile picture.

### 🔐 Authentication

- User Login:

  - Email/password login and Google social login.
  - "Forgot Password" functionality redirects users to reset their passwords via email.

- User Registration:
  - Name, email, photo URL, and password registration form with validation.

### 🎨 Unique Design

- Winter-themed layout.
- Fully responsive for mobile, tablet, and desktop.

### 🔧 Additional Features

- Environment variable-secured Firebase configuration.
- Custom 404 page with a button to redirect users to the home page.
- Animation on the home page using AOS (Animate On Scroll).

---

## 🛠️ Tools & Technologies

- **Frontend**: React, React Router, Tailwind CSS, DaisyUI
- **Icons**: React Icons
- **Authentication**: Firebase Authentication
- **Hosting**: Netlify / Firebase Hosting
- **Animation**: AOS (Animate On Scroll)
- **Toast Notifications**: React Hot Toast

---

🧑‍💻 Challenges Overcome
Responsiveness: Ensured a seamless experience across all devices.
Authentication Persistence: Maintained user session across page reloads on private routes.
Password Validation: Enforced strong passwords with uppercase, lowercase, and minimum length criteria.
Environment Variables: Secured sensitive Firebase keys.
👨‍👩‍👧‍👦 Contributors
ASM Shad
