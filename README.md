# Meal Planner Portal

A comprehensive meal planning system built with React for managing multiple homes' meal schedules, generating shopping lists, and creating prep instructions.

## Features

- Multi-home meal planning with dietary restriction support
- Drag-and-drop meal organization interface
- Automated PDF generation for menus
- Shopping list compilation
- Prep instructions for kitchen staff
- Meal popularity analytics

## Setup

1. Clone the repository:
```bash
git clone https://github.com/rirachii/meal-planner-portal.git
cd meal-planner-portal
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

## Project Structure

```
src/
  ├── components/           # React components
  │   ├── MenuGenerator.js # Main component
  │   └── ui/              # UI components
  ├── data/                # Sample data files
  │   ├── meals.json
  │   └── instructions.json
  ├── App.js
  └── index.js
```

## Usage

1. Upload the Master Spreadsheet containing home information
2. Select a home from the dropdown
3. Plan meals using the drag-and-drop interface
4. Generate menu PDFs
5. Compile shopping and prep lists
6. Export PDFs for kitchen staff

## Dependencies

- React
- react-beautiful-dnd
- recharts
- jsPDF
- XLSX
- TailwindCSS
- Radix UI

## License

MIT