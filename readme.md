# Currency Converter Android App

## Overview
This repository contains the source code for a Currency Converter Android app. The app allows users to convert currency based on the latest exchange rates.

## Features
- Select source and target currencies.
- Enter an amount to convert.
- Fetch the latest exchange rates from a remote API using Retrofit.
- Perform currency conversion and display the result.

## Screenshots
![image](https://github.com/limafgustavo/CurrencyConverterRetrofit/assets/136847064/206c76cd-0b5e-45dd-9db3-6788e263b5ed)
![image](https://github.com/limafgustavo/CurrencyConverterRetrofit/assets/136847064/afb8b512-81cb-4b5b-873a-9c5b2a41c26d)


## Technologies Used
- Android Studio
- Kotlin
- Retrofit
- Gson
- [Currency API](https://github.com/fawazahmed0/currency-api)

## How to Use
1. Clone this repository to your local machine.
2. Open the project in Android Studio.
3. Build and run the app on an Android emulator or device.

## Project Structure
- `MainActivity`: The main activity of the app, responsible for user interaction and currency conversion logic.
- `NetworkUtils`: A utility class for creating Retrofit instances.
- `Endpoint`: Retrofit interface for defining API endpoints.
