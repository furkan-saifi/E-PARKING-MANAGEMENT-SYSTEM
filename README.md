# E-Parking Management System

A command-line parking management project written in Python.

## Features

- Register vehicle entries
- Prevent duplicate vehicle numbers
- Remove vehicle records
- View currently registered vehicles
- Display remaining parking spaces for bicycles, bikes, and cars
- Display hourly parking rates
- Calculate parking charges and an additional 18% charge

## Parking Rates

| Vehicle type | Rate |
| --- | ---: |
| Bicycle | ₹20 per hour |
| Bike | ₹40 per hour |
| Car | ₹60 per hour |

## Requirements

- Python 3

The project uses Python's built-in features and does not require external packages.

## Run the Project

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Run:

```bash
python parking.py
```

On some systems, use `python3 parking.py` instead.

## Notes

This is a basic console-based project. Vehicle records are currently stored in in-memory lists, so they are not retained after the program exits. Review and test the billing and input-validation logic before using it beyond a learning/demo setting.
