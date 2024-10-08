# BookMySpace

<h1 align="center">2. Meeting Room Booking System for Co-working spaces</h1>

<h3 align="center">⚠️ Read the entire requirement thoroughly. Every detail must be carefully reviewed from start to finish.</h3>

---

**Objective:**  
Our platform is designed to provide a seamless and intuitive experience for users booking meeting rooms. With a focus on user-friendly design, secure processes, and robust management tools, the system serves both regular users and administrators.

---

#### **Public Pages**

**1. Homepage / Landing Page**

- **Header Section / Navbar:**

  - **Logo/System Name:** Positioned at the top left. Clicking redirects to the homepage.
  - **Navigation Links:** Home, Meeting Rooms, About Us, Contact Us, Login/Register.
  - **User Icon/Dropdown:**
    - **For Authenticated Users:** My Bookings, Logout.
    - **For Admins:** Dashboard, Logout.

- **Hero Section:**

  - **Visual Appeal:** Large banner image or video of a modern workspace.
  - **Headline & Subheadline:**
    - Headline: "Book Your Ideal Meeting Room with Ease."
    - Subheadline: "Efficient, hassle-free room booking for all your meeting needs."
  - **CTA Button:** "Book Now" redirects to the Meeting Rooms page.

- **Service Advertisement Section:**

  - **Highlighted Services:** Real-Time Availability, Instant Booking Confirmation, Flexible Scheduling, 24/7 Support.

- **Featured Rooms Section:**

  - **Room Cards:**
    - Image, Room Name, Capacity, Price Per Slot, "See Details" Button.
  - **See More Button:** Redirects to the Meeting Rooms page.

- **Extra Sections:**

  - **Why Choose Us?:** Highlights features like "Seamless Booking Experience" and "Secure Transactions."
  - **How It Works Section:**
    - Steps: Select a Room, Choose Date & Time, Confirm Booking.
    - Icons/Illustrations for each step.
  - **Customer Testimonials Section:**
    - Carousel with customer profile pictures, names, roles, and testimonials.

- **Footer Section:**
  - **Contact Information:** Email, phone number, office address.
  - **Social Media Links:** Clickable icons.
  - **Additional Links:** Privacy Policy, Terms of Service.

**2. About Us Page**

- **Design Elements:**
  - Creative presentation with animations and visuals.
- **Content Sections:**
  - **Our Mission:** Purpose and goals.
  - **Meet the Team:** Team member images and bios.
  - **Our Story:** Background and evolution.

**3. Contact Us Page**

- **Contact Information:**
  - Email, phone number, office address.
- **Contact Form:**
  - **Form Fields:** Name, email, subject, message.
  - Basic animations for form elements.

**4. Error Pages**

- **Features:** Custom 404 page for non-existent routes.
- **Functionality:** Navigation options to guide users back to safe pages (e.g., Home, Login).

**5. User Authentication Pages**

- **Sign Up Page:**
  - **Form Fields:** Name, email, password, phone number, address.
  - By default, every user will have the "USER" role. Initially, there should be an admin in the database. Later, that admin can promote a user to the "ADMIN" role.
  - **Functionality:**
    - Allows users to create a new account.
    - Form validation (e.g., correct email format).
    - Displays success or error messages based on the outcome.
- **Login Page:**
  - **Form Fields:** Email, password.
  - **Functionality:** Login, token-based authentication, proper error messages.
  - **Please make sure to provide the admin login credentials when submitting the assignment.**

**6. Meeting Rooms Page**

- **Room Listings:**
  - **Card View Display:** Image, Room Name, Capacity, Price Per Slot, "See Details" Button.
  - **Search Functionality:**
    - **Search Bar:** Search by room name or keyword.
    - **Filtering Options:** Capacity, Price.
    - **Sort Options:** By Price Per Slot (ascending, descending).
    - **Clear Filter Button:** Resets all filters.
    - **Pagination:** If needed, depending on the project scope.

---

#### **User Pages [Private/Protected Route]**

**7. Room Details Page**

- **Room Information:**
  - **Detailed Display:** Multiple Images, Room Name, Room No., Floor No., Capacity, Price Per Slot, Amenities.
  - **Book Now Button:** A "Book Now" button that navigates to the booking page.

**8. Booking Process**

- **Booking Form:**
  - **Date and Time Selection:** Calendar view (Allows users to choose a booking date), available time slots (Show available time slots for that selected date. (based on isBooked = false)).
  - **User Information Form:** Pre-filled with user details.

**9. Confirmation and Payment / Checkout Page**

- **Booking Summary:** Room name, date, time, cost, user info.
- **Payment Selection Options:** Implement any payment system.
- **Confirm Booking Button:** Finalize the booking.
- **Confirmation Modal:** Booking details and thank you message.

**10. My Bookings Page**

- **Booking List:**
  - Display user all bookings with Room Name, Date & Time, and Status (Unconfirmed/Confirmed).

---

#### **Admin Pages [Private for Admin Only]**

**1. Admin Dashboard Page**

- **Room Management:**

  - **Create Room Button:** Form for adding new rooms.
  - **Room List Table:** Room Name, Room No., Floor No., Capacity, PricePerSlot, Action Buttons (Update/Delete).
  - **Real-Time Updates:** Optimistic updates for create, update, and delete operations.

- **Slots Management:**

  - **Create Slot Button:** Form for adding new slots.
  - **Slots List Table:** Room Name, Room No., Date, Start Time, End Time, Action Buttons (Update/Delete).
  - **Real-Time Updates:** Optimistic updates for create, update, and delete operations.

- **Booking Management:**
  - **Booking List Table:** Room Name, User Name, Date & Time, Status (Confirmed/Unconfirmed).
  - **Actions:** Approve/Reject Bookings, Delete Bookings with confirmation prompt.

---

### **Bonus Features**

- **Debounce API Calls:** Implement search debouncing.
- **Animations:** Micro-animations for interactive elements.
- **Integrate Payment:** Secure payment processing using AmarPay/SSLCOMMERCE/Stripe.
- **Scroll to Top Button:** Implement a "Scroll to Top" button for easy navigation.
- **GitHub Contributions:** Minimum of 15 commits with meaningful progress.

### **Deliverables**

- Fully functional frontend application integrated with the backend.
- Responsive design for all pages.
- User and Admin dashboards with described features.
- Complete backend integration.
- Clean, well-organized, and documented code.
- Creative solutions to integration challenges.

### **References for Idea Generation**

- **Inspiration Sites:**
  - [Booking.com](https://www.booking.com/)
  - [Convene](https://www.convene.com/)

**[N.B: If backend updates are needed for Assignment-3 to meet these requirements, please adjust as necessary.]**
