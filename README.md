CAPSTONE PLANNING
2/28/2020
8:15 - 8:45 create README, read assignment, plan day
8:45 - 9:45 research on writing good test cases and user stories
9:45 - notes for user stories and acceptance criteria for this MVP


Name of Project: MS Health Tracker

Project’s Purpose or Goal: (What will it do for users?)

This app will help people who have multiple sclerosis (like me!) record and keep track of what matters most to them. Your medical records never tell the whole story of what it’s like to have a chronic health condition or what you’ve done to take care of yourself; doctors and other medical professionals aren't always interested in details that matter a lot to patients. This app will help patients document the full picture of how the disease is affecting them and all the things that they are doing to take care of themselves.

List the absolute minimum features the project requires to meet this purpose or goal:

Options for user to decide what to track, including doctor-driven actions (appointments, tests, medications) and/or patient-driven actions (other forms of care, exercise, diet, social support, etc.).

Symptom journaling that helps a user sort through one-off/short-duration symptoms from bigger concerns, while also helping organize symptom info over time to look for patterns; with that info, the user can prep for appointments or other communications with a doctor’s office.

Journaling will be possible by typing or by transcribing audio recorded by the user.

* * *

What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific.

WebSpeechAPI or similar tool for speech recognition and transcription: https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API

React and/or React Native (but probably React Native to start?), Redux, JavaScript, HTML, CSS, custom API to store info (so Ruby/Postgres?), authentication via bcrypt or Devise, some kind of encryption that meets health info privacy standards (?)

* * *

If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.

I would like to have a web version and a mobile version, so that people can work on the device of their choosing, but my MVP will be to do only one of these (starting point still to be determined, based on developing comfort level with React vs. React Native)

Other features could be

Calendar integration (for medical appointments and other reminders);

Medication management: photos of your medications/dosages; refill reminders;

Insurance information;

Authorizing other users to view your info;

Social media function to connect to other patients;

Other ways you can connect to MS community: research study participation, advocacy, fundraising.

* * *

What additional tools, frameworks, libraries, APIs, or other resources will these additional features require?

Calendar integration: Google calendar API and similar for other calendar apps

Sharing health info with another user: OAuth or comparable service?


USER STORIES FRAMEWORK
