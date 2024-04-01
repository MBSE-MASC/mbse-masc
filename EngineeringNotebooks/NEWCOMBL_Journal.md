# Semester 1

## 10/23/2023

Continuing on the context diagram. Trying to also revise the stakeholder needs past our initial list.

I learned that Git merges aren’t going to work for our project, but I figured out the Magic System of Systems Architect project merge feature, and the 3-way merge is ideal for our project and will work for concurrent work.
10/25/2023

I created the beginnings of our real system context diagram from our plan.

## 10/26/2023

We met with Akbas and the TA about our project and had our scrum meeting in class.

MagicDraw doesn’t like to merge unrelated projects, and it was faster to re-create my context diagram in Shawn’s project instead of merging them.

We finished the first draft of our system context diagram.

## 10/27/2023

We met with Kathryn to discuss our system context diagram and how to move forward. She told us that our system context looked good, and we just needed to modify our stakeholder needs to be more uniform and use “the system should” instead of “I need.”

We modified the system context diagram a bit, changing arriving and departing crew to just be a bidirectional “crew” arrow.

## 10/30/2023

Today the team met briefly to move forward with the use case diagram. We found out that we did the system context incorrectly even though Kathryn said that it looked good. We have kept that in mind and are following the MagicGrid book of knowledge until we can have another meeting with Kathryn to discuss what she thinks about any discrepancies.

I fixed the system context diagram by changing the stereotype/type of the various external systems away from “External System” which seemed right, but was actually something left in from the MagicGrid v2 template from the car example. We need to create new Actors as blocks and set the type of each Part Property in the system context to each corresponding actor type. Then we could drag the actors directly onto the use case diagram and it worked fine.

## 10/31/2023

I worked on our Sprint 2 demo presentation throughout the morning adding our current work as best as I could. Yesterday the rest of the team worked on creating a use case diagram, or at least the start of one. By the looks of the email that they sent Kathryn they were a bit confused, as I was. It has a use case, and there is a corresponding high-level activity diagram describing what is happening in the use case, and it involves all of the actors in the system. It looks good. My current priority is to understand how that was created, and work on the presentation.

Added our 2nd presentation slides to the GitHub repository

We worked on the Software Design Document updating it with our most current process for creating the models.

We created and added the Sprint 2 Demo presentation to the GitHub repository

## 11/01/2023

Today we identified and categorized our stakeholder requirements and created the measures of effectiveness from the model's current nonfunctional requirements. It was a bit of a challenge figuring out how to assign different measures different unites but we figured it out.

## 11/03/2023

Due to the final end goal of our presentation being to submit a paper about our experience to a reputable journal, we have been researching different opportunities for submitting our research.

## 11/14/2023

Today we revisited our use case scenario for the manage flight use case making it more detailed, referencing a model that we found online as a reference. This will count towards our functional analysis part of the model process for MagicGrid.

## 11/16/2023

Today we met with Kathryn in order to have her review the current state of our model. We got great feedback on our current context diagram and its differences with her context diagram. We were confused about why the relationships in her model were the way that they were. She used composition to the system of interest compared to our model where we thought it made more sense to have an aggregation relationship between the various external components of our model and the external system block. We figured out that the reason that she did that was for later on in the model. We also reconstructed our system context model to be a block definition diagram vs. an internal block diagram. This is because later in the model we will keep those same relationships and MagicDraw will identify those external systems as being a reference rather than a component of the system.

## 11/17/2023

Shawn read the SysML distilled book and helped us fix our model to conform better to well-known SysML practices, although we identified that our model and SysML in general is highly subjective since it is just a modelling language and not a framwork for operation. This has made us respect MagicGrid a lot more.

## 11/28/2023

Today we identified that an early opportunity for showing our work is the Boeing Aviation Safety poster event.

## 11/30/2023

Today we finished up our models to be completely self-consistent and internally complete for our final demonstration. We created our final presentation slides and presented to the class.

## 12/04/2023

Today we created and completed our Boeing CAAS event poster for presenting the current state of our research.

## 12/05/2023

Today since we missed the INCOSE conference so we identified other conferences that we could present our work at.

# Semester 2

## 2/7/2024

I met with the team to reassess splitting of tasks and creating a work breakdown structure. I’m focused on figuring out how to delegate tasks and work concurrently. We’ve determined that a control flow doesn’t need to be placed between two functional analysis activities if there is already an object flow in that direction. I’ve been helping Walter determine the conceptual subsystems and Shawn create the lower level functional analyses.

## 2/10/2024

I worked a bit on refactoring the model's functional analysis activity diagrams by myself. I studied the MagicGrid book of knowledge a bit more and maybe see where it is going.

## 2/13/2024

Today we had a meeting with Kathryn. I was supposed to present because Shawn was going to be late for the meeting but he made it in time so he presented our work. Kathryn gave us a lot of good feedback on our model and overall claimed that she was proud of our work. Luckily we rememebered to record this meeting for future reference. We learned that we need to do our subsystem decomposition a bit differently, but she liked our activity diagrams. We need to focus tomorrow on requirements tracing and generation as well as lower level functional analysis because we decided to meet with her again on Thursday (2/15/2024).

## 2/14/2024

Today the team met together to work and focus on improving the model. Shawn and I worked on improving the functional analysis and subsystem decomposition while Walter and Clay worked on requirements tracing. We discovered a problem with the requirements tracing where in our stakeholder needs "Traced To" section of the table it has way too many elements showing up than it should. It should only show the requirements generated from the stakeholder needs and the MoE constraint blocks. We got a lot of good work done today.

## 2/15/2024

This morning we met with Kathryn again to see if we were implemeting her advice correctly. I had to present our model as Kathryn wasn't there. I enjoyed it and I think it went a little bit more efficiently. She explained a lot and we learned a lot of valuable information. The issue we had with our stakeholder needs table she didn't like and also couldn't figure out. It is possible that it is an issue with the tool itself. We learned a lot more about how to do FMEA and we got a really good starting explanation. I got a hands-on tutorial. We learned more about requirements tracing and she liked all of the work we did yesterday. The next steps are just to take things a lot further.

I took the liberty of merging all of our changes from all of those meetings and it was relatively painless.

## 2/29/2024

Today we met with Kathryn in order to have her check our work that we did on FMEAs and our requirements traceability.

## 3/04/2024

Today we met with Kathryn and had her check our sprint 2 demo presentation for accuracy. The meeting was fairly successful although we should have had more of it done beforehand. She liked what we had to say and told us to include more graphics. 

## 3/05/2024

Today we gave our sprint 2 presentation. We were over time by a little bit but everyone seemed to be okay with it and we got a lot of good questions. Some notes for the next one are that we need to improve how we describe moving through our model, we need some sort of "map".

## 3/29/2024

Today we had a follow-up meeting with Kathryn again checking the new work we did on our FMEAs and ideas for the final presentation. She wants us to virtually present to one of her classes as practice for the final.

## 3/31/2024

Today Walter and I worked a little bit more on performing the hazard analysis portion of the FMEA table.