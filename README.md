# Java University Room Booking System — Swing, MVC & JUnit 5

[![Java](https://img.shields.io/badge/Java-17-ED8B00?logo=openjdk&logoColor=white)](https://openjdk.org/)
[![JUnit](https://img.shields.io/badge/JUnit-5-25A162?logo=junit5&logoColor=white)](https://junit.org/junit5/)
[![License](https://img.shields.io/github/license/AlakhiarovSalekh/University-Room-Booking-Application)](LICENSE)
[![Stars](https://img.shields.io/github/stars/AlakhiarovSalekh/University-Room-Booking-Application?style=social)](https://github.com/AlakhiarovSalekh/University-Room-Booking-Application/stargazers)

A Java room-booking system with both command-line and Swing interfaces. The project uses an MVC-style structure and includes JUnit 5 tests for the model and booking behavior.

## Features

- Add, remove, and view users
- Add, remove, and view buildings
- Add, remove, and view rooms
- Create and delete room reservations
- Find reservations by booking ID or email
- View booked rooms
- Query room availability by time or time range
- View a room schedule
- Save application data to a file
- Load application data from a file
- CLI and Java Swing interfaces

## Architecture

The application separates models, services, controllers, and views. Core areas include:

- User model/service
- Building model/service
- Room model/service
- Reservation model/service
- Booking controller
- CLI view
- Swing GUI view

## Tech Stack

- Java 17
- Java Swing
- JUnit 5
- MVC-style application design
- File-based persistence

## Running the Project

Clone the repository and inspect the `src` directory:

```bash
git clone https://github.com/AlakhiarovSalekh/University-Room-Booking-Application.git
cd University-Room-Booking-Application/src
```

Compile the Java sources and run `RBSystem` using JDK 17. The project contains both command-line and graphical interfaces.

## Testing

The repository includes JUnit 5 tests for the booking system model and related behavior.

## Background

This project was developed as coursework for CS5001 Object-Oriented Modelling, Design and Programming and is useful as a compact example of Java OOP, MVC separation, Swing UI development, and test-driven development practices.

## Contributing

Issues and focused pull requests are welcome, particularly for test coverage, documentation, validation, and UI improvements.

> If this project is useful to you, consider starring the repository. It helps you find it again and helps other developers discover the project.

## More Projects by Salekh

- [Marks Manager](https://github.com/AlakhiarovSalekh/Marks-Manager) — Java console/Swing student marks management.
- [Parking Lot System](https://github.com/AlakhiarovSalekh/Parking-Lot-System) — Java OOP system-design project.
- [Food Ordering App](https://github.com/AlakhiarovSalekh/Food-Ordering-App) — Java Swing client-server ordering system.

## Author

**Salekh Alakhiarov** · [GitHub](https://github.com/AlakhiarovSalekh)

## License

MIT — see [LICENSE](LICENSE).
