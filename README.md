# 📚 BookReviews Platform

A modern web application for book enthusiasts to discover, review, and discuss their favorite books.

## 🌟 Features

- **Book Discovery**: Browse through an extensive collection of books
- **Detailed Reviews**: Read and write in-depth book reviews
- **User Profiles**: Personalized profiles to track your reviews and reading journey
- **Rating System**: Rate books on a 5-star scale
- **Responsive Design**: Seamless experience across all devices

## 🛠️ Technology Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Database**: Supabase
- **Authentication**: Supabase Auth
- **Routing**: React Router v6

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd book-review-platform
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the root directory with the following variables:
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Start the development server:
```bash
npm run dev
```

## 📦 Project Structure

```
book-review-platform/
├── src/
│   ├── components/      # React components
│   ├── lib/            # Utility functions and configurations
│   ├── App.tsx         # Main application component
│   └── main.tsx        # Application entry point
├── public/             # Static assets
└── supabase/          # Supabase configurations and migrations
```

## 🔑 Key Components

- **BookList**: Displays the collection of available books
- **BookDetail**: Shows detailed information about a specific book
- **Profile**: User profile management
- **Navigation**: Main navigation component
- **Home**: Landing page component

## 🔒 Security

- Row Level Security (RLS) enabled for all database tables
- Secure authentication flow
- Protected routes for authenticated users
- Input validation and sanitization

## 🚀 Deployment

Build the project for production:

```bash
npm run build
```

The built files will be in the `dist` directory, ready for deployment.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📫 Support

For support, please open an issue in the repository or contact the maintainers.
