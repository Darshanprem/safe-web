# CyberShield

CyberShield is a secure, end-to-end encrypted cybercrime reporting system designed to streamline the communication between citizens and law enforcement. The platform provides a transparent case management solution with specialized portals for victims, officers, and administrators to ensure efficient investigation and resolution of digital crimes.

## Features

**Three Distinct Portals:**
* **Citizen Portal:** Secure interface for victims to register, report incidents, and upload digital evidence.
* **Police Portal:** Advanced tools for law enforcement to review cases, analyze evidence, and update investigation statuses.
* **Admin Portal:** Comprehensive system oversight, including user role management and activity monitoring.
* **Authentication:** Secure role-based access control (RBAC) ensuring data privacy across all user levels.
* **Digital Evidence Vault:** Encrypted storage for images, documents, and logs related to cybercrime cases.
* **Real-time Tracking:** Live status updates and case progression tracking for citizens and investigating officers.

## Tech Stack

* **Frontend:** HTML5, CSS3 (Vanilla), and JavaScript (ES6+)
* **Backend:** Firebase (Serverless Architecture)
* **Database:** Firebase Cloud Firestore (NoSQL Real-time Database)
* **Authentication:** Firebase Authentication with Role-Based Identity Management
* **Storage:** Firebase Storage for secure digital artifact and evidence hosting

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd safe-web
   ```

2. Set up Firebase:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Authentication, Firestore, and Storage
   - Copy your Firebase config to `firebase-config.js`

3. Configure Firestore rules:
   - Deploy the rules in `firestore.rules` to your Firebase project

## Usage

1. Open `index.html` in a web browser to access the main page.
2. Navigate to the appropriate portal:
   - Citizen Portal: `victim-portal.html`
   - Police Portal: `police-portal.html`
   - Admin Portal: `admin-portal.html`

3. For local development, serve the files using a local server (e.g., using Python: `python -m http.server` or VS Code Live Server extension).

## Project Structure

- `index.html`: Main landing page
- `victim-portal.html`: Citizen reporting interface
- `police-portal.html`: Law enforcement dashboard
- `admin-portal.html`: Administrative controls
- `main.js`: Shared JavaScript utilities
- `citizen-app.js`: Citizen portal logic
- `police-app.js`: Police portal logic
- `admin-app.js`: Admin portal logic
- `firebase-config.js`: Firebase configuration
- `firestore.rules`: Database security rules
- `styles.css`: Global styles

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
