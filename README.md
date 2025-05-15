# Weather App

A modern weather application built with Next.js that provides real-time weather information and forecasts.

## Features

- Real-time weather data
- Location-based weather information
- Detailed weather forecasts
- Responsive design for all devices
- Dark/Light mode support

## Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Styling:** Tailwind CSS
- **UI Components:** shadcn/ui
- **Database:** Drizzle ORM
- **State Management:** React Hooks
- **Logging:** Built-in logger for server components
- **Notifications:** Toast for client components

## Prerequisites

- Node.js 18.0 or later
- npm or yarn
- A weather API key (e.g., OpenWeatherMap)

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd weather
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory and add the following:
```env
NEXT_PUBLIC_WEATHER_API_KEY=your_api_key_here
DATABASE_URL=your_database_url_here
```

4. Run the development server:
```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
weather/
├── app/                 # App router pages and layouts
├── components/          # Reusable components
├── lib/                 # Utility functions and configurations
├── public/             # Static assets
├── styles/             # Global styles
└── types/              # TypeScript type definitions
```

## Development

- Server components use the built-in logger for debugging
- Client components use toast notifications for user feedback
- Follow the component structure guidelines in the documentation

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
