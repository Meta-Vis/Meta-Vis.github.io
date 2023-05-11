---
title: Industrial Components Appearance Inspection

# event: Wowchemy Conference
# event_url: https://example.org

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: An application scenario for injection moulded products
abstract: Application examples for injection moulded products

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2030-065-01T13:00:00Z'
date_end: '2030-05-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-05-01T00:00:00Z'

authors: [admin]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: #'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---

## Project Background

An injection moulding factory needs to upgrade the production of traditional injection moulding machines to an unmanned digital factory. 
![Overview of appearance inspection system](bg1.png "Overview of appearance inspection system")
On the one hand, the defective products are removed from the production process and automatically packed with good products.

On the other hand, the defect detection information is fed back to the injection moulding machine to improve the yield, of which defect detection becomes a key part.
![](bg2.png "Example of possible defects")
The injection moulded products are randomly distributed on the conveyor belt and the main inspection surfaces are located around the sides, so the robot is used to track and locate the defects and detect the indispensable defects.

Based on our defect detection algorithm platform and nearly thirty years of experience in vision imaging, the few-shot defect detection algorithm was successfully applied and promoted in an injection moulding factory.

## Applications Scenarios
- Automotive parts
- Electronic components
- Metal processing

## Advantages of the System

### A.I. Detection Algorithm

![](ad1.png "Window of the Software")
The system is a **self-developed all-in-one tool for labeling, training and deployment**. 

![](ad2.png "Examples of the defects found by our system")

For classic image processing method:
- Large amounts of defect data are needed, with a high requirement for data balance.
- Manual operation is cumbersome and requires manual annotation of a large amount of data.
- The accuracy is not high, with a large number of false positives and false negatives, and the parameter adjustment is complex.

For our A.I. system:
- Suitable for **few-shot** scenarios in factories.
- Self-developed few-shot deep learning algorithm with **all-in-one easy operation** for data labeling, model training, and deployment.
- **99% high accuracy**, capable of detecting **small**, **low-contrast** defects.

### Visual-Guided Grasping & All-round Detection

![](ad3.png "Component captured by the manipulator")

The machine hand picks up scattered parts one by one from the conveyor belt and delivers them to a designated inspection area. 

![](ad4.png "OKs and NGs")

After inspection, the OK parts are placed back on the conveyor belt. 
This system can be used in industries such as **automotive parts, electronic components, and metal processing**.

### Multi-Dimensional Imaging - Flexible and Freely Combinable Imaging
![](ad5.png "Example of imaging system")
With a powerful self-developed vision system and various image recognition sensors, automatic inspection and component identification can be implemented.

![](ad6.png "Different illuminations of imaging")
This system can fuse multiple imaging techniques such as ring illumination, bar illumination, coaxial illumination, and backlit illumination, and is compatible with various types of cameras, including area scan and line scan cameras.

## System Specifications

- Inspection Precision: 0.1mm (customizable according to demand)
- Imaging Modality: 2D or 3D (customizable according to demand)
- Capable Detection Tasks: 
  - identification
  - appearence inspection
  - presence/absence detection
  - workpiece sorting
  - other requirements please contact us to inquery


Thanks for reading. For more details and inqueries, please contact the project manager listed on the bottom of this page.






