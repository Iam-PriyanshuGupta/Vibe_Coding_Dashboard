Vibe Coding: Enterprise Adoption & Impact Dashboard

An interactive, single-page web application that visualizes the complex landscape of AI-assisted coding ("vibe coding") in enterprise environments. This dashboard synthesizes key findings from recent industry reports (2024-2025) into an easily digestible and explorable format.

The application moves beyond a static infographic, providing a dynamic experience with interactive charts and navigable sections, allowing users to delve into the nuances of developer productivity, sentiment, and the challenges of enterprise adoption.

Key Features:
- Interactive Dashboard UI: A clean, modern interface with a persistent sidebar navigation for seamless exploration of different data facets.
- Thematic Sections: The report's data is organized into logical, user-friendly sections: Overview, Productivity, Sentiment, Challenges, Human Factor, and References.
- Dynamic & Responsive Charts: All visualizations are rendered using Chart.js and are fully responsive, providing an optimal viewing experience on desktops, tablets, and mobile devices.
- Interactive Elements: Users can engage with the data through UI elements like chart toggles and content tabs to compare different data points and reveal detailed information.
- Single-File Application: The entire dashboard is contained within a single HTML file, requiring no build steps, dependencies, or web server to run.

Technology Stack:
- HTML5: For the semantic structure of the application.
- Tailwind CSS: For the entire utility-first styling and responsive design. Loaded via CDN.
- Vanilla JavaScript: For all interactivity, including navigation, state management, DOM manipulation, and dynamic chart updates.
- Chart.js: For creating all the beautiful, responsive, and interactive data visualizations. Loaded via CDN.

Information Architecture:
- Sidebar Navigation: A fixed sidebar was chosen to provide a constant and intuitive means of navigating the key themes. This pattern is common in web applications and allows users to jump between topics without losing context.
- Card-Based Layout: Each section uses a card-based layout to segment information into logical, visually distinct chunks. This enhances scannability and prevents the user from being overwhelmed by data.
- User-Driven Exploration: By breaking the content into thematic sections, the application empowers users to explore the topics that are most relevant to them, rather than forcing them through a linear narrative.

Setup and Usage:
- Clone this repository or download the vibe_coding_dashboard_v2.html file.
- Open the vibe_coding_dashboard_v2.html file in any modern web browser (like Chrome, Firefox, Safari, or Edge).
- That's it! The application is fully self-contained and will run locally without any issues.

Data Sources:
The information and statistics presented in this dashboard are synthesized from a variety of authoritative industry reports and surveys, including:
- AI Coding Assistant Trial: UK Public Sector Findings Report
- The 2024 & 2025 Stack Overflow Developer Surveys
- METR's Report: "Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity"
- Various enterprise and market analyses from firms like Softura, Netcorp, and IT Revolution.

License:
This project is distributed under the MIT License. See the LICENSE file for more information.
