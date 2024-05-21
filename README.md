# Jenkins Infra Statistics UI Implementation

✈️ [Follow Sagar Gaud](https://www.linkedin.com/in/sagargaud332/)

## Project Overview
The goal of this project is to enhance the current GitHub Pages-based UI for Jenkins Infra Statistics into a comprehensive, user-friendly, and fully-featured website. This website will offer detailed visualizations of Jenkins infrastructure statistics, providing users with insightful data presented in an accessible manner.

## Project Components
1. **Statistics in Detail**: Provide a detailed breakdown of various Jenkins statistics.
2. **Plugin Installation Trend**: Visualize the installation trends of Jenkins plugins over time.
3. **Plugin Versions by Jenkins Version**: Show the distribution of plugin versions across different Jenkins versions.
4. **Jenkins Plugin Dependency Graph**: Illustrate the dependencies between different Jenkins plugins.

## Skills to Improve
- JavaScript/TypeScript
- HTML/CSS
- Dashboard and Data Visualization
- UI/UX Design

## Tools and Technologies
- **Frontend Framework**: React (preferably with Gatsby.js or Vite.js), but Angular or Vue can also be considered.
- **Plotting Libraries**: Plotly.js and Apache ECharts.
- **Data Source**: Existing data available at [Jenkins Infra Statistics](https://stats.jenkins.io/).

## Rationale
The current GitHub Pages site is basic and lacks an intuitive user interface. Enhancing the UI will improve user experience, making it easier for users to interact with and understand the data.

## Implementation Plan
### 1. Design Phase
- **Research**: Study the current statistics site and understand the data available.
- **Wireframing**: Create wireframes for the new UI, focusing on user-friendly navigation and layout.
- **UI/UX Design**: Develop design mockups using tools like Figma or Adobe XD.

### 2. Development Phase
- **Setup**: Initialize the project using the chosen frontend framework (React with Gatsby.js or Vite.js).
- **Component Development**: 
  - Develop individual components for each major section (Statistics, Plugin Trends, Versions, Dependency Graph).
  - Ensure reusability and modularity of components.
- **Data Integration**: 
  - Fetch and integrate data from the existing site.
  - Use Plotly.js and ECharts to visualize the data.
- **Styling**: 
  - Apply styles using CSS or a preprocessor like SASS.
  - Ensure responsiveness for various devices.

### 3. Testing Phase
- **Unit Testing**: Write unit tests for individual components.
- **Integration Testing**: Ensure that components interact correctly.
- **User Testing**: Gather feedback from potential users and make necessary adjustments.

### 4. Deployment Phase
- **Build and Deploy**: Optimize the build and deploy the site to a suitable hosting platform.
- **Documentation**: Write comprehensive documentation for future contributors and users.

## Project Timeline
The project is expected to be completed in approximately 175 hours, divided into the following phases:
- **Design Phase**: 35 hours
- **Development Phase**: 90 hours
- **Testing Phase**: 25 hours
- **Deployment Phase**: 25 hours

## Contributors and Mentors
- **Contributors**: 
  - Kris Stern
  - Vandit Singh
  - Hervé Le Meur
- **Mentors**: 
  - Kris Stern
  - Vandit Singh
  - Hervé Le Meur

## Communication Channels
- **Gitter**: For real-time communication and queries.
- **Meetings**: Regular meetings to discuss progress and roadblocks.

## Resources
- **Jenkins GSoC Page**: Documentation and application guidelines.
- **Jenkins Newcomer Landing Page**: Participate and contribute to Jenkins.
- **Newbie-friendly Issues**: List of organization-wide newbie-friendly issues.

## Project Repository README

```markdown
# Jenkins Infra Statistics UI

## Project Overview
This project aims to transform the current GitHub Pages-based UI for Jenkins Infra Statistics into a comprehensive, user-friendly, and fully-featured website. The site will offer detailed visualizations of Jenkins infrastructure statistics, providing users with insightful data presented in an accessible manner.

## Project Components
- **Statistics in Detail**
- **Plugin Installation Trend**
- **Plugin Versions by Jenkins Version**
- **Jenkins Plugin Dependency Graph**

## Technology Stack
- **Frontend Framework**: React (Gatsby.js or Vite.js)
- **Plotting Libraries**: Plotly.js, Apache ECharts
- **Languages**: JavaScript/TypeScript, HTML, CSS

## Getting Started

### Prerequisites
- Node.js
- npm or yarn

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/jenkins-infra-statistics-ui.git
    cd jenkins-infra-statistics-ui
    ```
2. Install dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

### Running the Project
To start the development server:
```bash
npm start
# or
yarn start
```

### Building the Project
To create a production build:
```bash
npm run build
# or
yarn build
```

## Contributing
We welcome contributions! Please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions, please reach out to:
- Kris Stern
- Vandit Singh
- Hervé Le Meur
```
