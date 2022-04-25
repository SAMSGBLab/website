---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Zefxis"
subtitle: "A QoS-aware distributed Message Broker for the IoT."
summary: "Supporting wide-scale IoT applications."
authors: []
tags: [qos,iot]
categories: []
date: 2017-01-01

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The Zefxis message broker is designed to support the deployment of large-scale, heterogeneous and dynamic IoT applications. 
These consist of diverse Things including both resource-constrained/rich devices with a considerable portion being mobile.
Zefxis adopts a pub/sub interaction paradigm that enables decoupling IoT devices in both time and space and supports distributed 
applications spanning a wide-area through a set of independent, communicating brokers. 
Zefxis supports efficient delivery of data from IoT sources to relevant subscribers while considering several QoS semantics and requirements related to the mobile IoT.

Queueing Network (QNs) offer a simple modeling environment which can be used to represent various application scenarios and provide accurate analytical 
solutions for performance metrics (e.g., system response time).
We use QNs to model the performance of middleware protocols found in IoT that are classified within the pub/sub interaction paradigm with both reliable and unreliable 
underlying network layers. We also consider QoS semantics for data validity, buffer capacities and intermittent availability of mobile IoT devices. 
We then introduce a pub/sub mechanism for probabilistic event dropping by considering the devices' intermittent 
connectivity and QoS requirements. The consequent PerfMP performance modeling pattern may be tailored for a variety of deployments in order 
to control fine-grained QoS semantics.

We showcase the application of our analysis in concrete scenarios relating to Traffic Information Management systems 
that integrate both reliable and unreliable participants. 
We are currently developing a prototype implementation of the Zefxis message broker.  

#### Useful links and references

* The Zefxis performance modeling pattern has been used in the {{% staticref "http://www.inf.ufg.br/~ricardo/achor/" "newtab" %}}ACHOR{{% /staticref %}} international research project to allocate broker nodes on Cloud.