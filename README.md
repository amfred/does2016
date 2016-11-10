This repo contains some of my favorite insights from DevOps Enterprise Summit 2016.

# How do we break down silos?
- Seed teams with change agents 
- Aligning into cross functional product teams w/people from various specialties 
- What value is the silo protecting? How will that value be protected?
- “Cylinders of excellence”
- Culture of safety to experiment 
- Room to experiment 
- Build bridges between silos 
- Non functional requirements in product backlogs 


# How to get out of cycle of ridiculous exec commitments burning people out, conflicting priorities 
- Make your work visible to execs (backlog)
- Air cover, understand long term impact to people, turn over
- What are you willing to de-prioritize 
- Survey to see how people are feeling 


# Influence trust, culture
- How do you earn trust?
- How transparent can you be?
- People want to look good
- Trust is a transitive property 
- Company policies to build trust: are we doing what we said we’d do?


# Executive buy-in that Agile/DevOps align to business value
- Pioneer team, set them up for success, green field, let them work out bumps in the road and teach others
- Collect data and measure metrics, KPIs
- Find out what they care about 
- Situational awareness
- Show progress
- Maturity model is a good way to quantify it


# Encouraging a more agile workflow across development orgs; managing interdependencies 
- API contracts

# State of DevOps Report, Gene Kim and Steve Brodie
High performers have:
- 200x more frequent deployments 
- 2,555x shorter change deployment lead times
- 3x lower change failure rate
- 24x lower MTTR

# Target talk, Heather Mickman
- Great things never come from comfort zones
- Try and fail, but never fail to try
- Whatever you do, make it great
- I'm not here to be average, I'm here to be awesome 
- It's a misconception that changes lead to incidents

# AA Merger Talk, Susanna Brown and Ben Chan
- The amount of time required to deliver changes goes up exponentially as the % load on the team increases
- Anyone can add value to any team from anywhere 
- Automation is the Achilles Heel of DevOps

# ChatOps with Daniel Perez
Hubot design considerations and best practices:
- Lightweight: small, on cloud, in Docker
- Automated build/deploy, tied to SCM
- Keep it simple
- Aviod creating a single point of failure 
- Keep it chat tool agnostic 
- Reuse code as much as possible 
Security considerations:
- Express Framework enables basic auth for ports
- Implement nginx proxy pass for SSL endpoint
- Secure Hubot.env and store all ENV variables there
- App accounts are safer than personal accounts for integrations 
- Implement SSO on chat platforms that support it
- Use the enterprise version of the chat tool
