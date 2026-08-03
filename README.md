# 📊 autodesk-report-hub - View and manage your Autodesk reports

[![Download autodesk-report-hub](https://img.shields.io/badge/Download-autodesk--report--hub-blue?style=for-the-badge&logo=github)](https://github.com/Heavierthanair-whitsuntuesday761/autodesk-report-hub)

## 📥 How to Download and Run

1. Visit the download page: [https://github.com/Heavierthanair-whitsuntuesday761/autodesk-report-hub](https://github.com/Heavierthanair-whitsuntuesday761/autodesk-report-hub)
2. Click the green "Code" button.
3. Select "Download ZIP" from the menu.
4. Save the ZIP file to your computer (your Downloads folder works best).
5. Right-click the ZIP file and choose "Extract All".
6. Pick a folder to extract the files into (like your Desktop).
7. Open the extracted folder.
8. Double-click the file named `index.html`.
9. The report hub opens in your web browser.

You do not need to install any software. The app runs in your browser.

## 🎯 What This Tool Does

autodesk-report-hub is a browser-based tool that shows Autodesk reporting content in one place. You can view reports, check data, and work with project information without opening multiple programs.

Key tasks you can do:

- View Autodesk project reports
- Browse report summaries
- Check task status and progress
- Review project timelines
- See resource usage data
- Export report data to view offline

## 🖥️ System Requirements

Your computer needs:

- Windows 7, 8, 10, or 11
- Any modern web browser (Chrome, Edge, Firefox, or Safari)
- 2 GB of RAM (4 GB recommended)
- 50 MB of free hard drive space
- Internet connection for initial download

The tool works on Mac and Linux computers too. The steps to run it are the same.

## 📖 Getting Started Guide

### First Time Use

1. Open the `index.html` file in your browser.
2. You see the main dashboard with a list of reports.
3. Click any report name to open it.
4. Use the search bar at the top to find specific reports.
5. Click the filter buttons to sort by date, project, or status.

### Main Screen Layout

- **Top bar**: Shows the tool name and has a search box.
- **Left panel**: Lists all available reports.
- **Center area**: Shows the report you selected.
- **Right panel**: Shows details about the selected item.

### Common Actions

**View a report**: Click the report name in the list. The report opens in the center area.

**Search for a report**: Type a word or phrase in the search box. The list filters as you type.

**Filter reports**: Click the filter buttons (Date, Project, Status) above the report list.

**Export a report**: Click the "Export" button above the report. Choose PDF or CSV format. The file saves to your Downloads folder.

**Refresh data**: Click the "Refresh" button to get the latest information.

## 🔧 Customization Options

You can change how the tool looks and works.

### Change the Theme

1. Open the `settings` folder in the extracted files.
2. Open the file `theme.css` with Notepad.
3. Find the line that says `--background-color: #ffffff;`
4. Change `#ffffff` to your preferred color code.
5. Save the file.
6. Refresh the `index.html` page in your browser.

### Add Your Company Logo

1. Place your logo image file (PNG or JPG) in the `images` folder.
2. Open the `settings` folder.
3. Open the file `config.js` with Notepad.
4. Find the line that says `logo: "default-logo.png"`
5. Change it to `logo: "your-logo-filename.png"`
6. Save the file.
7. Refresh the page.

### Set Default View

1. Open the `settings` folder.
2. Open `config.js` with Notepad.
3. Find the line `defaultView: "list"`
4. Change `list` to `grid` or `table`.
5. Save the file.
6. Refresh the page.

## 🗂️ Report Types

The tool supports these report formats:

- **Project summaries**: Overview of project status, budget, and timeline.
- **Task reports**: Details about individual tasks and their completion.
- **Resource reports**: Shows who works on what and for how long.
- **Time reports**: Tracks hours spent on projects.
- **Cost reports**: Shows expenses and budget usage.
- **Progress reports**: Visual progress bars and completion percentages.

## 📂 File Structure

When you extract the ZIP file, you see these folders and files:

```
autodesk-report-hub/
├── index.html          (Main file to open)
├── css/                (Style files)
│   └── theme.css       (Colors and layout)
├── js/                 (Script files)
│   └── config.js       (Settings)
├── images/             (Picture files)
│   └── logo.png        (Default logo)
├── data/               (Report data files)
│   └── reports.json    (Example report data)
└── docs/               (Help files)
    └── help.html       (Built-in help page)
```

## 🔄 How to Update

### Check for Updates

1. Visit the download page: [https://github.com/Heavierthanair-whitsuntuesday761/autodesk-report-hub](https://github.com/Heavierthanair-whitsuntuesday761/autodesk-report-hub)
2. Look at the "Releases" section on the right side.
3. Compare the version number with your current version (shown at the bottom of the tool).

### Install an Update

1. Download the newest ZIP file from the release page.
2. Extract it to a new folder.
3. Copy any custom files (like your logo or config.js changes) from your old folder to the new folder.
4. Start using the new `index.html` file.
5. Delete the old folder after you confirm the update works.

## ❓ Troubleshooting

### The tool does not open

Make sure you extracted all files from the ZIP. Double-click `index.html` directly. If nothing happens, right-click the file and choose "Open with" then select your browser.

### Reports show no data

The tool comes with example data. To use your own data:

1. Open the `data` folder.
2. Open `reports.json` with Notepad.
3. Replace the example data with your report data.
4. Follow the same format (JSON structure).
5. Save the file.
6. Refresh the page.

### The layout looks wrong

Your browser zoom might be off. Press `Ctrl + 0` (Windows) or `Cmd + 0` (Mac) to reset zoom. If the issue continues, clear your browser cache and refresh.

### Search does not find reports

Check that your report data files are in the correct folder. Make sure the data follows the expected format. Open the browser console (press F12) to see any error messages.

### Export button does nothing

Your browser may block automatic downloads. Check your browser settings and allow downloads from this page. Try right-clicking the Export button and selecting "Save link as".

## ⚙️ Advanced Settings

These settings are in the `config.js` file.

| Setting | What it does | Default value |
|---------|--------------|---------------|
| `pageTitle` | Changes the browser tab name | "Autodesk Report Hub" |
| `refreshInterval` | Auto-refresh time in seconds | 60 |
| `itemsPerPage` | How many reports show per page | 20 |
| `enableAnimations` | Turns animations on or off | true |
| `dateFormat` | How dates display | "MM/DD/YYYY" |
| `language` | Sets the interface language | "en" |

To change a setting, open `config.js`, find the setting name, change the value after the colon, save the file, and refresh the page.

## 📄 License

This tool is free to use. You can modify it for your needs. See the `LICENSE` file in the downloaded folder for details.

Keywords: autodesk, report, hub, viewer, dashboard, project management, Windows, browser-based, HTML