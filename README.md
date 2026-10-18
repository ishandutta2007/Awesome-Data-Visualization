# Awesome-Data-Visualization

# Top Data Visualization Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Declarative Charting, Grammar of Graphics & High-Performance Rendering*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Visualization**. These tools enable developers to transform raw datasets into interactive charts, maps, and exploratory graphics—from low-level primitives that give complete control over every pixel to high-level grammars that describe visual intent in a single statement.

**Examples** include D3.js, Chart.js, Apache ECharts, Highcharts, Plotly.js, Recharts, Nivo, ApexCharts, G2, and CanvasJS (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, declarative charting, and open visualization primitives—ideal for frontend developers, data engineers, and organizations seeking transparent, vendor-independent data visualization.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Highcharts (Commercial License)**  
  **Pure JavaScript/TypeScript charting library** trusted by **80 of the world's 100 largest companies** . **Core library is free for personal and non-commercial use**; commercial license required for revenue-generating applications. **Zero dependencies**, **ES6 module support** with tree shaking, **WebGL/WebGPU** for millions of data points, and **built-in accessibility** (keyboard navigation, screen reader support, audio charts) . **Best for**: enterprises wanting a battle-tested, feature-complete charting library with commercial support.

## Open-Source GitHub Projects

- **[D3.js](https://github.com/d3/d3)**  
  **The foundational JavaScript library for visualizing data with HTML, SVG, and CSS** (ISC) — **the low-level toolkit every other library builds on or learns from**. **Not a charting library in the traditional sense**—it binds data to the DOM and applies data-driven transformations. **The most powerful and flexible visualization library**—nothing else matches its control . **The learning curve is steep**, but it enables custom visualizations that no other library can produce. **Best for**: novel chart types, bespoke visualizations, and teams willing to invest in learning the primitives.

- **[Chart.js](https://github.com/chartjs/Chart.js)**  
  **Simple yet flexible JavaScript charting library** (MIT) — **the fastest path to beautiful charts**. **Canvas-based rendering** with **8 chart types** (line, bar, radar, pie, doughnut, polar area, bubble, scatter), **smooth animations**, **responsive by default**, and **extensive customization** . **Works with React, Vue, and Vanilla JS** . **CDN drop-in** with minimal configuration. **Best for**: dashboards, admin panels, and teams that want charts rendering in minutes, not days.

- **[Apache ECharts](https://github.com/apache/echarts)**  
  **A powerful, interactive charting and data visualization library for browser** (Apache-2.0) — **the feature-complete enterprise choice**. **ECharts 6.0** adds a **new theme**, **chord series**, and **matrix coordinate system** with declarative layout across grid, geo, and polar . **The charting engine powering Apache Superset**. **Best for**: complex enterprise dashboards requiring broad chart type coverage and performance with large datasets.

- **[Plotly.js](https://github.com/plotly/plotly.js)**  
  **Open-source JavaScript charting library behind Plotly and Dash** (MIT) — **the scientific charting choice** . **Dozens of chart types**: **statistical charts, 3D graphs, scientific charts, SVG and tile maps, financial charts** . **Powers Plotly.py and Plotly.R** in their respective ecosystems. **MathJax integration** renders mathematical expressions within plots . **Best for**: scientific, statistical, and financial visualizations.

- **[Recharts](https://github.com/recharts/recharts)**  
  **Redefined chart library built with React and D3** (MIT) — **the React-native choice** . **Declarative components** (`<LineChart>`, `<Line>`, `<XAxis>`) compose like React itself. **Native SVG support**, **lightweight with minimal dependencies** . **27,300+ GitHub stars** and **used by 857,000+ repositories** . **Best for**: React applications where charts should feel like native components, not foreign libraries.

- **[Nivo](https://github.com/plouc/nivo)**  
  **Rich set of dataviz components built on top of D3 and React** (MIT) — **the visually polished React choice** . **SVG, HTML, and Canvas rendering** options, **server-side rendering**, **motion/transitions powered by react-spring**, **patterns and gradients**, **theming**, and **responsive charts** . **Best for**: React applications where aesthetics matter—Nivo charts look great with zero configuration.

- **[ApexCharts](https://github.com/apexcharts/apexcharts.js)**  
  **Modern & interactive open-source charts** (MIT) — **the animation-focused choice** . **SVG-based** with **beautiful animations** and **responsive design**. **Tree-shakeable core** (`apexcharts.core.js` at **136,921 B gzipped** vs. **252,005 B** for the full bundle) . **Unit chart** with **39 shapes** a count can take (heart, house, globe, checkmark, etc.) . **Best for**: modern dashboards where animation and visual polish matter.

- **[G2 (AntV)](https://github.com/antvis/G2)**  
  **A highly interactive data-driven visualization grammar** (MIT) — **the grammar-of-graphics choice** . **Stable grammar of graphics**—map data to graphics to draw any chart. **New grammar of interaction** with Trigger and Action mechanisms. **Advanced View module** for multi-dimension data analysis. **Dual-engine rendering**—switch Canvas and SVG freely. **Fully embraces TypeScript** with complete type definitions . **Best for**: developers wanting a declarative grammar with fine-grained control over interaction and rendering.

- **[CanvasJS](https://github.com/tsur/canvasjs)**  
  **Easy to use JavaScript & HTML5 Charts library built on Canvas element** — **the performance-focused choice** . **Runs across devices** including iPhone, iPad, Android, and Windows. **Over 10x faster than conventional Flash and SVG Charts** . **Note**: **Free for personal use, commercial license required** for commercial use . **Best for**: performance-sensitive dashboards where Canvas rendering speed matters.

### Additional Strong Open-Source Options

- **Visx (Airbnb)** — Collection of reusable low-level visualization components (MIT). **The middle ground between D3 and Recharts**—provides D3 primitives as React components without forcing a chart abstraction. **Best for**: teams wanting D3-level control with React idioms.
- **Victory** — Composable React components for interactive data visualizations (MIT). **Cross-platform**—works with React, React Native, and web. **Best for**: teams building custom visualizations from composable primitives.
- **uPlot** — Small, fast chart for time series, lines, areas, ohlc & bars (MIT). **The fastest charting library for large datasets**—handles millions of data points where other libraries choke. **Best for**: real-time monitoring and financial trading dashboards.
- **Observable Plot** — Concise API for exploratory data visualization (ISC). **The most modern D3 abstraction**—declarative marks and scales with sensible defaults. **Best for**: exploratory data analysis in notebooks.
- Community **n8n** workflows for chart data pipeline automation and dashboard alerting.

**Frameworks for building custom systems**: Combine **D3.js** for custom visualizations with **Recharts** or **Nivo** for React components, **Apache ECharts** for complex enterprise dashboards, **uPlot** for high-performance time series, and **G2** for grammar-of-graphics control—creating a comprehensive visualization stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Data visualization libraries must be evaluated for **rendering technology** (SVG vs. Canvas), **performance** with your dataset size, and **licensing** (MIT vs. commercial). **Highcharts and CanvasJS require commercial licenses** for revenue-generating use.
- **The abstraction level is the key decision.** **D3.js** for **maximum control** and custom visualizations . **Recharts/Nivo** for **declarative React components** . **Chart.js** for the **fastest path to charts** . **ECharts** for **feature completeness** . **Choose based on how much control you need versus how fast you want to ship.**
- **Rendering technology matters for performance.** **SVG** (Recharts, Nivo, ApexCharts) for accessibility and crisp rendering at any zoom. **Canvas** (Chart.js, ECharts, uPlot) for large datasets and animation performance. **uPlot handles millions of points** where SVG libraries choke.
- **The "grammar of graphics" distinction is real.** **G2** provides a **declarative grammar**—describe the visual appearance in one statement and let the library handle the rendering . **D3.js** provides **primitives**—you build the grammar yourself. **Recharts** provides **components**—you compose pre-built pieces. **Choose based on whether you want to describe, build, or compose.**
- **Self-hosted open-source solutions require proper bundling, tree-shaking, and performance optimization.** **Charting libraries can bloat bundles**—choose lightweight options (Chart.js, uPlot) when bundle size matters.

---

**Made for frontend developers, data engineers, and organizations building transparent visualization solutions.**  
Let's make Data Visualization more open, data-driven, and expressive.
