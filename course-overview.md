---
title: "Course overview"
layout: single
classes: wide
---

Welcome!  This is an overview of the fall 2021 edition of CSE232 ("Distributed Systems"), a graduate course in the Computer Science and Engineering Department at the UC Santa Cruz Baskin School of Engineering.

## Instructor

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/lindsey-kuper.jpg" alt="Lindsey Kuper" width="140" style="float: right; margin: 0px 15px 0px 15px; padding: 0px 15px 0px 15px;" />


Hi, I'm [Lindsey Kuper](https://users.soe.ucsc.edu/~lkuper/)!  (Feel free to call me by my first name.)

  - Email: for anything CSE232-related, send a PM on the course Zulip instead.  Otherwise: <lkuper@ucsc.edu>
  - Office location: Engineering 2, Room 349B
  - Office hours: TBD
  - Research areas: programming languages, distributed systems, software verification, parallelism and concurrency (check out the [Languages, Systems, and Data Lab](https://lsd.ucsc.edu/) website for more information)
  - <http://pronoun.is/she>

## A few essential details about the course

  - 5-unit graduate seminar course (in this context, "seminar" means a course where we discuss assigned readings and everyone participates actively in the discussion)
  - Satisfies the [breadth requirement](https://grad.soe.ucsc.edu/cse/curriculum/breadth-requirements) in the "Systems and Security" category for the UCSC CSE MS and Ph.D. programs
  - Class meets in person Mondays, Wednesdays, and Fridays, 2:40-3:45pm Pacific time
  - Course GitHub repo (public; for class discussion summaries): <https://github.com/lkuper/CSE232-2021-09/>
  - Canvas (for reading responses and grades): <https://canvas.ucsc.edu/courses/46250>
  - Zulip (private; for announcements, live chat during lectures, Q&A, communicating with course staff, and socializing): <https://ucsc-cse232.zulipchat.com> (all enrolled and waitlisted students will receive an invitation by email)
  - Course web page (you're soaking in it): <http://composition.al/CSE232-2021-09/> (URLs are case-sensitive after the domain name, so be sure to capitalize "CSE"
  
## What's this course about?

The field of _distributed systems_ studies the design, implementation, and behavior of systems that involve independent components that communicate by passing messages to one another over a network. In addition to the usual challenges of _concurrency_, distributed systems may be characterized by unbounded _latency_ between components and independent _failure_ of components, making them challenging to reason about and debug.

Some of the foundational distributed systems concepts we'll explore in this course are:

  * **Time and asynchrony.**  No two computers can reason about each others' perception of time.  What does it mean to talk about time when we don't share a clock?
  * **Fault tolerance and replication.**  Given that computers crash and messages get lost, how can we write protocols and algorithms that have adequate redundancy to tolerate failure?  Maybe if I think a computer will crash, it's a good idea to run the same computation on more than one computer!  Maybe if I think messages will be lost, I should send the same message more than once!
  * **Consistency and consensus.**  Is our system storing the right data and providing the right responses?  I might have two "replicas" that aren't actually replicas!  If replicas disagree, how do we know which one is right?  Or is it better to try to ensure that they agree in the first place?
  
The [schedule](schedule.md) has more details!

### In this course, you will:

  - Become familiar with foundational distributed systems concepts.
  - Get a sense of the history of the field of distributed systems.
  - Improve your technical reading, writing, speaking, and listening skills.
  
All of these skills will serve you well in your future career, whether in industry or in academia.
  
## What will this course be like?

CSE232 will be a *combination lecture and discussion* course.  We will be reading and discussing papers from the distributed systems research literature, interleaved with lectures to give you the necessary background to get the most out of the papers. We'll alternate between lecture days and discussion days.  On discussion days, you'll come to class having read and responded to a reading assignment, and you'll spend 30 minutes of class in a small group of 3-4 students, discussing specific questions about the reading.

In these small-group discussions, each student will play a designated role of *ambassador*, *manager*, or *scribe* (discussed in further detail below).  Each student will play each role several times throughout the term.

Some people will like this format, while others won't like it at all -- so give some thought to whether it is what you want before you commit to taking this course.  (In particular, if you want to take a course where one student gives a slide presentation about a paper while other students listen silently, that's *not* what this course will be.)

On lecture days, the material we'll cover in CSE232 will be similar to my undergrad distributed systems course, CSE138, although the pace will be faster.  Some of you may find my [Spring 2021 CSE138 lecture videos](http://composition.al/CSE138-2021-03/schedule.html) to be a helpful resource.

On discussion days, we'll discuss mostly older papers, primarily from the 80s and 90s, because a lot of our focus will be on the foundations of the field and the historical development of distributed systems ideas.  In fact, the most recent of the papers on the [schedule](schedule.html) was published in 2007.  If you're mostly interested in reading shiny new distributed systems papers instead of older ones, this course is probably not for you.

This course will _not_ have a required programming component.  If you were hoping for a course with a large distributed programming project, I recommend taking or auditing CSE138 instead of this course.

## As we return to in-person teaching

This course will meet in person.  Our classroom has a capacity of 31 (that's 30 of you plus one of me), and it is important that we not overcrowd the room.  Therefore I cannot expand enrollment beyond the listed capacity of 30 students, and you should not attend class unless you are enrolled.  If you're currently on the waitlist and you're certain you want to enroll in the course, please hang in there -- a spot will very likely open up soon.

Because of the way the course is structured, in-person attendance on discussion days is very important.  However, you can miss a couple of in-person discussions without it harming your grade.  Should it become necessary to move to a remote format, we will use Zoom breakout rooms on discussion days.
	
On lecture days, I will use the in-classroom lecture capture system to record the class.  In-person attendance is not as important for lecture days as it is for discussion days.  However, keep in mind that the recorded lectures will not be available instantaneously (there won't be a live stream or a Zoom meeting), and that the experience of watching the recorded lectures may be inferior to the in-person experience.  Should it become necessary to move to a remote format, we will use Zoom for synchronous lectures on lecture days.

### What we can expect from each other

Each individual at UC Santa Cruz should act in the best interests of everyone else in our community.  We must all comply with university guidelines about masking in indoor settings, performing daily symptom and badge checks, testing as required by the campus vaccine policy, and self-isolating in the event of exposure.  Please do not come to class if your badge is not green. If you forget your mask, you can ask me for one; there is a limited supply of disposable masks in each classroom. If you are ill or suspect you may have been exposed to someone who is ill, or if you have symptoms that are in any way similar to those of COVID-19, please err on the side of caution and stay home until you are well or have tested negative after an exposure. Let me know that you're not feeling well and I’ll respond about how best you can keep learning. 

### What you can expect from me

I have designed our course following campus guidance and with current public health guidelines in mind. However, these guidelines may change in accordance with shifting infection rates or the emergence of new variants. If updated public health recommendations and university requirements make our current course format unfeasible, or if I experience a need to self-isolate, I will alter the format. This may include moving in-person sessions onto Zoom. I will  communicate clearly with you via Zulip about any changes that occur. I will provide as much advance warning as possible and give you all the information you need to transition smoothly to the new format. If you have questions about the changes, please reach out to me so I can answer them.

### What I expect from you

If you experience an illness or exposure that requires you to miss class sessions or to attend remotely, please communicate with me as soon as possible and I will provide you with options to allow you to continue making progress in the class.

## Reading and responding to research papers

We will spend half our time in this course **reading, responding to, and discussing research papers**.  Reading research papers is a skill that requires a great deal of practice.  In this class, you will work on developing that skill.  You will need to finish each reading assignment in advance of the day we discuss it in class.  In fact, you will need to turn in a reading response by 5pm Pacific time on the day _before_ the day we discuss it in class.

### Some advice on how to read papers

Attempting to plow right through a paper from beginning to end is usually not the most productive approach.  Here's some great [advice from Manuel Blum on how to read and study](http://www.cs.cmu.edu/~mblum/research/pdf/grad.html):

> Books are not scrolls.  
> Scrolls must be read like the Torah from one end to the other.  
> Books are random access -- a great innovation over scrolls.  
> Make use of this innovation! Do NOT feel obliged to read a book from beginning to end.  
> Permit yourself to open a book and start reading from anywhere.  
> In the case of mathematics or physics or anything especially hard, try to find something  
> anything that you can understand.  
> Read what you can.  
> Write in the margins. (You know how useful that can be.)  
> Next time you come back to that book, you'll be able to read more.  
> You can gradually learn extraordinarily hard things this way.

You may also be interested in time-tested paper-reading advice [from Michael Mitzenmacher](https://www.eecs.harvard.edu/~michaelm/postscripts/ReadPaper.pdf) and [from S. Keshav](https://svr-sk818-web.cl.cam.ac.uk/keshav/wiki/index.php/HTRAP).

### What to include in your reading response

For each paper we read, you will submit a short reading response.  The reading response process is designed to help you develop the skill of **asking good questions** about the readings.  You should include the following in your reading response:

  * **Paper Summary**: Using only your own words, write an overview of the paper that can serve as an explanation of the paper for your classmates.  Your summary should answer the following questions: What problem does the paper address (1-2 sentences)?  What are the paper's key insights (1-2 sentences)?  What are the paper's key scientific and technical contributions (2-3 sentences)? What are its shortcomings or flaws (up to 3 sentences)?  (These guidelines for summarizing a paper are taken from the [ASPLOS 2021](https://asplos-conference.org/2021/) review process, with thanks to [Emery Berger](https://emeryberger.com/).)
  * **Discussion questions**: Please suggest 1-2 questions about the reading for our in-class discussion.  These must be **questions whose answers do not appear verbatim in the paper**.  Instead, try to go deeper.  Keep in mind that you may need **several sentences** just to provide sufficient context for a question.  For example, if a question has to do with how the paper's topic relates to other work you were previously familiar with, you'll need to summarize the relevant part of that other work as part of the question.  Furthermore, your questions must be _unique_ (after you submit, you'll get to see other people's submitted questions).

(By the way, the summary I'm asking you to write does _not_, by itself, comprise a _review_ of the paper, like those you would write if you were serving on a conference program committee.  A review is much longer and more detailed, and would, among other things, make a case for acceptance or rejection of the paper.)

### How to write discussion questions

A good discussion question should be specific to the paper and offer enough detail and context to be understandable by your classmates, i.e., people who have read the paper but may not have internalized every detail.  Here are examples of *good* discussion questions from students who've previously taken this course (but don't reuse these questions for the same papers; come up with your own!).  In each case, the question begins with a sentence of contextual information from the paper and then follows that up with a question.

  * "Chain replication improves on primary-backup replication by splitting the read and write responsibility amongst two nodes. Would this be sufficient for an unpredictable workload? Under what circumstances would you choose primary-backup replication over CR?" (for ["Chain Replication for Supporting High Throughput and Availability"](readings/chain-replication.pdf); discussion question contributed by Meghna Burli)
  
  * "The paper mentions at the end of section 5.2 that changing masters in networks with poor connectivity is undesirable and boosting sequence numbers with the “right” frequency should help avoid this. How exactly does a master prevent the cycle of changes of masters, using boosting?" (for ["Paxos Made Live: An Engineering Perspective"](readings/paxos-made-live.pdf); discussion question contributed by Ramtin Roshanmanesh)
  
Here are examples of how *not* to write a discussion question:

  * "How can the task of maintaining, implementing and designing fault-tolerant distributed systems be simplified?"  (for ["Fundamentals of Fault-Tolerant Distributed Computing in Asynchronous Environments"](readings/fault-tolerance.pdf))  This question is too broadly scoped and not specific enough to the paper under discussion.
  
  * "How to deal with the scalability issue of vector time?"  (for ["Detecting Causal Relationships in Distributed Computations: In Search of the Holy Grail"](readings/holy-grail.pdf))  There's the start of a good question here, but more context is needed.  The question writer should explain what "scalability issue" they mean, and if possible, relate their question to a part of the paper under discussion.

### Reading response submission logistics

Reading responses are due **at 5pm Pacific time on the day before we discuss the reading in class**.  The reason for this relatively early deadline is to give me time to look at the responses before class so that I can structure the in-class discussion based on them.  Don't be surprised if you see some of your questions used in the in-class discussions!

You will submit your reading response [on Canvas](https://canvas.ucsc.edu/courses/46250), in the discussion forums set up for each paper.  Once you submit, you'll get to see other people's submissions.  After submitting, take a look at the other submissions to make sure that your questions aren't a repeat (or very close to a repeat) of any already-submitted questions.  In that case, you should edit your questions to make them clearly distinct from the previously-submitted ones.  _It is to your advantage to turn in your reading response relatively early_, because the earlier you turn it in, the less likely it is that your questions will be a repeat of any previously-submitted questions!

## In-class discussion process

On discussion days, we'll use a structured in-class discussion process.  The process we will use is inspired by one used by [Matthew Ahrens](https://www.eecs.tufts.edu/~mahrens/), [Kathleen Fisher](http://www.cs.tufts.edu/~kfisher/Kathleen_Fisher/Home.html), and [Norman Ramsey](https://www.cs.tufts.edu/~nr/) in courses taught at Tufts University, and the below description borrows heavily from [their](https://www.cs.tufts.edu/comp/150PLD/Consensus.pdf) [documentation](https://www.cs.tufts.edu/comp/150PLD/ic00-1.html), with their permission.

### Small-group discussion (30 minutes)

At the start of each discussion day, after at most 5 minutes for announcements, the class will split into small groups of 3-4 students for 30 minutes.

Each member of each small group must take on one of the following **roles**.  You must carry out this role in addition to actively participating in the conversation.  Each student in the class should serve in each of the roles **four or more times** during the term.

  * **Scribe**: The role of the scribe is to take notes during the conversation, while participating in the conversation themselves.  After class, all the scribes will meet and contribute to a formal write-up of the class discussion on the course's public GitHub wiki.  One student in each small group will serve as the scribe.  
  * **Manager**: The role of the manager is to keep track of time and make sure that all of the discussion questions get touched upon.  Afterward, they will be responsible for recording everyone's role on a shared spreadsheet.  One or two students in each small group will serve as the manager.
  * **Ambassador**: The role of the ambassador is to represent their small group in the large-group discussion afterward.  They will also be the first ones to answer follow-up questions from the rest of the class, or to pose questions to the rest of the class that would be helpful to discuss. Then, they will meet with the instructor before the end of the class to go over the "meta" of the class, and discuss how workload, group pacing, and other housekeeping items went.
  
The small-group discussion will use the following process:

1. Each member of the group should **introduce themselves**.
2. The group should **assign roles** to each member.
3. The group should **discuss answers to the provided questions about the reading assignment**.  On each discussion day, I'll provide a short list of discussion questions, many of which will be drawn from the reading responses that you and your classmates submitted previously.  During the discussion phase, feel free to work together in a shared document and use any resources you like.  This is a "brainstorming" phase.  Don't stop with a single answer; look at things from all angles.
4. The group should try to **reach consensus on the most satisfying answers**.  Perhaps the group will agree on answers that satisfy everyone.  Perhaps there will be significant dissent -- maybe even no majority view.
5. The group should **prepare to report verbally to the class as a whole**.  The ambassador's report should cover the following points:
   * The preferred answers according to the consensus reached by your group.
   * The _reasons_ that you prefer these answers.
   * Any significant minority views.
   * A few words about answers that your group considered but ultimately rejected.
	
### Large-group discussion (20 minutes)

After 30 minutes, small groups will conclude, and the entire group will reconvene for 20 minutes.  At this point, ambassadors from individual groups will present their groups' conclusions.  During the large-group discussion, **ambassadors speak first**, for a couple of minutes each.  Once all ambassadors have had a turn to speak, if there's time remaining, we'll open the floor to the whole class.

In the large-group discussion, we'll discuss and evaluate the groups' conclusions and try to forge a coherent consensus view that the whole class can agree on, but also be alert for gaps, inconsistencies, and incoherence.  When possible, I'll compare the conclusions reached by the class with my interpretation of the consensus position of the body of researchers interested in distributed systems.

### Wrap-up (10 minutes)

During the last ten minutes of class:

  * **Ambassadors** will gather with Lindsey and discuss how they think the day went, how they think the pacing went, what they are looking forward to, any concerns they might have about the class, and so on.
  * **Managers** will update the shared _role spreadsheet_ (link to be distributed privately) to list the role that each member of their small group played.  They will then create an [issue on the course GitHub repository](https://github.com/lkuper/CSE232-2021-09/issues) for Lindsey to follow up on the scribes' class discussion summary once it is complete, @-mention all the scribes in the issue description, and assign the issue to Lindsey (@lkuper).  (There should be a single issue created per paper discussion, so only one manager needs to create it, but the other managers should make sure that the scribe from their group gets an @-mention.)
  * **Scribes** will gather to start writing a _discussion summary_ on the [course GitHub wiki](https://github.com/lkuper/CSE232-2021-09/wiki), to be finished by at most a week from the day the in-class discussion took place.  You may update the wiki either through the web interface, or by [cloning the wiki locally](https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/adding-or-editing-wiki-pages#adding-or-editing-wiki-pages-locally).  I recommend doing the latter, *especially* if you're not yet particularly fluent with git, since it's a good idea to become comfortable with it.
  
## Discussion summaries

The discussion summary on the course GitHub wiki will include (1) a brief overview of the paper (which can draw from the paper summaries in reading responses previously written by the scribes, but should also incorporate any updated understanding gained from the in-class discussion), and (2) summaries of the in-class discussions about each discussion question.  The purpose of the discussion summary is to serve as a sort of annotated bibliography of the papers we read, for your future use as well as the use of anyone else in the world who might be interested in these papers (the wiki is public, after all).  Think of the discussion summary as an exercise in collaborative note-taking.  You may come back to these papers later on in your career, so when you are in the scribe role, it's a gift to your future self (as well as to anyone else reading the wiki!) to try to be as thorough and detailed as you can when creating the discussion summary.

After managers create a GitHub issue for use by the scribes, the scribes can use the issue throughout the week that they work on the discussion summary as a place to keep track of what needs to be done.  They can comment on the issue with an @-mention of me (@lkuper) to let me know when a draft of the discussion summary is ready for me to look at.  It's fine to ask for feedback from me before the deadline, and I may use the GitHub issue as a place to comment and give feedback on the in-progress discussion summaries.
  
## Grading

Your grade in this course will be based 50% on your participation in the course and 50% on your reading responses.  Credit for participation can be earned primarily by fulfilling your role on discussion days and completing the follow-up tasks for your role.  Credit for reading responses can be earned by submitting thoughtful, well-written paper summaries and discussion questions.

Needless to say, the above grading approach assumes no violations of academic integrity.

## Academic integrity

**Everything you write for this course must be your own original work.**  It is a very important part of your job as a scholar to understand [what counts as plagiarism](https://guides.library.ucsc.edu/citesources/plagiarism), and make sure you avoid it.  Here's a [handy flowchart](https://writingcenter.ashford.edu/sites/default/files/inline-files/Did%20I%20Plagiarize%20Flowchart.pdf) that you should internalize.

**Properly attribute any work that you use.**  If you use someone else's words, you must _quote_ and _cite_ them.  The only time you can leave out the citation is if it's obvious from context.  For example, if you're turning in a reading response for a given paper, you don't have to cite the paper you're responding to, but you definitely do have to _quote_ any text from the paper that you use.

Many of the papers we're reading are classics, and much has been written and said about them.  It's absolutely fine to consult existing videos, blogs, etc. to check your understanding, but using other people's words without appropriately citing and quoting them is unacceptable.  **I would much rather have you submit your own writing, even if it is not perfect, and even if you need to turn it in a little late.**

If I see that the writing you do for this course contains material that is copied from a source without appropriate citation and quotation, *at a minimum*, you will get no credit for the assignment in question, and you risk further penalties, such as failing the course.

## A note on accessibility

If you have a disability and you require accommodations to achieve equal access in this course, please submit your Accommodation Authorization Letter from the [Disability Resource Center (DRC)](https://drc.ucsc.edu/index.html) to me by email, preferably within the first two weeks of the quarter.  I am eager to discuss ways we can ensure your full participation in the course.

I encourage all students who may benefit from learning more about DRC services to [contact the DRC](https://drc.ucsc.edu/about/contact-us/index.html).
