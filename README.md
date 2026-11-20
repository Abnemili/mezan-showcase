# MÉZAN

MÉZAN is a restaurant website and reservation platform. Guests can explore the menu, book a table from their phone, and receive a confirmation card with a QR code. Staff can find the reservation in their dashboard and confirm the guest’s arrival.

Explore the live demo

## Try the booking and check-in flow

1. Open Reservations, choose a date, party size, and time, then confirm using the sample guest details.
2. On the confirmation card, you can download the QR code, reschedule, or cancel the booking. Keep the booking reference for the next step.
3. Open the Staff Dashboard in the same browser. Sign in with host@mezan.example and mezan-demo.
4. In QR check-in, enter the booking reference or scan the QR displayed on another screen. Select Confirm arrival to see the reservation move to Arrived.

The demo saves sample reservations in your browser. Email delivery is simulated, and no real table is booked.

## What I built

| Area | Features |
|---|---|
| Restaurant website | Responsive home, story, menu, and visit pages |
| Guest reservations | Availability by date and party size, contact validation, QR confirmation, rescheduling, and cancellation |
| Staff dashboard | Reservation search and status filters, QR check-in, and settings for service hours, booking rules, and table capacity |

## Technology

The website and staff dashboard use Next.js, React, and CSS. The full application uses Express and PostgreSQL for reservations and staff operations. The public demo runs on Vercel and simulates those operations in the browser.

## Source and technical review

This repository is a project showcase. The full implementation and Git history are private. I’m happy to walk through the architecture, reservation logic, and deployment setup during a technical review.

If you add screenshots, put one strong image directly below the demo link. A mobile booking screen paired with the QR confirmation card would show the core experience at a glance.
