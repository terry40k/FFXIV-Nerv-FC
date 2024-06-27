# Nerv FC Dawntrail Raffle Sim

## Description

- This Python script simulates a raffle among members of the FFXIV FC, Nerv
- The simulation runs 100 times, rolling a random number between 1 and 999 for each member in each simulation
- The member who hits the user-specified winning number wins the raffle
- Additionally, the script tracks and displays the members who rolled numbers closest to the winning number across all simulations

## Features

- **Member List**: A predefined list of Nerv FC members
- **Random Number Generation**: Simulates rolling a random number between 1 and 999 for each member
- **Winning Number**: Prompts the user to input a winning number
- **Profile Fetching**: Fetches the profile image and details of the winning member from the FFXIV Lodestone
- **Details Display**: Displays the winning member's profile details in a table
- **Simulation Statistics**: Displays the total number of simulations run
- **Closest Members**: Tracks and displays members who rolled numbers closest to the winning number

## How It Works

1. **Initialization**: The script initializes a list of Nerv FC members
2. **User Input**: The user is prompted to enter a winning number between 1 and 999
3. **Simulation Loop**: The script runs 100 simulations:
   - For each member, a random number between 1 and 999 is rolled
   - Tracks the member who rolls a number closest to the winning number
   - If a member rolls the exact winning number, their profile image and details are fetched from the FFXIV Lodestone and displayed
4. **Statistics Display**: After all simulations, the script displays statistics including the total number of simulations and winners,
   and a table of members who rolled numbers closest to the winning number.

## Usage

1. Nothing fancy, just make sure to install the below library:
   ```sh
   pip install requests beautifulsoup4
