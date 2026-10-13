# F1 Engineering Lab

An interactive Formula 1 telemetry and race analysis platform that goes beyond displaying racing data. F1 Engineering Lab combines detailed telemetry visualizations with an AI Race Engineer that helps explain where drivers gain or lose time and what the underlying performance data reveals.

## Key Features

- AI Race Engineer — Performance Insights: An interactive, evidence-based analysis feature that lets users select sections of the circuit and receive concise explanations of driver performance differences, supported by sector timing and available telemetry.
- Driver vs Driver Comparison: Compare drivers across laps, sectors, and circuit sections using synchronized visualizations.
- Interactive 2D Circuit Visualizer: Follow driver movement around the circuit and inspect specific sections to explore performance differences.
- Telemetry Analysis: Visualize speed, throttle, braking, RPM, gear, and DRS data.
- Sector-by-Sector Analysis: Identify where time is gained or lost between drivers.
- Race Results and Fastest Laps: Explore session results and lap-time performance.
- Tyre Strategy and Pit Stops: Examine tyre compounds, stints, and pit-stop data.
- Race Conditions: Explore available weather information and race-control events.

## Tech Stack

- React
- Vite
- JavaScript
- Tailwind CSS
- shadcn/ui
- Recharts
- React Query
- OpenF1 API

## Data Source

Historical Formula 1 session, timing, and telemetry data is sourced from the OpenF1 API: https://openf1.org/

Data availability varies by session and endpoint.

## Getting Started

### Prerequisites

- Node.js
- npm
- Git

### Installation

Clone the repository and install dependencies:

```bash
git clone <your-repository-url>
cd F1_telementary
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL shown in your terminal.

Create a production build:

```bash
npm run build
```

## What Makes It Different?

Most telemetry dashboards focus on displaying data. F1 Engineering Lab aims to make that data easier to interpret.

Its AI Race Engineer connects driver comparisons with circuit sections and supporting telemetry, allowing users to investigate performance differences interactively. The goal is to move from simply asking "Who was faster?" to understanding "Where did they gain time, and what does the data show?"

## Project Status

Actively developed as an independent motorsport data-analysis project.

## Disclaimer

F1 Engineering Lab is an independent fan-made project and is not affiliated with or endorsed by Formula 1, the FIA, or any Formula 1 team.
