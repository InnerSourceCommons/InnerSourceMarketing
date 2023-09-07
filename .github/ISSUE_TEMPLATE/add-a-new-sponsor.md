---
name: Add a new Sponsor
about: This issue details the steps required when a new Sponsor joins ISC
title: Adding [company name] as a sponsor to ISC
labels: ISC OPS
assignees: ''

---

Checklist for new Sponsors:

## Update the Website
- [ ] Rename the logo file of the new Sponsor as: [company_name].png
- [ ] Upload this file in the static/images/logos folder on the website 
- [ ] Open the sponsors.md file located in the folder: content/about
- [ ] Go to the relevant section in this file (if adding a Partner go to the first section - Our Partners. If adding a Supporter go to the second section - Our Supporters.
- [ ] Copy and paste the following line of code in the correct place, following the alphabetical order:
{{< company name="[company name]" image="/images/logos/[company_name].png" >}}{{< /company >}}
- [ ] Save your changes and make sure to test the result before creating the pull request

## Update the sponsors slide for Community Calls and events
- [ ] Go to Canva and find the ISC Sponsors presentation
- [ ] Duplicate the first slide
- [ ] Add the new Sponsor to the slide under the relevant heading (Our Partners or Our Supporters)

## Update community channels and social media
- [ ] Create a slack post to announce new sponsor
- [ ] Create a LinkedIn post
- [ ] Create a Twitter post 

## Include in the next Newsletter
- [ ] An issue is created every month for topics to be added to the newsletter. Please comment on the issue and mention the new Sponsor.

## Other things to consider
- [ ] Is the new sponsor included on the InnerSource in Action Page?
- [ ] Is the new sponsor providing any services and if so would they like to be listed in the Services Directory?
