# Fundraising Thermometer Display

A simple, interactive fundraising thermometer visualization tool that helps track donations from multiple sources and displays progress towards a fundraising goal.

## Features

- Visual thermometer display that updates in real-time
- Track multiple donation sources:
  - Cash
  - Check
  - Pledges
  - Square payments
  - Website donations
- Automatic total calculation
- Manual total override option
- Adjustable fundraising goal
- Reset functionality

## Setup

1. You'll need to open two separate windows/files:
   - `main.html`: Contains the input interface for donation tracking
   - `display.html`: Shows the thermometer visualization

## How to Use

1. Open both `main.html` and `display.html` in separate windows
2. In `main.html`:
   - Enter amounts for different donation types (Cash, Check, Pledges, etc.)
   - The total will automatically calculate
   - Use "Override Total" if you need to manually set the total
   - Set your fundraising goal using the "Set Goal" button
   - Use Reset to clear all values
3. The thermometer in `display.html` will update automatically to show:
   - Current progress as a percentage
   - Visual fill level
   - Current goal amount

## Technical Notes

- The thermometer updates in real-time as values are entered
- The percentage display shows progress towards the goal
- All monetary values are handled in standard currency format

## Contributing

This project was created with the assistance of AI. Feel free to fork, modify, and improve upon it for your own fundraising needs.

## Support

If you encounter any issues or have questions, please open an issue in the repository.
