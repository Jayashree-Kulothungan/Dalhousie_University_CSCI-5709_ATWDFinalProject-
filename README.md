# Dalhousie_University_CSCI-5308_ASDC

The final project of CSCI 5709 - Advanced Topics in Web Development of MACS at Dalhousie University.

- Project Name : TakeOff
- Project Description :
  - 'TakeOff' is a travel management website which aims on providing the users with a one stop platform for flights, hotels, events and tours booking.
  - The deployed website is currently a semi functional prototype demonstrating each feature of the website and the experience it will provide to the users.
  - The website aims on providing a feedback to the user for all their actions. Every button provides a message to the user enhancing the user experience and usability of the website and also making sure that users are aware what each functionality offers.
- Technical Stack:
  - Front-end : React Js, HTML5, CSS, Bootstrap, Material UI
  - Back-end : Node Js, Express Js
  - Database : MongoDB
  - Deployment Platform : Heroku
  - Package Manager : NPM
- Team Name : Group no 13
- Team Members :
  - Bhavesh Lalwani
  - Harshit Lakhani
  - [Jayasree Kulothungan](jayasreekulothungan@gmail.com)
  - Kalpit Machhi
  - Meghna Kumar
  - Sharad Kumar
- Responsibility
  - Feature developed:
    - Event Management
      - Display list of events
      - Display details about each event
      - Create a booking and add it to cart
      - Modify an existing booking
      - Cancel an existing booking
    - Tour Management
      - Display list of tour packages
      - Display details about each tour packages
      - Create a booking and add it to cart
      - Modify an existing booking
      - Cancel an existing booking
- Front-end Files
  - frontend/src/components/Events/eventList/Events.jsx - The events.jsx file contains the code to display all the event cards and the filtering function to display cards based on the city and date
  - frontend/src/components/Events/BookingEvents/BookingEvents - The BookingEvents.jsx file contains the code to enter booking information and modal to display the booking summary.
  - frontend/src/components/TourPackages/TourPackages.jsx - The TourPackages.jsx file contains the code to display all the tour cards and the filtering function to display cards based on the city and date
  - frontend/src/components/TourPackages/BookingTour.jsx - The BookingTour.jsx file contains the code to enter booking information and modal to display the booking summary.
- Back-end Files
  - backend/models/eventModel.js - Contains the mongoDB model for events table
  - backend/models/bookingEvents.js - Contains the mongoDB model for eventBookings table.
  - backend/controller/event.js - Contains the logics for getting data from mongoDB evnts table.
  - backend/controller/eventBooking.js - Contains the logic for creating, updating and getting booking information.
  - backend/routes/eventRoute.js - Contains the API end point route for getting events.
  - backend/routes/eventBookingRoute.js - Contains the API endpoint routes for creating, updating and getting booking information.
  - backend/models/tourPackageModel.js - Contains the mongoDB model for tour package table.
  - backend/models/tourBookingModel.js - Contains the mongoDB model for tourPackageBookings table.
  - backend/controller/tourPackage.js - Contains the logics for getting data from mongoDB tour package table.
  - backend/controller/tourBooking.js - Contains the logic for creating, updating and getting booking information
  - backend/routes/tourBookingRoute.js - Contains the API endpoint routes for creating, updating and getting booking information.
  - backend/routes/tourPackageRoute.js - Contains the API end point route for getting tour packages.
