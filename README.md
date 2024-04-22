# Medical Appointment Application -Hello!

Welcome to the Medical Appointment Application! This API streamlines the process of booking appointments between patients and doctors. It enables patients to create, cancel, and mark appointments as completed, while also allowing doctors to manage their availability status. This `README.md` file offers an introduction to the application, as well as instructions for setting it up and utilizing its features.

## Table of Contents

1. [Features](#features)
2. [Setup](#setup)
3. [Endpoints](#endpoints)
    - [Patient Endpoints](#patient-endpoints)
    - [Doctor Endpoints](#doctor-endpoints)
    - [Appointment Endpoints](#appointment-endpoints)

## Features

- **CRUD for Patients**: Add, update, delete, and retrieve patient information.
- **CRUD for Doctors**: Add, update, delete, and retrieve doctor information.
- **Create Appointments**: Patients can schedule appointments with doctors.
- **Cancel Appointments**: Patients can cancel scheduled appointments.
- **Complete Appointments**: Completing an appointment marks it as finished and makes the doctor available for new appointments.
- **Set Doctor Availability**: Doctors can set their availability status to manage appointment bookings.

## Setup

To set up the Medical Appointment Application, follow these steps:

1. Clone the repository to your local machine:

    ```shell
    git clone https://github.com/ESOCODES/MED_APP_API.git
    ```

2. Navigate to the project directory:

    ```shell
    cd Altschool_Med_App
    ```

3. Create a virtual environment:

    ```shell
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On macOS/Linux:

        ```shell
        source venv/bin/activate
        ```

    - On Windows:

        ```shell
        venv\Scripts\activate
        ```

5. Install the required dependencies:

    ```shell
    pip install -r requirements.txt
    ```

6. Start the FastAPI server:

    ```shell
    uvicorn app:app --reload
    ```


