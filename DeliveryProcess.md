# Delivery process

## Principles

- We produce open source software created and maintained in repositories where it may be inspected by the public who places their trust in it and copied for use by other agencies
- We adhere to the basic practices of agile software development
- We foster an open, collaborative, welcoming environment
- We invite relevant decision-makers at the table during all meetings to maximize efficiency and maintain momentum
- We practice human-centered design
- Everything that we produce is highly accessible, per WCAG 2.0
- We seek to use DevSecOps to automate and measure our deployment process, relying on continuous integration, continuous delivery, and continuous security to ensure that our work is high-quality
- We will build APIs before we build software atop it, and we believe that APIs require a well-designed interface


## Frameworks

To set ourselves up for success for the quarter we are working on this engagement (and set up our partner for continued success once we leave), we apply a subset of [the Scaled Agile Framework](http://www.scaledagileframework.com/) (SAFe) to guide our work, as described in [Essential SAFe](http://www.scaledagileframework.com/what-is-safe#Essential). 

We set goals and prioritize work in three month periods called "program increments," or PIs, and practice a number of SAFe rituals around this quarterly cadence.

To manage our day-to-day work, we practice Scrumban, which means we practice [Kanban](http://blog.crisp.se/2009/06/26/henrikkniberg/1246053060000) around cardwall-style boards that track work from left-to-right as it is identified, prioritized, explored, delivered, and demonstrated. We augment Kanban with a subset of Scrum activities (or "rituals"), found below.


## Rituals

We run regular practices, or rituals, to structure our work. Though we regularly fine-tune how we do these, we perform them regulary so we can focus more on output than necessarily how we're doing the work.

### Standup

Daily standups allow us to regularly share where we are in our work and also allow us to identify when teammates are blocked, overwhelmed, or have extra capcacity to help.

What this looks like:
- A quick (15-minute) video or asynchronous (Slack) daily standup to communicate about the status of the work we commit to each sprint
- Project manager or any other team member can facilitate
- We go issue by issue rather than person by person to keep our focus primarily on the work
- This isn't a status report, but we should inquire if any pieces of work seems stalled or any team members seem underutilized

### Sprint review/demo

Sprint reviews serve two purposes: they are an opportunity to get immediate feedback and answer questions from stakeholders and also motivate the team to get as much work done as possible before the end of the sprint (since we only demo finished work).

What this looks like:
- Bi-weekly sprint demos for stakeholders and colleagues of our recent work to share and get feedback
- We currently ask team members to make slides for the work they've completed, but we can also do live demos

### Retrospectives

We run retrospectives so we can regularly get better in our work – building on strengths and mitigating weaknesses while giving the team time and space to reflect on its work.

What this looks like:
- Project manager or any other team member facilitates
- We write down individually what we feel went well and what didn't in the past sprint, vote to highlight which items we discuss, discuss them, and write down any actions we plan on taking
- If we write down many possible actions, we can vote on these, as well

### Sprint planning and grooming

So we can tackle the highest-value work each sprint, know what we'll be working on, and know what we are not working on, we plan our sprint together and groom issues so we know what the work looks like when it is done. 

What planning looks like:
- Product owner brings goals and, as much as possible, groomed stories to the team for prioritization and selection
- PO has final call on what is included and what is excluded from the sprint
- When a tentative plan is in place, we do a vote of confidence with the team. If we collectively vote over 60%, we consider the plan set and begin work

What grooming looks like:
- We groom issues by adding acceptance criteria (for which the PO is reponsible) and, as is useful, potential implementation steps (owned by the team)
- This should be done by the end of the sprint planning session or, ideally, sooner
- Three days before sprint planning can be a good to time to meet to groom issues in advance
- The whole team doesn't need to attend grooming, but about half the team generally should
- The PO can groom issues and also ask team members who may know most about the work to help groom them
- Issues should be groomed to take three days or less for one contributing team member to complete
- We like to have enough issues groomed to stay productive if our velocity is faster than expected. However, remember that groomed issues that we don't ever pick up are waste!

## Kanban process

Kanban basically says cards go through a set of states (represented columns on a board), but it doesn't say much about what the cards represent or how the states are defined. Here's what they mean to us:

### Cards on boards

Cards on our boards typically capture and track a bug, raw task, or user story. Bugs and tasks are what they sound like. **Stories** represent tactical increments of individually-valuable work deliverable by a team within a single iteration.

**Features** or **Epics** are roadmap-worthy changes in product capabilities tracked against regular milestones. That is, larger items that are worth planning and announcing on a regular basis.

### WIP Limits

Work-in-progress (WIP) limits help us focus and are generally designated on a per-column basis. That means we expect to see no more than that number of cards in the column at a time. If you want to move a card right into a column that's already at its WIP limit, first figure out how to help move one of the existing cards out to the right, including pairing with a team member to help out (and share context). If the next column is also at its WIP limit, that's your cue to keep working your way over to the right, asking "how can I help?" when you encounter something being worked on for which there's space to move.

In general we use WIP limits to gate how much time and effort we put into grooming cards when we haven't got capacity to do them yet, and to gate how many things we're trying to do at once so that we focus on finishing existing work before starting new work. We don't want individuals to be responsible for more than one or two cards in progress at a time, and we generally like team members to collaborate and pair up to get work done, so our WIP limit for cards actually getting development attention is set intentionally slightly low to encourage this.


## Special roles

### Product owner

To support this approach, it is essential that we have the support of a dedicated and empowered product owner within FRTIB who is responsible for representing the project and its deliverables internally while providing consistent access to relevant users and stakeholders. The product owner should also serve as the “champion for the engagement” by offering strategic advice and ensuring the active participation of key stakeholders for the duration of the engagement. 

We look to the product owner to prioritize research, design, and code deliverables and help shape the overall vision for our work. The product owner should also set the vision for various levels of work, including the product, engagement, and sprint while regularly reminding the team of these so they always know what work they are doing and why it is important.

There is more information about the product owner role in the [18F Partnership Playbook](https://18f.gsa.gov/partnership-principles/#partnering-with-an-empowered-product-owner).
