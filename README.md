# Hackbyte Preparation

### Overview
This repository contains all resources and files created during the Hackbyte event, jointly organized by Loblaws and Microsoft.

### Resources

- [**Event Photos**](https://photos.google.com/share/AF1QipM34X23VVCab81exg6ZStDZJ6x4YkGvsZpjbzFI4ldtO-htqoneQuuLDEZ3WngBhg?key=WDA5aTRXUXJ1THBSTkRqblBfZG9hMlYySnhPZ29n): A collection of moments from the event.

#### Meet Our Team on LinkedIn
- [Sundeep Pothula](https://www.linkedin.com/in/sundeeppothula/) - Specialized in image labeling and modeling with Azure.
- [Mubtaseem Zaman](https://www.linkedin.com/in/mubtaseemz/?originalSubdomain=ca) - Core backend development and deployment expert.
- [Amit Singh](https://www.linkedin.com/in/mubtaseemz/?originalSubdomain=ca) - Focused on image labeling and modeling with Azure.
- [Novina Wong](https://www.linkedin.com/in/novinawong/) - Front End Developer and UI/UX Designer.
- [Weqi Liu](https://www.linkedin.com/in/bblwq/) - Front End Developer.

### Project Phases

#### Phase 1: Business Problem Framing
- Brainstorming and ideation sessions.
- Client communication to identify key challenges.
- Formulating the best plan with team feedback.
- [Problem documentation (Google Drive)](https://docs.google.com/document/d/1oO5qgP7A-9FBh9zGr0-IfWLH5IveH4zZ1WJUxow8O0M/edit).

#### Phase 2: Layout and Wireframing
- Strategic planning for task distribution.
- [Developed a front-end web app, hosted on GitHub Pages](https://novinaw.github.io/user-list.html).

#### Phase 3: Data Preparation
- Creating a synthetic dataset and manually labeling it with Microsoft Azure Custom Vision API.
- [Dataset, event, and team photos (Google Drive)](https://drive.google.com/drive/folders/1m75WL8UZR0es2vJ1p69KnRd45iM6l1m9?usp=sharing).

#### Phase 4: Modeling
- Developed five versions of the model with the synthetically created and manually labeled data using Azure Custom Vision API.

#### Phase 5: Deployment
- Successful deployment on Microsoft Custom Vision API.
- Continued dataset building by capturing and labeling product images.
- Impressive model performance after seven iterations.

### Model Performance Metrics
The model showed outstanding results, as evidenced by the following metrics:

| Tag                  | Precision | Recall | A.P  | Image Count |
|----------------------|-----------|--------|------|-------------|
| Chocomini            | 96.8%     | 81.1%  | 84.4 | 100         |
| Vegetable Baby Food  | 94.7%     | 72.0%  | 86.9 | 110         |
| Apple Baby Food      | 94.6%     | 62.5%  | 82.0 | 153         |

### Conclusion
Our solution offers multiple benefits:
1. Streamlines the process for in-store shoppers and pickers.
2. Provides real-time item availability from the latest shelf images.
3. Eliminates the need for extensive camera installations by leveraging crowd-sourced data.

This innovative approach simplifies the process of locating and checking item availability, utilizing advanced computer vision techniques and Azure Custom Vision.

