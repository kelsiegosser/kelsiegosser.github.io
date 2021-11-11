---
title: 'Building a product from scratch'
subtitle: 'Jan 2021 - Present'
date: 2020-01-30 00:00:00
description: I assisted a practice in Milliman with the design and development of their new product using UX and design best practices.
featured_image: '/images/projects/depth/depth-lg.png'
---

# {{ page.title }}

{{ page.description }}

<img src="{{site.baseurl}}{{ page.featured_image }}" style="width:400px">

---

## Milliman DEPTH

Milliman DEPTH is a product that helps assess the performance of a benefits program and identifies areas where cost savings could potentially be achieved. 

<img src="{{site.baseurl}}/images/projects/depth/milliman-depth.png" style="width:250px">

Like most products I have worked on, DEPTH is proprietary information to Milliman, and so I cannot go into great detail with respect to content or design. However, I can walk through the process that I went through in order to help bring DEPTH to market.

---

## Background

DEPTH is a product idea that came out of a separate practice than the one that I work for, but they were looking for assistance with UX and design. I was introduced to a peer in that office and he explained the product idea and what he had been envisioning. He asked what the UX process looked like and I explained that I like to start with interviewing potential users, brainstorm with the team to come up with ideas based on feedback from the interviews, prototype and design, obtain feedback from stakeholders and potential clients, iterate, and then develop. 

---

## Interviewing

The first step in my UX process revolves around understanding the end user. I started out by working with my peer to craft interview questions. This can be surprisingly tricky as we (as humans) tend to introduce bias when asking questions. We worked hard to create 10 questions that were somewhat open-ended in an attempt to better understand their workflow, their pain points, existing solutions, etc.

Once we had our questions “perfected”, we scheduled time with 4 potential users and interviewed them using the questions as a basis. During this time, we learned quite a few things, and confirmed some thoughts we had but weren’t sure about. My peer expressed to me later that he hoped to continue this type of questioning for future consulting engagements as he was able to better understand his users through this process.

After we completed our interviews, I conducted a brainstorming session with my peers to identify what the users needed, what level of detail to include, how the users would access the information, etc. This helped us to set requirements for the UI/UX of the product.

---

## Prototyping 

Once the requirements were defined, I began the design process for DEPTH. My peers had been envisioning a dashboard style product, but after hearing from users and familiarizing myself with the data, I took a risk and mocked up a website style tool. I felt that this would align best with what the end users were looking for. 

---

## Obtaining feedback

After taking the risk with the totally new style of product, I presented it to internal stakeholders. I made sure to explain before showing the prototype that all feedback is important, especially the negative, so if they didn’t like it, please let me know. However, the feedback was overwhelmingly positive, so we decided to continue pursuing this style. 

After the feedback session with internal stakeholders, I iterated on the prototype. I made sure to address the issues that came up multiple times, and question the instances where only one person had an issue to ensure it was a change that should be made, or perhaps there was another solution to address that person’s concerns that worked for everyone.

From there, we presented the prototype to a potential client using their data to receive feedback. Again, the feedback was overwhelmingly positive. In fact, they decided to take action using the results that we demoed to them. There were still several changes that needed to be made to make the product more useful, which was fantastic for making DEPTH the best it could be.

---

## Development

After the prototype was “finalized”, I was able to begin development. I used the design system to style the report along with some custom CSS and HTML. For graphics, I used Plotly.js. It was my first time using Plotly (I have experience with D3 and Power BI embedded), and I immediately fell in love with the ease of use and flexibility. Using GitHub for source control, I was able to generate a UI for the product while one of my peers engineered an executable for running the data and inserting into the HTML file using Jinja.

<div class="gallery" data-columns="4">
    <img src="{{site.baseurl}}/images/projects/depth/html-css.png">
    <img src="{{site.baseurl}}/images/projects/depth/plotly.png">
    <img src="{{site.baseurl}}/images/projects/depth/github.png">
    <img src="{{site.baseurl}}/images/projects/depth/jinja.png">
</div>

---

## v1.0.0 product release

Once development was completed for all pieces (data analytics, executable, and UI), we were able to release v1.0.0 of the product. I immediately began working on a v1.1.0 to add a feature that we knew would be needed, but wasn’t necessary for the initial release. 
