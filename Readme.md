# Noise Pollution Data Upload and Visualization

This project is a web application for uploading and visualizing noise pollution data. The application allows users to upload CSV, XLSX, or JSON files containing noise pollution data, which is then validated and stored locally. The data can be visualized on a map with different noise levels for morning, afternoon, and evening.

## Features

- Upload noise pollution data in CSV, XLSX, or JSON format
- Validate the uploaded data
- Store data locally in the browser's local storage
- Visualize noise pollution data on a map
- Download a template for the data format

## Technologies Used

- Next.js
- React
- TypeScript
- Framer Motion
- PapaParse
- XLSX
- Lucide React
- Vercel for deployment

## Getting Started

### Prerequisites

- Node.js (>= 14.x)
- npm (>= 6.x) or yarn (>= 1.x)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/noise-pol.git
   cd noise-pol
   ```

2. Install the dependencies:

   ```sh
   npm install
   # or
   yarn install
   ```

3. Create a `.env` file in the root directory and add the following environment variable:

   ```env
   NEXT_PUBLIC_API_BASE_URL=http://localhost:3000/api
   ```

### Running the Development Server

To start the development server, run:

```sh
npm run dev
# or
yarn dev
```
