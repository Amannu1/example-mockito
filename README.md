# Example Mockito

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

This project is an API built using **Java, Spring Boot, H2 Console, and Mockito**, designed to simulate a **Mockito-based test implementation**.

The architecture is intentionally minimal, containing only one entity called **Product**, to make it easier to learn and practice mocks in service scenarios.

## Table of Contents

- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Tests](#test)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Amannu1/example-mockito
```

2. Install dependencies with Maven

## Usage

1. Start the application with Maven
2. Right click test > java
3. Click Run 'All Tests'

## Tests

### Product
- Insert should return productDTO when valid data
- Insert should return InvalidDataException when product name is blank
- Insert should return InvalidDataException when product price is negative or zero
- Update should return productDTO when id exist and valid data
- Update should return InvalidDataException when id exists and product name is blank
- Update should return InvalidDataException when id exists and product price is negative or zero
- Update should return resourceNotFoundException when id does not exist and valid data
- Update should return InvalidDataException when id does not exist and product name is blank
- Update should return InvalidDataException when id does not exist and product price is negative or zero
