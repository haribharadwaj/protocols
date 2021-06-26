# Overview of paperwork and record-keeping protocols at SNAPlab

Below is a general overview of the protocols. If there are questions,
please post in the lab slack group and we can sort it out.

When thinking about paperwork for research, it is useful to keep in mind
that there are three buckets under which we need detailed documentation:

- Documentation that is IRB protocol-specific ("IRB")
- Documentation that is grant/funding-specific ("grant")
- Documentation that is individual project/study-specific ("project")

In the ideal world, a single grant would fund one or more projects,
with each project having its own IRB.
In practice, however, these buckets overlap.
That is, more than one grant could fund a set of projects, and
the same IRB would cover multiple projects.

At SNAPlab, we have IRB protocols that are organized by
what measurements/procedures they allow,
with the constraint that all measurements for any given project would
be covered under a single IRB.
So each subject for any given project will be enrolled via one IRB.

As of this writing, we have three approved IRB protocols (and one dormant one):

- Protocol # 1609018209, which is the "main" protocol
- Protocol # IRB-2020-876 for web-only studies (this is technically an approved exemption)
- Protocol # 1904022076, which allows everything in the main protocol, but also allows interventions (earplug and noise-machine studies, currently).
- We have a dormant pediatric/family protocol from before than can be resurrected if needed (not currently approved).


