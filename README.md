# AIS-ITS-CII-SEEMP

**AIS-ITS-CII-SEEMP** is a project designed to calculate the **CII (Carbon Intensity Indicator)** based on ship movement data and provide **SEEMP (Ship Energy Efficiency Management Plan)** recommendations to improve energy efficiency and reduce carbon emissions. This project is part of **Vibra Dananjaya's thesis**.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **AIS-ITS-CII-SEEMP** project aims to help optimize ship energy efficiency by calculating the **CII** and generating recommendations based on **SEEMP**. This application helps vessel operators monitor their environmental impact and take action to improve fuel consumption and overall sustainability.

The project consists of both **Frontend (FE)** and **Backend (BE)** components, with the **BE** handling data calculations and API services, and the **FE** presenting the data in a user-friendly interface.

## Features

- **CII Calculation**: Calculates the Carbon Intensity Indicator based on ship's movement data.
- **SEEMP Recommendations**: Provides actionable suggestions for improving ship energy efficiency.
- **Interactive Dashboard**: Displays CII data and recommendations through a responsive UI.
- **Real-time Data**: Updates the data and recommendations in real-time based on ship operations.

## Tech Stack

- **Backend (BE)**:
  - **Express.js** (Web framework)
  - **TypeScript** (Language)
  - **MongoDB** (Database with Mongoose)
- **Frontend (FE)**:
  - **Vite** (Build tool)
  - **HTML/CSS/JavaScript** (Frontend technologies)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/ais-its-cii-seemp.git
   ```

2. Navigate to the backend folder and install dependencies:

   ```bash
   cd ais-its-cii-seemp/ais-its-cii-seemp-be
   ppm install
   ```

3. Navigate to the frontend folder and install dependencies:

   ```bash
   cd ../ais-its-cii-seemp-fe
   pnpm install
   ```

4. Set up environment variables for both frontend and backend (see `.env.example` for reference).

## Usage

### Backend

1. Start the backend server:

   ```bash
   cd ais-its-cii-seemp/ais-its-cii-seemp-be
   pnpm run dev
   ```

   Ensure that the backend is connected to a MongoDB instance (local or remote) as specified in your `.env` file.

   ```

   The backend will run on `http://localhost:5001` (or as configured in `.env`).
   ```

### Frontend

1. Start the frontend development server:

   ```bash
   cd ais-its-cii-seemp/ais-its-cii-seemp-be
   pnpm run dev
   ```

   The frontend will be available at `http://localhost:5173` (or as configured in `.env`).

## Contributing

We welcome contributions! If you'd like to help improve the **AIS-ITS-CII-SEEMP** project, please fork the repository and submit a pull request with your changes.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Open a pull request.

## License

This project is licensed under a **Private License** - use and modification are restricted to authorized users only.
