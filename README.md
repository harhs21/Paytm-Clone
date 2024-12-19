# Paytm Clone

A clone of the popular Paytm application built using Next.js for the frontend and PostgreSQL as the database. This project demonstrates the core functionalities of a payment platform with a modern tech stack.

## Features

- **User Authentication:** Secure user login and registration.
- **Payment Gateway:** Simulated payment functionality.
- **Wallet System:** Users can manage their wallets, view balance, and transaction history.
- **Transaction Management:** Track and record user transactions.
- **Responsive Design:** Fully optimized for both desktop and mobile.

## Tech Stack

- **Frontend:** Next.js
- **Backend:** API routes in Next.js
- **Database:** PostgreSQL
- **Styling:** Tailwind CSS

## Installation

Follow these steps to set up the project locally:

### Prerequisites

- Node.js (v16 or higher)
- PostgreSQL (v13 or higher)
- Git

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/harhs21/Paytm-Clone.git
   cd paytm-clone
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add the following:

4. **Initialize Database**
   Create the database and run migrations:
   ```bash
   npx prisma migrate dev --name init
   ```

5. **Run the Development Server**
   ```bash
   npm run dev
   ```
   Access the app at `http://localhost:3000`.

## Project Structure

```
|-- pages
|   |-- api
|   |   |-- auth.js       # Authentication APIs
|   |   |-- transactions.js  # Transaction APIs
|-- components
|   |-- Header.js        # Navbar and header
|   |-- Wallet.js        # Wallet-related components
|-- styles
|   |-- globals.css      # Global CSS
|-- prisma
|   |-- schema.prisma    # Database schema
```

## Screenshots

Add screenshots of the application here to showcase its features.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.



## Acknowledgments

- Paytm for the inspiration.
- Open Source Libraries and Tools used in this project.
