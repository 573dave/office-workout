# 💪 5-Day Office Workout

A free, ad-free, single-file web application for guided office workouts. Perfect for desk workers who want to stay active during work hours without leaving the office.

**[Try it now!](https://573dave.github.io/office-workout/)** *(No installation required)*

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

## Features

- **5 Different Daily Routines**: Comprehensive workouts targeting core, glutes, upper body, legs, and cardio
- **Built-in Timers**: Automatic countdown timers with audio notifications when each exercise is complete
- **Progress Tracking**: Your progress is automatically saved in your browser (localStorage)
- **Auto-Advance**: Option to automatically move to the next exercise when timer completes
- **Keyboard Shortcuts**: Navigate quickly with Space, N, P, and number keys
- **Proper Warmup & Cooldown**: Every workout includes 2-minute warmup and cooldown routines
- **Exercise Tutorials**: Links to professional exercise demonstrations from ACE Fitness, NHS Live Well, and Mayo Clinic
- **No Installation Required**: Just open the HTML file in any modern browser
- **Works Offline**: Single-file design means it works without internet (except for external tutorial links)
- **Privacy-First**: No tracking, no analytics, no data collection. Everything stays in your browser.

## Quick Start

### Option 1: Use Online (Recommended)
Visit **[https://573dave.github.io/office-workout/](https://573dave.github.io/office-workout/)** in your browser.

### Option 2: Download and Use Locally
1. Download `office-workout.html` from this repository
2. Open the file in any modern web browser
3. Bookmark it for easy access

### Option 3: Self-Host
```bash
# Clone the repository
git clone https://github.com/573dave/office-workout.git

# Serve with any static file server
cd office-workout
python -m http.server 8000
# Open http://localhost:8000/office-workout.html
```

## How to Use

1. **Select a Day**: Choose from Day 1-5 using the dropdown or press keys 1-5
2. **Start the Workout**: Click "Start" on the warmup or press Space
3. **Follow Along**: Complete each exercise for the timer duration
4. **Auto-Advance**: Enable the toggle to automatically move to the next step
5. **Track Progress**: Your completed steps are saved automatically
6. **Reset When Ready**: Use "Reset Progress" to start fresh

### Keyboard Shortcuts

- **Space**: Start/pause the current step timer
- **N**: Move to next step
- **P**: Move to previous step
- **1-5**: Switch between Day 1-5

## The 5-Day Plan

### Day 1 – Core & Glutes
- Dead Bug (40s)
- Glute Bridge (40s)
- Bird Dog (40s)
- Wall Sit (30s)

### Day 2 – Upper Body & Posture
- Incline Push-Up (40s)
- Chair Dips (30s)
- Plank (30s)
- Bodyweight Good Morning (40s)

### Day 3 – Legs & Balance
- Bodyweight Squat (45s)
- Reverse Lunge (45s)
- Step-Ups (45s)
- Standing Calf Raises (40s)

### Day 4 – Cardio & Core
- Step-Ups Fast (45s)
- Incline Mountain Climbers (40s)
- Dead Bug (40s)
- Side Plank (30s each side)

### Day 5 – Mixed Strength
- Bodyweight Squat (45s)
- Glute Bridge (40s)
- Bodyweight Good Morning (40s)
- Plank (30s)
- Side Plank (30s each side)

Each workout includes:
- 2-minute warmup
- 30-second rest periods between exercises
- 2-minute cooldown & stretch
- **Total time: 15-30 minutes**

## Technical Details

- **Single-file architecture**: The entire application is contained in one HTML file
- **No dependencies**: Pure HTML, CSS, and vanilla JavaScript
- **localStorage**: Progress and settings are persisted locally
- **Responsive design**: Works on desktop, tablet, and mobile
- **Accessibility**: ARIA labels and keyboard navigation support
- **Dark theme**: Eye-friendly color scheme suitable for office environments

## Development

This is a single-file application, so development is straightforward:

1. Edit `office-workout.html` in your favorite text editor
2. Open it in a browser to test
3. No build process or dependencies required

For more details about the code architecture, see [CLAUDE.md](CLAUDE.md).

## Deployment on GitHub Pages

To deploy your own version:

1. Fork this repository
2. Go to repository Settings → Pages
3. Select source: "Deploy from a branch"
4. Select branch: `main` (or `master`) and folder: `/ (root)`
5. Click Save
6. Your site will be available at `https://yourusername.github.io/office-workout/`

## Contributing

Contributions are welcome! Here are some ideas:

- Add more workout routines
- Improve exercise instructions
- Add more customization options
- Enhance accessibility features
- Fix bugs or improve performance

Please open an issue or submit a pull request.

## License

MIT License - feel free to use, modify, and distribute this project.

See [LICENSE](LICENSE) for full details.

## Credits

- **Created by**: [573dave](https://github.com/573dave)
- **Exercise tutorials from**: ACE Fitness, NHS Live Well, Mayo Clinic
- **Inspired by**: The need for simple, accessible office fitness solutions

## Support

If you find this useful, please:
- ⭐ Star this repository
- 🐛 Report bugs via [GitHub Issues](https://github.com/573dave/office-workout/issues)
- 💡 Suggest features or improvements
- 🔀 Fork and customize for your needs

---

**Stay healthy and keep moving!** 💪
