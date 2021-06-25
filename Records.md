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

As of this writing, we have three approved IRB protocols:

- Protocol # 1609018209, which is the "main" protocol
- Protocol # IRB-2020-876 for web-only studies (this is technically an approved exemption)
- Protocol # 1904022076, which allows everything in the main protocol, but adds interventions (allowing earplug and noise-machine studies, currently).


The intervention protocol requires special training,
and the web-based protocol is such that all thre required records are kept
either by Prolific.co or by snaplabonline.com, so we'll skip both here.
So IRB in the sections below refers to our **"main" protocol.**

Separate from IRB/grant/project level documentation,
we also have the COVID19 documentation and safety procedures,
which are not discussed here.

## IRB 101

*All* human subject procedures that we do (including recruitment procedures/flyers)
will need to be in the IRB we use. 

** Please read the IRB narrative text and consent forms carefully.
Referesh often. If you see anything that is odd or could be changed, we can discuss
and/or amend as needed. They are available on Slack, Z drive (Synology), and Google Drive.**

Currently, the "main" IRB allows:
- Playing sounds
- Tasks with verbal, button, or keyboard responses
- Acoustic measurements
- EEG measurements
- Any combination of the above
- Approved surveys/questionnaires

### Mandatory training requirements

All personnel who will work on a study need to be added to the IRB explicitly.
To be added to the IRB, you should have training associated with human subjects research.

- CITI: Information about CITI training can be found at the [Purdue IRB website](https://www.irb.purdue.edu/training/),
where you will find links to the training ["CITI Human Subjects Research Basic Course"](https://www.citiprogram.org/). 
If you have done any CITI training before, you can use your old account to login and affiliate with Purdue university once you are in -- this might let you skip some of the modules.
If you have done any CITI training, or if you just want to start afresh anyway,
you may have to create an online account with CITI.
Once you are in, for SNAPlab, please complete the **"Biomedical Research for Investigators and Key Personnel Learner Group"** training.

- RCR (Responsible Conduct of Research). This is ongoing training both via formal courses at Purdue, and via RCR faculty-led discussions that happen at various seminars (e.g., Seminars in Hearing Research, or SLHS Brown Bag seminar).

- Send CITI certificates to Hari upon completion of training. RCR training is tracked by Purdue.


### Technical training

- Technical training is informal within our lab and is somewhat self-paced.
- General principle is that you should be well-practiced in (have a reasonable understanding of)
all the measures you plan to collect on real subjects
before getting real subjects in.
- Practise by running self or other lab members.


## Enrollment and informed consent (IRB-specific)

- Legally/ethically needed
- Critical component of IRB protocol

### What to cover when obtaining informed-consent

- Overview of what's going to happen to the subject
(they'll hear sounds, have electrodes attached via "swimming" cap etc.).
- Remind them that all measurements are research-related and not clinical measurements:
For example, if a subject comes in thinking they have normal hearing, but we find
audiometric elevation, we  can explain that they don't meet our research critera for enrollment,
but also that this is not a clinical diagnosis. We then give them referral resources to follow up with
real clinicians.
- Mention risks:
	1. Loud sounds
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
- After signing consent form, have them fill our mandatory form(s).
- Assign a subject ID for the individual on the "SubjectContacts.xls" sheet on Z-drive.
All data are then associated with the subject ID (Sxxx, e.g, S123).

### Mandatory forms and where to store this data

All forms are available on Slack channel for printing. Paper copies will be in the cabinet.

- Consent form: Stored in binder (IRB-specific). Reconsent is always Ok.
- Demographics form: Age, gender, race and ethnicity (Required by funding agencies).
Paper copy stored with consent form. Electronically enter this info into our
demographics spreadsheet on google drive (link of Slack).
This will faciliate progress reports for NIH/NSF etc.
- Intro form: Asks about native speaker status, and visa status. This will prompt you
to inform international individuals appropriately.



## Subject payments (Specific to a combination of IRB and Grant)

- Payment forms specify IRB number and funding source, so will be a different one for each combination of
IRB and grant.
- Fill out electronically on the .XLS form, but **do not** save, print instead
- For extra visits, write payment number by hand
- At the end of all visits: Send scanned copy to Emily  via filelocker.
Make sure to sent to the right "Emily" (see Slack for details).
- Leave paper copy in the cabinet with some annotation (until subject gets paid, which should be 4-5 weeks). Then shred.
- Keep a record of who has been paid (**project-specific**, see visit log below)

## Visit log (project-specific)

- Data collection for all studies is organized as a set of subject visits (one or more).
The list of measurements to be done at each visit is pre-set before beginning the study and should followed closely for all subjects. It is also important to pre-determine study N and stick to it: **using data to decide when to can amount to p-hacking**.
- Keep a spreadsheet will allow for tracking which subjects have completed which visits, when. Also leave space for comments about data collection issues (e.g., "Re-ran OAE after realizing that the tip fell out half-way through. Repeat run is marked as v2").
- Never delete any data even if you re-run something.
- Have file naming conventions that include subject ID (e.g., S050_ProjectX_ABR.bdf)

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
One way to organize it would to have a table of planned measures of the study with empty boxes that you can check off
by writing an X.

One important component of this progress sheet is to include information about payment. This info should include:

- Date when payment form was submitted to business office
- Amount
- Subject ID

Progress sheets should be archived with the raw data at the end of the data-collection phase of the study (see "Raw data archival" below).


### Lab notebook (researcher-specific)

The lab notebook is essentially a place to document research progress as you go through the project.
Conventionally, lab notebooks are one at a time for a whole data-collection facility and served as visit log.
For us, formal visit logging is electronic, and so lab notebooks are less formal, and can contain:

- A handwritten version of data collection progress (like visit log)
- Analysis outcomes and thoughts surrounding that
- Design decisions


### Calendar logging

- Our google calendar also serves as a record of visits.
- When you reserve time, include your name and subject ID
- If it's new subject and you haven't assigned an ID yet (say something like Sxxx or Snew), and then on visit day, edit it to have the actual ID.


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

Individual subject (processed) data and code to reproduce figures should be shared with papers.
Example:
- For an EEG study, a ```.mat``` file with individual ERPs and time-frequency matrices, along with code to 
plot figures from them would be appropriate.
- For a behavioral study, spreadsheets with thresholds, percent-corrects etc., and code to plot them.
- For all studies, spreadsheets with subject age, audiogram, gender, etc. 

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


