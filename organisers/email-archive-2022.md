# Email Archive

Archive of emails relating to the planning of Software Carpentry at STFC 2022
(including notes from each planning meeting)

## Cast

E: Lead organiser  
P, K, J, I: Organisers  
All of the above plus M: Instructors  
B: UKAEA contact  
A: Group leader within SCD  
PY: Graduate & Industrial Placement Co-ordinator  
JM, TL: R34 Contacts  
RA: SSI Contact  
AB: STFC staff member  

## Recruitment of organisers and instructors

From: E  
To: Graduate channels (Slack and Teams)  
Sent: 22 March 2022

I'm looking for organisers/instructors for this year's Software Carpentry workshop:

The Software Carpentry training workshop will run in September/October for new starters in computing roles. I'd like to extend this year's workshop to include more intermediate level content, but to do so we will need more people to help plan the logistics and teach the material. If you'd like to get involved with organising and/or teaching (training is available and the material is pre-written), please reply/DM/email me. All are welcome; if you were an attendee in the last couple of years your experience would be really useful to draw on.

If you want to help just at the workshop itself - with debugging, answering questions, etc. - we'll call for that closer to the time.

## Planning

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

### Meeting Notes 13 May 2022 

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

### Action follow-up after 13 May 2022

From: I  
To: Organisers  
Sent: 13 April 2022  

Now that calendar invites have gone out I think there’s another action on me to check with Facilities IT about the availability of their training room. 

Do we want the room for all of the course dates (if it’s available)? I assume so, but I thought I’d check before contacting them.

---

From: E  
To: Organisers  
Sent: 13 April 2022  

Yes, we want the training room for all course dates if possible. The invites that P sent out include booking the R34 Training Room – we did have to change Thursday 3 Nov to Monday 7 Nov due to an existing booking of the room (see Slack) but all the other dates are fine.

It probably is worth getting in touch with Facilities IT directly though to give them a heads up on what we’re planning, if you could do that.

---

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
To: J  
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
To: J  
Cc: Organisers  
Subject: RE: R34 Training Room booking  

Hi JM,

Thanks for the pdf – I did see the version on Sharepoint (without the orange line and with the road 11 directions) but wasn’t sure if it was up to date (or would be, come October).

In terms of capacity that’s fine; we were planning to book a second room for those we can’t fit in the training room and just wanted to check how many we could fit.

Thanks again for all the information,

P

---

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

## Recruiting Instructors and Helpers - began July 2022

[moved to [email-templates.md](email-templates.md)]

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




