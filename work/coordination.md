---
parent: How We Work
nav_order: 3
---
# Coordination
{: .no_toc }

Since we're not necessarly physically co-located, we have to coordinate effectively and intentionally using a shared set of tools and processes.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


## Asynchronous Work
Since your coworkers are physically distributed, it's possible any one of them may be in a timezone where they won't even be awake when you are.  This necessitates an _asynchronous_ approach to workflows, since it would be hard to enforce tightly-coupled workflows.  For most people, your work shouldn't require that you're in constant communication throughout the entire day with someone.  Generally, things will be much smoother if you collaborate as though most things will get an answer eventually, but not necessarily right this second. Your first choice of action should be to post a message or a document about what you need to explain or need to know. Then others can read it on their schedule, when the natural lulls of the day allow it, rather than being interrupted right in their peak flow time.  You should be able to work effectively knowing that any of your co-workers may be offline, at any time, for any reason.

For some teams (customer support, compliance and safety checks, etc) more coordination is necessary and teams will need to be online at the same times.  Coordination will be up to those those teams to appropriately schedule and set clear expectations.

### Documentation :notebook:
Since you may be working while your coworkers are not, it's important to document everything important.  It's so important it's [in the Company Values](../values/index.md#write-things-down-notebook).  Documentation is a core foundation for [efficient work](../values/index.md#efficiency-runner); it allows for text-based long term communication.  You should document:

 * Every project, noting the context and reasons for the project's existence, status, and ongoing road map
 * Every big decision - the context, considerations, and reasons for the final decision
 * The results of every meeting - who has agreed to do what, and what the next steps are
 * Postmortems - if something breaks, why did it break and what will be done to prevent a future recurrence
 * Anything else that needs to be communicated to co-workers (or even yourself, at a later date)

Documentation **should** live in these places:

 * This handbook
 * Documents in the appropriate Google Shared Drive
 * Github comments for repositories / projects that live there
 * Asana tasks and comments

These locations **do not** count as documentation:

 * Slack conversations (they expire and are deleted after a short retention period)
 * Email conversations (people who aren't on the chain will not have access to it)

### Goals
Goals are an important part of our [measurement and tracking value](../values/index.md#track-and-measure-bar_chart).  You and your manager will agree on personal goals for you, your team and department has goals, and the company overall has goals.  Goals should all be:

 * Measurable - you can't fix what you can't measure
 * Attainable
 * Valuable - they should help the company move forward in a meaningful way
 * Monitored - ideally, in our Looker instance

One of the ways everyone can have [individual agency](../values/index.md#agency) is that there is accountability at every level to set and then deliver on goals.

## Communications Tools
Since we're [working asynchronously](#asynchronous-work), we need the ability to be able to effectively communicate without relying on lots of [meetings](#ad-hoc-meetings).

### Slack
Our Slack workspace is one of the main ways we communicate.  In general, prefer:

 1. public channels over private ones - people should be able to pop in and see what a team is working on, or get up to speed when joining a new project.  Public channels are also searchable by anyone.
 1. topic channels over water cooler channels - by sticking to the topic and purpose of a channel, you give people the ability to join only the channels that are relevant to their work.  Don't talk about puppies in the `#looker` channel, use the `#puppies` channel for that :dog:
 1. very selective use of `@here` and `@channel`

### Github
Github is used to version all of our product code, our technical documentation, and other text-based projects like this handbook.  In general, projects should be public (like this handbook) unless they are confidential.

### Asana
We use Asana to keep track of "To Do" lists per project.  Your team may use Asana however they feel makes them more productive, but you should document your team's process.

### Email
Email is a last resort for internal communication (though often the only choice for external communication).

### Google Hangouts
Google Hangouts is our preferred video chat service (other than Slack calls for scheduled meetings).  [Please avoid Zoom](https://techcrunch.com/2020/03/31/zoom-at-your-own-risk/) if you can.


## Ad-hoc Meetings
:warning: Try to avoid meetings, and if one is necessary, try to make attendance optional for as many people as possible. 

### Why to Meet
Meetings can be useful in some cases to move a project forward, address a blocker, or resolve a miscommunication.  Meetings should not be called to share information (since you should do that with [documentation](#documentation-notebook)).

### How to Meet
Every meeting should:

 1. put all participants on equal footing
   1. Avoid "hybrid" calls, with some participants in one room and others remote (in that case, everyone should be in a Hangout)
   1. avoid bias for one timezone.  Schedule in a way that accounts for all participants.   
 1. be scheduled with as much notice as possible (using a Google Calendar invite)
 1. start on time and end on time 
 1. have a link to a Google Doc agenda in the calendar invite 
 1. include live note taking inline within the agenda rather than using a seperate "notes" section
 1. include a section in the agenda doc for outcomes - complete with next steps and who has agreed to do what

### Meeting Outcomes
If you've followed the guidelines, you should have a Google Doc with the agenda filled out with inline notes and an Outcome section.  This doc should live in the appropriate Shared Drive on Google Drive so that everyone who needs to access (or search) the document in the future can.

## Scheduled Meetings
Regularly scheduled meetings have specific, on-going purposes.

### Team Standups
Teams should generally have a "standup" meeting each day.  Team members should share what they did the previous work day, what they intend on accomplishing for the current day, and any blockers to their work in a team standup [Slack](#slack) channel _before_ the meeting.  The standup meeting can then consist solely of talking through blockers, considering the remaining week's goals, and sharing any immediate questions.

### Weekly All-hands
The weekly all-hands meeting is a chance for company leadership to share (already documented) company updates and take questions from anyone.  There may additionally be presentations from teams to share details of their particular work or recent projects.
