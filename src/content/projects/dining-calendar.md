---
title: DiningCalendar
publishDate: 2020-03-04 00:00:00
img: /assets/abstract-4.jpeg
img_alt: Abstract digital beige art
description: |
  Python program to scrape Tufts dining website and make events in Google Calendar.
tags:
  - Web Scraping
  - Google Calendar API
  - Python
---

#### Overview

This Python program uses <a href="https://www.crummy.com/software/BeautifulSoup/bs4/doc/"> BeautifulSoup </a> and the <a href="https://developers.google.com/calendar/api/guides/overview"> GoogleCalendar API </a> to insert the daily menus of the Tufts University dining halls into a calendar and can filter them to according to dietary restrictions such as Vegan, Vegetarian or Halal. 

There are two different versions of the program: one which is simply a CLI tool that allows users to authorize their google calendar, pick a date and dining hall and create an event with today's menu. The other is a program that goes adds all the vegetarian meals at the two main dinings halls into my calendar every Monday, for the entire week and it runs using Windows Task Scheduler. Below are some photos that show the command-line tool and how the event appears in Google Calendar. 


#### Tech Stack
The program was built and deployed using:
- Python
- BeautifulSoup
- GoogleCalendar API
- Microsoft Azure

#### Code
Link to Github Repo: <a href="https://github.com/Lakshita110/tufts-dining-calendar">Here!</a>

#### Images
<img src="/assets/calendar-event.png" alt="A Google Calendar event of the Tufts dining menu">
<img src="/assets/calendar-cli.png" alt="Screenshot of the command line">