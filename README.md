- 👋 Hi, I’m @Jerry-Plybon-Professional-Portfoloio
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Jerry-Plybon-Professional-Portfoloio/Jerry-Plybon-Professional-Portfoloio is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
{
  "version": "1.0",
  "name": "Jerry Plybon Portfolio",
  "components": [
    {
      "type": "frame",
      "name": "Home Page",
      "width": 1440,
      "height": 1024,
      "children": [
        {
          "type": "header",
          "name": "Hero Section",
          "content": {
            "title": "Dynamic Sales Leader Driving Strategic Growth in Public and Private Sectors",
            "subtitle": "Over 20 years of expertise in SaaS, CX/EX solutions, and IT service management, building partnerships and exceeding revenue goals.",
            "cta": {
              "text": "Discover My Journey",
              "link": "#about"
            }
          },
          "styles": {
            "backgroundImage": "background-image-placeholder.jpg",
            "backgroundColor": "#007BFF",
            "textColor": "#fff"
          }
        },
        {
          "type": "navigation",
          "name": "Main Navigation",
          "links": [
            { "text": "Home", "link": "#home" },
            { "text": "About Me", "link": "#about" },
            { "text": "Experience", "link": "#experience" },
            { "text": "Core Competencies", "link": "#skills" },
            { "text": "Education", "link": "#education" },
            { "text": "Portfolio", "link": "#portfolio" },
            { "text": "Contact", "link": "#contact" }
          ]
        }
      ]
    },
    {
      "type": "frame",
      "name": "About Me Section",
      "width": 1440,
      "height": 1024,
      "children": [
        {
          "type": "text",
          "name": "About Me Content",
          "content": "Dynamic and results-oriented sales leader with over two decades of experience driving revenue growth, fostering strategic partnerships, and leading high-performing teams. My expertise spans both public and private sectors, specializing in SaaS, CX/EX solutions, and IT service management. I excel at securing multimillion-dollar contracts, optimizing team performance, and delivering measurable outcomes."
        },
        {
          "type": "list",
          "name": "Achievements",
          "items": [
            "Secured $3.5M+ annual contracts in the public sector.",
            "Delivered consistent 20% year-over-year revenue growth.",
            "Partnered with AWS Marketplace and Genesys AppFoundry for expanded SaaS offerings."
          ]
        }
      ]
    },
    {
      "type": "frame",
      "name": "Experience Section",
      "width": 1440,
      "height": 1024,
      "children": [
        {
          "type": "timeline",
          "name": "Career Timeline",
          "events": [
            {
              "title": "Director PubSec/SLED – East Coast",
              "company": "Mindful/VHT",
              "date": "July 2022 - Present",
              "description": "Secured $3.5M+ in annual contracts and grew pipeline opportunities by 25%."
            },
            {
              "title": "Regional Enterprise Sales Director",
              "company": "Actsoft Software Solutions",
              "date": "Aug 2021 - July 2022",
              "description": "Directed sales strategy across 10 states and achieved a 20% revenue increase."
            },
            {
              "title": "National Sales Director/SaaS Overlay",
              "company": "Iteris Roadway Services Division",
              "date": "June 2018 - Aug 2021",
              "description": "Achieved consistent 15% revenue growth and delivered a 40% conversion rate for SaaS sales."
            }
          ]
        }
      ]
    },
    {
      "type": "frame",
      "name": "Portfolio Section",
      "width": 1440,
      "height": 1024,
      "children": [
        {
          "type": "caseStudy",
          "name": "Case Study 1",
          "title": "Transforming Public Sector Operations with SaaS",
          "problem": "A federal agency struggled with inefficient communication channels, causing delays in operations.",
          "solution": "Implemented a customized SaaS CX/EX platform integrated with AWS Marketplace, streamlining processes and enhancing user engagement.",
          "outcome": "Boosted operational efficiency by 35%, with $3.5M in annual recurring revenue."
        },
        {
          "type": "caseStudy",
          "name": "Case Study 2",
          "title": "Driving Regional Sales Growth",
          "problem": "Low client acquisition rates in a 10-state territory.",
          "solution": "Revamped the sales approach, trained a team of 8 BDRs, and implemented advanced lead generation tools.",
          "outcome": "Achieved a 35% increase in client acquisition and a 20% rise in revenue."
        }
      ]
    },
    {
      "type": "frame",
      "name": "Contact Section",
      "width": 1440,
      "height": 1024,
      "children": [
        {
          "type": "form",
          "name": "Contact Form",
          "fields": [
            { "type": "text", "label": "Name", "placeholder": "Enter your name" },
            { "type": "email", "label": "Email", "placeholder": "Enter your email" },
            { "type": "textarea", "label": "Message", "placeholder": "Enter your message" }
          ],
          "submitButton": {
            "text": "Send Message",
            "action": "sendEmail"
          }
        },
        {
          "type": "text",
          "name": "Direct Contact",
          "content": "Email: Jerry.plybon@gmail.com | Phone: (843) 224-3261"
        }
      ]
    }
  ]
}
