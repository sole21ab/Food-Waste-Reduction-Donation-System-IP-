# Food Waste Reduction and Donation System

## 1. Project Overview

The **Food Waste Reduction and Donation System** is a university project developed for the Internet Programming course. It aims to reduce food waste by connecting food donors with distribution centers.

The proposed system allows restaurants, cafes, bakeries, supermarkets, and individuals to register surplus food donations, monitor food availability and freshness, and coordinate the delivery of donated food to people in need.

The project is being developed in stages, starting with HTML5.

## 2. Problem Statement

Large quantities of edible food are wasted every day by businesses and households, while many people lack reliable access to sufficient food.

A system that connects surplus food donors with distribution centers can help reduce unnecessary food waste and improve the distribution of available food to people in need.

## 3. Project Objectives

- Reduce food waste by redirecting surplus edible food to people in need.
- Provide a way for donors to register and manage food donations.
- Track food availability, freshness, and delivery status.
- Prioritize urgent food donations that require faster delivery.
- Generate summary reports showing total, available, assigned, delivered, and urgent food quantities.

## 4. Main System Features

The proposed system includes the following features:

- **Donation Registration:** Register surplus food donations from restaurants, cafes, bakeries, supermarkets, and individuals.
- **Donation Listing:** Display registered donations in organized tables.
- **Donation Management:** Search, update, and delete donation records.
- **Delivery Management:** Assign food donations to distribution centers and delivery drivers.
- **Delivery Tracking:** Update the status of assigned donations when they are delivered.
- **Urgent Food Monitoring:** Identify donations that require priority delivery.
- **Reports:** Display summaries of food quantities and donation statuses.
- **User Authentication:** Provide donor registration and login interfaces.
- **Contact:** Provide a form for inquiries and communication.

*These are the proposed system features. The current HTML stage provides the page structures and interfaces; application functionality will be developed in later stages.*

## 5. Technologies and Development Stages

### Current Technology

- **HTML5:** Used to structure the website content, pages, forms, tables, and multimedia elements.

The current stage does not use CSS, JavaScript, or Java.

### Development Stages

The project is planned in three stages:

1. **HTML5 – Current Stage:** Develop the website structure, navigation, forms, tables, and multimedia content.
2. **CSS – Planned:** Improve the website's appearance, styling, layout, and responsiveness.
3. **Java – Planned:** Implement application functionality, including authentication, donation management, delivery coordination, and reporting.

## 6. Project Folder Structure

```text
Food/
│
├── index.html
├── README.md
│
├── images/
│   ├── logo.png
│   ├── food-donation.png
│   └── urgent-food.svg
│
├── videos/
│   ├── intro.mp4
│   ├── intro-captions.vtt
│   └── system-overview.mp3
│
└── pages/
    ├── about.html
    ├── add-donation.html
    ├── contact.html
    ├── delivery-management.html
    ├── donations.html
    ├── login.html
    ├── manage-donations.html
    ├── register.html
    ├── reports.html
    └── urgent-food.html
```

## 7. Team Project Information

This is a collaborative university project developed for the Internet Programming course.

Team members share development responsibilities across the website's pages and features. The project is currently in the HTML5 development stage.

## 8. HTML5 Concepts Demonstrated

The following HTML elements, attributes, and concepts are demonstrated throughout the project.

### A. Text Formatting Elements

| Element | Pages | Purpose |
|---|---|---|
| `<b>` | about.html, add-donation.html | Bold text for labels and important information |
| `<strong>` | index.html, about.html, contact.html, login.html, register.html, manage-donations.html, delivery-management.html | Indicate important information |
| `<i>` | about.html | Italicize technical terms |
| `<em>` | index.html, about.html, contact.html | Emphasize notes and warnings |
| `<u>` | index.html | Underline the course project label |
| `<mark>` | index.html, about.html, urgent-food.html | Highlight important information |
| `<small>` | index.html, about.html, manage-donations.html, register.html | Display supplementary information |
| `<del>` | about.html, manage-donations.html | Demonstrate deleted or previous values |
| `<ins>` | about.html, manage-donations.html | Demonstrate inserted or updated values |
| `<sub>` | about.html | Demonstrate subscript notation |
| `<sup>` | about.html | Demonstrate superscript notation |

### B. Image Insertion

| Page | Image | Purpose |
|---|---|---|
| index.html | `images/logo.png` | Display the system logo |
| about.html | `images/food-donation.png` | Illustrate the food donation process |
| contact.html | `images/logo.png` | Display the system logo |

### C. Line Breaks and Horizontal Rules

- `<br>`: Used in about.html to create line breaks within text.
- `<hr>`: Used in index.html, about.html, donations.html, urgent-food.html, and reports.html to separate content sections.

### D. HTML Tables

| Page | Demonstrated Features |
|---|---|
| donations.html | Tables using `border`, `cellpadding`, `cellspacing`, and `colspan` |
| urgent-food.html | Tables using `border`, `cellpadding`, `cellspacing`, and `colspan` |
| reports.html | Tables using `border`, `cellpadding`, `cellspacing`, and `colspan` |

### E. Forms and Input Types

The project demonstrates HTML forms using `action="#"` and `method="post"`.

The following input types are included:

| Input Type | Usage |
|---|---|
| `text` | Donor names, food names, addresses, and subjects |
| `password` | Login and registration passwords |
| `file` | Food donation image upload |
| `email` | Donor and contact email addresses |
| `number` | Food quantities and donation IDs |
| `date` | Food expiry, pickup, and delivery dates |
| `hidden` | Internal form values |
| `radio` | Selection options |
| `checkbox` | Agreement and confirmation options |
| `color` | Preferred label color |

### F. Fieldset and Legend

`<fieldset>` and `<legend>` are used to group related form fields on:

- add-donation.html
- contact.html
- delivery-management.html
- login.html
- manage-donations.html
- register.html

### G. Dropdown Lists and Text Areas

- `<select>` and `<option>`: Provide selectable options, such as donor sources and food freshness.
- `<optgroup>`: Groups donor sources into businesses and individuals.
- `<textarea>`: Provides larger text input areas for contact messages and food descriptions.

### H. Buttons

The project demonstrates the following button types:

- `type="submit"`: Used for form submission.
- `type="reset"`: Used to clear form fields.
- `type="button"`: Used for demonstration buttons that do not perform application actions in the current HTML stage.

### I. Form Validation Attributes

The following HTML form validation attributes are demonstrated:

- `required`: Makes fields mandatory.
- `pattern`: Defines input formats, including username and phone number patterns.
- `min` and `max`: Restrict numerical input ranges.
- `step`: Defines permitted numerical increments.

### J. Multimedia Elements

The project demonstrates HTML5 multimedia elements:

- `<video controls>`: Displays the introductory video on index.html.
- `<track>`: Provides English captions for the introductory video using `videos/intro-captions.vtt`.
- `<audio controls>`: Plays the system overview audio on about.html.

## 9. Known Limitations

The current implementation focuses on the HTML structure and content of the website.

- Forms are structural only and do not store or process submitted information.
- User login and registration interfaces do not provide actual authentication.
- Donation management operations are not connected to a database.
- Delivery assignment and tracking are not yet functional.
- Reports do not retrieve or calculate data dynamically.
- CSS styling and Java functionality are planned for later development stages.

---

**Project:** Food Waste Reduction and Donation System  
**Course:** Internet Programming  
**Current Development Stage:** HTML5
