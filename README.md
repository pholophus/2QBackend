# Project Name

TwoQCompany-FullStackApp

## Table of Contents

- [Project Overview](#project-overview)
- [Architecture](#architecture)
- [Database](#database)
- [Libraries and Dependencies](#libraries-and-dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

CRUD Company API using Laravel 

## Architecture
```plaintext
|-- app
|   |-- Console
|   |-- Exceptions
|   |-- Http
|   |   |-- Controllers
|   |   |-- Middleware
|   |   |-- ...
|   |-- Models
|   |-- Providers
|-- config
|-- database
|-- public
|-- resources
|-- routes
|-- ...
```

## Database

### Database Schema

```plaintext

company
  - id
  - name
  - email
  - logo
  - website
```

## Libraries and Dependencies

- **Laravel Version**: 8.x
- **Database**: MySQL.
- **ORM**: Eloquent

## Installation

```bash
# Clone the repository
git clone https://github.com/your-username/your-project.git

# Install dependencies
composer install

# Set up the database
php artisan migrate

# Start the development server
php artisan serve
```

## Missing/ Not Yet Implemented Features
```plaintext
- authentication
- user
- repositories folder 
```
