# Food Waste Reduction and Donation System

## Project Title
Food Waste Reduction and Donation System

## Project Description
A university Internet Programming project that provides a platform for food donors (restaurants, cafes, bakeries, supermarkets, and individuals) to register surplus food donations, track food availability and freshness, and coordinate delivery of donated food to distribution centers so it reaches people in need instead of being wasted.

## Problem Statement
Large amounts of edible food are wasted every day by food businesses and households, while many people in communities lack reliable access to sufficient food. There is a need for a simple system to connect surplus food donors with distribution centers and food recipients, reducing food waste and supporting food security.

## Project Objectives
- Reduce food waste by redirecting surplus edible food to people in need.
- Allow donors to register and manage food donations.
- Track food availability, freshness, and delivery status.
- Prioritize urgent food donations requiring fast delivery.
- Generate summary reports covering total, available, assigned, delivered, and urgent food.

## Main Features
- Register new food donations from restaurants, cafes, bakeries, supermarkets, and individuals.
- Display and track all registered donations in a structured table.
- Search, update, and delete donations using donor credentials (planned).
- Assign food items to distribution centers and delivery drivers (planned).
- Mark assigned food items as delivered (planned).
- View urgent food donations requiring priority delivery.
- Generate summary reports (planned).
- Donor login and registration (planned).
- Contact form for inquiries (planned).

## Technology Currently Used
HTML5 only. No CSS, no JavaScript, and no Java are used at this stage.

## Project Development Stages
This project is developed in stages as part of an Internet Programming course:
1. HTML (current stage): structure and layout of all pages and forms.
2. CSS (planned): styling and layout enhancements.
3. Java (planned): functionality such as authentication, data storage, search, update, delete, delivery assignment, and reporting.

CSS and Java implementation are not yet complete and are not part of the current stage.

## Project Folder Structure
Food/
├── index.html
├── README.md
├── images/
│   ├── logo.svg
│   ├── food-donation.svg
│  
├── videos/
│   ├── intro.mp4 (missing - needs to be added)
│   └── intro.webm (missing - needs to be added)
└── pages/
    ├── add-donation.html
    ├── about.html
    ├── contact.html
    ├── delivery-management.html
    ├── donations.html
    ├── login.html
    ├── manage-donations.html
    ├── register.html
    ├── reports.html
    └── urgent-food.html

## Team Project Information
This is a team project for an Internet Programming course. Team member names are not listed here. All pages are developed collaboratively by the team under the HTML stage, with CSS and Java stages planned for later coursework.

## HTML Concepts Demonstrated

The following HTML5 concepts are demonstrated across the project:

### A. Text Formatting Elements
| Element | Page | Usage |
|---------|------|-------|
| `<b>` | about.html, add-donation.html | Bold text for donor types and important labels |
| `<strong>` | index.html, about.html, contact.html, login.html, register.html, manage-donations.html, delivery-management.html | Strong importance for key instructions |
| `<i>` | about.html | Italic for technical term "first-in, first-out" |
| `<em>` | index.html, about.html, contact.html | Emphasis on notes and stage warnings |
| `<u>` | index.html | Underline for course project label |
| `<mark>` | about.html, index.html, urgent-food.html | Highlight urgent food information |
| `<small>` | about.html, index.html, manage-donations.html, register.html | Fine print and supplementary notes |
| `<del>` | about.html, manage-donations.html | Show removed/old values in record updates |
| `<ins>` | about.html, manage-donations.html | Show inserted/new values in record updates |
| `<sub>` | about.html | Subscript in chemical notation (CO₂) |
| `<sup>` | about.html | Superscript in unit notation (cm³) |

### B. Image Insertion
| Page | Image | Alt Text |
|------|-------|----------|
| index.html | images/logo.svg | Food Waste Reduction and Donation System logo |
| about.html | images/food-donation.svg | Food donation process illustration: donor to distribution center |
| contact.html | images/logo.svg | Food Waste Reduction and Donation System logo |

### C. Line Breaks and Horizontal Rules
- `<br>`: Used on about.html in the Technical Notes section to break lines within a paragraph
- `<hr>`: Used on index.html, about.html, donations.html, urgent-food.html, reports.html to separate sections

### D. Tables
| Page | Table Features |
|------|---------------|
| donations.html | `<table border="1" cellpadding="5" cellspacing="0">`, `colspan="8"` |
| urgent-food.html | `<table border="1" cellpadding="5" cellspacing="0">`, `colspan="7"` |
| reports.html | `<table border="1" cellpadding="5" cellspacing="0">`, `colspan="2"` |

### E. Forms and Form Attributes
All forms use `action="#" method="post"`. Input types demonstrated:
- `text`: donor names, food names, addresses, subjects
- `password`: login and registration passwords
- `file`: food donation image upload (add-donation.html)
- `email`: donor and contact email addresses
- `number`: food quantity, donation ID
- `date`: food expiry date, pickup/delivery dates
- `hidden`: donation ID internal field (add-donation.html), form type (login.html)
- `radio`: donation recipient type (add-donation.html)
- `checkbox`: terms agreement (contact.html), deletion confirmation (manage-donations.html), remember me (login.html)
- `color`: preferred label color (add-donation.html)

### F. Fieldset and Legend
Used on all form pages to group related fields: add-donation.html, contact.html, delivery-management.html, login.html, manage-donations.html, register.html

### G. Dropdown Lists and Text Areas
- `<select>` / `<option>`: donor source, freshness options on multiple pages
- `<optgroup>`: grouping donor sources by "Businesses" and "Individuals" (add-donation.html, register.html)
- `<textarea>`: contact message (contact.html), food description (add-donation.html)

### H. Buttons
- `type="submit"`: form submission on all forms
- `type="reset"`: clear form fields on login, register, contact, add-donation, manage-donations, delivery-management
- `type="button"`: non-functional demonstration buttons clearly marked "(not functional in HTML stage)"

### I. Form Validation Attributes
- `required`: mandatory fields across all forms
- `pattern`: username pattern `[a-zA-Z0-9_]{3,50}`, Ethiopian phone pattern `^\+?[0-9]{9,15}$`
- `min` / `max`: quantity min="1", max="1000", donation ID min="1"
- `step`: step="1" for whole number quantities

### J. Multimedia
- `<video controls>`: index.html references videos/intro.mp4 and videos/intro.webm (video files need to be added to videos/ folder)
- `<audio controls>`: about.html references videos/system-overview.mp3 (audio file needs to be added)

## Known Limitations
- The videos/ folder is empty; intro.mp4, intro.webm, and system-overview.mp3 need to be added for multimedia to work.
- All forms are structural only; no data is stored or processed until the Java stage.
- CSS and Java will be developed in later coursework stages.
