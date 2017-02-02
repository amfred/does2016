This repo contains some of my favorite insights from DevOps Enterprise Summit 2016.

# Lean Coffee: Tactics for Influencing Executives and Middle Management - Leading Change
- Empathy with execs: competing priorities, delivering results, engaging workplace, too much work, risks, high rates of change, talent
- Empathy with middle managers: talent, features vs. technical debt, collaboration, shared outcomes, budget cuts, making the implicit explicit, empowering teams, in-sourcing 
- Encourage a growth mindset
- Make work visible (i.e. Kanban)

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
- Warning sign: if your backlog is growing, but your headcount is not (Aimee Bechtle)


# Influence trust, culture
- How do you earn trust?
- How transparent can you be?
- People want to look good
- Trust is a transitive property 
- Company policies to build trust: are we doing what we said we’d do?
- You can't fire your way to reliable (David Blank-Edelman)


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

# Lessons Learned Implementing a One Engineering System at Microsoft, Ed Blankenship and Sam Guckenheimer
- If you have more than about 4 open bugs per engineer, take a break from new features and fix them.
- Self forming teams. Once per month.  Team leads pitch their projects.  Developers put their 1st, 2nd, 3rd choice teams on stickies.  Team leads sort people into teams.  95% success with getting people into their preferred teams.  Just a few limits, like co-location.

# Nationwide talk, Cindy Payne
- "GitHub is just better at version control than Subversion"
- It's also faster and better at merging 
- "Give teams a half empty tool belt and they'll make their own tools. Then each team becomes a snowflake."
- "Instead of a plea to standardize, lure them with ease of use and low cost. (Make the "right" thing pleasant and people will do it.)
- They separated the presentation tier from the business tier and created separate paths to production for each.
- Being willing to run a test and potentially "miss" was a big psychological barrier they had to work through 
- It's much more powerful when the practitioners are teaching than when the transformation guy is teaching 

# Capital One talk
- Our backlog was growing, but our headcount was not

# Damon Edwards
How to stop burnout and help people thrive

People burnout from:
- Work overload 
- Lack of control 
- Insufficient rewards
- Breakdown of community 
- Absence of fairness 
- Value conflicts

People thrive with:
- Leveled work
- Empowered 
- Sufficient rewards
- Supportive community 
- Fairness and transparency 
- Aligned values 

# Mark Imbriaco
- Make tiny decisions.  It's ok to not plan too far ahead.  It's easier to make small decisions, and easier to change them when you're wrong.
- Fight hero culture. Enforce healthy balance.
- Recovery plans: If you have a plan that you haven't practiced, you don't have a plan.
- Test your run books monthly (rotating basis).  Get new hires to practice them before they go on call.  Be prescriptive so people don't have to make too many decisions at 2 AM.  
- During an outage, offload communications to someone, so technical poeple can focus.
- Learn from your failures and successes, and share the results publicly.
   - Apologize. And mean it.
   - Demonstrate a thorough understanding of the problem.
   - Explain what you're doing to reduce the likelihood of similar problems.  Don't over promise.
- Collaborate by default.  Visibility is the ultimate compensating control.

# 2016 State of DevOps Report
- URL: https://puppet.com/resources/whitepaper/2016-state-of-devops-report
