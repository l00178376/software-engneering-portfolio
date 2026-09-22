Software Engineering module 
it will contain lab work over the weeks

1.1 ## Week 01 reflection 
To me, software is more than just coding. It is a collection of instructions, data, and interfaces that work together to solve a problem or provide a useful service. I use software every day, from messaging apps and web browsers to banking and university systems. When software works well, I often barely notice it. For example, Google Maps usually gives me clear directions and updates quickly when conditions change, which makes it feel reliable and straightforward.

Engineering involves thinking about requirements, reliability, security, maintainability, testing, and how software will behave as more people use it. it involves using appropriate theories and and methods to solve a problem. Good engineering means considering not only whether something works today, but also whether it can continue working and be changed safely in the future.

I have also experienced software that was frustrating: websites that load slowly, apps that crash, or forms that lose information after an error. These experiences show that simply writing code that works is not enough. Software engineering is about building software that people can depend on. It combines technical knowledge with careful planning and consideration of the people who will actually use the software.

1.2
Software Failure: I have experienced problems with the Boots app where it did not load correctly while I was placing an order, and I was then charged twice for the same order. My first guess is that the developers could have handled failed or repeated transactions more carefully. For example, the system could check whether an order had already been processed before charging the customer again, and the app could provide clearer feedback when something goes wrong. This experience showed me that software needs to do more than simply work under normal conditions; it also needs to handle errors without causing problems for the user.

Software Success: Google Maps has consistently helped me navigate unfamiliar places by giving clear directions and updating routes when traffic changes. My first guess is that the developers invested heavily in testing, real-time data, and designing the interface to make important information easy to understand.

## The Four Process Activities: RetailSync Case Study
| Stage | Specification | Development | Validation | Evolution |
|---|---|---|---|---|
| Stage 1 — Kickoff | Weak — only a rough verbal description; no written requirements. | Present — developer began designing the database. | Missing — requirements were not checked with warehouse staff. | Missing — no process for handling future changes. |
| Stage 2 — Development | Weak — developers worked from their own understanding. | Present but weak — no coding standards, reviews, or proper version control. | Missing — no systematic testing or warehouse involvement. | Missing — no organised process for managing changes. |
| Stage 3 — Change of Plan | Weak — second warehouse requirements were introduced informally. | Present — existing system was patched to support the new warehouse. | Missing — new requirements were not properly tested. | Present but weak — change was made without proper change management. |
| Stage 4 — Testing | Missing — no written test cases or acceptance criteria. | Present — developers fixed crashes they encountered. | Very weak — developers tested themselves for only two days. | Weak — fixes were reactive rather than structured. |
| Stage 5 — Go-Live | Weak/Missing — system did not match actual warehouse workflows. | Present — system was deployed and subsequently modified. | Failed — users discovered major problems immediately. | Present — team made fixes after the failures. |

2.2 view:
I think the lack of proper specification at the beginning caused the most damage. The developers started work without written requirements or input from warehouse staff, so they made assumptions about how the system should work. This led to problems with the warehouse workflow and made later changes harder. Although testing was also a major failure, better specification could have prevented many of the problems before they reached the final system.
