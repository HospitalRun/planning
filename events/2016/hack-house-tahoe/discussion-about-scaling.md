# Scaling the Project Long List • meeting 3/16

## Some ways to think of scaling

- Aiming for 1.0 release (i.e. we are okay with people actually installing and using the software)
- Recruiting more contributors
- Getting people to make effective use of contribution opportunities
- Making evaluation and deployment super simple
- Long term vision where facilities could apply to get the software, and a corporate partner/contributor funds your instance
- Designing the software to accomodate a large number of users and patients
	- Permissions
	- Roles
	- Performance (technical architecture)

## Categories to think about scaling

### Functional changes in code
- Internationalization/localization organizing
	- create a form for non-techincal contributors to use to help with translation
- Need for form builders
	- for administrators to use internally (i.e. pharmacy, imaging, etc)
	- for administrators to use with patients
	- down side to custom form building is that if staff move from hospital to hospital then there is no parity that they can carry with them; part of the answer there though is it depends on the level of customization required
- Accessibility evaluation
- Moving reports

### Infrastructure considerations
- Is the app multi-tenant capable/should it become so?
	- ...vs us just hosting a bunch of VMs
	- benefits of MT makes monitoring instances often more straightforward than monitoring and maintaining VMs
	- downside is additional architectural work, data policy considerations
	- ...potentially talk to folks at Discourse about their experience there...
- Deployment and demoing solution
- Solution for hosting service for 1.0
	- potential for Microsoft involvement
- Define hardware requirements for in hospital machine to run server
	- build test data sets for hardware testing

### Community management
- Who do we want to target initially as developers?
- We can't just think of contributors as developers, but also thinking of recruiting folks who have other perspectives and experiences that can help us solve the problems
	- Identify the actors in the community who can be subject matter experts in helping us break the problems wide open and solve them
- Improving the demo experience (create video, demo version in app, etc) as a way to improve the experience for contributors
- Pairing sessions for onboarding contributors
- Define and surface explicit guidelines for how people can become a full fledge contributor/part of the project team
- Add code of conduct
- Define conference/marketing strategy
- What channels are we currently using to communicate with the community?
	- Slack - where technical contributors can communicate with us
	- GitHub issues - where we discuss/resolve codebase issues
	- Pivitol Tracker - to track workflow
	- We could use Discourse as a place to reach people who wouldn't otherwise encounter HospitalRun by people asking questions and it getting indexed by search engines


### Design and user experience considerations
- Get docs on the website
- Translation of docs and marketing site
- Create a framework of styleguides and pattern library so design can scale as we add engineering and design contributors
- Get an accessibility evaluation
- Defining and codifying personas
- Demo mode...

## Questions
- What happens when we get inquiries from agents for change who want to implement the software?
	- Joel talks to them 1:1 and gives them guidance
	- is that scalable?
- How far are we from 1.0 timeline?
	- Hopefully this year, and *hopefully* before summer is over
	- Define requirements for 1.0 (done - @tangollama finished a couple days ago)

## Getting to 1.0

From @tangollama's perspective:
- everything listed in code/functional area has to get done
	1. internationalization
	2. marketing strategy components (recruiting someone to own the marketing strategy)
	3. community management
		- how to become an official part of the project team
		- code of conduct
		- identifying subject matter expert
	4. design stuff
		- getting to a place where things are consistent designwise
		- design standards explicitly defined, styleguide, pattern library
		- recruiting more contributors
