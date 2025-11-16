---
sidebar_position: 1
---

# Add a club event

This guide will show you how to add a club event to your website.

### 1. Locate the Events Database
  - Go to `src/app` folder → `data` folder → `events-database.js` file

### 2. Add a new club event
Within the `allEvents` array, add a new object with the following properties:
- `id`: a unique identifier for the event, E.g. 1 means it's the first event being displayed, 2 means it's the second event being displayed, etc.
- `title`: the title of the event
- `description`: a brief description of the event
- `location`: the location of the event
- `date`: the date of the event in the format `January 1, 2025`
- `time`: the time of the event in the format `12:00PM` or `1:00PM - 2:00PM`
- `image`: the URL of an image for the event
 - Please note that the image must always be stored in the `events-images` folder
- `imageAlt`: the alt text for the image
- `rsvpurl`: the URL for the RSVP form
 - The RSVP url is optional, if you don't have one, leave it empty

An example of an **event object**:
```tsx title="src/data/events-database.js"
{
  id: 1,
  title: "Event Title",
  description: "Event description",
  location: "Event location",
  date: "January 1, 2025",
  time: "12:00PM",
  image: "/event-images/random_event_image.jpg",
  imageAlt: "Event image",
  rsvpurl: "https://example.com/rsvp"
}
```

### 3. Add more events
- You can always add more events but following the same format as the example above. Remember that each event should be encapsulated within a `{}` element. 
- There is no limit to the number of events you can add, but please ensure that each event is separated by a `comma`.
