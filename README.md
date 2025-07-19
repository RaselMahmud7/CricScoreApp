# 🏏 Cricket Scorer

A dynamic, responsive web application for keeping score during cricket matches. Built with React, TypeScript, and modern CSS.

## Features

### Match Setup
- **Team Configuration**: Enter both team names and match format at the start
- **Opening Players**: Set initial batsmen (striker & non-striker) and first bowler
- **Professional Setup**: Complete match configuration before scoring begins

### Live Scoring
- **Live Score Tracking**: Real-time score updates with ball-by-ball tracking
- **Proper Over Counting**: Overs start from 0 and count 6 legal balls per over
- **Cricket Rules Compliance**: Follows ICC rules including no consecutive overs by same bowler
- **Extras Handling**: Wide, No Ball, Bye, and Leg Bye support
- **Team Scorecard**: Complete batting and bowling statistics with professional layout

### Player Management
- **Auto-Prompts**: Automatically prompts for new batsmen after wickets and new bowlers after overs
- **Individual Statistics**: Track detailed stats for each batsman and bowler
- **Current Players**: See who is currently batting and bowling
- **Bowler Records**: Complete bowling statistics including overs, wickets, economy rate

### Match Management
- **Complete Match Management**: Support for both innings with automatic transitions
- **Match Statistics**: Run rate, required run rate, overs remaining, and more
- **Settings Management**: Customizable team names and match format
- **Scorecard Export**: Export match data in JSON, CSV, or text formats
- **Undo Functionality**: Ability to undo the last ball
- **Modern UI**: Beautiful gradient design with smooth animations

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository or navigate to the project directory
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

## How to Use

### Basic Scoring

1. **Runs**: Click on the number buttons (0-6) to score runs
2. **Wickets**: Click the "W" button to record a wicket
3. **Extras**: Use the extras section for wides, no-balls, byes, and leg byes

### Match Setup

1. **Team Names**: Enter both team names at the start
2. **Match Format**: Choose from 5, 10, 20 (T20), or 50 (ODI) overs
3. **Opening Players**: Set initial batsmen (striker & non-striker) and first bowler
4. **Professional Setup**: Complete match configuration before scoring begins

### Player Management

1. **Add Players**: Click the "Players" button to add batsmen and bowlers
2. **Auto-Prompts**: App automatically prompts for new batsmen after wickets and new bowlers after overs
3. **Track Statistics**: Individual player statistics are automatically updated
4. **Current Players**: See who is currently batting and bowling
5. **Bowler Records**: Complete bowling statistics including overs, wickets, economy rate
6. **Cricket Rules**: Bowlers cannot bowl consecutive overs (ICC rules compliance)

### Match Management

1. **Settings**: Click the Settings button to customize team names and match format
2. **Export**: Use the Export Scorecard button to download match data
3. **Undo**: Use the Undo button to remove the last ball
4. **Reset**: Use the Reset Match button to start a new match

### Features

- **Automatic Over Management**: The app automatically tracks overs and balls
- **Innings Transition**: Automatically switches to second innings when first innings is complete
- **Match Completion**: Tracks when the match is complete based on overs or wickets
- **Target Calculation**: Shows target and required run rate for second innings

## Technical Details

### Tech Stack

- **Frontend**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: CSS3 with modern features (Grid, Flexbox, CSS Variables)
- **Icons**: Lucide React
- **State Management**: React Hooks with custom hooks

### Project Structure

```
src/
├── components/          # React components
│   ├── AutoPrompts.tsx
│   ├── BatsmanScores.tsx
│   ├── Controls.tsx
│   ├── ExtrasSection.tsx
│   ├── MatchInfo.tsx
│   ├── MatchSetup.tsx
│   ├── PlayerManagement.tsx
│   ├── RunsGrid.tsx
│   ├── ScoreDisplay.tsx
│   ├── ScorecardExport.tsx
│   ├── TeamScorecard.tsx
│   └── SettingsModal.tsx
├── hooks/              # Custom React hooks
│   └── useCricketMatch.ts
├── types.ts            # TypeScript type definitions
├── App.tsx             # Main application component
├── main.tsx            # Application entry point
└── index.css           # Global styles
```

### Key Features

- **Type Safety**: Full TypeScript implementation for better development experience
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
- **Performance**: Optimized with React hooks and efficient state management
- **Accessibility**: Semantic HTML and keyboard navigation support
- **Modern UI**: Beautiful gradients, animations, and smooth transitions

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the MIT License.

## Support

If you encounter any issues or have questions, please open an issue on the repository.

---

**Enjoy scoring your cricket matches! 🏏** 