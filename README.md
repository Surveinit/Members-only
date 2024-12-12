# 🫂 Members Only

**Members Only** is an exclusive web application where members can anonymously write and share posts. This project allows members to create posts, view others' posts, and discover who authored each post within the club. 
Outside the club, users can see only the content of the posts and not the identities behind them, keeping the stories anonymous to non-members.

## Features

- **User Authentication**: Users can sign up, sign in, and sign out with Devise, a powerful authentication system for Rails.
- **Post Creation**: Signed-in members can create posts that are only visible to other signed-in members.
- **Anonymous Viewing**: Non-members can view the posts but cannot see who authored them.
- **Membership Exclusivity**: Only registered users can see the author of posts, ensuring a sense of exclusivity for club members.
- **Flash Notifications**: Users receive notifications about successful actions like signing up, logging in, or creating posts.

## Technologies Used

- **Ruby on Rails**: The backend framework used to build the application.
- **Devise**: For authentication and user management.
- **PostgreSQL**: The database to store user and post data.
- **HTML/CSS**: For frontend development and styling.

## Setup and Installation

Follow the steps below to set up **Members Only** on your local machine:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/members-only.git
    cd members-only
    ```

2. **Install dependencies**:
    Make sure you have Ruby and Rails installed, and then run:
    ```bash
    bundle install
    ```

3. **Set up the database**:
    Run the following commands to set up the database and apply the migrations:
    ```bash
    rails db:create
    rails db:migrate
    ```

4. **Start the Rails server**:
    Launch the Rails server:
    ```bash
    rails s
    ```

5. **Access the application**:
    Open your browser and navigate to `http://localhost:3000` to access the Members Only application.

## Usage

- **Sign Up**: Create a new account to become a member of the clubhouse. Only members can see the authors of posts.
- **Sign In**: If you already have an account, sign in to gain access to the members' area.
- **Create Posts**: Write posts that are shared with other members.
- **View Posts**: As a signed-in user, you can view posts and see the authors. Non-members can only read the posts without knowing the authors.
- **Sign Out**: Log out to exit the clubhouse.
