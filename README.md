# INFR3120-portfolio

## Overview

This website was created for my Assignment 1 in Web and Scripting Programming using HTML5 and CSS3. It introduces my background, interests, and previous projects.
Website link: https://sebastienmarion1.github.io/INFR3120-portfolio/
Repository link: https://github.com/sebastienmarion1/INFR3120-portfolio

## Structure

My website contains four HTML pages:

A home page with a short introduction.

An about me with my background, photo, and introductory video with controls and a poster image.

A projects page with five previous projects worked on throughout my academic and professional career.

A contact me page with a form that has name, email, phone, and message fields.

Each page includes navigation in the footer, my contact email, and a copyright notice. I adapted the class template by moving navigation from the side to the bottom.

## Responsive Design

For my sizing, I followed the template given in the Week 3 lecture slides and code, being:
Desktop: 960px and wider, using full.css.

Tablet: 481px to 959px, using tablet.css.

Phone: 480px and narrower, using smartphone.css.

The desktop layout uses a centred 960px panel. The tablet and phone layouts use the available width on screen so the desktop panel does not extend beyond smaller screens. I made use of percentage widths, media queries, and stacking content to ensure it would adapt. I did not include any fixed heights so sections could be added to easily.

Navigation links are large and stacked vertically at all times, so they are easy to see and click. My portrait stays 220px wide across the layouts.

## Colour Scheme

I chose navy and slate blue backgrounds with white text and light blue links. I find it is a nice contrast and easy to read/look at from any device, and works well on a mobile device outside in my testing. I kept the colours consistent in all formats.

The main colours are:

#0F172A: main content.

#1E293B: footer/navigation backgrounds and  darker gradient colour.

#334155: lighter gradient colour.

#F1F5F9: desktop text.

#FFFFFF: header text and smaller-screen text.

#ADD8E6: navigation and email links.

## Gradients

The desktop body background uses a vertical linear gradient from #1E293B to #334155. This is visible around the middle website panel.

The header uses an angled linear gradient between the same colours at -45 degrees. This appears on all four pages and in all three stylesheets.

Both gradient techniques were based on the Week 1 lecture examples.

## Class Sources and Changed

My starting code came from the INFR3120 lecture materials and class files. Specifically the week 3 versions.

I referred to the week 1 material for the foundation, colours, and gradients.

I referred to the week 2 material for the video, forms, required fields, email validation, and telephone inputs.

I referred to the week 3 material for the responsive template and media-query.

I used full.css, tablet.css, and smartphone.css for the starting styles.

I referred to semantic.html for examples of semantic tags, project sections, figures, and the footer email link.

I referred to form.html for the contact form structure.

I referred to video.html for the introductory video structure.

I referred to the week 4 material for the fixed desktop copyright notice.

I changed the content, colours, sizes, and navigation placement to fit my portfolio. I left comments throughout my code explaining the sources and changes. My photo and introductory video are my own media.

## Contact Form

The first name, last name, email, and phone fields are required. The email input checks that the entry has an email format. The labels are connected to their matching fields, and the reset clears the form.

The form uses the mailto action example shown in class. It asks the viewer's default or chosen email app to prepare a message.

The phone field uses tel and required.

## Testing and Validation

I used the W3C HTML Validator, W3C CSS Validator, and W3C Link Checker: to ensure I had no errors or unnecessary code.

I ensured the video plays with audio, and preloads.

Note: I have found the video cannot be played through the integrated web browser in Visual Studio Code, so it must be opened in Chrome or any other web browser.