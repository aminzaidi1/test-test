# Social Determinants of Health (SDoH) Dashboard Improvement Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Original Code Issues and Initial Work](#original-code-issues-and-initial-work)
3. [Code Updates](#code-updates)
   - [Python Script Updates](#python-script-updates)
   - [HTML & CSS Enhancements](#html--css-enhancements)
4. [Dashboard Improvements](#dashboard-improvements)
   - [First Version Changes: Enhanced Usability and Layout](#first-version-changes-enhanced-usability-and-layout)
   - [Second Version Changes: Revised Layout and Enhanced Functionality](#second-version-changes-revised-layout-and-enhanced-functionality)
   - [Usability Enhancements and Category Management](#usability-enhancements-and-category-management)
   - [Backend Enhancements](#backend-enhancements)
5. [Final Solution/Prototype](#final-solutionprototype)
6. [Test Plan and Results](#test-plan-and-results)
7. [Future Work and Recommendations](#future-work-and-recommendations)

---

## Project Overview

The **Social Determinants of Health (SDoH) Dashboard Improvement Project** was initiated to refine an existing dashboard by enhancing its usability, functionality, accessibility, and overall performance. Originally developed by a previous cohort, the dashboard was designed to help users access critical community resources but faced multiple challenges, such as poor UI/UX design, inconsistent data representation, and limited responsiveness. This project addressed these shortcomings by following a structured workflow that assigned specific roles to participants and included rigorous testing to deliver a modern, user-friendly dashboard.

---

## Original Code Issues and Initial Work

The initial assessment of the dashboard revealed several issues, including inconsistent UI elements, poor responsiveness, and an inefficient filtering system. These findings were documented in a PowerPoint presentation that outlined the challenges and proposed solutions. To address these issues, a **swimlane diagram** was created to map the assigned roles and responsibilities of each participant, ensuring a structured approach to the redesign process.

Participants were assigned roles representing key areas: **Project Manager (PM)**, **User Experience (UX)**, **Development (Dev)**, and **Quality Assurance (QA)**. The PM focused on defining project scope, gathering stakeholder feedback, and ensuring adherence to accessibility standards. UX participants analyzed the current UI, gathered user feedback, and proposed design improvements. Developers implemented code updates and made structural changes, while QA participants ensured the accuracy and functionality of the new features.

The initial improvements were focused on **adjusting the map placement** and **repositioning elements** such as the logo and search bar to create a more intuitive layout. These adjustments aimed to improve the dashboard's usability and responsiveness without introducing significant structural changes. While these modifications resolved some usability issues, deeper functionality enhancements were deferred to later stages of the project.

---

## Code Updates

### Python Script Updates

The backend logic was significantly optimized in the second phase of the project. A key update introduced in the **second version changes** was the implementation of a **new category mapping system** in the `app.py` file. This system replaced the subcategory-based filtering with broader **general categories**, such as "Food & Nutrition Services" and "Health & Medical Services." This change simplified the filtering process for users and improved the structure of backend queries. Additionally, the integration of Google Sheets and Excel workflows ensured that resource data remained up-to-date, automating a previously manual process.

### HTML & CSS Enhancements

The HTML and CSS components of the dashboard underwent extensive updates throughout the project. Early enhancements included repositioning elements like the logo, search bar, and map to create a cleaner layout. As the project progressed, a complete **UI redesign** was implemented to modernize the dashboard’s appearance. This redesign incorporated responsive design principles, ensuring the dashboard adapts seamlessly across devices. Intuitive visual feedback, such as hover effects and error messages, was added to guide users and enhance interactivity.

---

## Dashboard Improvements

### First Version Changes: Enhanced Usability and Layout

The first iteration of the redesigned dashboard focused on improving usability through minor layout adjustments. The map placement was optimized to make it more prominent, and the search bar and logo were repositioned for better alignment. While these changes improved the visual structure, the underlying functionality remained largely unchanged, and some usability issues persisted, such as incomplete information in search results and limited feedback mechanisms.

### Second Version Changes: Revised Layout and Enhanced Functionality

The second iteration introduced significant improvements to both the layout and functionality. The webpage layout was overhauled, introducing a cleaner and more modern design. The filtering system was transformed with the addition of a **new category mapping system**, consolidating resources under general categories for easier navigation. Furthermore, category counts were removed to reduce visual clutter, allowing users to focus on the quality of resources rather than their quantity.

### Usability Enhancements and Category Management

Usability enhancements included the introduction of synchronized **checkbox filters** and dropdown menus for categories, enabling users to refine their searches more effectively. These filters dynamically updated based on user selections, ensuring a consistent and intuitive experience. The category management system, implemented in the second version, further streamlined the resource filtering process by consolidating related subcategories into broader categories. This change improved both the frontend user experience and backend query efficiency.

### Backend Enhancements

The backend improvements were pivotal in enhancing the dashboard’s performance. Query response times were reduced through optimized database interactions, and the integration of Google Sheets and Excel workflows allowed for real-time updates to resource data. These enhancements ensured that the dashboard remained accurate, efficient, and scalable.

---

## Final Solution/Prototype

The final version of the dashboard is a culmination of iterative improvements made throughout the project. It features a modernized UI, responsive design, and advanced filtering capabilities. The introduction of general categories and synchronized filters has significantly enhanced usability, while backend optimizations ensure faster performance and dynamic updates. Screenshots showcasing the before-and-after differences illustrate the dramatic transformation of the dashboard.

---

## Test Plan and Results

The dashboard underwent testing to validate its functionality, usability, and accessibility. Functional testing confirmed the accuracy of features such as category filtering, map integration, and resource display. Usability testing highlighted improvements in navigation and performance, while ADA compliance testing ensured that the dashboard met accessibility standards. The results demonstrated that the new version of the dashboard outperformed the original in every key metric.

---

## Future Work and Recommendations

To further enhance the dashboard, future efforts should focus on implementing **advanced analytics** to track user interactions and identify trends in resource usage. Adding **multilingual support** would make the platform more inclusive, catering to a diverse audience. Developing a **mobile application** would also expand accessibility and convenience for users. These initiatives would build on the dashboard’s current success, ensuring it continues to meet evolving user needs.

---
