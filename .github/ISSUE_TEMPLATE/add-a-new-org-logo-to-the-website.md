---
name: Add a new Org Logo to the Website - Stories Page
about: Use this to add your company's logo to the InnerSource in Action page on the
  website
title: Add [organisation name] logo to the Stories Page
labels: website
assignees: ''

---

<!--
README:
The template below capures essential instructions to add a new logo to the website.

If you are NOT comfortable with using git/GitHub:
- provide the information outlined in '### Issue Checklist'
- then click "Submit new issue"
- somebody else will pick up this issue and perform the remaining steps.

However if you are familiar with git/GitHub you can do most of this on your own:
- provide the information outlined in '### Issue Checklist'
- assign the issue to yourself
- then click 'Submit new issue'
- perform the tasks listed in Steps to add the logo to the website" 

In case of any questions, add those questions to the issue itself.
-->

### Issue Checklist

_Note:_ This is done by the person that wants to add their org logo to the website.

- [ ] Replace `[organisation name]` with your company name in the title of this GitHub issues.
- [ ] Check the [Stories Page][stories] on the website to see if the logo of your organisation is already featured
- [ ] Upload the logo of your organisation to this issue. Nname the logo according to the template `organisation_name.png`.
- [ ] Provide a link to evidence of the company doing InnerSource (this could be an article, a video, or a [pattern][patterns-repo]

### Steps to add the logo to the website

_Note:_ This is typically done by a website administartors (or by you, if you are familiar with git/GitHub).

- [ ] fork the [website repository][website-repo]
- [ ] add the logo file to the folder `static/images/logos`, following this template for naming the logo file: `organisation_name.png`
- [ ] edit the file for Stories Page located at: `content/en/stories/_index.md`
- [ ] add the logo in the correct place in the list, following alphabetical order. Include the link to the evidence, by using the following code snippet. If the evidence is an article, replace 'video' with 'article'.
```
{{< company name="[Company Name]" image="/images/logos/[organisation_name].png" video="[link to evidence]">}}
{{< /company >}}
```
- [ ] if you want to provide an extra quote about how your org is applying InnerSource, extend the entry like this:
```
{{< company name="[Company Name]" image="/images/logos/[organisation_name].png" video="[link to evidence]" author_name="[author name here]" author_title="[author title/role here]">}}
[quote here]
{{< /company >}}
```
- [ ] create a Pull Request. Specify in the Pull Request why you are adding the logo to the site e.g.: "I work for the company and know they are doing InnerSource".

### Acceptance Criteria

- The logo file is named according to the convention: `organisation_name.png`
- The logo file has been uploaded to the correct folder
- The logo appears on the [Stories Page][stories] in the correct place based on alphabetical order

### Help Needed / Blockers

[stories]: https://innersourcecommons.org/stories/
[website-repo]: https://github.com/InnerSourceCommons/innersourcecommons.org
[patterns-repo]: https://github.com/InnerSourceCommons/InnerSourcePatterns
