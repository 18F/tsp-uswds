# Federal Retirement Thrift Investment Board - Thrift Savings Plan (tsp.gov)

## Welcome!
This repository contains documentation describing the Federal Retirement Thrift Investment Board (FRTIB) tsp.gov engagement. It is intended to be a place where project team members, stakeholders, and other interested parties can keep track of goals and resouces as we work together. 

## History

FRTIB, the agency that administers the Thrift Savings Plan to help government employees save for retirement, has engaged 18F to help FRTIB’s in-house design team in the Office of Communications and Education (OCE) develop capabilities in agile software development, user-centered design, and content strategy. This work will set direction and build practices to continue redesigning tsp.gov in an agile and user-centered way. 

## Users and stakeholders

FRTIB serves over five million participants (current or former federal employees, and uniformed service members) as well as their beneficiaries. In the start of 2018, the agency began enrolling and transitioning thousands of uniformed service members into the TSP’s new “blended retirement” system, resulting in an estimate of hundreds of thousands of new users each year. 

FRTIB also coordinates with over 100 payroll offices in the federal government that oversee those employees. In addition to serving users through tsp.gov, FRTIB manages a large volume of phone calls (2.8-3 million in 2017) in its call centers, a number which is likely to increase as users will start retiring in larger amounts. 

## Problem being solved

In collaboration with federal agencies, we want to help federal employees, uniformed service members, and their beneficiaries develop an understanding of their retirement options in order to be engaged in investing through the TSP.

## Anticipated outcomes

We currently anticipate the following key outcomes for this work:
 - To define users of tsp.gov, including their needs, motivations, and preferences when accessing the site. 
 - To develop a vision and roadmap for tsp.gov that outlines design priorities for the site based on user needs, the mission of FRTIB, and stakeholder goals. The roadmap will leverage the US Web Design System and other best practices, including agile product development, to recommend specific opportunities for improving the user experience and content for the site.
 - To provide coaching throughout the engagement that helps FRTIB work in a more agile, open, and human centered way. Examples of this may include developing a repeatable process for testing new design iterations and strategies for prioritizing the product backlog.
 - To provide a foundation so that FRTIB can relaunch tsp.gov successfully in 2018.

At the end of our work together, the in-house team at FRTIB will have developed additional skills and capabilities needed to successfully implement against a prioritized roadmap. 

Any features and recommendations should be developed and implemented by the in-house FRTIB team as they are best positioned to implement and iterate on the roadmap that we will collaboratively develop together. 

## Metrics for success

These are the metrics we are following to determine the degree to which this engagement has been successful:
 - Whether or not the team, as a whole, is developing and testing hypotheses with users by using prototypes
 - Whether or not FRTIB team members are planning and leading research sessions
 - Whether or not FRTIB team members are leading standups, sprint planning, sprint review, and retrospectives
 - Whether or not we have created research findings, content recommendations, and a roadmap to deliver at the end of the engagement

## Roadmap

The work we plan to take on is sequenced in our project [Trello board](https://trello.com/b/QvYdQMaY/18f-tsp-uswds). We are also developing a recommended roadmap with FRTIB for the next few quarters as a deliverable for this engagement so the design team has a clear path toward desired outcomes once this engagement ends.

## Risks and mitigations

Risk: We are not aligned on the key work to be done.
Mitigation: We conducted a kickoff meeting to discuss scope and areas of opportunity, making sure we are aligned on what work we may and may not take on as part of this engagement. We also conduct sprint planning jointly with FRTIB team members empowered to make decisions about this project and are conducting “50%” and “75%” meetings to check in on progress and any changes to priorities over the course of the engagement.

Risk: FRITB is unable to continue this work once 18F rolls off the engagement.
Mitigation: FRTIB and 18F team members work alongside each other every day and conduct activities, including daily stand-up meetings, sprint planning, retrospectives, and execution of work together. Before the end of the engagement, we intend for FRTIB team members to lead all regular rituals and also have experience leading activities such as user research, hypotheses development, and vision-setting.

Risk: Technical and workflow obstacles, including Github being blocked on the FRTIB network and lack of access to a shared documents tool, hamper our work.
Mitigation: With 18F security leads, we met with FRTIB Office of Technology Services (OTS) staff to learn about their context and concerns regarding these tools so they can be unblocked. Simultaneously, we've focused on value where it can be delivered today using existing tools.

## Tools
 - [Research notes document](https://docs.google.com/document/d/1ddTUx7zpGNtUzcHHCnEqvFnB6QG-FNuoyOpU1OY-eXs/edit#)
 - [Statement of Work](https://drive.google.com/open?id=1Iy1iFCO3z2pLbyU1q7Zm5O38L5F-Mj9B8xDbD4x0g6k)
 - [Project brief](https://github.com/18F/tsp-uswds/blob/master/projectbrief.md)
 - [Google Drive folder for 18F](https://drive.google.com/drive/folders/1JazpgWiJphe-YOSUjPuksulaHqjEh_tY) 
 - [Google Drive folder for partners](https://drive.google.com/open?id=1USchlpJni0qYwBKPVW9xPtaeIecl3ZJC)
 - [Trello backlog](https://trello.com/b/QvYdQMaY/18f-tsp-uswds) (we currently use this instead of Github issues as FRTIB has more regular access to Trello)
 - [Retrospective board](https://trello.com/b/vPwxwObJ/18f-frtib-tspgov-uswds-retrospective)
 - [Board for post-engagement roadmap - WIP](https://trello.com/b/jBW83JZ6/wip-ftrib-tspgov-roadmap-subject-to-change)

## Tock and staffing

- The 18F Tock code for billing time to this project is FRTIB WDS Consulting #686
- [18F staffing issue](https://github.com/18F/staffing-and-resources/issues/428)

## Prototype

### About the prototype

* The prototype uses [Jekyll](https://jekyllrb.com), a Ruby-based static site generator. For more information about using Jekyll, refer to the [Jekyll documentation](http://jekyllrb.com/docs/home/).

* The prototype is also built with the [U.S. Web Design System](https://designsystem.digital.gov), a set of reusable, high-quality components for modern websites. We're using the Web Design System [Jekyll theme](https://github.com/18F/uswds-jekyll) with some customized styles.

### Running prototype locally

After cloning the repo, navigate to the correct folder and install Jekyll and any necessary dependencies using:
```
cd tsp-uswds/sandbox
```

```
npm install
```

```
bundle install
```

To run the site locally, from the `sandbox` folder, run:

```
bundle exec jekyll serve --baseurl ''
```

If all goes well, visit the site at `http://localhost:4000`.

## Contributing

To provide feedback on this repository, [open an issue](https://github.com/GSA/tsp-uswds/issues/new).

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
