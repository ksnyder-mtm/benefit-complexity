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
- **Interactive Scoring**: Rate projects on benefit (1-5) and complexity (1-5) scales
- **Real-time Visualization**: Projects appear on the matrix as soon as they're scored
- **Driver-based Categorization**: Tag projects with primary drivers:
  - Mission Impact (Red)
  - Efficiency (Green)
  - Smarter Decisions (Blue)
  - Risk Reduction (Orange)
  - Capacity Building (Purple)

### Data Management
- **Flexible Input**: Add projects manually through an intuitive form
- **Bulk Import**: Upload projects via CSV files
- **Export Capabilities**: 
  - CSV export for further analysis
  - PDF reports with executive summary and matrix visualization
- **Local Storage**: All data persists between sessions
- **Sample Data**: Load example projects to explore functionality

### User Experience
- **Progress Tracking**: Visual progress bar shows scoring completion
- **Hover Details**: See project information by hovering over matrix points
- **Responsive Design**: Works on desktop and tablet devices
- **No Installation Required**: Runs entirely in the browser

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
5. Score the project using the 1-5 scale for both benefit and complexity

### Importing Projects
1. Click "Import CSV"
2. Download the template or prepare a CSV with these columns:
   - `name` (required)
   - `description` (required)
   - `category` (optional)
   - `drivers` (optional, semicolon-separated)
   - `benefit` (optional, 1-5)
   - `complexity` (optional, 1-5)
3. Select your CSV file
4. Review imported projects

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

1. **Be Consistent**: Establish clear criteria for benefit and complexity ratings
2. **Involve Stakeholders**: Use the tool in collaborative sessions
3. **Regular Reviews**: Update scores as projects evolve
4. **Focus on Quick Wins**: Start with high-benefit, low-complexity projects
5. **Document Assumptions**: Use descriptions to capture key considerations

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

### Version 1.0 (Current)
- Initial release
- Core matrix functionality
- CSV import/export
- PDF report generation
- Local storage persistence
- Driver-based categorization
- Sample data loading

---

Built with simplicity and effectiveness in mind. No frameworks, no complexity - just a tool that works.
