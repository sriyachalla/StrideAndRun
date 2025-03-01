# StrideAndRun
Run Club Website

# StrideAndRun Runners Database

A simple website to display and manage the StrideAndRun runners community database. This project uses GitHub Pages to host a responsive, interactive table of runner information.

## Features

- 📊 Complete runners database with detailed information
- 🔍 Search functionality to quickly find runners
- 🏷️ Filter runners by founder status
- 📱 Responsive design works on mobile and desktop
- 📈 Quick statistics overview
- 🔄 Sortable table columns

## Setup Instructions

### Option 1: Quick Setup with GitHub Pages

1. **Fork or clone this repository** to your GitHub account
2. **Rename the repository** to `yourusername.github.io` for your primary GitHub Pages site, or keep any name for a project site
3. **Enable GitHub Pages** in the repository settings:
   - Go to Settings > Pages
   - Select "main" branch as the source
   - Click Save
4. **Your site will be published** at `https://yourusername.github.io/` or `https://yourusername.github.io/repository-name/`

### Option 2: Local Development

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/yourusername/strideandrun.git
   cd strideandrun
   ```

2. **Open the project** in your favorite code editor

3. **Test locally** by opening `index.html` in your browser

4. **Make your changes** and commit them:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

## Customizing the Database

To update the runner information:

1. Open `index.html` in a code editor
2. Locate the `runnersData` array in the JavaScript section
3. Modify the existing entries or add new ones following the same format
4. Save the file and push the changes to GitHub

## Adding All Runners

The current version includes a subset of runners. To add all runners from your complete database:

1. Copy your full runner data into the `runnersData` array format
2. Make sure each entry follows the structure:
   ```javascript
   { 
     name: "Runner Name", 
     attendance: 0, 
     friendsBrought: 0, 
     runHistory: "Run Events", 
     role: "Role Description", 
     contact: "contact@email.com", 
     founderStatus: "✅|pending|", 
     pace: "0:00", 
     streak: 0, 
     notes: "Additional notes" 
   }
   ```

## Future Enhancements

Potential future improvements:

- Add data export functionality (CSV, Excel)
- Implement runner profile pages
- Add run event history page
- Integrate with a backend for dynamic data updates
- Add user authentication for admin features

## License

This project is available for StrideAndRun internal use
