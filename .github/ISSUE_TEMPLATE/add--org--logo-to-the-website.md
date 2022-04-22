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

Please ensure to carry out the steps outlined in the '### Issue Checklist'.

You do not need to change anything else in the following 2 sections (### Steps to adding the logo to the website and ### Acceptance criteria).

If you are familiar with GitHub and are confident in performing the steps below, please assign the issue to yourself and carry out the work.
Alternatively, you can complete the help needed section at the bottom and just create the issue.
Someone else will pick it up and add the logo to the website.

-->

### Title

Add [organisation name] logo to the InnerSource in Action page

Please replace [organisation name] with your company name and place this short summary in the title of the GitHub issue.

You can delete the whole `### Title` section from this issue.

### Issue Checklist

- [ ] Check the [InnerSource in Action](https://innersourcecommons.org/community/action/) page on the website to see if the logo of your organisation is already featured
- [x] Give the issue the title specified above
- [ ] Delete the `### Title` section above
- [ ] Upload the logo of the organisation to this issue (name the logo according to the template `organisation_name.png`)
- [ ] Provide a link to evidence of the company doing InnerSource (this could be an article or a video)

### Steps to add the logo to the website:

- [ ] fork the [website repository](https://github.com/InnerSourceCommons/innersourcecommons.org)
- [ ] add the logo file to the folder `static/images/logos`, following this template for naming the logo file: `organisation_name.png`
- [ ] edit the InnerSource in Action page located at: `content/community/action.md`
- [ ] add the logo in the correct place in the list, following alphabetical order. Make sure to include the link to the evidence, by using the following code (if the evidence is an article, replace 'video' with 'article' in the code below).
```
{{< company name="[Company Name]" image="/images/logos/[organisation_name].png" video="[link to evidence]">}}
{{< /company >}}
```
- [ ] if you want to provide a quote from the video/article, please extend the entry as shown below:
```
{{< company name="[Company Name]" image="/images/logos/[organisation_name].png" video="[link to evidence]" author_name="..." author_title="...">}}
[quote here]
{{< /company >}}
```
- [ ] create a Pull Request and specify in the Pull Request why you are adding the logo to the site (e.g.: "I work for the company and know they are doing InnerSource")

### Acceptance Criteria

- The logo file is named according to the convention: `organisation_name.png`
- The logo file has been uploaded to the right folder
- The logo appears on the InnerSource in Action page in the correct place based on alphabetical order

### Help Needed / Blockers
