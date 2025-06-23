# Conference Event Planner

A modern React-based web application for planning and budgeting conference events. This application helps event organizers calculate costs for venues, audio-visual equipment, and catering services.

## 🎯 Project Overview

Conference Event Planner is a comprehensive budgeting tool designed for event organizers and conference planners. It provides an intuitive interface for selecting venues, audio-visual equipment, and meal services while automatically calculating total costs based on selections and attendee count.

## ✨ Features

### 🏢 Venue Selection
- **Multiple venue options** with different capacities and pricing
- **Conference Room** (Capacity: 15) - $3,500
- **Auditorium Hall** (Capacity: 200) - $5,500 (Limited to 3 bookings)
- **Presentation Room** (Capacity: 50) - $700
- **Large Meeting Room** (Capacity: 10) - $900
- **Small Meeting Room** (Capacity: 5) - $1,100

### 🎥 Audio-Visual Equipment
- **Professional audio-visual equipment** selection
- **Quantity-based pricing** for equipment rentals
- **Real-time cost calculation** as quantities change

### 🍽️ Catering Services
- **Meal service options** for different group sizes
- **Per-person pricing** based on attendee count
- **Flexible meal selection** for various dietary needs

### 💰 Cost Management
- **Real-time cost calculation** across all categories
- **Detailed breakdown** of venue, equipment, and meal costs
- **Total cost summary** with itemized details
- **Interactive quantity controls** for precise budgeting

### 🎨 User Experience
- **Modern, responsive design** with intuitive navigation
- **Smooth transitions** between different sections
- **Professional styling** with clean, business-focused interface
- **Mobile-friendly** layout for on-the-go planning

## 🛠️ Technologies Used

### Frontend
- **React 18.2.0** - Modern UI library for building interactive interfaces
- **Redux Toolkit 2.2.3** - State management for complex application state
- **React Redux 9.1.1** - React bindings for Redux
- **Vite 5.2.0** - Fast build tool and development server

### Development Tools
- **ESLint 8.57.0** - Code linting and quality assurance
- **React ESLint Plugin** - React-specific linting rules
- **Vite Plugin React** - React support for Vite

### Styling
- **CSS3** - Custom styling with modern CSS features
- **Responsive Design** - Mobile-first approach

## 🚀 Getting Started

### Prerequisites
- **Node.js** (version 16 or higher)
- **npm** or **yarn** package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SametDulger/conference_event_planner.git
   cd conference_event_planner
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to view the application

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint for code quality
- `npm run preview` - Preview production build locally

## 📁 Project Structure

```
conference_event_planner/
├── public/                 # Static assets
├── src/
│   ├── assets/            # Images and static files
│   ├── App.jsx            # Main application component
│   ├── App.css            # Main application styles
│   ├── main.jsx           # Application entry point
│   ├── index.css          # Global styles
│   ├── ConferenceEvent.jsx # Main conference planning component
│   ├── ConferenceEvent.css # Conference component styles
│   ├── AboutUs.jsx        # About section component
│   ├── TotalCost.jsx      # Cost calculation component
│   ├── TotalCost.css      # Cost component styles
│   ├── store.js           # Redux store configuration
│   ├── venueSlice.js      # Venue state management
│   ├── avSlice.js         # Audio-visual state management
│   └── mealsSlice.js      # Meals state management
├── package.json           # Project dependencies and scripts
├── vite.config.js         # Vite configuration
├── .eslintrc.cjs          # ESLint configuration
└── README.md              # Project documentation
```

## 🎮 How to Use

### 1. Getting Started
- Click the **"Get Started"** button on the welcome page
- The application will transition to the main planning interface

### 2. Venue Selection
- Navigate to the **"Venue"** section
- Browse available venue options with their capacities and costs
- Use **+** and **-** buttons to adjust quantities
- Note: Auditorium Hall is limited to 3 bookings

### 3. Audio-Visual Equipment
- Go to the **"Add-ons"** section
- Select audio-visual equipment needed for your event
- Adjust quantities using the control buttons

### 4. Meal Planning
- Visit the **"Meals"** section
- Choose catering options for your attendees
- Costs are calculated per person based on your attendee count

### 5. Cost Review
- Click **"Show Details"** to view a detailed breakdown
- Review itemized costs for all selections
- See the total cost calculation in real-time

## 🔧 State Management

The application uses **Redux Toolkit** for state management with three main slices:

### Venue Slice
- Manages venue selections and quantities
- Handles venue-specific business rules (e.g., Auditorium Hall limits)

### AV Slice
- Controls audio-visual equipment selections
- Manages equipment quantities and costs

### Meals Slice
- Handles meal service selections
- Calculates per-person meal costs

## 🎨 Design Features

- **Professional Color Scheme** - Business-appropriate styling
- **Responsive Layout** - Works on desktop, tablet, and mobile
- **Smooth Animations** - Enhanced user experience with transitions
- **Intuitive Navigation** - Clear section organization
- **Visual Feedback** - Interactive elements provide immediate response

## 🤝 Contributing

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add some amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Development Guidelines
- Follow the existing code style and formatting
- Add appropriate comments for complex logic
- Test your changes thoroughly
- Update documentation as needed

## 📝 License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **IBM Developer Skills Network** - Original project inspiration
- **React Community** - Excellent documentation and support
- **Redux Toolkit Team** - Powerful state management solution
- **Vite Team** - Fast and modern build tool

## 📞 Support

For questions, issues, or contributions:
- **Issues**: [GitHub Issues](https://github.com/SametDulger/conference_event_planner/issues)
- **Discussions**: [GitHub Discussions](https://github.com/SametDulger/conference_event_planner/discussions)

---

**Built with ❤️ using React and Redux Toolkit**
