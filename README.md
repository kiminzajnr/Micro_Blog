# Micro_Blog

This is a simple microblogging application built using HTML, CSS, Python Flask, and MongoDB. The application allows users to create and view blog entries.

## Features

- **Create Blog Entries:** Users can create new blog entries by submitting content through the web interface.
- **View Blog Entries:** All blog entries are displayed on the homepage, along with the date they were posted.

## Technologies Used

- **Frontend:** HTML, CSS
- **Backend:** Python Flask
- **Database:** MongoDB

## Setup Instructions

### Prerequisites

- Python 3.x
- MongoDB
- pip (Python package installer)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/simple-microblog.git
   cd simple-microblog

2. **Install the required Python packages:**
    ```pip install -r requirements.txt

3. **Set up environment variables:**
    Create a `.env` file in the root directory of the project and add your MongoDB connection string:
    ```MONGODB_URI=your_mongodb_uri

4. **Run the application:**
    ```flask run

The application will be available at http://127.0.0.1:5000/.
