---
dg-publish: true
---

So, in each Daily Note, you link to a bird's note.

Let's look at what is in a bird's note.

# Naming:
- To keep the ordering simple and in line with code I have, please enter the name as Case # 4 letter species code. Ex: [[2501 AMKE|2501 AMKE]]

# Templates:
- There are two types of templates I made for a bird's note.
- [[bird-info-template|bird-info-template]]
	- This includes all the different properties.
- [[bird-info-template-most-common-properties|bird-info-template-most-common-properties]]
	- This only includes some of the properties.
	- Most birds do not have something in all the properties so I just made this to limit it.

# Properties:

Here are the different properties in the bird note.

| Properties        | What                                                                                                                                                                                                                         |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tags              | Used by Auto Note Mover plug-in to move the note to the RARE Birds folder. <br>No need to mess with this.                                                                                                                    |
| dg-publish        | This is what tells the Digital Garden plugin that I want this note to be published on the website. No need to mess with this.                                                                                                |
| Species           | Enter the species code. I have several entered already. So when you click into it, it's like a dropdown of what has been entered. <br>I have notes for several of the species and I use the alias of the 4 letter bird code. |
| Age               | Enter Nestling, Hatch Year, Juvenile, Adult                                                                                                                                                                                  |
| Finder            | Enter what the type the finder is. There is a dropdown of several options.                                                                                                                                                   |
| Location          | I enter City and County or just County if City is not known.                                                                                                                                                                 |
| Recovery Address  | Enter the address the bird was found. Leave blank if not known.                                                                                                                                                              |
| Recovery GPS      | Enter the GPS coordinates where the bird was found. Leave blank if not known.                                                                                                                                                |
| LocationReleased  | The City and County the bird was released.                                                                                                                                                                                   |
| Release Address   | Enter the address the bird was released. Leave blank if not known.                                                                                                                                                           |
| Release Address   | Enter the GPS coordinates where the bird was released Leave blank if not known.                                                                                                                                              |
| InjuryEvent       | The reason why the bird was admitted. In the OSU data, this is the Situation for Admit column.                                                                                                                               |
| Injury            | You can enter multiple injuries here. I usually format it so it is Type of Injury - Side - Body Part. Ex: FX L Humerus. If the side of the [[Fracture\|FX]] was not known, I would enter FX - Humerus.                       |
| Admit Condition   | The condition the bird was admitted as. Has a dropdown of options. If not known, leave blank.                                                                                                                                |
| Admit Keel Score  | What the keel score was when admitted. If not known, leave blank.                                                                                                                                                            |
| Admit Weight (kg) | The weight the bird was when admitted in kg. If not known, leave blank.                                                                                                                                                      |
| Last Weight (kg)  | The weight the bird was when admitted in kg. If not known, leave blank.                                                                                                                                                      |
| Lead (ug/dL)      | The value given on the lead test. Can look at [[Lead Test Results|Lead Test Results]] to help interpret it.                                                                                                                                    |
| Intake            | The date the bird was admitted.                                                                                                                                                                                              |
| Outtake           | The date the bird was no longer in our care.                                                                                                                                                                                 |
| Disposal          | The date the bird was disposed of if the bird died in our care.                                                                                                                                                              |
| Status            | The status of the bird. Has a dropdown menu.                                                                                                                                                                                 |

# Sections of the Bird Note:

Using [[2501 AMKE|2501 AMKE]] as an example:

## Summary Table:

![[2501 AMKE#Summary Tables|2501 AMKE > Summary Tables]]

These tables are the same as what is seen in the properties but just broken up. Mostly used so the properties can be seen in the Digital Garden website.

## Significant Events:

![[2501 AMKE#Significant Events|2501 AMKE > Significant Events]]

The Significant Event Notices code takes all the lines with the #🦅💥-significant-event tag in them and shows them as a nice list of events. So, you can get an overview of what happened when.

In the comments section, any tasks with the #🦅🩺-bird-care/long-term tag in them show up here.

## Overall:

![[2501 AMKE#Overall|2501 AMKE > Overall]]

The code here goes through each daily note and first finds the heading for each section (Clinic, New Admit, or Barn.) Then, in that section, it looks for a line that contains the name of the note. It then pulls in all that information. So, nothing on your end needs to be done here. You just need to name the note and the code will handle the rest.

# Up Next:
- [[Charts|Charts]]