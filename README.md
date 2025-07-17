# AI-Powered QA Agent Dashboard

A comprehensive frontend testing automation platform that demonstrates AI-powered test case generation, execution, and reporting.

## Features

- **Video Processing**: Upload and analyze how-to videos to extract user workflows
- **AI Test Generation**: Automatically generate comprehensive test cases covering:
  - Core user flows
  - Edge cases and boundary conditions
  - Cross-browser and mobile variants
  - Accessibility checks
  - Performance considerations
- **Test Execution**: Simulate Playwright test execution with real-time progress
- **Results Dashboard**: Detailed reporting with screenshots, logs, and analytics

## Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Extract the project files to your desired directory
2. Open terminal/command prompt in the project directory
3. Install dependencies:
   ```bash
   npm install
   ```

### Running the Demo

Start the development server:
```bash
npm run dev
```

The application will be available at: **http://localhost:5173**

### Demo Flow

1. **Video Upload Tab**: 
   - Click "Upload Video" to simulate video processing
   - Watch the AI extract transcriptions and segment steps

2. **Test Generation Tab**:
   - Click "Generate Test Cases" to see AI-powered test creation
   - Review different test categories (Core Flows, Edge Cases, Accessibility)

3. **Test Execution Tab**:
   - Click "Run All Tests" to simulate Playwright execution
   - Watch real-time test progress and status updates

4. **Results & Reports Tab**:
   - View comprehensive test results
   - See pass/fail statistics and detailed error reports
   - Export functionality for sharing results

### Project Structure

```
src/
├── components/
│   └── Dashboard.tsx     # Main dashboard component
├── App.tsx              # Root application component
├── main.tsx            # Application entry point
└── index.css           # Global styles with Tailwind CSS
```

### Technologies Used

- **React 18** with TypeScript
- **Tailwind CSS** for styling
- **Lucide React** for icons
- **Vite** for development and building

### Building for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.

## Demo Tips

- The application uses simulated data and workflows for demonstration
- All interactions are designed to showcase the complete QA automation pipeline
- Progress indicators and animations make the demo engaging
- Responsive design works on all screen sizes for presentations
