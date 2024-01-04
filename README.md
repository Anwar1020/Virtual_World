# Virtual_World


Virtual World is a social media platform that facilitates user interactions within a virtual space. It allows users to sign up, log in, create profiles, upload images, connect with others, like posts, and explore a feed of user-generated content(image,caption).

## Features

- **User Authentication**: Users can sign up, log in, and manage their profiles securely.
- **Profile Creation**: Users can create and customize their profiles with personal information and images.
- **Image Upload**: Ability for users to upload images to their profiles or posts.
- **Connections**: Users can follow or connect with others to see their posts in their feed.
- **Engagement**: Users can like posts to show appreciation or interest.
- **Explore Feed**: A feed displaying user-generated content for users to explore and interact with.

## Technologies Used

- **Django**: Python-based web framework used for backend development.
- **SQLite**: Database management system for storing user data.
- **HTML/CSS**: Frontend development for creating user interfaces and styles.
- **JavaScript**: Used for interactive elements and enhancing user experience.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Anwar1020/Virtual_World.git
    ```

2. Install dependencies:

    ```bash
    cd virtual-world
    ```

3. Run migrations:

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

4. Start the development server:

    ```bash
    python manage.py runserver
    ```

5. Access the application in your web browser at `http://localhost:8000`.


## Creating a Superuser

To access the Django admin panel and manage the application's data, you can create a superuser account using the following steps:

1. Ensure your Django project is running. If not, start the development server:

    ```bash
    python manage.py runserver
    ```

2. Open a terminal or command prompt and navigate to your project directory.

3. Run the following command:

    ```bash
    python manage.py createsuperuser
    ```

4. You will be prompted to enter a username, email address, and password for the superuser account.

5. Once the superuser account is created successfully, you can access the Django admin panel by going to `http://localhost:8000/admin/` in your web browser.

6. Log in with the superuser credentials to access the admin panel and manage users, content, and other site functionalities.



## Usage

1. Register a new account or log in with existing credentials.
2. Set up your profile with information and an avatar.
3. Explore the platform, follow other users, upload images, and engage with posts.




## Acknowledgments
- This is mainly for lerning purpose.
- This project was inspired by the need for a virtual social platform to connect users in a digital space.
- Thanks to the Django and open-source community for their invaluable contributions.

