# LinkedIn CAPI Demo with Adobe Integration

A responsive web application that demonstrates LinkedIn Conversion API (CAPI) integration with Adobe. This application provides a form interface for collecting user data and showcasing LinkedIn's CAPI functionality.

## Features

- Mobile responsive design that works on all device sizes
- LinkedIn CAPI integration demo
- Form data collection with validation
- Modal-based result display
- First-party cookie detection (li_fat_id)

## Getting Started

### Prerequisites

- Node.js (v18 or later recommended)
- pnpm package manager

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/cse-capi-demo-simplified-adobe.git
   cd cse-capi-demo-simplified-adobe
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

### Run the application locally

Start the development server:

```bash
pnpm start
```

The application runs on port 3000. Open a browser and navigate to [http://localhost:3000](http://localhost:3000) to view the application.

### Testing Responsiveness

The application is designed to be fully responsive:

- Desktop: Full layout with two-column form sections
- Tablet: Adaptive layout with proper spacing
- Mobile: Single column layout optimized for smaller screens

You can test responsiveness using browser developer tools (F12 → Toggle device toolbar), resizing your browser window, or viewing on actual mobile devices.

## Deployment

### Deploy to Vercel

1. **Prepare for deployment**:

   Modify the `package.json` file by either:

   - Removing the `homepage` property, or
   - Setting it to the production URL from Vercel (which will be generated automatically during deployment)

2. **Install Vercel CLI**:

   ```bash
   npm install -g vercel
   ```

3. **Deploy to Vercel**:

   ```bash
   vercel
   ```

   You will be prompted to log in and answer a few configuration questions. Choose the default options for a standard setup.

4. **Deploy to production**:

   Once you're satisfied with the preview deployment, deploy to production:

   ```bash
   vercel --prod
   ```

5. **Access the application** by opening your browser and navigating to the production URL provided by Vercel.

## Application Structure

- **App.tsx**: Main application component
- **ContactForm.tsx**: Form component with LinkedIn CAPI integration
- **Modal.tsx**: Modal component for displaying form submission results
- **App.css**: Styles including responsive design implementations

## Technologies Used

- React with TypeScript
- TailwindCSS for styling
- LinkedIn Conversion API (CAPI)
- Adobe integration

## License

This project is licensed under the Apache 2.0 License - see the LICENSE file for details.

## Last Updated

June 3, 2025
