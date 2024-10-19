# ONLINE-CINEMA-TICKET-BOOKING-SYSTEM

A Console-Based Ticket Booking Experience highlights the nature of the application

# SUMMARY

The Movie Ticket Booking System is a console-based application designed to streamline the process of booking movie tickets. The system offers a user-friendly interface where users can select from a variety of languages, including English, Tamil, Telugu, Hindi, Kannada, and Malayalam. Based on the chosen language, users are presented with a list of movies available for selection.

Once a movie is selected, users can choose from several popular theatres such as AGS, Sathyam Cinemas, PVR Cinemas, IMAX, and Casino. The application provides multiple showtimes to accommodate different schedules. Users are informed about seat availability and the cost per ticket, enabling them to make informed decisions.

# OVERVIEW 

The system is divided into several interactive sections, each guiding the user through the ticket booking process. It begins by allowing users to choose their preferred language from a list of six, after which they are presented with movies available in that language. Following movie selection, the user chooses a theater and showtime from the available options. After selecting the number of tickets, the user is prompted to choose between paying by cash or card.

# PURPOSE

briefly explains the goal of the application, which is faciliate movie ticket bookings throughs a console interface.the Movie Ticket Booking System simplifies the ticket purchasing process, making it accessible and convenient for users. It ensures a smooth flow from language and movie selection to theatre and showtime choice, culminating in a flexible payment process. This project effectively demonstrates the potential of console-based applications in providing efficient and user-friendly solutions for everyday tasks.

# FEATURES

* Language Selection: Users can select their preferred language from a list of six (English, Tamil, Telugu, Hindi, Kannada, Malayalam), making the application accessible to a wide audience.

* Movie Selection: Based on the chosen language, a list of movies is displayed, from which users can select the movie they wish to watch.

* Theatre Selection: Users can choose from multiple theater options, including AGS, Sathyam Cinemas, PVR Cinemas, IMAX, and Casino, providing flexibility in terms of location.

* Showtime Selection: Multiple showtimes are offered to cater to different user schedules, including options like 10:30 AM, 12:00 PM, 1:30 PM, 2:45 PM, and 3:00 PM.

* Seat Availability & Pricing: The system informs the user of the number of available seats (70) and the fixed price per ticket (210 units), allowing users to choose up to a maximum of 10 tickets at a time.

* Payment Options: The system offers two modes of payment—cash and card.

Cash: Displays booking details with "Payment Pending" status and asks users to proceed to the counter for completing the payment.
Card: Prompts users to enter card details, including card number, expiry date, and PIN, and confirms the booking with "Payment Successful."
Confirmation: After successful payment, the system displays a confirmation with all booking details, including the movie name, theater, showtime, number of tickets, total cost, and payment status.

# CODE WALKTHROUGH
1.Class Definition: The MovieTicketBooking class encapsulates the entire ticket booking process. It contains methods to handle each stage of booking.

2.Main Method – TicketBooking(): This method handles the user interactions step-by-step, allowing the user to select a language, movie, theater, showtime, and payment method.

3.Loops and Input Validation: The system ensures that user input is validated at each step. For example, the language must be chosen from the available options, and the movie must match one listed for that language. Invalid inputs prompt the user to try again.

4.Dictionary Structure: Movies are stored in a Python dictionary with languages as keys and movie lists as values. This allows dynamic display and selection of movies based on language choice.

5.Payment Processing: For card payments, the user is required to enter card information, which simulates a real-world transaction. For cash payments, the system notifies users of pending payment status and instructs them to complete it at the counter

# CONCLUSION

The Movie Ticket Booking System offers a complete and easy-to-understand flow for booking tickets, replicating the steps users would take in real-world movie ticket booking scenarios. By providing language options, theater choices, showtimes, and flexible payment methods, the application ensures a rich and interactive experience for the user. Additionally, it teaches important concepts in programming, such as user interaction management, validation, conditional logic, and the handling of multiple user inputs.
