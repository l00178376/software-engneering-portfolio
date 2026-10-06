# Task 1 – Waterfall Change Impact
## 1
The new multi-restaurant ordering feature was requested in Month 4, after the requirements and design had already been signed off. Because the project follows a waterfall process, the change causes re-work in several completed or planned stages.
Overall, the change creates re-work because it arrives after requirements and design have already been completed and signed off. This is a key disadvantage of making significant changes late in a waterfall project

Step 1 – Change Request
The new feature should be formally recorded as a change request and its impact assessed.
Why: It was not part of the original agreed scope so need to do formal change request.

Step 2 – Update Requirements
The affected requirements for ordering, checkout, payment and restaurant processing need to be updated and signed off again.
Why: The original requirements were already approved and the new feature changes them.

Step 3 – Update Design
The affected design needs to be reviewed and approved again.
This includes:
Order data model
Payment splitting
Kitchen notifications
UI
Why: The original design was based on the old requirements.

Step 4 – Rework Existing System
Already-built components need to be changed:
Order data model → support multiple restaurants.
Payment logic → split one payment between restaurants.
Kitchen notifications → send each restaurant only its items.
UI → allow multiple restaurants in one checkout.
Why: These components were built using assumptions from the original requirements.

Step 5 – Update Testing
New test cases and regression testing are required.
Why: The new feature must work correctly without breaking existing functionality.

Step 6 – Review Project Plan
The timeline, resources and budget need to be reassessed.
Why: The extra design, development and testing require additional work and may require more people, time or money.

The Month 6 deadline may therefore be at risk, although it does not automatically have to be delayed.

## 2
# Task 1 – Impact of the Change Using 2-Week Increments
If the same team worked in 2-week increments, the impact of the new feature would generally be easier to manage because the project is designed to accommodate changing requirements.

Step 1 – Request the Change
The university requests the multi-restaurant ordering feature.
The team assesses the change and discusses its importance with the client/product owner.

Step 2 – Prioritise the Change
The feature is added to the project backlog and prioritised.
It can then be planned into a future 2-week increment.
Why: The team can adjust upcoming work instead of having to completely change an already-fixed project plan.

Step 3 – Update Requirements and Design
The affected requirements and design are updated as needed.
This includes:
Order data model
Payment splitting
Kitchen notifications
UI
Why: The system still needs to be designed correctly, but there is more flexibility to change the requirements and design as the project develops.

Step 4 – Develop the Feature
The team implements the changes during a 2-week increment.
The work can be broken into smaller tasks and delivered incrementally.

Step 5 – Test the Changes
The new functionality is tested during the increment, along with regression testing to make sure existing features still work.
Why: Testing happens continuously rather than waiting for one large testing phase at the end.

Step 6 – Client Review
At the end of the increment, the client reviews the working feature and provides feedback.
Further changes can be added to a later increment if required.

Step 7 – Review Project Impact
The team may need to review time, resources and budget if the feature is large.
However, the impact can often be managed by reprioritising other work rather than changing the entire project plan.

# comparison 
| Area | Waterfall | 2-Week Increments |
|---|---|---|
| Requirements | High effort – signed-off requirements need updating and approval. | Lower effort – change can be added to the backlog and prioritised. |
| Design | High effort – completed design needs to be revisited. | Lower effort – design can be adjusted for the next increment. |
| Development | High effort – already-built components need rework. | More manageable – work can be planned into a future increment. |
| Testing | High effort – new and regression testing may affect the planned testing phase. | More manageable – testing happens within each increment. |
| Timeline | Higher risk of delay to the Month 6 deadline. | More flexible – other work can be moved to accommodate the change. |
| Resources | May require additional developers/testers. | Resources can be adjusted between increments if needed. |
| Budget | Greater risk of extra cost due to rework and resources. | Usually easier to manage, but a large change can still increase costs. |
| Approvals | More formal – affected requirements and design may need sign-off again. | Less formal – mainly requires prioritisation and client/product owner approval. |
| Overall Effort | **Higher** – completed work must be revisited. |
