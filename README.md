# Notes-App
## Notes is an easy to use free note taking app made with Node.Js, EJS & MongoDB.

# Features

- **User Authentication:** Allow users to create accounts and log in securely to access their notes.
- **Create, Edit, and Delete Notes:** Provide functionality to create new notes, edit existing ones, and delete notes when they are no longer needed.
- **Organize Notes:** Implement features to organize notes into categories or folders for better management and navigation.
- **Search Functionality:** Include a search bar to quickly find specific notes based on keywords or tags.

## Requirements
- MongoDB Database
- Google Console Account to create API Auth Keys

## Setup
1. Create a `.env` file to store your credentials. Use the following format:
    ```plaintext
    MONGODB_URI=mongodb+srv://<username>:<password>@mongodburlhere
    GOOGLE_CLIENT_ID=YOUR_GOOGLE_ID_HERE
    GOOGLE_CLIENT_SECRET=YOUR_GOOGLE_CLIENT_SECRET_HERE
    GOOGLE_CALLBACK_URL=http://localhost:5000/google/callback
    ```
    Replace `<username>`, `<password>`, `YOUR_GOOGLE_ID_HERE`, and `YOUR_GOOGLE_CLIENT_SECRET_HERE` with your actual credentials.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Notes-NodeJs-CRUD-MongoDB.git
    cd Notes-NodeJs-CRUD-MongoDB
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    npm start
    ```

Now you can access your Notes CRUD application at `http://localhost:5000`.

Demo:
<img width="940" alt="image" src="https://github.com/Adxtxs/Notes-App/assets/138885162/dba9b719-c69e-482d-8c74-471afc91761e">
<img width="944" alt="image" src="https://github.com/Adxtxs/Notes-App/assets/138885162/ff14287c-8936-4ccb-8aca-c4c55336e1be">
