---
name: Update Website with new Community Call details
about: Use this for community call website update
title: Update website with new Community Call Details
labels: website
assignees: ''
---

### Purpose and Details

Please update the website with the new Community Call details as follows:
Name: [Community Call Name]
Link: [Community Call Event Brite Link]
Date: [dd/mm/yy]
Description: [Community Call Description for website]

### Steps to Updating the Website

- [ ] Go to the `_index.md` file and change the details within the ``{{`<notice>`}}`` section. Update the Link, the date and the name of the event.
- [ ] Download the picture of the event from eventbrite and rename it: `meetup-mm-yyyy.jpg` (where mm is the month of the event and yyyy is the year of the event) 
- [ ] Upload the picture of the event in the folder: `static/images/events`
- [ ] Go to the folder: `content/events` and find the latest event file. It should be named under the format: `meetup-mm-20yy.md`
- [ ] Change the "featured:" value to "false"
- [ ] Create a new event file in the folder: `content/events`
- [ ] Name the file: `meetup-mm-2021.md` (where mm is the month the event is taking place) 
- [ ] Copy and paste the following code in the file and insert the required information under the headings. Then make sure to update the description of the event below. 

```
---
title: [Title of The Event Goes Here]
type: redirects
redirect: "[Link to the event goes here]"
image: "images/events/meetup-[mm]-[yy].JPG" 
date: [Today's date goes here in the format: yyyy-mm-dd Note: DON'T use the date of the event as it will not show up on the website]
featured: true
---

In this session, we will be joined by [Speaker1] from [Company1], [Speaker2] from [Company2] and
[Speaker3] from [Company3] who will be sharing their experiences of [Theme of the event] with
InnerSource.
```

- [ ] Create a pull request after completing the steps above.
