
# Welcome to Soldar Energy Estimation App

A fullstack mobile app that helps users estimate the solar energy potential of any location based on panel size, efficiency, and real solar irradiance data.

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

## Features

 1. # Location Input:
  a. Enter manually via search

  b. OR use device GPS (geolocation)

 2. # Solar Energy Estimation:

  a. Based on panel size (kW) and efficiency (%)

  b. Dynamic energy irradiance values (NASA / Copernicus)

 3. # Monthly Radiation Breakdown:

  a. View seasonal solar energy output

  b. Beautiful bar chart visualization

 4. # Save Locations:

  a. Save multiple addresses for easy access later

 5. # Offline History:

  a. Estimations are stored locally using AsyncStorage


## Tech Stack

   # Frontend	                                     Backend
  React Native (Expo)	                           Spring Boot
  AsyncStorage	                                  REST API
  Expo Location                                  API	Java 17+
  React Native Chart Kit                  	Spring MVC + Validation
  Animated UI Components	                  Copernicus / NASA POWER Data


## Installation

Frontend (React Native)

"bash
CopyEdit
git clone https://github.com/mr33qy/solar-energy-estimator.git
cd solar-energy-estimator/frontend
npm install
npm start
"


Install Expo Go on mobile device for test.



Backend (Spring Boot)

"bash
CopyEdit
cd solar-energy-estimator/backend
./mvnw spring-boot:run
"
Backend will be available at http://localhost:8080/api.



# How to Use

1. Open the app (Expo)

2. Tap Add Location

3. Use search bar (type city or address)

   OR tap Use My Current Location


4. Tap Continue to Estimation

  a. Enter panel size (kW) and panel efficiency (%)

  b. Tap Estimate


5. View:

  a. Estimated annual output

  b. Monthly solar radiation graph

  c. Potential savings!



# Future Improvements 


Add different panel types (monocrystalline vs polycrystalline)
Calculate payback period (investment vs savings)
Cloud sync using Firebase
Light/dark theme toggle

👨‍💻 Author
Made by Cristian Sudacevschi
