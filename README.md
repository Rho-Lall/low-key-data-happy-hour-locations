# Low Key Data Happy Hour Locations

This repository contains the official location data for **Low Key Data Happy Hour** meetups displayed on [lowkeydatahappyhour.com](https://lowkeydatahappyhour.com).

## About Low Key Data Happy Hour

Low Key Data Happy Hour is a global community of data professionals, analysts, engineers, and enthusiasts who gather for casual, informal meetups. Our Low Key Data Happy Hour events take place in cities around the world, providing a relaxed environment for networking, learning, and sharing experiences in the data industry.

## What This Repository Does

The `locations.json` file in this repository powers the interactive map on the Low Key Data Happy Hour website. When you update this file, the changes automatically appear on [lowkeydatahappyhour.com](https://lowkeydatahappyhour.com), making it easy to keep our Low Key Data Happy Hour community informed about meetup locations worldwide.

## How to Add Your Low Key Data Happy Hour Location

Want to add a new Low Key Data Happy Hour meetup to the map? Follow these simple steps:

### Step 1: Fork This Repository

Click the "Fork" button at the top right of this page to create your own copy of the Low Key Data Happy Hour locations repository.

### Step 2: Edit the locations.json File

1. Open the `locations.json` file in your forked repository
2. Add your Low Key Data Happy Hour location using this format:

```json
{
  "name": "Your City Name",
  "lat": 40.7128,
  "lng": -74.0060,
  "url": "https://your-meetup-link.com"
}
```

**Field Descriptions:**
- `name`: The city name for your Low Key Data Happy Hour meetup
- `lat`: Latitude coordinate (you can find this on [Google Maps](https://maps.google.com))
- `lng`: Longitude coordinate (you can find this on [Google Maps](https://maps.google.com))
- `url`: Link to your Low Key Data Happy Hour meetup page (Meetup.com, Eventbrite, Google Form, etc.)

### Step 3: Find Your Coordinates

To get the latitude and longitude for your Low Key Data Happy Hour location:

1. Go to [Google Maps](https://maps.google.com)
2. Search for your city
3. Right-click on the location
4. Click on the coordinates to copy them
5. The first number is latitude, the second is longitude

### Step 4: Submit a Pull Request

1. Commit your changes with a descriptive message like "Add [City Name] Low Key Data Happy Hour location"
2. Click "Pull Request" 
3. Provide a brief description of your Low Key Data Happy Hour meetup
4. Submit the pull request

Our team will review your Low Key Data Happy Hour location submission and merge it. Once merged, your location will automatically appear on the Low Key Data Happy Hour map at [lowkeydatahappyhour.com](https://lowkeydatahappyhour.com)!

## Example Low Key Data Happy Hour Location Entry

```json
{
  "name": "Seattle",
  "lat": 47.6062,
  "lng": -122.3321,
  "url": "https://www.meetup.com/seattle-low-key-data-happy-hour/"
}
```

## Join the Low Key Data Happy Hour Community

Low Key Data Happy Hour brings together data professionals from all backgrounds and experience levels. Whether you're a data scientist, analyst, engineer, or just data-curious, there's a Low Key Data Happy Hour meetup for you.

### Find a Low Key Data Happy Hour Near You

Visit [lowkeydatahappyhour.com](https://lowkeydatahappyhour.com) to:
- View the interactive map of all Low Key Data Happy Hour locations
- Find Low Key Data Happy Hour meetups in your city
- Connect with local data professionals at Low Key Data Happy Hour events
- Learn about upcoming Low Key Data Happy Hour gatherings

### Start Your Own Low Key Data Happy Hour

Don't see a Low Key Data Happy Hour in your city? Start one! Low Key Data Happy Hour meetups are community-driven and open to anyone passionate about data. Once you've set up your meetup page, add it to this repository so others can find your Low Key Data Happy Hour group.

## Questions About Low Key Data Happy Hour?

If you have questions about adding your location to the Low Key Data Happy Hour map or need help with your pull request, please open an issue in this repository.

---

**Low Key Data Happy Hour** | Connecting data professionals worldwide, one happy hour at a time.

Visit us at [lowkeydatahappyhour.com](https://lowkeydatahappyhour.com)
