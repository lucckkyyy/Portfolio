# Aryan Rajguru — Portfolio Context

## Project Overview
Personal portfolio website built with plain HTML, CSS, and vanilla JavaScript.
Live at: aryanrajguru.com

## Design System
- Background: #000000 (black)
- Primary Accent: #D2B48C (tan)
- Secondary: #F5F5DC (cream)
- Text: #FFFFFF (white)
- Font: Roboto / Space Grotesk

## Design Rules
- Dark, minimal aesthetic — never add light backgrounds
- Use tan (#D2B48C) for all highlights, bullets, borders, and hover effects
- Cards use subtle border: rgba(210, 180, 140, 0.2) with border-radius: 12px
- Hover effects: translateY(-5px) with tan glow shadow
- All animations should be smooth and subtle — nothing flashy
- Buttons are pill-shaped with transparent background and tan border

## File Structure
- index.html — main portfolio page
- style.css — all styles
- thank-you.html — form submission redirect

## Sections (in order)
1. Intro animation (Hello World)
2. Nav — About, Education, Experience, Projects, Skills, Achievements, Contact
3. About Me
4. Education
5. Experience
6. Projects
7. Skills
8. Achievements
9. Contact form (Formspree)

## Notes
- Contact form uses Formspree (mkgbebko)
- Scroll reveal animations via IntersectionObserver
- Mobile responsive with grid → single column at 768px