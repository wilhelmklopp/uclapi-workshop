# Workshop: Build a Slack integration
## UCL API Hackathon

![lecture roulette](https://user-images.githubusercontent.com/7718702/72665642-61993e80-3a02-11ea-937d-2db8ca87585f.png)


<p align="center">
  <a href="https://glitch.com/edit/#!/remix/lecture-roulette-starter">
    <img src="https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg" alt="Remix With Glitch">
  </a>
</p>

---

### Workshop Pre-requisites

- Be a member of the hackathon Slack (https://uclapihack2020.slack.com)
- Have a working UCL API token (get it from https://uclapi.com/dashboard)

### Useful links throughout the workshop
- UCL API, get room bookings: https://uclapi.com/docs#roombookings/bookings
- Slack block kit builder: https://api.slack.com/tools/block-kit-builder
- Slack blick kit reference: https://api.slack.com/reference/block-kit/blocks

Follow along live: https://glitch.com/edit/#!/open-boursin

### Goals and learning outcomes
- Understand Booking object in UCL API
- Understand Slack Block Kit
- Understand Simple Poll API

### Workshop steps
1. Create your Glitch app by following this link: https://glitch.com/edit/#!/remix/lecture-roulette-starter
1. Wait for Glitch to load and for it to install all the dependencies. You can see progress by clicking on "Tools" and then "Logs" in the bottom left corner
1. Go to the .env file and paste in your UCL API token
1. In a new tab, open the following URL to create your Slack app https://api.slack.com/apps
      - make sure to select "UCL API Hack 2020" as your development workspace
1. Click on "Slash commands"
      - Under "Command" enter your initials and then "roulette", so for me that would be "wk-roulette"
      - Under "Request URL", paste the URL that is displayed on Glitch
1. After saving your slash command click on "Install app" in the sidebar and install your app on the Slack workspace
1. Then head back to Glitch, it's time to write some code!

### Extend and improve your app further
- Adjust the time window during which to search for lectures
- Select lectures from specific modules or departments
- Create a poll for the five different options so that a group of people can decide on where to go
- Display the five random lectures in Slack's new ["app home" feature](https://api.slack.com/start/overview#app_home) and provide similar functionality there
