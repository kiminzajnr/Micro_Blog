# Micro_Blog

This is a simple microblogging application built using HTML, CSS, Python Flask, and MongoDB. The application allows users to keep track of everything they have learnt.

## Features

- **Create Blog Entries:** 
- **View Blog Entries:** 

## Technologies Used

- **Frontend:** HTML, CSS
- **Backend:** Python Flask
- **Database:** MongoDB

## Setup Instructions

### Prerequisites

- Python 3.x
- MongoDB
- pip

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kiminzajnr/Micro_Blog.git
   cd Micro_Blog

2. Create an environment
    ```
    python3 -m venv .venv

3. Activate the environment
    ```
    . .venv/bin/activate

4. **Install the required packages:**
    ```
    pip install -r requirements.txt

5. **Set up environment variables:**
    Create a `.env` file in the root directory of the project and add your MongoDB connection string:
    ```
    MONGODB_URI=your_mongodb_uri

6. **Run the application:**
    ```
    flask run

The application will be available at http://127.0.0.1:5000/.
