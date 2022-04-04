# Food Futures at testing at the Media Lab

RSVP forms go out over a series of weeks.
In each case there are multiple experiment arms. There is a control, and each of the following experiment arms are duplicates of the control where the menu options have been tweaked.

Participants are randomly assigned to the control vs experimental arm(s) via a random redirect to different google forms.

This directory has a redirect page for each event.

## Set up process:

For each week:
- Choose menu options
- Create (control) RSVP form
- Duplicate control form for experiment arm(s) and modify
- Set up spreadsheet to capture responses (private, only accessible by COUHES registered/approved personnel)
- copy `template.html`
- rename as `[number].html` and modify to include links to control vs experiment RSVP forms
- create new shortlink that redirects to `https://aberke.github.io/ff/ml-surveys/[number].html` in order to hide this sketchy repo link
- test! random rediction works and spreadsheet populates
- share short link

<!-- ## Ethics

This study went through the COUHES process, with a consent waiver and debrief statement due to the deception: participants RSVP'ing for free food are unknowingly in a study. -->
