---
#
# See the Github wiki for how to use Markdown in the editable content below:
# link here
#
# Title and Description display on the page and in HTML meta tags
title: Getting started
description: Get your team set up with the tools and resources they'll need throughout the digital delivery lifecycle.
#
# Internal page menu - titles here match titles in Markdown
sections:
  - General team onboarding
  - Onboarding for designers
  - Onboarding for developers
  - Onboarding for agile
#
# Don't edit items below - they control the page layout
return-top: yes
layout: page
page-type: subpage
page-description: yes
sidebar-type: /delivery
permalink: /delivery/onboard-team
pagination: yes
phase-prev: Overview
page-prev: none
phase-next: Research + Discovery
page-next: none

#
---

### Getting started

{% for item in page.sections %}
* [{{ item}}](#{{item | downcase | replace: ' ', '-'}})
{% endfor %}

<hr>

### General team onboarding

**Github**
Veteran Tools Platform teams use <a title="Go to VA Github" href="https://github.com/department-of-veterans-affairs" target="_blank">Github</a> for sharing project documents. We do this so all Veteran Tools Platform teams can learn from what other teams are doing.

Starting in the Alpha phase, your developers will start integrating with the Veteran Tools Platform release management process. We use Github Issues to manage that process.

To get started

1. Have everyone on your team create a Github account. *Note:* Github requires Two-Factor authentication (2FA) to create an account.

2. Email a list to **{{ site.contact-handbook.email }}** of all names, email addresses, and Github usernames for your team.
  * Indicate which people on the list are developers (so we can give developer access to the right people).

3. We'll add the people on the list to the VA Github organization and
  * Give everyone access to a team folder on Github, which you'll use to store and share project documents
  * Developers will need to complete <a title="go to developer getting started" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/getting-started.html#getting-started" target="_blank">additional onboarding steps</a> to access the code repositories and tools they'll need for developing on the Veteran Tools Platform

4. If your team is new to Github, we can arrange a short meeting to show you how to use it share documents.


**Slack**

* We'll create a <a title="Go to Slack" href="https://slack.com" target="_blank">Slack</a> channel for your team to use. This channel may include people from other Veteran Tools Platform teams working on a similar service, so you can share findings and ask each other questions.
<!--* We'll also give you access to the *#dsva-platform-project channel*, which you can use if you have questions about the process described in this Handbook.-->

<a href="#">Return to top</a>

<hr>

### Onboarding for designers

The design system for the Veteran Tools Platform is based on the <a title="Go to USWDS" href="https://designsystem.digital.gov/" target="_blank">United States Web Design System (USWDS)</a>, with some additional specifications to meet the needs of VA’s particular audiences.

> **Our design files use <a title="Go to Sketch" href="https://www.sketchapp.com/" target="_blank">Sketch App</a>, which is a Mac application.**
Designers should review the [Design guide](related/design) and [download the Sketch files](related/design#design-tools) so they can design using the latest Veteran Tools Platform templates.

<a href="#">Return to top</a>

<hr>

### Onboarding for developers

<!--
* Give developers access to repositories and tools they'll need to develop on the Veteran Tools Platform (see [Onboarding for developers](#onboarding-for-developers))
-->

Developers should complete the <a title="go to developer getting started" href="https://department-of-veterans-affairs.github.io/va-digital-services-platform-docs/docs/vets-developer-docs/getting-started.html#getting-started" target="_blank">additional onboarding steps</a> as soon as they've received the email invitation to join the VA Github organization.

<a href="#">Return to top</a>

<hr>


### Onboarding for agile

* coming soon

<a href="#">Return to top</a>

