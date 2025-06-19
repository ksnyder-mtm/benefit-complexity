# Benefit-Complexity Matrix Tool

A strategic prioritization tool that helps organizations make data-driven decisions by visualizing projects on a benefit vs. complexity matrix. This interactive web application enables teams to identify quick wins, plan major initiatives, and avoid low-value efforts.

![Benefit-Complexity Matrix](https://img.shields.io/badge/Version-1.0-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## Overview

The Benefit-Complexity Matrix is a powerful decision-making framework that plots initiatives on two axes:
- **Benefit (Y-axis)**: The strategic value, impact, or return on investment
- **Complexity (X-axis)**: The effort, time, resources, and risk required

Projects automatically fall into four quadrants:
- **DO (Quick Wins)**: High benefit, low complexity - prioritize these immediately
- **PLAN (Major Projects)**: High benefit, high complexity - requires careful planning
- **CONSIDER (Fill-ins)**: Low benefit, low complexity - tackle if resources permit
- **PARK (Thankless Tasks)**: Low benefit, high complexity - generally avoid

## Features

### Core Functionality
- **Precision Scoring**: Rate projects using smooth range sliders with decimal precision (1.0-5.0)
- **Real-time Feedback**: Slider values update instantly as you drag, showing exact scores (e.g., 3.7, 4.2)
- **Smart Label Control**: Toggle project labels on/off to reduce visual clutter when many projects are plotted
- **Real-time Visualization**: Projects appear on the matrix immediately as they're scored
- **Driver-based Categorization**: Tag projects with primary drivers:
  - Mission Impact (Red)
  - Efficiency (Green)
  - Smarter Decisions (Blue)
  - Risk Reduction (Orange)
  - Capacity Building (Purple)

### Data Management
- **Flexible Input**: Add projects manually through an intuitive form
- **Bulk Import**: Upload projects via CSV files with decimal score support
- **Export Capabilities**: 
  - CSV export with decimal precision for detailed analysis
  - PDF reports with executive summary and high-resolution matrix visualization
- **Persistent Storage**: All data including decimal scores persists between sessions
- **Enhanced Sample Data**: Load example projects with realistic decimal scores

### User Experience
- **Intuitive Sliders**: Modern range controls with visual markers and real-time value display
- **Clean Matrix View**: Labels hidden by default, show on hover or toggle all visible
- **Progress Tracking**: Visual progress bar shows scoring completion percentage
- **Enhanced Tooltips**: Detailed project information with decimal scores on hover
- **Responsive Design**: Optimized for desktop and tablet devices
- **Zero Installation**: Runs entirely in the browser with no dependencies

## Getting Started

### Quick Start
1. Open `index.html` in a modern web browser
2. Click "Load Sample" to explore with example data, or
3. Click "+ Add Project" to begin adding your own initiatives

### Adding Projects
1. Click the "+ Add Project" button
2. Fill in required fields:
   - Project Name
   - Description
   - Primary Drivers (select at least one)
3. Optionally add a category
4. Click "Add Project"
5. Score the project using precision sliders:
   - **Benefit slider**: Drag to set value between 1.0-5.0 (e.g., 3.7)
   - **Complexity slider**: Drag to set value between 1.0-5.0 (e.g., 2.3)
   - Values update in real-time as you drag

### Matrix Navigation
- **Show/Hide Labels**: Click "Show Labels" to toggle all project names on the matrix
- **Hover for Details**: Hover over any project dot to see name and exact scores
- **Visual Feedback**: Labels appear automatically when hovering over individual projects

### Importing Projects
1. Click "Import CSV"
2. Download the template or prepare a CSV with these columns:
   - `name` (required)
   - `description` (required)
   - `category` (optional)
   - `drivers` (optional, semicolon-separated)
   - `benefit` (optional, decimal values 1.0-5.0)
   - `complexity` (optional, decimal values 1.0-5.0)
3. Select your CSV file
4. Review imported projects with their decimal scores

### Exporting Results
- **CSV Export**: Click "Export CSV" to download all project data
- **PDF Report**: Click "Export PDF" to generate a comprehensive report including:
  - Executive summary
  - Matrix visualization
  - Detailed project lists by quadrant

## Technical Details

### Technology Stack
- **Frontend**: Pure HTML5, CSS3, and Vanilla JavaScript
- **Styling**: CSS Grid, Flexbox, CSS Variables
- **Data Persistence**: Browser LocalStorage
- **PDF Generation**: jsPDF and html2canvas libraries
- **No Backend Required**: Fully client-side application

### Browser Compatibility
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

### File Structure
```
benefit-complexity/
├── index.html          # Main application file
├── README.md          # This documentation
└── sample_data.csv    # Example CSV template (generated on demand)
```

## Use Cases

### Strategic Planning
- Annual planning sessions
- Portfolio prioritization
- Resource allocation decisions
- Digital transformation initiatives

### Project Management
- Sprint planning
- Backlog prioritization
- Risk assessment
- Stakeholder communication

### Innovation Management
- Idea evaluation
- Innovation pipeline management
- R&D project selection
- Investment decisions

## Tips for Effective Use

1. **Be Consistent**: Establish clear criteria for benefit and complexity ratings across your team
2. **Use Decimal Precision**: Take advantage of decimal scoring (e.g., 3.7 vs 4.0) to distinguish between similar projects
3. **Involve Stakeholders**: Use the tool in collaborative sessions for consensus building
4. **Toggle Labels Wisely**: Hide labels for clean overview, show them when discussing specific projects
5. **Regular Reviews**: Update scores as projects evolve and new information becomes available
6. **Focus on Quick Wins**: Start with high-benefit, low-complexity projects for immediate impact
7. **Document Assumptions**: Use descriptions to capture key considerations and scoring rationale

## Privacy & Security

- All data is stored locally in your browser
- No data is transmitted to external servers
- Clear your browser's local storage to remove all data
- Export your data regularly for backup

## Contributing

This is an open-source project. Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software for personal or commercial purposes.

## Support

For issues, questions, or suggestions:
- Open an issue on GitHub
- Review existing documentation
- Check browser console for error messages

## Changelog

### Version 1.2 (Current)
- **🎯 Precision Scoring**: Replaced 1-5 radio buttons with smooth range sliders supporting decimal values (1.0-5.0)
- **👁️ Smart Labels**: Added toggle button to show/hide project labels on matrix for cleaner visualization
- **🎨 Enhanced UX**: Real-time slider feedback with visual markers and live value display
- **📊 Improved Exports**: PDF and CSV exports now include decimal precision formatting
- **🗃️ Better Sample Data**: Enhanced sample projects with realistic decimal scores for demonstration

### Version 1.1
- Matrix visualization improvements
- Enhanced hover tooltips
- Performance optimizations

### Version 1.0
- Initial release
- Core matrix functionality
- CSV import/export
- PDF report generation
- Local storage persistence
- Driver-based categorization
- Basic sample data loading

---

Built with simplicity and effectiveness in mind. No frameworks, no complexity - just a tool that works.
