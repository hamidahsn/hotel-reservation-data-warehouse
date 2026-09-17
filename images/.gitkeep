# Hotel Reservation Data Warehouse

## Project Overview

This project develops a **Data Warehouse for hotel reservation management** using a dimensional data modeling approach.

The project transforms hotel reservation data into a structured analytical database consisting of a central **fact table** and multiple **dimension tables**. An Entity Relationship Diagram (ERD) was also developed to illustrate the relationships between entities and the overall database structure.

The project is designed to support analysis of hotel reservations, guests, rooms, payments, reservation status, hotel locations, and booking dates.

---

## Project Objectives

The main objectives of this project are:

1. Design a structured database for hotel reservation data.
2. Apply dimensional modeling concepts using a fact table and dimension tables.
3. Organize reservation data into an analytical data warehouse structure.
4. Establish relationships between fact and dimension tables.
5. Develop an ERD to represent the database structure.
6. Prepare SQL scripts and structured datasets for database implementation.

---

## Data Warehouse Design

The data warehouse uses a **Star Schema** approach, with the hotel reservation fact table as the center of the model.

### Fact Table

**Tabel Fakta Reservasi Hotel**

The fact table contains reservation-level information, including:

- Reservation ID
- Reservation timestamp
- Number of nights
- Price per night
- Total cost
- Guest ID
- Room ID
- Payment ID
- Reservation Status ID
- Hotel City ID
- Check-in ID
- Check-out ID

### Dimension Tables

The fact table is connected to several dimension tables:

| Dimension | Description |
|---|---|
| Dim Tamu | Guest information |
| Dim Tipe Kamar | Room type information |
| Dim Metode Pembayaran | Payment method information |
| Dim Status Reservasi | Reservation status information |
| Dim Kota Hotel | Hotel location information |
| Dim Tanggal Check In | Check-in date information |
| Dim Tanggal Check Out | Check-out date information |

---

## ERD

The Entity Relationship Diagram illustrates the structure of the hotel reservation database and the relationships between the fact table and its related dimensions.

![Hotel Reservation ERD](erd/ERD_Reservasi_Hotel.png)

The model places **Tabel Fakta Reservasi Hotel** at the center and connects it to the relevant dimensions through their corresponding identifiers.

---

## Data Modeling

The project applies dimensional modeling principles by separating:

- **Measures and transactional information** into the fact table.
- **Descriptive attributes** into dimension tables.

This structure allows reservation transactions to be analyzed from different perspectives, such as:

- Guest
- Room type
- Hotel city
- Reservation status
- Payment method
- Check-in date
- Check-out date

---

## SQL Implementation

The SQL script contains the database implementation for the hotel reservation data warehouse.

The SQL workflow includes the creation and population of tables required for the reservation database.

The main SQL file is:

```text
sql/
└── reservasi_hotel.sql

---

## Data Structure
data/
├── tabel_fakta.csv
├── dim_kota_hotel.csv
├── dim_metode_pembayaran.csv
├── dim_status_reservasi.csv
├── dim_tamu.csv
├── dim_tanggal_checkin.csv
├── dim_tanggal_checkout.csv
└── dim_tipe_kamar.csv

---

## Repository Structure
hotel-reservation-data-warehouse/
│
├── README.md
│
├── sql/
│   └── reservasi_hotel.sql
│
├── data/
│   ├── tabel_fakta.csv
│   ├── dim_kota_hotel.csv
│   ├── dim_metode_pembayaran.csv
│   ├── dim_status_reservasi.csv
│   ├── dim_tamu.csv
│   ├── dim_tanggal_checkin.csv
│   ├── dim_tanggal_checkout.csv
│   └── dim_tipe_kamar.csv
│
└── erd/
    └── ERD_Reservasi_Hotel.png

---

## Tools & Technologies
SQL
Relational Database
Data Warehouse
Dimensional Modeling
Star Schema
Entity Relationship Diagram (ERD)
CSV

---

## Project Deliverables

The main deliverables of this project are:

Hotel reservation data warehouse structure
Fact and dimension tables
SQL database implementation
Master data in CSV format
Entity Relationship Diagram (ERD)

---

## Limitations

This project focuses on the design and implementation of the hotel reservation data warehouse.

The repository does not represent a production hotel reservation system. The data warehouse is intended primarily for learning, data modeling, database implementation, and analytical purposes.
