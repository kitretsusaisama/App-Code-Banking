# App Landing Page
Visit: https://app-code-banking.vercel.app/
Figma: https://www.figma.com/community/file/1145991068621514311


## Project Description

This project is a responsive landing page for a mobile application, designed using HTML, CSS, and optionally, Next.js. The design follows the provided Figma reference and is optimized for both desktop and mobile devices. The landing page includes various sections such as Hero, Features, Gallery, Testimonials, Pricing, and Contact.

## Design Reference

- [Figma Design Link](Figma_Link)
- [Figma Dev Mode Link](Figma_Dev_Mode_Link)
- [Video Explanation](Video_Link)

## Features

- Hero section with a catchy headline and call-to-action buttons.
- Features section showcasing the app's main features.
- Gallery section displaying the app interface.
- Testimonials section with user feedback.
- Pricing plans or subscription details.
- Contact or download section with a form or direct download links.
- Responsive layout using CSS Grid or Flexbox.
- Consistent styling throughout the page as per the Figma design.
- Optional additional features like hover effects, smooth scrolling, lightbox effect, dark mode toggle, animations, and Tailwind CSS for styling.

## Tech Stack

- HTML
- CSS (Flexbox and Grid)
- JavaScript
- Next.js (Optional)
- Google Fonts

## Installation Instructions

### Prerequisites

- Node.js (for Next.js setup)
- Git

### Setup for HTML and CSS (Basic Implementation)

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/app_landing_page.git
    ```

2. Navigate to the project directory:

    ```sh
    cd app_landing_page
    ```

3. Open `index.html` in your browser.

### Setup for Next.js (Advanced Implementation)

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/app_landing_page.git
    ```

2. Navigate to the project directory:

    ```sh
    cd app_landing_page
    ```

3. Install dependencies:

    ```sh
    npm install
    ```

4. Run the development server:

    ```sh
    npm run dev
    ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Data Structure (data.json)

The data for the landing page is stored in a JSON file (`data.json`) and fetched using `getStaticProps` in Next.js.

```json
{
  "hero": {
    "headline": "Discover Our App",
    "subheadline": "The best app for all your needs.",
    "ctaButtons": [
      {
        "text": "Download Now",
        "link": "/download"
      },
      {
        "text": "Learn More",
        "link": "#features"
      }
    ]
  },
  "features": [
    {
      "title": "Feature One",
      "description": "Description of feature one.",
      "icon": "https://via.placeholder.com/100"
    },
    {
      "title": "Feature Two",
      "description": "Description of feature two.",
      "icon": "https://via.placeholder.com/100"
    }
  ],
  "testimonials": [
    {
      "name": "User One",
      "feedback": "This app is fantastic! It has changed my life.",
      "avatar": "https://via.placeholder.com/50"
    },
    {
      "name": "User Two",
      "feedback": "I can't imagine my daily routine without this app.",
      "avatar": "https://via.placeholder.com/50"
    }
  ],
  "pricing": [
    {
      "plan": "Basic",
      "price": "$9.99/month",
      "features": ["Feature A", "Feature B", "Feature C"]
    },
    {
      "plan": "Premium",
      "price": "$19.99/month",
      "features": ["Feature A", "Feature B", "Feature C", "Feature D"]
    }
  ]
}
