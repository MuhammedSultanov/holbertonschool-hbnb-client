# HBnB Evolution Project
![HBNB](https://th.bing.com/th/id/OIG4.T4fNkuNskDusfAO7LsJ8?w=1024&h=1024&rs=1&pid=ImgDetMain)
## Overview

In Part 3 of the HBnB Evolution project, In this phase, you’ll be focusing on the front-end development of your application using HTML5, CSS3, and JavaScript ES6. Your task is to design and implement an interactive user interface that connects with the back-end services you have developed in previous parts of the project.

## Project Structure

The project is divided into three main layers:

1. **Services Layer**: Handles API requests and responses.
2. **Business Logic Layer**: Processes and makes decisions based on the application's logic.
3. **Persistence Layer**: Manages data storage (currently file-based, moving to a database in the future).

### Key Entities

- **Places**: Representing rental locations with various attributes like name, description, address, etc.
- **Users**: Owners (hosts) or reviewers with attributes like email, password, first name, and last name.
- **Reviews**: User feedback and ratings for places.
- **Amenities**: Features of places such as Wi-Fi, pools, etc.
- **Country and City**: Each place is tied to a city, and each city belongs to a country.

### Business Logic Rules

- Unique Users: Each user is identified by a unique email.
- One Host per Place: Every place must have exactly one host.
- Flexible Hosting: A user can host multiple places or none.
- Open Reviewing: Users can write reviews for places they don’t own.
- Amenity Options: Places can have multiple amenities from a catalog, and users can add new ones.
- City-Country Structure: A place belongs to a city, and each city belongs to a country.

## Setup and Installation

### Prerequisites

- Python 3.x installed on your system.
- `pip` package manager.

### Installation Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/MuhammedSultanov/holbertonschool-hbnb-client
    cd holbertonschool-hbnb-client
    ```

2. **Create a virtual environment**:
    ```bash
    python3 -m venv venv
    ```

3. **Activate the virtual environment**:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```

4. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Contributing

Contributions are welcome! Please create a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License.

## Authors

- Kamran Qureyshi
- Muhammed Sultanov