The intervention protocol requires special training,
and the web-based protocol is such that all the required records are kept
by our [SNAPlabOnline Django app](https://www.snaplabonline.com/), so we'll skip both here.
So IRB in the sections below refers to our **"main" protocol.**

Separate from IRB/grant/project level documentation,
we also have the COVID19 documentation and safety procedures,
which are not discussed here.

## IRB 101

*All* human subject procedures that we do (including recruitment procedures/flyers)
will need to be in the IRB we use. 

** Please read the IRB narrative text and consent forms carefully.
Refresh often. If you see anything that is odd or could be changed, we can discuss
and/or amend as needed. They are available on Slack, Z drive (Synology), and Google Drive.**

Currently, the "main" IRB allows:
- Posting **approved** flyers to recruit
	- Adults with normal hearing
	- Adults with hearing complaints (e.g., difficulties in background noise, sensorineural hearing loss, tinnitus, hyperacusis)
	- Adult musicians
	- Adults in a specified age range
	- Adults who are regularly exposed to loud sounds
- Playing sounds to subjects via headphones, earphones or bone vibrators
- Pressuring subjects' ears (e.g., for tympanometry)
- Having subjects do tasks with verbal, button, or keyboard responses
- Making acoustic measurements on subjects (e.g., OAEs, MEMRs)
- Electrophysiological measurements caps and external electrodes (EEG, EOG, EKG, etc.)
- Any combination of the above
- Approved surveys/questionnaires


## Mandatory training requirements

All personnel who will work on a study need to be added to the IRB explicitly.
To be added to the IRB, you should have training associated with human subjects research.

- CITI: Information about CITI training can be found at the [Purdue IRB website](https://www.irb.purdue.edu/training/),
where you will find links to the training ["CITI Human Subjects Research Basic Course"](https://www.citiprogram.org/). 
If you have done any CITI training before, you can use your old account to login and affiliate with Purdue university once you are in -- this might let you skip some of the modules.
If you have done any CITI training, or if you just want to start afresh anyway,
you may have to create an online account with CITI.
Once you are in, for SNAPlab, please complete the **"Biomedical Research for Investigators and Key Personnel Learner Group"** training.

- RCR (Responsible Conduct of Research). This is ongoing training both via formal courses at Purdue (e.g., GRAD 612),
and via RCR faculty-led discussions that happen at various seminars (e.g., Seminars in Hearing Research, or SLHS Brown Bag seminar).

- Send CITI certificates to Hari upon completion of training to be added to protocol. RCR training is tracked by Purdue.


## Technical training

- Technical training is informal within our lab and is somewhat self-paced. 
- General principle is that you should be well-practiced in (and have a reasonable understanding of)
all the measures you plan to collect, and be comfortable working in sync with our IRB protocol
before getting real subjects in.
- Practise by running self or other lab members.
- Everybody, regardless of background will be able to pick up data analysis skills and have a working understanding of the details.
Perhaps the most effective way of picking up quantitative skills relevant for data analysis is to start with some actual data and an associated research question (especially from your own project).
- One technical aspect of our work that is not easy is programming stimulus presentation sequences, behavioral tasks, and/or adapting data acquisition hardware to set up new measurement paradigms. This is so because it requires an array of different skills and considerable familiarity with the literature surrounding the specific measures. Therefore, if you are undertaking this task, please work closely with lab members who are experienced in this aspect throughout the set up process.
- There are no specific documentation formalities for technical training in our lab (should we change this?).


## Enrollment and informed consent (IRB-specific)

- Post approved flyers on various physical and virtual bulleting boards
- Informed consent legally/ethically needed
- Consenting is a critical component of the IRB protocol
- Once a subject is enrolled following informed consent, assign a subject ID by looking at the password-protected ```SubjectContact.xlsx``` spreadsheet on the Z drive and incrementing the ID number by 1.
It's possible that a "new" subject has
actually participated in studies in our lab before, and you'll be able to see that when looking at the spreadsheet.
- Re-consenting is fine, but please use a subject's old ID if they have one.
In this case, update the "consent date" field in the spreadsheet.


### What to cover when obtaining informed-consent

- Overview of what's going to happen to the subject
(they'll hear sounds, do tasks, have electrodes attached via "swimming" cap etc.).
- Remind them that all measurements are research-related and not clinical measurements:
For example, if a subject comes in thinking they have normal hearing, but we find
audiometric threshold elevation, we  can explain that they don't meet our **research critera** for enrollment,
but also that this is **not** a clinical diagnosis. We can then give them referral resources to follow up with
real clinicians (see IRB narrative for more details).
- Mention risks and how they are unlikely, but could happen:
	1. Loud sounds (if they find anything too loud, they can remove headphones/earphones and let us know)
	2. Skin irritation from contacts/gels/wipes
	3. Risk to privacy: We'll collect information like SSN, address, etc. for payment purposes
- Mention how they'll get paid (& how much)
- If they are on a visa, then extra paperwork needed for payments
	Either SSN (e.g., Purdue employees) -- or -- 
	1. Glacier form
	2. Passport copy
	3. Copy of I-94
	4. Copy of their status form (depend on visa: I-20 for F-visas, DS-2019 for J-visas)

- If subjects don't want to or don't have the documents needed for us to pay them,
then we can't pay them and you should not run them.
- After signing consent form, have them fill our mandatory forms (see below).
- Assign a subject ID for the individual on the ```SubjectContacts.xlsx``` sheet on Z-drive.
All data are then associated with the subject ID (Sxxx, e.g, S123).

### Mandatory forms obtained during the consent process and where to store this data

All forms are available on Slack channel for printing. Paper copies will be in the cabinet.
Please print more if you see that we are running low.

- Consent form: Stored in binder (IRB-specific). Reconsent is always Ok.
- Demographics form: Age, gender, race and ethnicity (Required by funding agencies).
Paper copy stored with consent form. Electronically enter this info into our
demographics spreadsheet on google drive (link of Slack).
This will faciliate progress reports for NIH/NSF etc.
- Intro form: Asks one question each about native speaker status, loud sound-exposure status, and visa status.
This will also prompt you to inform international individuals appropriately. Save this form on paper with the consent form.


## Subject payments (Specific to a combination of IRB and Grant)

- Payment forms specify IRB number *and* funding source, so will be a different one for each combination of
IRB and grant.
- Fill out electronically on the .XLS form in the lab computer, but **do not** save, print instead
- For extra visits, write payment number by hand
- At the end of all visits: Send scanned copy to Emily  via filelocker (delete any electronic version made in the process)
**Make sure to sent to the right "Emily" (see Slack for details).**
- Leave paper copy in the cabinet with some annotation (until subject gets paid, which should be 4-5 weeks). Then shred.
- Keep a record of who has been paid (**project-specific**, see progress sheet below)

## Visit log (project-specific)

- Data collection for all studies is organized as a set of subject visits (one or more).
The list of measurements to be done at each visit is pre-set before beginning the study and should followed closely for all subjects. It is also important to pre-determine study N and stick to it: **using data to decide when to can amount to p-hacking**.
- Keep a spreadsheet will allow for tracking which subjects have completed which visits, when. Also leave space for comments about data collection issues (e.g., "Re-ran OAE after realizing that the tip fell out half-way through. Repeat run is marked as v2").
- Have file naming conventions that include subject ID (e.g., S050_ProjectX_ABR.bdf)
- Never delete any data even if you re-run something. Add suffix to filename instead (e.g., S050_ProjectX_ABRv2.bdf)


Recommended structure for visit log:

| Date | Subject ID | Experimenter | Visit number (within project) | Measures collected | Comments (data quality, file naming) |
|------|------------|--------------|-------------------------------|--------------------|--------------------------------------|
|      |            |              |                               |                    |                                      |

Please fill out the visit log while you are in the lab collecting data rather than retroactively.
Visit logs also have legal weight in priority disputes (e.g., patenting).

Visit logs should be archived with the raw data at the end of the data-collection phase of the study (see "Raw data archival" below).

### Data-collection progress sheets (project-specific)

This is different from visit logging.
This is a place to track which subject has done what parts of the study concisely.
The best organization for this spreadsheet will depend on the project.
One way to organize is to have a table of planned measures of the study as columns, and subject ID as rows with empty boxes that you can check off
by writing an X.

Another important component of this progress sheet is to include columns about payment.
For each subject, this info should include.

- Date when payment form was submitted to business office
- Amount for which form was submitted.

Progress sheets should be archived with the raw data at the end of the data-collection phase of the study (see "Raw data archival" below).


### Lab notebook (researcher-specific)

The lab notebook is essentially a place to document research progress as you go through the project.
Conventionally, lab notebooks are one at a time for a whole data-collection facility and served as visit log.
For us, formal visit logging is electronic, and so lab notebooks are less formal, and can contain:

- A handwritten version of data collection progress (like visit log)
- Analysis outcomes and thoughts surrounding that
- Design decisions while piloting
- etc.


### Calendar logging

- Our google calendar also serves as an additional a record of visits.
- When you reserve time, include your name and subject ID
- If it's new subject and you haven't assigned an ID yet (say something like Sxxx or Snew), and then on visit day, edit it to have the actual ID.
- If you have a no-show or last-minute cancellation, remember to delete or move the old event.


## Raw data archival (universal)

Prior to the COVID19 pandemic, raw data was archived on the "Z drive" (lab synology drives).
Any raw data you collect in the lab post-COVID (starting June 2020) should be cloud archived using Box.
Access is provided by Purdue for free here: https://purdue.account.box.com/

Specifically, any *raw* data collected should be in the ```SNAPlab Data Archive``` folder (you should have received invitations). Within that, there is a folder for each researcher in the lab.  If it's a joint study, achive under one of your names.

For each our your studies, create the following structure inside the folder with your name (avoid spaces in names, use camel case or underscores):

```
Project_Name
|
+-- Pilot
|
|	+--	SubjID1
|		+-- Measure1
|		+-- Measure2
|		+-- ...
|	+--	SubjID2
|		+-- Measure1
|		+-- Measure2
|		+-- ...	
|
+-- FullStudy
|
|	+--	SubjID1
|		+-- Measure1
|		+-- Measure2
|		+-- ...
|	+--	SubjID2
|		+-- Measure1
|		+-- Measure2
|		+-- ...	
|
+--	VisitLogs (add at end of data collection phase of the study)
+--	Progress Sheets (add at end of data collection phase of the study)

```

By Fall semester (Aug 23rd, 2021), let's try to be current with raw data archival.

Keep extra copies on Z-drive (optional for post-COVID data). Don't delete any data from Z-drive.


## Processed data and results archival (project-specific)

At the time when the data is written up for publication, the following should be done:
- Final individual-subject results from which figures can be made should all be in one location.
- Code to plot figures should be stored with the data needed to reproduce figures.
- Code to go from raw data to final results should be available (ideally on github **and** with the final processed data).
- Any intermedite large files can optionally be archived on Box if appropriate (e.g., will help with future new analyses on same data).

### Data sharing for papers

We will practice open-science as much as possible.
Individual subject (processed) data and code to reproduce figures should be shared/shareable with papers.
Example:
- For an EEG study, a ```.mat``` file with individual ERPs and time-frequency matrices, along with code to 
plot figures from them would be appropriate.
- For a behavioral study, spreadsheets with thresholds, percent-corrects etc., and code to plot them.
- For all studies, spreadsheets with subject age, audiogram, gender, and other demographic or hearing status info. 

Make a folder on Box under the ```MANUSCRIPT_DATA``` for each submitted paper and dump this information there.

## Overall Checklist for Recordkeeping

| Document | Where to store? |
|----------|-----------------|
| Consent form | On paper in the binder inside our lab cabinet |
| Demographics form | On paper with consent form, Electronically enter on google drive |
| Intro/intake form | On paper with consent form |
| Visit logs | Electronic, with individual researcher, archive with raw data at the end of study |
| Progress sheet | Electronic, with individual researcher, archive with raw data at the end of study |
| Payment form | Print and submit, don't save |
| Payment log | Electronic, along with progress sheet |
| Raw data | Archive on Box as per recommended structure |
| Processed data | Archive on Box, code on github or Box, at the time of paper writing |
| Lab notebooks (informal) | Keep with individual researcher until part of lab |
| Calendar logging | Done audiomatically |


