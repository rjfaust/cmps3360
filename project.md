# Graduate Project

Due Dates:
-  Pitch: February 14, 2024
-  Pitch write-up: February 17, 2024, 11:59pm
-  Update: March 21, 2024, 11:59pm
-  Presentations: April 28 & 30, 2024
-  Final Report: May 7, 11:59pm

 
## Project Description

Projects can come in one of two flavors: (1) Find and implement a technique from a paper published at a relevant visualization venue, such as [IEEE VIS](https://ieeevis.org/year/2024/welcome) or [EuroVIS](https://event.sdu.dk/eurovis), from the past 5 years or (2) **\*\*For Non-CS Majors Only\*\*** Design and develop an interactive visualization tool for data in your field of expertise. Graduate students with a CS background are required to use the first option. For the second option, it may be more difficult to select a problem of sufficient scope.

### Option 1: Implementing a Past Technique

In this option, you will choose a recent work from [IEEE VIS](https://ieeevis.org/year/2024/welcome) or [EuroVIS](https://event.sdu.dk/eurovis) to implement. Other venuse may be considered (such as ACM CHI), upon instructor approval, provided that the paper contains sufficient visualization contributions. The chosen technique should be of significant scope. You may also opt to implement only part of a technique if the scope is too large for a semester project, subject to the instructors approval. 

The language and platform used for the project is your choice, but you **may not** use any existing code repositories associated with the paper - we will be checking! 

To help assess the scope, it may be useful to enumerate the requirements for successfully implementing and evaluating (through usage scenarios or computational benchmarks) the technique and consider whether all of those are (1) achievable in roughly 8-9 weeks and (2) are not achievable in less than 5 weeks.


### Option 2: Design an Interactive Visualization of Data in Your Field

In this option, you will design an interactive visualization tool for data from your field. You will identify a source of data and subsequent problem with or unanswered question about that data, and design an interactive visualization tool to help address it. Your problem should not be easily solved with a single or a few static visualizations.  

To help assess the scope, it may be useful to enumerate the tasks needed to address the problem and consider whether they can be addressed by simple, static visualizations and where interaction is necessary to accomplish them. 

## Milestones

### Project Pitches (5%)

Projects must be pitched and approved by the end of week 5. You must schedule a time with me outside of class to discuss your project idea. To help demonstrate the scope of your project, I recommend coming prepared with a description of the requirements for success in your project (e.g. the necessary components that need to be designed and/or implemented, what needs to be done to test/evaluate it, etc.). I will give feedback on the viability of your plans, especially about whether you've picked the right scope (not too big, not too small). Projects must be significant in scope to receive approval. You must meet with me and get your project approved by February 20.

Following this meeting (and project approval), you will submit a description of your approved project, the requirements for success, and a tentative timeline for carrying out those requirements. This description should be about 1 page in length (and no more than 2) and must be submitted on Canvas by 11:59pm on February 23.

 
### Project Update (15%)

At the end of the 10th week, you will submit an update describing the progress you have made on your project so far. Your update should start by describing the project and include a description of what you have accomplished so far, what is still in progress and what work is left to be done. You should include screenshots of what you have accomplished so far. Additionally, you should discuss any barriers to success you have encountered thus far, and any adjustments/refinements you need to make to your proposed project. It is expected that your work will be preliminary/incomplete, the goal is just go give a status update.


I recommend structuring your update similar to your final report so that you can re-use content as possible.

 
### Project Presentation (30%)

In week 16, you will present your projects to the class. I have set aside two class periods for this but we may not need to use both of them. Your presentation will be 10 minutes long with an additional 2 minutes for questions from the class. Your presentation should use slides, which you will submit with the final project submission. Where appropriate, your presentation should include a demo (either live or per-recorded) of your project. At a minimum, your slides should contain images of your final project.

 

 
### Project Submission and Report (50%)

For your final project submission, you will need to submit three things: a link to your project repository on GitHub, the slides from your presentation, and a final report.

 
#### GitHub Repository

Your GitHub repository should contain the well-documented source code for your final project. Additionally, it must contain a README.md file that contains the following:

 -   A detailed description of how to build and run your project. If your project requires any external libraries or tools, or was built using a specific browser, be sure to note that down.
 -   A roadmap describing the repository, such as which parts are your code, which are other libraries (if used), etc.

 
#### Final Project Report

You will write a final project report that detailing your project. The purpose of this report is to demonstrate your knowledge of the problem, what you achieved in your implemented solution, and what challenges you overcame along the way. If you choose the first option of implementing a technique from past work, you are allowed to reference the existing paper but of course may not directly copy any components of the paper. Your project report should demonstrate that you understand the problem and the implemented solution. There is not page minimum or maximum, but I anticipate that your reports will be around 5-8 pages, single column. **Note,** this is a visualization project - your report should include several images and screenshots to show your visualizations!

Your report should have roughly the following components (not necessarily in this order or these exact sections):

 -   Abstract
       - a concise summary of your project. Do not include citations
 -   Introduction
     -   A big picture description of the problem you were solving (with necessary background) and a high-level description of your implemented solution. If you implemented a past technique, describe the scope of your implementation with respect to the original technique.
 -   Related Work
       - A description of closely related work.
           - **For option 1:** If you are implementing an existing technique, this will largely be discussing the paper you are implementing. However, you may also want to describe some closely related work to provide more context.
        - **For option 2:** If you are implementing a visualization system for your own data, you should provide more detail on relevant techniques. This includes techniques solving similar problems as well as techniques that design similar solutions. Note, it is not required that you design a novel/unique visualization solution but you should discuss how existing work is similar/dissimilar to your solution.
-    Data and Task Abstractions
       - You should describe the data and task abstractions, as outlined by Munzner's framework. It is likely that you will need to have domain specific descriptions for both the data and tasks, followed by the abstracted versions.
-    Solution
       - **For option 1:** If implementing existing work, give a big picture description of what you did, especially if you only implemented a portion of what was in the original paper. You do not need to explain the solution at the level of detail of the original paper but provide enough context for the reader to understand the approach and your implementation.
      -  **For option 2:** If implementing a visualization of your data, describe your solution and justify your design choices against alternative possibilities. Where applicable, use the principles described in class to describe/justify your design.
-    Implementation
      -  Provide a detailed description of the implementation of your project. Include the specifics of what you implemented vs what external tools you built upon. This section will be much more detailed than in a typical research paper.
       - **For option 1:** At this point, you should also discuss any challenges or issues that arose in your implementation, such as choices you had to make that were not clearly specified in the paper. In what ways did the description in the paper fall short and how did you overcome these shortcomings?
-    Results
       - This should include at least one example scenario or, where applicable, computational benchmarks to demonstrate your implementation. This should consist of several screenshots that walk the reader through scenarios using the visualization. This section is key for demonstrating how your implemented visualization helps solve the described problem.
-    Discussion
      -  Reflect on your project. Describe the strengths, weaknesses, and limitations of the solution/implementation. Discuss any challenges overcome and lessons learned. Finally, describe avenues for future work (what questions remain unanswered by this solution, what would you do if you had more time).
-    Conclusion
      -  Summarize/recap what you've done in a way that's different from the abstract.
 -   Bibliography
       - Cite any referenced work. Use a single citation format for all of your citations.

