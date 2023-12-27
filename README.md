# PriceWise
This is a Next.js project bootstrapped with create-next-app.
## Getting Started
Follow these steps to set up the project locally on your machine.
Prerequisites

Make sure you have the following installed on your machine:

    Git
    Node.js
    npm (Node Package Manager)
### Cloning the Repository
git clone git@github.com:priyanshusinha11/pricewise11.git
cd pricewise11
### Installation
npm install
### Set Up Environment Variables
Create a new file named .env in the root of your project and add the following content:

BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=
MONGODB_URI=
EMAIL_USER=
EMAIL_PASS=
Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on the specific websites from BrightData, MongoDB, and Node Mailer.
### Running the Project
npm run dev
Open http://localhost:3000 in your browser to view the project.

## TECH STACK
    Next.js
    Bright Data
    Cheerio
    Nodemailer
    MongoDB
    Headless UI
    Tailwind CSS

  ## FEATURES
  Header with Carousel: Visually appealing header with a carousel showcasing key features and benefits

Product Scraping: A search bar allowing users to input Amazon product links for scraping.
Scraped Projects: Displays the details of products scraped so far, offering insights into tracked items.
Scraped Product Details: Showcase the product image, title, pricing, details, and other relevant information scraped from the original website
Track Option: Modal for users to provide email addresses and opt-in for tracking.
Email Notifications: Send emails product alert emails for various scenarios, e.g., back in stock alerts or lowest price notifications.
Automated Cron Jobs: Utilize cron jobs to automate periodic scraping, ensuring data is up-to-date
and many more, including code architecture and reusability

## Live Deployement
The project is live and deployed on https://pricewise-priyanshu-11.vercel.app/.
