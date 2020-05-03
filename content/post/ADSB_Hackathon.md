+++
title = "ADS-B Hackathon, Airbus Toulouse"
date = 2018-11-02T20:40:33+05:30
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []
# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = "ADSB-Hackathon-AllParticipantsPic.jpg"
caption = ""
preview = true
+++
I recently started my data science internship at __Airbus Operations GmbH__, Hamburg in September 2019 and was awarded the opportunity to participate in this ADS-B Hackathon at Airbus Leadership University, Toulouse, France.
<!--more-->
### Machine Learning for Air Traffic Management
  Airsense (a division within Airbus - Munich) organized this 2 day ADS-B Hackathon at [Airbus Leadership University](https://www.airbus.com/newsroom/press-releases/en/2016/09/Airbus-Group-Opens-Leadership-University-In-Toulouse-.html), Toulouse on Oct 29 and Oct 30, 2018. The goal of this hackathon was to develop various data analytics and ML based solutions to optimize Air Traffic Management using the _Automatic Dependent Surveillance Broadcast_ (ADS-B) data. The participants had to pick a particular _user story_ (team). I joined the following team:<br>

#### USER STORY - Runway and Holding Pattern Detection:
*  **Project Title:** [Runway and Holding analysis using LHR airport arrivals case](https://communities.intra.corp/sites/ads-b/ADSB%20Hackathon%202018/ADS-B%20Hackathon_Outcome_Team3.pdf)
* **My Task** : Detect holding patterns and do runway classification with flight arrivals data for LHR (London Heathrow) airport.

 <!-- <p align="middle">
  <img src="https://communities.intra.corp/sites/ads-b/ADSBHackathon%202018%20Pictures/DSC01147.JPG" width="405" />
  <img src="https://communities.intra.corp/sites/ads-b/ADSBHackathon%202018%20Pictures/20181029_152053.jpg" width="308" />
</p> -->

In this team project I implemented  various Machine Learning algorithms (such as LSTMs, MLPs and XGBoost) for predicting various parameters related to _Air Traffic Control_ such as Flight Trajectory, ETA and Runway Classification. The collection of implementation works have been uploaded in this Git Repository: github.com/diliprk

**Presentation Slides**:
<iframe src="https://onedrive.live.com/embed?cid=6E68E8BA03D8E3A5&amp;resid=6E68E8BA03D8E3A5%2110866&amp;authkey=ACNSZHbM1l7dkXg&amp;em=2&amp;wdAr=1.7777777777777777" width="683px" height="541px" frameborder="0">This is an embedded <a target="_blank" href="https://office.com">Microsoft Office</a> presentation, powered by <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>
