# Email Archive

Archive of emails relating to the planning of Software Carpentry at STFC 2022
(including notes from each planning meeting)

## Cast

E: Lead organiser  
P, K, J, I: Organisers  
All of the above plus M: Instructors  
B: UKAEA contact  
A: Group leader within SCD  
G: SCD Admin contact  
PY: Graduate & Industrial Placement Co-ordinator  
JM, TL: R34 Contacts  
RA: SSI Contact  
AB: STFC staff member  

## March

### Recruitment of organisers and instructors

From: E  
To: Graduate channels (Slack and Teams)  
Sent: 22 March 2022

I'm looking for organisers/instructors for this year's Software Carpentry workshop:

The Software Carpentry training workshop will run in September/October for new starters in computing roles. I'd like to extend this year's workshop to include more intermediate level content, but to do so we will need more people to help plan the logistics and teach the material. If you'd like to get involved with organising and/or teaching (training is available and the material is pre-written), please reply/DM/email me. All are welcome; if you were an attendee in the last couple of years your experience would be really useful to draw on.

If you want to help just at the workshop itself - with debugging, answering questions, etc. - we'll call for that closer to the time.

---

## April

### Meeting Notes 13 April 2022

From: E  
To: Organisers  
Sent: 13 April 2022  

Hi all,

Long email, the first two sections are the important bits to read.

Extra thoughts from the meeting:
*	I realised May is actually very soon and we should put the starter pack & support channel together ASAP – I’m going to give P and K actions to work on this
*	IMO dedicating and advertising some time for support encourages people to actually use the material and ask for support when they need it – perhaps we can pick out a week in each of May/July to keep a closer eye on the support channel and be available for debugging (or recruit helpers for this). Let’s discuss this next time
*	drop-in sessions are another alternative, though I don’t know if drop-in sessions are ever well attended…
*	Finally, there’s also a Databases/SQL basics Carpentries module, link below – don’t know if it’s worth including in the workshop as it’s a bit more specialised, but could go in the starter pack as well in case it’s useful to some

Actions:
*	I to check intake details with IP coordinator (see notes below for what’s needed)
*	E to check same details with grad coordinator
*	J to check same details with apprentice coordinator
*	P to look through the two Python modules below and suggest which one better fits our needs
*	K to draft the ‘starter pack’  – probably just a text document including links and a bit of context that we can send out as an email
*	E to set up next meeting (early May)
*	E to contact UKAEA guy (B) who ran the intermediate workshop there & get tips from him

Links:
*	Unix shell: https://swcarpentry.github.io/shell-novice/
*	Git: https://swcarpentry.github.io/git-novice/
*	Python (original): https://swcarpentry.github.io/python-novice-inflammation/ 
*	Python (newer with slightly different focus): http://swcarpentry.github.io/python-novice-gapminder/ 
*	Databases/SQL: http://swcarpentry.github.io/sql-novice-survey/ 
*	Intermediate development: https://carpentries-incubator.github.io/python-intermediate-development/ 
*	Instructor training course: https://carpentries.github.io/instructor-training/ 
*	Become an instructor: https://carpentries.org/become-instructor/ (Open Instructor Training Program option)

Notes from the discussion:
*	Material
    *	definitely UNIX and Git basics
    *	perhaps add Python basics, as basic Python knowledge is expected for the intermediate course
    *	full intermediate software development course (switching PyCharm to VS Code for instructor familiarity reasons)
    *	short extra "showcases" of instructors applying the tools in practice, e.g. WSL, Windows terminal, VS Code extensions
*	format
    *	prefer half days over full days for information retention
    *	aim for similar hybrid format to last year as this worked quite well
    *	2-half-day basics UNIX & Git
    *	2-half-day basics Python? (perhaps combined with the UNIX and Git, with option to attend either or both)
    *	4-half-day intermediate software development
    *	intermediate course should have a week or two gap from the basics course to give people a chance to apply the basics they learned (also helps with organisation)
*	graduates start dates are staggered this year – May, July, Sep
    *	we will run courses after the September start only as we expect the earlier groups to be small (and organising many workshops is a lot of work!)
    *	instead collate and distribute ‘starter pack’ with the Carpentries material to earlier starters, as the basic skills are often needed right after starting
    *	support channel for those working through the starter pack on their own – Slack or Teams workspace (I favour Slack)
*	instructor training
    *	can sign up for training through the Carpentries, but the waiting list is long and there's a good chance you don't get a place before autumn
    *	instead work through the instructor training material during the summer and set up some sessions to practice live coding in July/August (supported by E)
*	dates and numbers
    *	need to check with scheme coordinators
        *	number of new starters in computing roles
        *	start dates (September-ish or staggered)
        *	induction dates

---

From: E  
To: Organisers  
Sent: 13 April 2022  

One more thing: I’ve added everyone to an #organisers-2022 channel on the Slack workspace we used for helpers at the workshop last year - [redacted] (K, you should have an invite to join the workspace since you weren’t in it already). Perhaps we can re-purpose the workspace with support channels too – let’s discuss next time.

---

## May

### Agenda 13 May 2022 

From: E  
To: Organisers  
Sent: 13 May 2022

Hi all,

