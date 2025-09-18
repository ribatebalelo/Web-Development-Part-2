# HealthCare+ Website Project

**HealthCare+** is a comprehensive healthcare appointment booking system designed to improve patient access to healthcare services. The website was developed by **Tebalelo Riba (ST10477225)** and features a fully responsive design with multiple interconnected pages, aligned with international digital health standards (WHO, 2023; BMA, 2022).

---

## Table of Contents

- [Project Overview](#project-overview)  
- [Project Description](#project-description)  
- [Features](#features)
- [Changelog](#Changelog)  
- [CSS Enhancements and Customizations](#css-enhancements-and-customizations)  
  - [Base Styles and Reset](#base-styles-and-reset)  
  - [Typography System](#typography-system)  
  - [Color Scheme](#color-scheme)  
  - [Responsive Design Implementation](#responsive-design-implementation)  
  - [Interactive Elements](#interactive-elements)  
  - [Navigation System](#navigation-system)  
  - [Form Styling](#form-styling)  
- [Technical Implementation](#technical-implementation)  
  - [Frontend Technologies](#frontend-technologies)  
  - [Browser Compatibility](#browser-compatibility)  
  - [Performance Considerations](#performance-considerations)  
- [References](#references)  

---

## Project Overview

This project documents the **HealthCare+ website**, a digital healthcare platform for appointment booking. The documentation includes updates, CSS enhancements, and customization techniques. The website is fully responsive and aligned with global digital health standards (WHO, 2023; BMA, 2022).

---

## Project Description

HealthCare+ is a patient-centered healthcare platform that allows users to:

- Browse medical services and specialist doctors  
- View detailed doctor profiles including qualifications and availability  
- Book appointments online  
- Learn about the healthcare facility and its mission  
- Contact healthcare providers directly  

By offering these features, HealthCare+ improves digital access to healthcare, in accordance with guidance from the **British Medical Association (BMA, 2022)** and the **World Health Organization (WHO, 2023)**.

---

## Features

- Fully responsive website design  
- Intuitive online appointment booking system  
- Detailed doctor and service profiles  
- Interactive and accessible user interface components  
- Mobile-first layout for tablets and smartphones  
- Optimized performance and cross-browser compatibility  

---

#  Changelog

###  Added

* Integrated new CSS styling to enhance layout, colors, and overall design of the new website.

### Fixed

* Corrected and updated citations in the website proposal draft to ensure proper formatting and accuracy.

---

## CSS Enhancements and Customizations

### Base Styles and Reset

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
````

This reset eliminates default browser styling and ensures consistent sizing using the **border-box model** (MDN Web Docs, 2025).

### Typography System

* **Headings:** Roboto Bold
* **Body Text:** Open Sans Regular
* **Color Contrast:** High contrast for accessibility

Typography choices follow **Material Design guidelines** (Material Design, 2025) and usability principles (Krug, 2014; Norman & Nielsen, 2020).

### Color Scheme

* **Primary:** Blue (#1E88E5) – trust and dependability
* **Secondary:** Green (#43A047) – wellness and health
* **Neutral:** White (#FFFFFF) and Grey (#F5F5F5) – clean, modern aesthetic

Based on *Universal Principles of Design* (Lidwell, Holden & Butler, 2010) and Material Design recommendations (Material Design, 2025).

### Responsive Design Implementation

* Mobile-first grid system using **CSS Grid** and **Flexbox**
* Breakpoints at **768px** and **480px** for tablets and mobile devices
* Responsive typography scaling
* Flexible image handling using `object-fit`

Ensures accessibility across devices and compliance with **WCAG 2.1 standards** (NHS Digital, 2021).

### Interactive Elements

* Smooth hover effects on cards and buttons
* Subtle transform animations for interactivity
* Gradient overlays on doctor images
* Custom scrollbar styling

Supported by best practices in **interaction design** (Norman & Nielsen, 2020).

### Navigation System

* Gradient background
* Animated hover highlights
* Mobile-responsive collapse functionality
* Sticky positioning

Enhances usability and navigation flow (Krug, 2014; Norman & Nielsen, 2020).

### Form Styling

* Consistent input field design
* Visual validation indicators
* Custom radio buttons for time slots
* Accessible focus states

Adheres to accessibility guidelines for inclusive design (NHS Digital, 2021; MDN Web Docs, 2025).

---

## Technical Implementation

### Frontend Technologies

* **HTML5:** Semantic markup for accessibility and SEO (MDN Web Docs, 2025)
* **CSS3:** Custom styles using Flexbox and Grid (MDN Web Docs, 2025)
* **Bootstrap 5.3.0:** Responsive component framework (Material Design, 2025)

### Browser Compatibility

Tested on **Chrome, Firefox, Safari, and Edge**, following **W3C and MDN guidance** (MDN Web Docs, 2025).

### Performance Considerations

* Optimized image delivery
* Minimal external dependencies
* Efficient CSS class reuse
* Responsive image handling

Follows **NHS Digital security and efficiency standards** (NHS Digital, 2021) and usability best practices (Krug, 2014).

---

## References

 British Medical Association (BMA). (2022) *Improving digital access to healthcare*. [https://www.bma.org.uk](https://www.bma.org.uk) \[Accessed 4 Aug. 2025].
 Krug, S. (2014) *Don't Make Me Think, Revisited: A Common Sense Approach to Web Usability*. 3rd ed. New Riders.
 Lidwell, W., Holden, K. & Butler, J. (2010) *Universal Principles of Design*. Revised and updated edition. Rockport Publishers.
 Material Design. (2025) *Color and Typography Guidelines*. [https://material.io/design/](https://material.io/design/) \[Accessed 19 August 2025].
 MDN Web Docs. (2025) *HTML: HyperText Markup Language*. [https://developer.mozilla.org/en-US/docs/Learn/HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML) \[Accessed 19 August 2025].
 MDN Web Docs. (2025) *JavaScript Basics*. [https://developer.mozilla.org/en-US/docs/Learn/JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) \[Accessed 19 August 2025].
 National Health Service (NHS) Digital. (2021) *Data Security and Protection Toolkit*. [https://digital.nhs.uk/data-security](https://digital.nhs.uk/data-security) \[Accessed 4 Aug. 2025].
 Norman, D.A. & Nielsen, J. (2020) *The Design of Everyday Things*. Revised and expanded edition. MIT Press.
 World Health Organization (WHO). (2023) *Digital health*. [https://www.who.int/health-topics/digital-health](https://www.who.int/health-topics/digital-health) \[Accessed 4 Aug. 2025].

```

