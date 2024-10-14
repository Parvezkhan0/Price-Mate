# Price Mate: E-Commerce Product Scraping Site

This e-commerce product scraping site, developed using Next.js and Bright Data's webunlocker, is designed to assist users in making informed decisions while shopping online. By utilizing advanced web scraping techniques, the site notifies users when a product drops in price and helps competitors by alerting them when the product is out of stock. These functionalities are managed through cron jobs, ensuring timely and accurate updates.

## Table of Contents 

- [Tech Stack](#tech-stack)
- [Features](#features)

## ⚙️ Tech Stack <a name="tech-stack"></a>

- **Next.js**: A React framework for building server-side rendered applications.
- **Bright Data**: A web scraping platform used for retrieving data from various websites.
- **Cheerio**: A lightweight and fast HTML parser for Node.js, used for scraping data.
- **Nodemailer**: A module for Node.js applications that allows sending emails.
- **MongoDB**: A NoSQL database used for storing scraped product data and user information.
- **Headless UI**: A set of completely unstyled accessible UI components for building polished and accessible user interfaces.
- **Tailwind CSS**: A utility-first CSS framework used for styling the application.

## 🔋 Features <a name="features"></a>

- **Header with Carousel**: A visually appealing header with a carousel showcasing key features and benefits of the site.
  
- **Product Scraping**: Users can input Amazon product links into a search bar for scraping, providing them with real-time data on product details, pricing, and availability.

- **Scraped Products Dashboard**: Displays the details of products scraped so far, offering insights into tracked items and their status.

- **Scraped Product Details**: Showcase the product image, title, pricing, details, and other relevant information scraped from the original website.

- **Track Option**: Users can opt-in to receive email notifications by providing their email addresses through a modal.

- **Email Notifications**: Automated email notifications are sent to users for various scenarios, such as back in stock alerts or lowest price notifications, ensuring they stay updated on their desired products.

- **Automated Cron Jobs**: Utilizes cron jobs to automate periodic scraping, ensuring data is up-to-date and accurate.

- **Code Architecture and Reusability**: The project is structured to promote code architecture and reusability, allowing for easier maintenance and scalability.

