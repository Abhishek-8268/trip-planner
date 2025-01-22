```html
<div align="center">
  <h1 align="center">JourneyJolt</h1 >
  <a href="https://trip-planner-by-satendra.vercel.app/" target="_blank">
    <img src="https://i.ibb.co/X7N17ps/main.png" style="border-radius: 10px;" alt="Logo" width="" height="250">
  </a>

  <h3>AI-Based Trip Planner</h3>

  <p align="center">
    Discover personalized itineraries and curated hotel recommendations tailored to your interests. Simplify travel planning with smart suggestions for top destinations and activities, making every trip easy and enjoyable.

  </p>
</div>
</br>
<div align="center">

## About The Project

</div>

<div class="sampleImages" align="center" style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
    <a href="https://ibb.co/gRX4Bcx"><img src="https://i.ibb.co/X7N17ps/main.png" alt="image" style="border-radius: 10px; height: 170px; border: 0;"></a>
    <a href="https://ibb.co/f1zjdLn"><img src="https://i.ibb.co/TbHgn5W/form.png" alt="image-2" style="border-radius: 10px; height: 170px; border: 0;"></a>
    <a href="https://ibb.co/yySg2kP"><img src="https://i.ibb.co/QDkGLrS/trip.png" alt="image-1" style="border-radius: 10px; height: 170px; border: 0;"></a>
    <a href="https://ibb.co/26srCZS"><img src="https://i.ibb.co/bPcmZwX/all.png" alt="image-3" style="border-radius: 10px; height: 170px; border: 0;"></a>
</div>
</br>

**JourneyJolt** is an AI-based travel planning application designed to make trip planning _easier and more efficient_. This project leverages artificial intelligence to analyze user preferences and provide personalized recommendations for destinations, accommodations, and activities.

Key features of JourneyJolt include:
* **Personalized Recommendations**: The AI suggests ideal destinations, hotels, and activities tailored to the traveler’s preferences.
* **Automated Itinerary Generation**: The app automatically creates a full itinerary that considers factors like travel time and user preferences.

JourneyJolt aims to enhance the travel experience by providing a streamlined, easy-to-use platform for trip planning, designed for both casual travelers and frequent explorers alike.

## Built With

This project is built with the following major frameworks, libraries, and services:

* [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&background=E4E4E4)](https://reactjs.org/)
* [![Vite](https://img.shields.io/badge/Vite-000000?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev/)
* [![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
* [![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/)
* [![Gemini AI](https://img.shields.io/badge/Gemini%20AI-FF5F00?style=for-the-badge&logo=google-cloud&logoColor=white)](https://cloud.google.com/blog/topics/ai-machine-learning/introducing-gemini-the-new-ai-powered-google-cloud-platform)
* [![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
* [![Auth0](https://img.shields.io/badge/Auth0-000000?style=for-the-badge&logo=auth0&background=E4E4E4)](https://auth0.com/)
* [![React Hot Toast](https://img.shields.io/badge/React%20Hot%20Toast-FF5733?style=for-the-badge&logo=react&logoColor=black)](https://react-hot-toast.com/)

## Getting Started

Setting up JourneyJolt is simple — just configure your ```.env``` file, and you're ready to go!

To get started with JourneyJolt, follow these instructions to set up the project locally on your machine for development and testing.

### Prerequisites

Before you begin, ensure you have the following installed:
* Node.js  _(v16.0 or above)_ - [Download Node.js](https://nodejs.org/en)
* VS Code _(Code Editor)_ - [Download VS Code](https://visualstudio.microsoft.com/downloads/)

### Services & API Keys Setup

To fully integrate JourneyJolt with third-party services, you'll need to sign up for the following services, configure the required settings, and obtain API keys. Below are the steps for each service:

 
<details>
  <summary>Google Cloud Setup</summary>
    Follow these steps to set up Google Cloud for your project:
  <ol>
    <li>Create an account on <a href="https://cloud.google.com" target="_blank">Google Cloud</a>.</li>
    <li>As a new user, you will receive a free trial with 90 days and ₹25,000 in free credits, which you can use for your project.</li>
    <li>After setting up your account, go to the <b>APIs & Services</b> section to create an API key.</li>
    <li>Next, enable the following APIs:
      <ul>
        <li>Maps JavaScript API</li>
        <li>Maps Embed API</li>
        <li>Geolocation API</li>
        <li>Geocoding API</li>
        <li>Places API</li>
        <li>Places API (New)</li>
      </ul>
    </li>
    <li>The "Places API (New)" may require you to set up a billing account. Don’t worry, your free credits are more than enough to cover the cost!</li>
    <li>Once everything is set up, you will have your Google API key ready to use.</li>
    <li>Paste the API key in your environment file: 
      <pre><code>VITE_GOOGLE_MAP_API_KEY="YOUR_GOOGLE_API_KEY"</code></pre>
    </li>
  </ol>
</details>

<details>
  <summary>Gemini API Setup</summary>
    Follow these steps to set up the Gemini API:
  <ol>
    <li>Go to the <a href="https://ai.google.dev/" target="_blank">Gemini AI website</a>.</li>
    <li>Create an account if you don't have one, or sign in with your existing account.</li>
    <li>The Gemini API is free, meaning there are no charges associated with using it for your project.</li>
    <li>Once your account is set up, you can start using the Gemini API for your project.</li>
    <li>Paste the API key in your environment file: 
      <pre><code>VITE_GEMINI_API_KEY="YOUR_GEMINI_API_KEY"</code></pre>
    </li>
  </ol>
</details>


<details>
  <summary>Auth0 Setup</summary>
  <p>
    Follow these steps to set up Auth0 for your project:
  </p>
  <ol>
    <li>Go to the <a href="https://auth0.com/" target="_blank">Auth0 website</a>.</li>
    <li>Create a free account. The free plan supports up to 25,000 monthly active users, which is more than enough for our project.</li>
    <li>After signing up, select the type of project you are creating. Choose "Single Page Application" as we are building a React app.</li>
    <li>Once your account is set up, create a new

 "Application" and copy the <b>Client ID</b> and <b>Client Secret</b>.</li>
    <li>Paste the credentials in your environment file as follows:
      <pre><code>VITE_AUTH0_CLIENT_ID="YOUR_CLIENT_ID"</code></pre>
      <pre><code>VITE_AUTH0_CLIENT_SECRET="YOUR_CLIENT_SECRET"</code></pre>
    </li>
  </ol>
</details>

### Installing Dependencies

Once your environment is set up, install the necessary dependencies for JourneyJolt.

1. Clone the repository:
   ```bash
   git clone https://github.com/satendra03/trip-planner-by-satendra.git
   ```
2. Navigate to the project folder:
   ```bash
   cd trip-planner-by-satendra
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the App Locally

1. Start the development server:
   ```bash
   npm run dev
   ```
2. Open your browser and visit `http://localhost:5173` to view JourneyJolt in action.


## Acknowledgments

Special thanks to all the libraries and services used in this project, including:

* [React](https://reactjs.org/)
* [Google Cloud](https://cloud.google.com/)
* [Gemini AI](https://ai.google.dev/)
* [Auth0](https://auth0.com/)
* [Firebase](https://firebase.google.com/)

---

Enjoy planning your next trip with JourneyJolt!

