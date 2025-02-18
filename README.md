# Music Events Application

## Overview

This project is the development of a mobile application for exploring, purchasing, and managing tickets for different music events. The platform provides an intuitive experience, enabling users to discover events based on categories, as well as access detailed event information.

## Problem

Music event organization and promotion face various challenges, such as lack of visibility, difficulty in accessing clear and concise information about events, and complexities in the ticket purchasing process. Users often struggle to find events of interest near their location, leading to a frustrating experience when trying to attend concerts and shows. This application aims to address these issues by providing a user-friendly and accessible interface that allows users to discover events, access relevant information, and make purchases efficiently.

## Features

### **Home Page**
- **Search Bar**: Allows users to type in the input tab (it doesnt send the request, only typing).
- **Category Menu**: Offers categories like music concerts, exhibitions, stand-up shows, theater, etc (only visual feature, doesnt work on filtering).
- **Trending Events**: Displays popular events in cards, each including an image, band name, event title, location, date, and price.
- **Events Near You**: Shows relevant events based on the user's location (only visual feature, doesnt work location data).

### **Details Page**
- **Event Cards**: Contains an image of the event, band name, event title, location, date, and attendee count with profile pictures.
- **Description**: Provides detailed event information, with a "Read More" button that opens a modal for additional details.
- **Price and Location**: Displays the event's location, ticket price, and a button to purchase tickets.

### **Ticket Purchase Page**
- **Event Card**: Displays a different image for the event along with the artist name, event title, ticket code, gate, seat, date, time, and a barcode for entry access.

## Technologies & Tools

- **Figma**: [Figma Design File](https://www.figma.com/community/file/1243768936820156796/evento-event-mobile-app)
- **HTML & CSS**: The front-end of the application is developed using pure HTML and CSS.
- **GitHub**: Version control using GitHub with conventional commits.

## Design Constraints

- **Screen Resolution**: The application is designed to be viewed **only in vertical orientation** (portrait mode).
- **Phone Screen Sizes**: The app will be displayed properly on phones with screen widths between **390px and 428px**.

## Setup

To run the application locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/JohanAndreyGuarinReatiga/Conciertos-Conectados
   cd Conciertos-Conectados

2. Open index.html in your preferred browser.

