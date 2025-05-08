# Password Reset System (Laravel 12 API)

This is a *RESTful API-based password reset system* built using *Laravel 12* and *MySQL*. It provides users with the ability to request a password reset via email and securely update their password using Laravel’s built-in reset system.

> This project is uploaded on GitHub *only for code review and portfolio purposes*.  
> Only the most essential files are included. *It is not intended for production use or as a plug-and-play package.*

---

## Features

- *Password Reset Email*
  - Users can request a password reset link via email.
  - Emails are sent using Laravel *Queues and Jobs* for performance.
  - The queue driver is set to database to improve response time.

- *Password Update*
  - Uses *Laravel's built-in password reset system* to handle secure password changes.

---

## Tech Stack

- Laravel 12
- MySQL
- Laravel Queues & Jobs (database driver)
- Laravel Mail

---

## API Based

This system is *completely API-driven*, designed for use in SPAs or mobile applications.

---

## Important Note

This code is intended for *demonstration purposes only*. It includes only the core logic and essential files.  
It is *not* a complete standalone system and should *not be used as a ready-made plugin or production package*.
