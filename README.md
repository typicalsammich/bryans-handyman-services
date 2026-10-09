# Bryan's Handyman Services website

Responsive bilingual (English/Spanish) website with project gallery, 24 individual service URLs, 17 service-area URLs, and a booking-request form.

## Deployment
Upload the folder to GitHub and import the repository into Vercel as an **Other** framework project. The included `vercel.json` routes detail URLs to the single-page site. No build command is needed.

## IMPORTANT: Booking setup
The form currently opens a **pre-filled email** to `emersonbrayan96@gmail.com`. This avoids falsely claiming a booking has been submitted when no server exists. For fully automatic online submissions, connect a form backend such as Formspree, Basin, or a custom server endpoint and update `submitBooking` in `script.js`. Bookings are requests, not confirmed appointments.

## Content verification before publishing
- Business card: (415) 724-5238 and emersonbrayan96@gmail.com; user-provided primary emergency phone: (831) 321-5181. Both are displayed, with 831 as the main CTA.
- License number BL25-0000847 was supplied by the client and **has not been independently verified**. Confirm exact license classification and permitted service scopes before publication.
- The Roaring Camp photo was excluded from the gallery because it does not clearly show a handyman job.
- Before/after uses the supplied stovetop images, but the images do not establish every detail of the work performed.
- The logo transparency was approximated from the low-resolution supplied logo. Requesting a high-resolution transparent original from the client will improve sharpness.
- Service area pages are listed as coverage inquiries, not guaranteed availability.
