# Project 1 --- Engineering Assignment

## Reusable SaaS Pricing Page

## Company

**Cloud Inc.**\

---

# Executive Summary

Marketing currently maintains the Pricing page in Webflow. The page has
become difficult to maintain, inconsistent with our design system, and
cannot be reused by engineering teams.

Your task is to rebuild the Pricing Page using only HTML5 and CSS3 so it
becomes a reusable, maintainable production component.

No JavaScript is required for this milestone.

---

# Business Context

Current problems:

- Inconsistent styling across pages
- Duplicate CSS
- Poor mobile experience
- Difficult maintenance
- Components cannot be reused

This sprint begins migrating Marketing pages into the Engineering Design
System.

---

# Success Metrics

- Responsive at 320px, 768px, 1024px, 1440px
- Lighthouse Accessibility target \>95
- No horizontal scrolling
- Semantic HTML
- CSS variables for design tokens
- No duplicate styles
- Mobile-first implementation

---

# Folder Structure

```text
pricing-page/
├── index.html
├── css/
│   ├── reset.css
│   ├── variables.css
│   ├── global.css
│   ├── layout.css
│   ├── components.css
│   └── responsive.css
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

---

# Functional Requirements

## Step 1 --- HTML Only

Build semantic HTML first.

Use:

- header
- nav
- main
- section
- article
- footer
- table
- ul
- li
- button
- h1--h4
- p
- img

No CSS until HTML is complete.

---

## Page Sections

1.  Header
2.  Hero
3.  Pricing Cards
4.  Comparison Table
5.  FAQ
6.  CTA
7.  Footer

---

## Header

- Logo
- Navigation
- Login
- Start Free Trial

Navigation:

- Products
- Solutions
- Pricing
- Docs
- Blog

---

## Hero

- Badge
- Heading
- Description
- Two CTA buttons
- Trusted Companies

Use realistic SaaS copy.

---

## Pricing Cards

Plans:

- Starter
- Pro
- Enterprise

Each contains:

- Name
- Price
- Description
- Feature List
- CTA

Highlight Pro.

---

## Comparison Table

Must use `<table>`.

Include:

- Storage
- API
- Analytics
- Users
- SSO
- Support
- Custom Domain

---

## FAQ

Use semantic article elements.

---

## CTA

"Ready to scale? Start your free trial today."

---

## Footer

Company, Resources, Legal, Social.

---

# CSS Requirements

- CSS Variables
- Reset
- Global Typography
- Flexbox
- Grid
- Media Queries
- Position
- Overflow
- Specificity
- Inheritance

Mandatory selectors:

- Tag
- Class
- Child
- Descendant
- Adjacent sibling
- General sibling
- Attribute
- :hover
- :nth-of-type()

Mandatory positioning:

- relative
- absolute
- fixed

---

# Design System

Spacing Scale

4,8,12,16,24,32,48,64

Use variables for:

- Colors
- Radius
- Shadow
- Font Sizes
- Spacing

No hardcoded colors.

---

# Accessibility

- Proper heading hierarchy
- Alt text
- Navigation inside nav
- Buttons use button element
- Table caption
- Keyboard accessible
- WCAG AA color contrast

---

# Browser Support

- Chrome Latest
- Firefox Latest
- Safari Latest
- Edge Latest

---

# Engineering Constraints

Do NOT

- Use inline CSS
- Use !important
- Use IDs unless necessary
- Hardcode colors
- Duplicate CSS
- Nest selectors beyond three levels

---

# Edge Cases

Your layout must support

- Extremely long plan names
- Long descriptions
- 20 feature list items
- Very large prices
- Missing company logos

Nothing should break.

---

# Definition of Done

- Acceptance criteria pass
- Responsive tested
- HTML validated
- CSS organized
- README completed
- Peer review ready

---

# QA Checklist

- Mobile
- Tablet
- Desktop
- Landscape
- Keyboard Navigation
- Zoom 200%
- Overflow
- Broken Images

---

# Code Review Checklist

- Semantic HTML
- Reusable CSS
- Variables used
- Clean naming
- Readability
- Accessibility

---

# Git Workflow

- Create feature/pricing-page
- Commit frequently
- Use meaningful commit messages

---

# Stretch Goals

- Sticky header
- Floating support button
- Dark theme
- Print stylesheet
- Subtle CSS animations

---

# README Requirements

- Project Overview
- Folder Structure
- Tech Stack
- Challenges
- Assumptions
- Future Improvements
