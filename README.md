# Project Name

## Description
- Developed a full-featured video conferencing web application supporting up to 100+ concurrent users, providingall essential functionalities of modern video conferencing apps.
## Features
- Socket.io
- React Material UI
- MVC architecture
- Frontend and backend with database validation

## Tech Stack
- **Frontend:** React, Material-UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Cloud Storage:** Mongo Atlas
- **Other Tools:** Socket.io, Cors, Bcrypt, Crypto

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/DhiravAgrawal/Konnect.git
    cd Konnect
    ```

2. **Install dependencies for both frontend and backend:**
    ```bash
    # Install backend dependencies
    cd backend
    npm install

    # Install frontend dependencies
    cd ../frontend
    npm install
    ```

3. **Setup environment variables:**
    - Create a `.env` file in the `backend` directory and add the following:
      ```
      ATLASDB_URL=your_atlas_cluster_url
      ```

4. **Run the application:**
    ```bash
    # Run backend server
    cd backend
    npm run dev

    # Run frontend server
    cd ../frontend
    npm start
    ```


## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature-branch`)
6. Open a pull request

