## Gym Website by Manjeet Barman 💪 (MERN Stack)

This project is a full-featured gym website built with the powerful MERN stack.

* **M**ongoDB: Stores gym data like plans, user information, and potentially workout routines (optional) 🏋️‍♀️.
* **E**xpress.js: Provides the backend server for handling API requests (subscriptions, user management, email) 🌐.
* **R**eact.js: Creates the dynamic and interactive user interface 🎨.
* **N**ode.js: Acts as the runtime environment for the entire application ⚙️.

### Features 🏋️‍♀️

* **Frontend:**
    * View various subscription plans with details like price, benefits, and duration 💲🏆⏱️.
    * Use the BMI calculator to assess fitness level (optional) 📊.
    * Contact form for inquiries (optional) 📝.
* **Backend:**
    * Users can subscribe to plans through a secure form 🔒.
    * System  automatically sends welcome emails upon successful subscription (configurable) 📧.
      
### Technologies Used 💻

* Frontend: React.js ⚛️
* Backend: Express.js, Node.js ⬢
* Database: MongoDB ️

### Getting Started 🚀

**Prerequisites:**

* Node.js and npm (or yarn) installed on your system 🖥️.
* A MongoDB instance running locally or remotely 🌐.


1. **Clone the repository:**

   ```bash
   git clone https://github.com/manjeetbarman/Gym-website-by-Manjeet-Barman.git
   ```

2. **Install dependencies:**

   ```bash
   cd Gym-website-by-Manjeet-Barman
   npm install  # or yarn install
   ```

3. **Configure Database connection:**

   - Create a `.env` file in the project root.
   - Add variables for `MONGODB_URI` (MongoDB connection string) and email service credentials (if applicable) 🔐.

4. **Start the development server:**

   - Run the backend server:

     ```bash
     npm run server  # or yarn run server
     ```

   - Run the React development server:

     ```bash
     npm run start  # or yarn start
     ```

   - Access the application in your browser at `http://localhost:4000/`.


### Contributing 🤝

Feel free to fork this repository and contribute your own enhancements!  💡
