# Hotel Website
![Alt text](/img/image.jpg "Optional title")
## Team members
- Huynh Anh Tien
- Dang Huu Hoc
- Do Huu Nguyen
- Hoang Dang Hai

## Table of Contents
- [Overview](#overview)
- [Endpoints](#endpoints)
  - [Rooms](#rooms)
  - [Bookings](#bookings)
  - [Guests](#guests)
  - [Billing](#billing)

---

## Overview

The API uses various endpoints to manage room, booking, guest, and billing data. Each endpoint provides basic CRUD (Create, Read, Update, Delete) operations to support functionalities for a hotel management system. The following sections describe each endpoint's functionality.

## Endpoints

### 1. Rooms

- **Base URL:** `https://672209072108960b9cc29c4a.mockapi.io/api/v1/T_room`
- **Description:** Manage room data, including room details and types.

#### Endpoints

| Method | Endpoint                       | Description                   |
|--------|--------------------------------|-------------------------------|
| GET    | `/T_room`                      | Retrieve all rooms            |
| GET    | `/T_room/{id}`                 | Retrieve a specific room      |
| POST   | `/T_room`                      | Create a new room             |
| PUT    | `/T_room/{id}`                 | Update an existing room       |
| DELETE | `/T_room/{id}`                 | Delete a room                 |

### 2. Bookings

- **Base URL:** `https://672209072108960b9cc29c4a.mockapi.io/api/v1/T_booking`
- **Description:** Manage booking records, including booking details, statuses, and guests assigned.

#### Endpoints

| Method | Endpoint                       | Description                   |
|--------|--------------------------------|-------------------------------|
| GET    | `/T_booking`                   | Retrieve all bookings         |
| GET    | `/T_booking/{id}`              | Retrieve a specific booking   |
| POST   | `/T_booking`                   | Create a new booking          |
| PUT    | `/T_booking/{id}`              | Update an existing booking    |
| DELETE | `/T_booking/{id}`              | Delete a booking              |

### 3. Guests

- **Base URL:** `https://6717a745b910c6a6e0294dfb.mockapi.io/api/v1/T_guest`
- **Description:** Manage guest information, including names, contact details, and stay information.

#### Endpoints

| Method | Endpoint                       | Description                   |
|--------|--------------------------------|-------------------------------|
| GET    | `/T_guest`                     | Retrieve all guests           |
| GET    | `/T_guest/{id}`                | Retrieve a specific guest     |
| POST   | `/T_guest`                     | Add a new guest               |
| PUT    | `/T_guest/{id}`                | Update guest information      |
| DELETE | `/T_guest/{id}`                | Delete a guest                |

### 4. Billing

- **Base URL:** `https://6717a745b910c6a6e0294dfb.mockapi.io/api/v1/T_billing`
- **Description:** Manage billing information, including invoices, payment details, and associated bookings.

#### Endpoints

| Method | Endpoint                       | Description                   |
|--------|--------------------------------|-------------------------------|
| GET    | `/T_billing`                   | Retrieve all billing records  |
| GET    | `/T_billing/{id}`              | Retrieve a specific billing record |
| POST   | `/T_billing`                   | Create a new billing record   |
| PUT    | `/T_billing/{id}`              | Update billing information    |
| DELETE | `/T_billing/{id}`              | Delete a billing record       |

---

## Usage

Each endpoint can be accessed through standard HTTP methods (GET, POST, PUT, DELETE) to manage the respective resource. Ensure appropriate data formatting in request bodies and check responses for status codes to handle errors.

**Note:** MockAPI URLs are for testing purposes and may have limited data persistence.

## License

This project is provided under an open-source license. See the LICENSE file for more details.
