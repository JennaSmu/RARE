---
dg-publish: true
---

Ok, we are going to now look at an example of a Daily Note. The example we will be looking at is [2025-01-05]({{< ref "2025-01-05" >}})

# What is in a Daily Note:

## Naming of Daily Notes!

First, let's look at the name of the daily note.

The name of this one is 2025-01-05. This follows the date convention of YYYY-MM-DD. It is ***imperative*** to follow this naming structure for the following reasons:

1. Bits of code throughout the vault use the information in the title to pull out the year, month, and day. So, keeping it in this format helps that out.
2. This way, the daily notes are in a nice time order in the Daily Notes folder.
	1. If we had it as 01-05-2025, we would see all the 01-05 notes from 2021 onwards grouped together.
	2. The format of YYYY-MM-DD helps keep it in a nice order.
3. Every other note already follows this structure and I like it this way.

## Daily Note Tag:

The first line shows a Tag property.

This tag property just means that this note is Daily Note. The Auto Note Mover plug-in sees that and automatically moves the note to the Daily Notes folder. This tag doesn't really serve any other purpose.

# Sections:

The typical sections in a daily note are:
- Clinic
- Barn
- New Admit (if there are any new admits)
- Calls (if there are any calls)

## 🏥 Clinic Section:

The Clinic heading helps to show that the following information comes from Clinic notes on this particular day.
The next line puts the names of whoever was at Clinic that day.

Now, the next heading under Clinic shows information from a particular bird.

### Clinic Section Template:

I have a template that can be put into a note for the Clinic section. Below is what is looks like and I'll go over what I usually do for each part.

![daily-notes-clinic-template](/images/daily-notes-clinic-template)

I enter the data from that day and separate it into these different sections. I find that it helps to visually break up the information.

For this template of the clinic section, the first thing that I do is replace the CaseID with the bird code of the bird the following notes will be for. This is very important as the code in the RARE Birds folder needs that.

#### I only keep the 🏥 Clinic heading and volunteers once for each note:
- If there are multiple birds in clinic, you will need to add multiple [daily-notes-clinic-template]({{< ref "daily-notes-clinic-template" >}}).
	- Each time, it will show you the # 🏥 Clinic and the [volunteers::]
	- I only keep those first two lines for the first entry and delete them for any subsequent entries.

##### Volunteers:
- The volunteers field allows you to enter any volunteers that day.
- So just enter people's name but be sure to include a comma between them.
	- The comma tells Obsidian that what is before and after the comma are different.
- [volunteers:: Jay, Jay S.]
	- In this example, the volunteers are Jay and Jay S. and they are two separate things according to Obsidian.
- You can use this to search for any notes where the volunteer is Jay or Jay S.

#### The Notice callout is where I put any important information:
- [What goes in the Significant Events Section]({{< ref "What goes in the Significant Events Section" >}})
- Comments is just the Misc section for anything that doesn't fit one of the other categories.

#### Food callout:
- [What goes in the Food Callout]({{< ref "What goes in the Food Callout" >}})
- [Filling in a Table in a Callout]({{< ref "Filling in a Table in a Callout" >}})

#### Medical Callout:
- [What goes in the Medical Callout]({{< ref "What goes in the Medical Callout" >}})

### Example:

![2025-01-05#Killy](/images/2025-01-05#Killy)

## New Admit:

### New Admit Template:

I have a template that can be put into a note for the New Admit section. Below is what is looks like and I'll go over what I usually do for each part.

![new-admit-template](/images/new-admit-template)

The Notice, Food, and Medical Callouts are similar to the Clinic ones.

Whenever there is a new admit, I enter the #🦅💥-significant-event tag to say there is a new admit.
I fill in any other information that is written down.

Then I have more callouts that dive into what other information can be seen in the initial exam. That way, not all of this information goes into the Observations section of the Medical callout.

[What goes into the New Admit Callout]({{< ref "What goes into the New Admit Callout" >}})

### Example:

There was a new admit on [2025-01-05]({{< ref "2025-01-05" >}}). Let's take a look.

![2025-01-05#✨New Admit](/images/2025-01-05#✨New Admit)

## 🏡 Barn:

### Barn Section Template:

The Barn template is very similar to the Clinic callout.

The main difference is that is there no table for new food anymore as 99.9% of the time, the food is being given whole so there is no reason to denote that.

![daily-notes-barn-template](/images/daily-notes-barn-template)

### Example:

![2025-01-05#24118 RTHA](/images/2025-01-05#24118 RTHA)

## Calls:

### Calls List Template

![daily-notes-call-template](/images/daily-notes-call-template)

 - This is a simple template that just makes the heading for you.
 - I just make a bullet point list of the different calls.
 - I have a more complicated call template: [daily-notes-OLD-COMPLICATED-calls-template]({{< ref "daily-notes-OLD-COMPLICATED-calls-template" >}}) but that amount of information is usually not needed and I think it is overcomplicated.
 - The template above is the [daily-notes-call-template]({{< ref "daily-notes-call-template" >}}).

# Tip for Entering Data:

## Delete Blank Fields:
- Not every part of every callout will have information in it for that day. If a portion (ex: Clean) doesn't have any relevant notes, I will delete that part of the callout so that it's not cluttered with a bunch of blank fields. You can see this in the examples compared to the templates above. The templates have a lot more fields and the actual notes in [2025-01-05]({{< ref "2025-01-05" >}}) only have the relevant sections.

## Keep the Multi-Callout Layout:
- For the callouts, to make them appear side-by-side, I use a piece of css code that requires some formatting.
- First, the line > [!multi-column] has to stay. Do not delete that.
- Second, when going from one callout to another, there has to be a line with 1 singular > instead of >>.
	- Having a line with one > will tell the code that the next information belongs to a new callout.

## There is Automatic Cleaning Up:
- I have the Linter plug-in installed and once you leave a note, it will clean up any odd spacing between the headers. So even if you have 10 blank lines between 1 header and another, Linter will come in and delete those blank lines. This just helps to make it look nicer and more uniform without any more work on your end.

# Up Next:
- [A Bird's Note]({{< ref "A Bird's Note" >}})