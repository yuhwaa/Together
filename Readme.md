# Together
Together is a new app designed for 100devs. Together is a group calendar for public events, so you can see what's going on in your community. We're making it easier to find out about the events that are happening in Discord and let you know how much fun they'll be!

**Link to project:** https://together.cyclic.app/

![alt tag](https://i.ibb.co/vVH3qjx/Screen-Shot-2022-11-05-at-12-13-17-PM.png)

## How It's Made:

**Tech used:** Tailwind, JavaScript, MERN

Work in Progress

## Optimizations
*(optional)*

Work in Progress

## Lessons Learned:

Work in Progress

## Want to Contribute?

Checkout [MVP Tasks Porject Board](https://github.com/users/Caleb-Cohen/projects/1/views/1). We have instructions on how to contribute [here](https://github.com/Caleb-Cohen/Together/blob/main/CONTRIBUTING.md). To claim a task comment on an open issue located [here](https://github.com/Caleb-Cohen/Together/issues), or open a new issue from the issues tab. You can also convert a draft todo on the project board to an issue. 

## MVP Tasks
MVP Tasks are viewable [here](https://github.com/users/Caleb-Cohen/projects/1/views/1). 

## Next Level 

- [ ] OAuth will check to see if they are in the 100devs guild(server)
- [ ] users can add or delete events (two-step delete process for confirmation)
- [ ] (can have an event log tied to the user name)

## Next next-level stuff
- [ ] users rsvp events, and a total is displayed
- [ ] discord bot that will message users for events they are rsvp'd in?
- [ ] events can have channels tagged that match the server channel emojis' daily view. Clicking on the day can bring up a day planner view, just like the google calendar
- [ ] users can add an event to their calendar through a click
- [ ] users can filter events based on pre-determined tags (beginner-friendly, networking, group learning)
- [ ] users can share events on Twitter
- [ ] new event notification dots(easy mode might be to just highlight new events on each reload)

## The Penultimate Goal
- [ ] Discord guilds can create their own together calendar 

## thinking ahead,
keep these in mind to prevent the project from being "caged."
can integrate with slack or Discord and work on other servers besides 100devs

Resources:
https://codepen.io/robstinson/pen/BaKOZry 

---

# Things to add

- Create a `.env` file in the config folder and add the following as `key = value.`
  - PORT = 2121 (Do not change)
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your Cloudinary cloud name`
  - API_KEY = `your Cloudinary API key`
  - API_SECRET = `your Cloudinary API secret`
  - DISCORD_CLIENT_ID = `discord client ID`
  - DISCORD_CLIENT_SECRET = `discord client secret`

---

# Install & Run

- `npm install` installs the required dependencies & rebuilds front-end. 
- `npm run dev` in the root folder to start both frontend and backend for development/testing.

If you make changes to the front end you must execute `npm run build` otherwise the backend will serve the outdated build file. 

Still having troubles? 

You can join the discussion in the together discord channel [here](https://discord.com/channels/735923219315425401/1038482732633825442). You must be a part of the 100Devs discord to view the discussion.  