Agenda for today’s Software Carpentry planning meeting:
*	Discuss potential attendee numbers, start dates, induction dates
*	Decide whether to offered dedicated support time for May/July starters working through material alone 
*	Review feedback from A (below) and B's experience running the course at UKAEA 
*	Confirm what modules to include
*	Choose workshop dates in September/October
*	Starter pack and support channel
*	Next steps – workshop website, registration form 
    *    One registration/website or multiple?

I asked A ([redacted] group leader who hosts many grads, IPs and apprentices) what she thought of the intermediate course and what she felt was important to cover:  
> The concepts/skills that I think would be great to cover are testing, which I see that Python intermediate course covers partly. It would also be good to cover how to do code reviews, and even perhaps how to tackle changes in legacy code that has no tests. Also, how to develop APIs. 
In terms of languages, python is a very good language to learn, as it is versatile, and we use it for multiple things. Object-oriented programming is good to know.

---

### Meeting Notes 13 May 2022 

From: E  
To: Organisers  
Sent: 13 April 2022  

Hi all,

Added a couple of extra actions since the meeting so please double check yours.

Actions:
*	E to migrate [stfc-carpentries-workshops](https://github.com/stfc/stfc-carpentries-workshops) repo to the stfc org and get everyone write permissions
*	K to finalise the starter pack, convert it to Markdown format, and add it to the stfc-carpentries-workshops repo
*	Everyone to add their favourite extra resources to the starter pack once it’s on GitHub
*	J to set up the workshop-template for this workshop - last year’s [repo](https://github.com/elichad/2021-10-05-ral-online) and [website](https://elichad.github.io/2021-10-05-ral-online/) may be useful to reference as I had to do some customisation for hybrid stuff (shout in Slack if you run into issues) 
*	E to ask SCD Admin team to set up the registration form
*	I and K to ask for stfc organisation and Carpentries team access on GitHub (try contacting [redacted] or anyone else with owner role: https://github.com/orgs/stfc/people?query=role%3Aowner )
*	I to update Slack workspace – change name, make URL more memorable, create support channel (or channels? One for each course?), make existing helper channels private
*	P to book R34 computer training room for all the course dates and flag if any are unavailable

Notes:
*	I counted 9 apprentices, 19 grads, and 10 IPs in computing roles. This is hard to count accurately since job titles are all we have to go on, but it seems that an upper limit of 50 attendees is reasonable.
*	We will set up some drop-ins for May and July shortly after sending out starter pack material
*	We will all keep an eye on the support channel for questions – this will be a channel in the existing Slack workspace
*	Reviewed A’s feedback – we agree that code review should be showcased if not already present in the course material, but legacy code and APIs are a bit too advanced/specialised to cover.
*	Reviewed B’s [blog post](https://bielsnohr.github.io/2022/04/25/review-intermediate-course.html) – based on his experience we will extend the intermediate course to 5 half days rather than 4
*	We will use the ‘inflammation’ Python module rather than ‘gapminder’ as it seems more relevant from a software developer perspective
*	Selected dates (I think we previously agreed on 9am-1pm each day, shout in Slack if you have other opinions):
    *    4-5 Oct: Unix & Git
    *    11-12 Oct: Intro to Python
    *    1-3 & 8-9 Nov: Intermediate Software Development
*	I expect to be out of work for approximately one month in the autumn due to surgery – I will let you all know as soon as I have those dates
*	Considered putting the starter pack on Sharepoint, realized we all dislike Sharepoint but do like the idea of a living document, so we’ll put it on GitHub instead, as part of the pre-existing stfc-carpentries-workshops repo
*	Starter pack content itself looks good, should add course dates and useful extras such as https://explainshell.com (ideally without becoming overwhelming – we could split to multiple pages if needed)
*	We need to set up the workshop website and event registration – we will use one site/registration form to cover everything, but allow people to choose between in-person and online attendance for each ‘chunk’

### Action: P to book R34 computer training room for all the course dates and flag if any are unavailable

From: I  
To: Organisers  
Sent: 13 May 2022  

Now that calendar invites have gone out I think there’s another action on me to check with Facilities IT about the availability of their training room. 

Do we want the room for all of the course dates (if it’s available)? I assume so, but I thought I’d check before contacting them.

---

From: E  
To: Organisers  
Sent: 13 May 2022  

Yes, we want the training room for all course dates if possible. The invites that P sent out include booking the R34 Training Room – we did have to change Thursday 3 Nov to Monday 7 Nov due to an existing booking of the room (see Slack) but all the other dates are fine.

It probably is worth getting in touch with Facilities IT directly though to give them a heads up on what we’re planning, if you could do that.

---

## June

### Meeting Notes 09 June 2022

From: E  
Sent: 09 June 2022  
To: Organisers  

Hi all,

Actions:
*	K and I to join STFC organization on GitHub
*	K to find out about the graduate ‘streams’ from grad liaisons and HR – how they are allocated and whether we should be advertising to the computing stream directly.
*	P to check that there isn’t construction work planned around the R34 Training Room during the workshop, and confirm the number of computers available (12? 16?)
*	P to forward course invites to CR12, which appears to be free for all dates right now
*	P to choose a Carpentries Instructor Training course to attend
*	E (and anyone else who fancies it) to review starter pack
*	E to chase SCD Admin to set up registration form
*	E to check in with B about his recent second run of the intermediate course and course updates for VS Code
*	E to schedule next meeting in early July
*	E to check with SSI that other people can spend & claim the SSI funding while E is on medical leave
*	Everyone to add their favourite resources to the starter pack

Notes:
*	One day of the intermediate workshop was changed from 10 Nov to 7 Nov. Finalised dates are 4-5 Oct, 11-12 Oct, 1-2 & 7-9 Nov. R34 is booked for all these dates, but we should grab another room as well.
*	The workshop website ([site](https://stfc.github.io/2022-10-04-ral-carpentries/), [repo](https://github.com/stfc/2022-10-04-ral-carpentries)) and resource pages ([site](https://stfc.github.io/stfc-carpentries-workshops/), [repo](https://github.com/stfc/stfc-carpentries-workshops)) are now live. The workshop also appears on the Carpentries website, thanks J for submitting it!
*	The workshop has been submitted through the SCD Events form and I’ve been waiting for SCD Admin to get back to me to set up the registration
*	The Slack workspace URL has been updated to [redacted] and a #support channel has been added
*	P encountered the UKAEA RSE team (which includes SSI Fellows [redacted] and B) at another event  – they expressed interest in doing a yearly joint workshop in the future
*	Noted that the Python course uses Anaconda for installation – instructors need to be familiar with this and know how to launch Jupyter Notebook from Anaconda
    *    Jupyter Notebook will “eventually” be replaced by JupyterLab. We need to check the releases included with Anaconda closer to the time of the workshop and make sure the install instructions are up to date.
    *    VS Code can also be installed and run through Anaconda. Not sure if we should promote this though.
*	My surgery has been scheduled for 28 Oct. I’ll be off for 6 weeks after that, so I’ll be missing the intermediate course. 
*	P and K told us about graduate ‘streams,’ but we’re not sure why grad HR hasn’t encouraged us to use the computing stream to advertise stuff. We think it’s best to share the workshop with all grads and their LMs anyway though.

--- 

### Action: P to check that there isn’t construction work planned around the R34 Training Room during the workshop, and confirm the number of computers available (12? 16?)

From: JM  
Sent: 26 May 2022  
To: P  
Subject: R34 Training Room booking  

Hi P, 

I see you’ve requested the R34 Training room for Software Carpentry sessions. 
I’ll go through and approve them all in a second. 

If you’d like to see the room in advance of your sessions, please get in touch with me, as I’m on site most Tuesdays – Fridays (although after today not until 7th June) and happy to show you the room so you can check it is has everything you need. Obviously you’re welcome to look at the room anytime, but it is generally locked, and people have struggled to find it as I haven’t yet got any signage put up (on my to do list, so hopefully would be done by your sessions anyway). 

If you will need anything installed on the computers or if the computers need to be set up in a particular way or anything, can I please point you to my colleague [redacted] in Facilities IT Service Desk, who is best reached via FITservicedesk@stfc.ac.uk as he deals with the technical side of the room. 

Best wishes, 
JM 

---

From: P  
Sent: 09 June 2022  
To: JM  
Cc: Organisers  
Subject: RE: R34 Training Room booking 

Hi JM,

Thanks for this, and sorry for not replying sooner. Though I’ve not seen it myself, the R34 training was used for last year’s Software Carpentry sessions, so in general we should be happy with it. Having said that, I understand that there is ongoing construction work that might make the room more difficult to access – do you have any idea of what impact this might have come October? Also what’s the capacity / number of computers available in the room?

In terms of the computer setup we’ll probably get in touch with FIT closer to the time when we’re sure of the exact versions that we’d want installing.

---

From: JM  
Sent: 09 June 2022  
To: P  
Cc: Organisers  
Subject: RE: R34 Training Room booking 

Hi P, 

In terms of construction work impacting access to the room, on the attached map there are two routes to get into the training room, blue and orange. The orange route is completely blocked by the building site currently, and I’m not sure what it will be like in October (I will try to find out). 

If people are ok with steps, the blue route is fine. If people need to avoid steps, the best route I’ve identified so far, is to go along the roads round the back of R12 (on road 11) and enter there, and then go through the building to R34 Training room. I’m pretty sure that is step free, although need to walk it fully to confirm. If anyone needed to do this, I’d also look at asking whether it’d be possible for someone to park near the R12 entrance, as otherwise it’s quite a long distance around the buildings and has to be on the road, which seems unsafe for someone with mobility constraints. 

Sensible to contact Service Desk closer to the time with versions, etc. that you require, I’m not sure how much noticethey need, so can try and find that out for you. 

There are 12 computers in the room (two monitors each) for learners, plus an empty desk at the front (for the person delivering the training to sit at and they are apparently expected to have their own laptop). Is that enough for you, or would you be aiming to squeeze in a few more people and like me to investigate that? 

JM 

---

From: P  
Sent: 09 June 2022 13:19  
To: JM  
Cc: Organisers  
Subject: RE: R34 Training Room booking  

Hi JM,

Thanks for the pdf – I did see the version on Sharepoint (without the orange line and with the road 11 directions) but wasn’t sure if it was up to date (or would be, come October).

In terms of capacity that’s fine; we were planning to book a second room for those we can’t fit in the training room and just wanted to check how many we could fit.

Thanks again for all the information,

P

---

From: JM  
Sent: 11 August 2022  
To: P  
Cc: Organisers  
Subject: RE: R34 Training Room booking 

Hi P,

Apologies for the very slow response, but I’ve finally remembered to ask the contractors working on the NQCC building project, and there are no plans to move the hoarding, so the access will remain as it is currently for the foreseeable future (construction work is due for completion in Q3 2023).

The Wates contractors said that if there was a need for access via the ramp, they could potentially look at timings and see whether they could facilitate but someone else from estates suggested using another room may be a better solution. As you have multiple sessions and you’re already intending to have a second room, I think it would probably be easier (and safer) that anyone who needed ramp access would go to that room instead? They suggested visitor centre or CR12/13 as being good in terms of accessibility. 

Depending on the size you need, I’d say that there is also a new meeting room on ground floor of R3 (G34, probably called ISIS meeting room R3 G34 in outlook) and there is at least one disabled toilet on ground floor of R3 (and the other toilets are gender neutral). The room has only recently become available, so may have more space than other rooms. It’s only for about 8 people though, and I’m not sure if it is set up for all of those people to be able to plug laptops in. 

Regarding the R34 training room and the blocked ramp, I think it is technically possible to get to it currently, but it means going on road 11 (no pavement) all the way round to entrance of R12, in through R12 and along, so it’s adding a lot of distance to the route, some of which is on a road, which seemed non ideal for anyone with mobility issues. If you think anyone will do this, do let me know and I’ll go walk it and check that it doesn’t have steps and that I can’t see any better options. I would think though, that other rooms may be better as I suspect they will have nearer accessible toilet facilities too? 

I have also got a few signs up in place now to guide people through R12 to R34 and along to the training room. So for most people, it should be easier than it was going through the buildings to find the room. 
Hope that’s helpful, and apologies for the huge delay! 

JM

---

From: P
Sent: 11 August 2022
To: Organisers  
Subject: FW: R34 Training Room booking 

Hi everyone,

Just to update on room accessibility, it seems the access situation for the R34 room will remain as it currently is. Do we know yet if we have anyone with accessibility requirements attending, or how many in total? As Julia mentioned CR12 as being a better option and we already have that booked it might be that (provided we have enough attendees to justify manning both rooms) we can just recommend CR12 for anyone who would struggle with the long way round to R34?

Cheers,

P

---

From: E  
Sent: 09 June 2022 13:19  
To: P  
Cc: Organisers  
Subject: RE: R34 Training Room booking 

Hi P,

Thanks for this. We have to ask G to send us the registration list whenever we want to check on it, so I’ll ask for that now ahead of next week’s meeting. I think it’s fine to assign people to CR12 if they need step-free access, the only challenge would be if they also need a computer provided. I suggest we work things out with the attendee directly if someone does hit that combination.

Thanks,

E


### Action: E to chase SCD Admin to set up registration form

From: G  
Sent: 08 June 2022  
To: E  
Subject: Registration Form

Hi E,

Sorry for the delay in getting back to you about this event!

I will aim to get a draft registration page done for this asap – where are the workshops taking place?

I see you are looking to do these as hybrid but where will the in person aspect be?

Kind regards,
G

---

From: E  
Sent: 10 June 2022  
To: G  
Subject: RE: Registration Form

Hi G,

We’ve booked CR12 and the R34 Training Room. 

I dug out the questions and blurb I gave you last year and made some tweaks since we’re making this a series of workshops now, they’re included below.

One problem we did have last year was people not remembering what options they’d selected when registering – are confirmation emails sent out that include people’s selections?

[Blurb and questions moved to [registration-templates.md](registration-templates.md)]

Thanks,

E

---

Subsequent regular contact between G and E omitted. E asks G for the up-to-date list of registrations every month or so until September, then more frequently as the first workshop approaches. G responds with the relevant spreadsheet.

---

### Action: E to check with SSI that other people can spend & claim the SSI funding while E is on medical leave

From: E  
Sent: 13 June 2022  
To: RA  
Subject: SSI Funding

Hi RA,

I requested some SSI funding to run Software Carpentry at STFC – we are planning to run this as a series of workshops over the course of October and November. However, I’ve now been scheduled to have surgery in late October and so I will be on medical leave for the last half of this workshop series. My co-organisers will be continuing to run things without me, but I’m just wondering how funding claims work in this situation. Can my colleagues claim expenses from my fellowship pot directly, or would I have to submit claims on their behalf? I expect to be off work for at least six weeks, so there might also be some delay if I need to submit any claims (possibly even until January) – is that likely to be problematic?

Thanks,

E

---

From: RA  
Sent: 13 June 2022  
To: E  
Subject: SSI Funding  

Hi E 

You can either get them to fill and sign in expenses claims with their details or you can submit expenses claims on your name and settle it separately with your colleagues. There is a third, hybrid way, which is when you complete and sign the expenses claim but put someone else’s bank details. I don’t recommend this last option.

In the first case, your colleagues will not be able to submit the expenses via lowFAT, therefore I suggest they might email them to finance@software.ac.uk / cc fellows-management@software.ac.uk quoting the relevant lowFAT link. In this case, please make sure you pass on to them all instructions on how to submit expenses claims properly (https://www.software.ac.uk/SSI-expenses-guidEnes).

Thanks

All the best,
[redacted] (representing RA)

---

## July

### Meeting Notes 11 July 2022

From: E  
Sent: 14 July 2022  
To: Organisers

Hi all,

Sorry for the delay writing these notes up. I’ve already got some updates so I’ll go through those first.

Extra bits from after the meeting:

Copied from Slack:
> I’ve been thinking about the (visible) diversity of our instructor set and how we can improve it – I know we already provisionally assigned content to people, but I think it’d be a good idea to make some space for one or two more people from under-represented groups, if there are some who are interested in instructing.

K and J agreed, so I’ll include this in the call for helpers.

B from UKAEA sent over the supplementary material they used for covering VS Code: https://ukaea-rse-training.github.io/python-intermediate-development/vscode/index.html . Their instructions were something along the lines of "when you hit a part of the course about PyCharm, go to this document and find the analogous bit about VSCode. Try to make sure you can get the same functionality in VSCode that is described for PyCharm."

The UKAEA instructor slides I mentioned are here: https://github.com/ukaea-rse-training/python-intermediate-development/tree/ukaea-instructor-led/slides 

B also told me that section 3 of the intermediate course (Software Design and Architecture) was the slowest bit to get through, sounds like they spent most of their extra half day on it.

Last year’s Slido event is here: [redacted]. You might need an account to access it.

Last year’s slides and various other bits are on my personal OneDrive – I’ll see if I can set up a group area instead so others can add to them. I’ll probably stick the slides on GitHub but some things are better kept private (e.g. the attendee list!)

Stuff from the actual meeting:

Actions:
*	I to join STFC organization on GitHub
*	K to ask [redacted] if the SCD Early Careers resources page can be made available to all staff (or at least all early career staff)
*	K to finish up 'Which courses are right for me?'-type page for stfc-carpentries-workshops by Friday 
*	E to check in with B about his recent second run of the intermediate course and course updates for VS Code
*	E to send out a call for helpers/instructors by Friday
*	E to ask PY to circulate registration form & starter pack by Friday
*	E to move last year’s resources to a shared area
*	P to make an account on slido.com 
*	P to attend instructor training
*	J to update schedule and dates on workshop website by Friday

Provisional teaching allocation (subject to change):  
Unix 1-3 – E  
Unix 4-7 – I  
Git 1-7 – K  
Git 8-13 – I (with K as the ‘collaborator’ mentioned in episode 8 & 9)  
Python 1-2 (day 1) – J  
Python 3-6 (day 1) – P  
Python 7-9 (day 2) – J  
Python 10-12 (day 2) – P  
Intermediate section 1 – K  
Intermediate section 2 – J   
Intermediate section 3 – P  
Intermediate section 4 – I  
Where two people teach on the same day, they’ll act as backup for each other. For the intermediate material, K/P and J/I are the provisional backup pairings, but I think we’ll have to change this up if we get extra instructors.

_[Note from the future (11 Oct 2022): The split for Unix ended up being 1-4 E/5-7 I, with the break after episode 4.]_

Notes:
*	The graduate streams are based on what chartership track people choose (for computing, it’s BCS) – so we can’t make use of these as not everyone who does computing tasks will be on the computing stream (some choose IoP/IEEE/etc)
*	R34 has 12 computers, plus a desk for the instructor who should bring their own machine
*	There is no construction work planned close to R34 right now, but this could change
*	Instructor training courses open for registration one month in advance, and often fill up within a week, so the window to register is actually quite small. P has booked onto a course at the end of July
*	J shared his notes from his course in Slack – thanks!
*	Registration form is now set up and ready to share
*	Anyone can make claims against my SSI funds – details below
*	The SCD Early Careers group have set up a Sharepoint page to share resources – this serves a similar purpose to our starter pack, but currently it isn’t accessible outside the group without requesting permissions. We should try not to duplicate this material but instead make sure both pages link to each other.
*	Only one of us needs a Slido membership to ‘host’ the events, everyone else can contribute polls etc as ‘guests’ – P volunteered to have the membership (we’ll sort this out closer to the time as the SSI expenses system is down for a couple months and there’s no need for you to be out of pocket for ages)

From the SSI:
> You can either get them to fill and sign in expenses claims with their details or you can submit expenses claims on your name and settle it separately with your colleagues. There is a third, hybrid way, which is when you complete and sign the expenses claim but put someone else’s bank details. I don’t recommend this last option.  
In the first case, your colleagues will not be able to submit the expenses via lowFAT [the SSI Fellows portal], therefore I suggest they might email them to finance@software.ac.uk / cc fellows-management@software.ac.uk quoting the relevant lowFAT link. In this case, please make sure you pass on to them all instructions on how to submit expenses claims properly (https://www.software.ac.uk/SSI-expenses-guidEnes).


Thanks,

E

---

### Action: E to send out a call for helpers/instructors by Friday

From: E  
Sent: 14 July 2022  
To: Organisers

Hi all,

I’ve made a Google form for helper/instructor sign-up – unfortunately Doodle doesn’t let you have multiple options in the same time slot any more (ie the RAL/online split), but the Google form helps us gather some extra info anyway. Could you all fill it out so we can collect everyone’s availability in one place: [redacted - questions preserved in [registration-templates.md](registration-templates.md)]

The link to edit the form/see responses is here: [redacted]

Let me know (ideally today) if you think anything needs changing.

Thanks,

E

---

Registration emails circulated among new grads, apprentices, and IP students.

Helper/instructor recruitment emails circulated among older grad cohorts and helpers from 2021.

Those emails have been moved to [email-templates.md](email-templates.md).

---

From: AB  
Sent: 03 August 2022  
To: E  
Subject: Software Carpentry workshops – Call for helpers & instructors 

Good Afternoon E,

I have seen the email below and think the intermediate research software development course looks really good. I have recently led a graduate project that developed a piece of software, so I realise how useful these skills are and I think it is brilliant you are delivering tuition on the subject. 

In my experience of developing this software (which is limited) I found a key problem was how do you get from a description of the problem to a design for the domain layer that is optimal (if not half decent) in the way that it assigns responsibility to software objects. I found that the GRASP patterns were very useful in solving this problem. Additionally, I found that expressing object interactions as a system sequence diagram was an invaluable part of the software design process and a good way of ensuring that I was applying the correct design principle. 

I was wondering if there was any scope to include these GRASP patterns and diagramming techniques in the course. 

Kindest Regards, 
AB

---

From: E
Sent: 03 August 2022  
To: AB  
Subject: Software Carpentry workshops – Call for helpers & instructors

Hi AB,

Thanks for getting in touch! I’m not actually familiar with GRASP patterns myself, though I’ve done a bit of diagramming and I definitely agree that that’s something that benefits a design.

The intermediate course is still in beta and it’s our first time running it this year, so we’re planning to stick closely to the current course material as we don’t know how long each part will take with our STFC audience. However, we could add something to our ‘extra resources’ list, which we will point people to at the end of the course. Can you share any good beginner-friendly resources that cover GRASP patterns and/or diagramming techniques?

I’d also recommend raising this as an issue on the course repository for discussion, I know the course developers are rethinking that whole section at the moment and your input would be welcome: https://github.com/carpentries-incubator/python-intermediate-development/issues. It might be that these could be included in future versions of the course material.

Thanks,

E

---

## August

### Meeting notes 16 August 2022

Hi all,

Long overdue write-up from the August meeting. There’s some extra notes based on completed actions.

Actions (many already done and not evenly distributed, oops):
* P to contact Franz Lang to see why he registered 
* P to make some analytics stuff for the registration form so we can track how many people are attending each workshop online/in person 
* E to dig out last year’s preliminary registration numbers and see how they compared to the final numbers 
* P to make some analytics for the helper sign-up form data so we can figure out how many people we have available for either/both formats on each day
* E to check recent Zoom versions for new features we could use
* E to respond to the R34 people about software versions
* J and P to finish their Instructor checkout process
* E to contact M; all of us to negotiate what he’ll teach according to his knowledge 
* E to create September meeting (this will be some time next week)

Finalised teaching allocation:
Unix 1-3 – E (backup: I)
Unix 4-7 – I (backup: E)
Git 1-7 – K (backup: I)
Git 8-13 – I (with K as the ‘collaborator’ mentioned in episode 8 & 9; backup: K with E as collaborator)
Python 1-2 (day 1) – P (backup: M)
Python 3-6 (day 1) – M (backup: P)
Python 7-9 (day 2) – J (backup: P)
Python 10-12 (day 2) – P (backup: J)
Intermediate section 1 – K (backup: I)
Intermediate section 2 – J (backup: K)
Intermediate section 3: Paradigms, OOP, Functional Programming – M (backup: P)
Intermediate section 3 Software Design, Persistence - P (backup: M)
Intermediate section 4 – I (backup: J)
Every teaching stint includes a designated 'backup' - someone who should familiarise themselves with the material such that they're comfortable to help answer questions and would be able to step in to teach in an emergency (doesn't need to be practiced, just have a knowledge of how the lesson goes). This person also acts as a natural partner to practice material with (partners should organise this practice themselves).

Notes:
* As of 16 Aug we had approximately 12 registrations for each workshop, with a preference for online attendance. As of today (06 Sep) we’re up to 15-16 per workshop with about two-thirds of people wanting to attend online. There are 21 registered individuals in total so far.
    * I am surprised how many people have registered for the Python workshop since it is very basic and most folks coming into computing roles probably have the knowledge already; we should send out an email to attendees closer to the time reminding them that it is for absolute beginners just in case they have misunderstood the level. (maybe it’s possible that we’ve reached beyond the regular computing roles by emailing all the graduates)
    * P was concerned by the registration of someone that he knows doesn’t need to attend the basic workshops, but has since reached out and established that he only really wanted to attend the intermediate one
    * I’m also surprised how skewed things are towards online attendance even when a lot of people have returned to site part-time. We don’t need to do anything about this, it’s just interesting to observe
* Last year we had 27 registrations by 10 Sep – 10 in person and 17 online. Our final attendance was 52 – 16 in person and 36 online. So I’d expect us to roughly double our registrations from today if the same pattern holds this year.
* We had one additional instructor volunteer – M. He’s got school teaching experience and is happy teaching Python and computing concepts, but less confident with Git. Thanks P and J for helping to share out the chunks of teaching.
* We know a few people among the SCD grads and ex-grads who we think would make good instructors and who also belong to underrepresented groups, but none of them volunteered themselves through the helper signup form. Those people will definitely have seen the call for instructors, so they probably have good reasons for not volunteering and we should not chase them further (e.g. many of them are heavily involved in outreach and may not have the time to spare). 
    * Next year we will try to reach out earlier in the planning process to individuals who we know have the right skill sets for instructing and organising to see if they are interested, as well as advertising the opportunity through staff networks and the SCD EDI group to try and broaden our reach beyond our own personal networks.
* There have not been any features added to Zoom in the last year that are useful enough to make a newer version mandatory for attendees, so we’ll stick with the Zoom 5.7.3+ requirement from last year. We’ll also use the most recent Anaconda, VS Code, and Git Bash versions.
* UKAEA’s VS Code extras should be added to the central version of the intermediate course material ‘soon’ – B intends to make this PR before our workshop
* I mentioned Windows Sandbox, which seems a very useful tool in general but not quite appropriate for our needs as software and files are deleted when the sandbox is closed, and we want people to leave with a software setup that works permanently!
* We will mix up the breakout room groups for each workshop even if there’s a lot of overlap in attendees – but within a single week, breakout groups should remain the same on each day (this helps to build a bit of group rapport and support)
* J and I tried installing Anaconda to see how easy/difficult this is. It took 20+ minutes to install, so we need to emphasise to attendees that this must be done before the workshop. We should consider running a drop-in before each workshop to assist anyone who has difficulties installing Anaconda or anything else.
* We now have a SharePoint group for Carpentries stuff: [redacted] . Click ‘Documents’ for slides etc. This also created a group email address: [redacted]. It’s not quite a mailing list, but you can read emails to this address under Groups > Carpentries in Outlook. It’s probably good to direct attendees to contact this email address for updating their registration, getting support with installation, etc. as long as we’re clear about who’s responsible for it (let’s discuss this next meeting)

Thanks,

E

---

### Action: E to respond to the R34 people about software versions

From: TL  
Sent: 15 August 2022  
To: P  
Subject: Software Carpentry course 

Hi P

I can see your bookings for the R34 training room in October and November.
To ensure the machines have the software for the course installed on them, can you advise what you will need? (and if there is a particular version required).

Regards
TL

---

From: E  
Sent: 15 August 2022  
To: TL  
Subject: Software Carpentry course 

Hi TL,

Sorry for the slow response. The machines will need:
•	[Git for Windows](https://gitforwindows.org/) 2.37+ (upgrade from last year)
•	[Anaconda](https://www.anaconda.com/products/distribution) 22.05 with Python 3.9 (not used last year, this is the current version as of today)
•	[Visual Studio Code](https://code.visualstudio.com/) – this should be installed as part of Anaconda but please double-check this and install it manually if needed

For the first two, please follow the install process described on this page to get all the settings correct for our workshops: https://stfc.github.io/2022-10-04-ral-carpentries/ 

Thanks,

E

---

From: E  
Sent: 28 September 2022  
To: TL  
Subject: Software Carpentry course 

Hi TL,

Can you confirm if these softwares have been installed on the machines in R34? Our first workshop begins on Tuesday so we need them in place by then.
I also realized that the Anaconda install does not include VS Code by default as I had thought, so VS Code will need to be installed separately after all.

Can you also confirm if there are working speakers/large screen in the room that can be connected to a laptop? We will be connecting to a zoom call through an instructor’s laptop and I remember we had some trouble with the audio last year. 

Thanks,

E

---

From: TL  
Sent: 28 September 2022  
To: E  
Subject: Software Carpentry course

Hi E

I’ve installed the required software on all 12 machines, using the installation guide provided for Git and Anaconda.
For Anaconda, I can’t set the PATH variable for an All Users installation, this will need to be done when the user of each machine logs in.

I’ve added your Fed ID to the remote desktop users group on TCPC-R34-01, feel free to remote in and take a look if you wish.

You’ll need to collect the key to the training room from R3, G.37 I’ll leave it on my desk.

Regards
TL

---

From: TL
Sent: 30 September 2022
To: E
Subject: Software Carpentry course

Hi E

Possibly the main screen at the front has speakers but I’ve not tried this. 
However, this is something that I’ve been pushing to get ordered so there will hopefully be an audio system in the future.

TL

[*Note from the future: The screen/room does have speakers built in. In 2022 it was straightforward for helpers to connect to these.*]

## September

### Meeting notes 12 September 2022

Hi all,

Notes from Monday – allocated some unassigned actions to people so, as ever, please double check yours.

Actions:
* Everyone to upgrade to Office 365 (especially those involved in logistics)
* E to email the people who registered from [external university] and let them know they’re not eligible to attend
* K to update workshop website to remove individual emails and include the Carpentries group email
* K to update workshop website to clarify what is meant by ‘STFC staff’ (i.e. it doesn’t include STFC-funded researchers at other institutions)
* P to purchase premium Slido account & submit expenses claim to SSI
* P to create Slido events covering the workshop dates & invite everyone as collaborators
* J to ask around in the Carpentries community about how to manage the pre- and post-workshop surveys
* E to schedule helper briefing, instructor meetings, logistics meeting, and drop-in sessions
* E to update planning timeline document

Notes:
* The Carpentries group email has been updated to Carpentries@stfc.ac.uk.
* We will direct people to contact the Carpentries group email when they have questions, so it is easier to cover when people are on leave/sick/etc
* We discovered some idiosyncrasies of the SharePoint group email system, namely that 
    * Outlook 2016 doesn’t seem to play very nicely with it, but the browser and Outlook 2020/whatever’s in Office 365 are better
    * Replies are sent as individuals, not as the group, so you need to always reply-all to make sure the rest of the group can continue to see the conversation
    * You can ‘subscribe’ to the group to have the emails copied to your inbox (so that you get notifications for them)
    * It is not the same as a mailing list, but serves a broadly similar purpose in our case. We decided that making a mailing list as well wasn’t worth it
* There are a number of responsibilities that need to be allocated in the run up to the workshops – these fall broadly into three groups:
    * Teaching responsibilities: This was already allocated, but covers teaching material, backing up other instructors, making slides/notebooks/Slido questions/etc, welcome/wrap-ups at the start and end of each day
    * (Zoom) Hosting responsibilities: managing waiting room, breakout rooms, watching for questions & comments in Zoom/Etherpad/Slack (last one will be helpers only). 
    * Logistics responsibilities: Allocating people to rooms ahead of the workshops, booking catering, emailing attendees with advance information, watching the Carpentries group inbox, arranging access accommodations where needed
    * Note: in a change from previous messaging, the host will not do the welcome/wrap-up comments, because that’s incompatible with handling the waiting room and breakout rooms! Instead, instructors can do this – it’s the same slides each time so barely any extra preparation needed.
* Logistics will be handled by E, J, and K
* Hosting has to vary more by its nature:
    * Unix & Git: P
    * Python: K
    * Intermediate days 1,2,5: P
    * Intermediate day 3: K
    * Intermediate day 4: J
* No backups are specified for hosting, the job can be taken over by anyone that’s present on the Zoom (even regular helpers if needed)
* I is not very available in the next couple of weeks before the first workshop so has opted out of logistics (I’ve also avoided giving him actions for this reason)
* The pre- and post-workshop surveys pose some challenges. It would be nice to collect data for each course, especially as the intermediate course is new and would benefit from having separate feedback because of that. But the Carpentries infrastructure only gives us one survey link to go along with the website, so how can we collect those responses on a per-course basis? This is one to direct to the wider Carpentries community as we are kind of stuck for ideas.
* We should plan some meetings in the week before the first workshop for sorting logistics, checking in with instructors, and briefing helpers. We should also have an instructor meeting before the intermediate course since people might be preparing in the few-weeks gap we have before it. I’ll schedule them and we can cancel some if we decide they are no longer needed.

Thanks,

E

---

Calendar invites created for the workshop days and pre-workshop drop-ins, and circulated to whoever needed them at this time.

After the final start date for new starters (mid-late September), requested that registration info be re-circulated.

---

All subsequent internal communication before the course start took place in Slack.

---

## October

All attendees and helpers were contacted with workshop info ahead of each workshop, following templates in [email-templates.md](email-templates.md) (with customisation per-course as necessary).

Recordings, slides, Etherpad link, full course material, and post-workshop survey were sent to all attendees afterward.

---

From: GL  
Sent: 06 October 2022  
To: E  
Subject: Software Carpentry registration

Hi E,

I have received the below message from [redacted] and while looking into this I have noticed that the registration page has reached the 50 person capacity. 

How would you like me to respond to [them] and do you need this capacity extending?

Kind regards,
GL 

---

From: E  
Sent: 06 October 2022  
To: GL  
Subject: Software Carpentry registration

Hi GL,

We asked the admin team last week to open the registrations to capacity 53 as we had some duplicate/invalid registrations, but I think this got lost in an email flurry. In the end we started accepting extra registrations via direct email to Carpentries@stfc.ac.uk with answers to the registration questions – we tried to circulate this request to potential attendees as best we could, but clearly this person was missed which is a shame.

We’ve also hit capacity for some of our courses due to the number of helpers we have available, so we’re now adding those new registrants to a waiting list.

Could you please update the registration form to add a note saying potential registrants should contact the email above directly? I’ll also contact [redacted] with the recordings etc. from the workshop and help them get on our waiting list.

It’s become really cumbersome for us to do all this back-and-forth to manage our event, to be honest, especially with lots of last-minute changes and registrations and not being able to access or update the form ourselves. I’d be happy to chat sometime about how the system could be improved, but we’ll probably manage registrations ourselves in future – it seems easier for all of us.

For clarity, please don’t change the registration form capacity now.

Thanks,

E

---

From: E  
Sent: 07 October 2022  
To: TL  
Subject: Software Carpentry course

Hi TL, 

During our Git workshop this week, a few attendees created SSH keypairs on the machines in R34 and used them to connect to GitHub. We’ve asked those attendees to disconnect the key on the GitHub side after the workshop, but for safety, could you also remove these SSH keys from the R34 machines themselves? They would have been created on Wednesday 5 Oct. 

Thanks,

E