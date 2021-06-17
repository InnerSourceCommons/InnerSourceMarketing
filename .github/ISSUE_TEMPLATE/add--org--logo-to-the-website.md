---
name: Add [Org] Logo to the Website
about: Use this to add your company's logo to the InnerSource in Action page on the
  website
title: Add [organisation name] logo to the InnerSource in Action page
labels: website
assignees: ''

---

<!--
README:
The template below provides the format for how to create an issue around adding a new logo to the website. 

Please ensure to carry out the 3 steps outlined in the '### Issue Checklist'. 

You do not need to change anything else in the following 2 sections (### Steps to adding the logo to the website and ### Acceptance criteria).

If you are familiar with GitHub and are confident in performing the steps below, please assign the issue to yourself and carry out the work. 
Alternatively, you can complete the help needed section at the bottom and just create the issue. 
Someone else will pick it up and add the logo to the website.

-->

### Title

Add [organisation name] logo to the InnerSource in Action page

Please replace [organisation name] with your company name and place this short summary in the title of the GitHub issue.

You can delete the whole `### Title` section from here.

### Issue Checklist 

- [ ] Check the InnerSource in Action page on the website to see if the logo of your organisation is already featured: https://innersourcecommons.org/community/action/
- [x] Give the issue the title specified above
- [ ] Delete the `### Title` section above
- [ ] Upload the logo of the organisation to this issue in an organisation_name.png format.

### Steps to adding the logo to the website:

- [ ] fork the [website repository](https://github.com/InnerSourceCommons/innersourcecommons.org) and add the logo to the InnerSource in Action page as follows:
- [ ] the logo file must be named following the template: organisation_name.png
- [ ] the logo file must be uploaded in the following folder: static/images/logos of the InnerSource Commons website repository
- [ ] please edit the InnerSource in Action page located at the following path: content/community/action.md
- [ ] please add your logo in the correct place in the list, following alphabetical order, by using the following code:
{{< company name="organisation_name" image="/images/logos/organisation_name.png" >}}{{< /company >}}

### Acceptance Criteria

- The logo file is named according to the convention: organisation_name.png
- The logo file has been uploaded to the right folder
- The logo appears on the InnerSource in Action page in the correct place based on alphabetical order

### Help Needed / Blockers