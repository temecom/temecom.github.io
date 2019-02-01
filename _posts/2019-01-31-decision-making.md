# Decisions, Decisions
## The Art of Decision Making in Software Architectural Design

Decision making is tough sometimes. You have lots of opinions from many sources including team members and self proclaimed experts (like myself) on the internet. You might ask "How do I filter all of that noise down to something that we can use make the correct decision or at least avoid making the wrong decision?".

Well, I am here to tell you that in most cases the only truly wrong decision is no decision. Often you are choosing between several 'correct' options where one may be a little more correct than the others depending on your situation. Sorry to take the wind out of the long winded debates that rage on the internet like the Crusades. 

A classic example is the choice of IDE that your team will use. It is important that the tool set used by the team members is consistent so that wiki instructions for set up and use are common and not duplicated for each individual's environment. That being said the top 2 or 3 IDE's are pretty well equivelent in features and utility and the choice is probably not going to impact the project delivery  significantly. 

Long drawn-out arguments over which is the right one to use will, however, impact overall productivity and team cohesion much more than any productivity gain or loss associated with a particular choice.

I have seen teams locked in IDE wars to the point of total breakdown where management was forced to let a member go because of fiercely held personal preferences. 

Clearly not a desired outcome for management, the team or the team member. 

You could also just dictate the choice of IDE and move on, leaving a part of the team delighted and the other team members disgruntled. Again not a sound strategy for building a smoothly functioning team. 

Presented here are four strategies that you can use in different scenarios for making decisions as a team and a team leader. 

### Team Vote Strategy
In cases of personal preferences like one outlined above a team vote is often the best way to resolve an issue. Here are the steps to quickly arrive at a team decision: 

- Call a brief (<1hr) meeting to: 'Make a team decision on xyz'
  - Ask team members to prepare their arguments ahead of time in written form on your 'Decisions' Wiki page (you have one don't you?)
  - Provide a time limited session (5 minutes perhaps) for each team member to present their arguments in concise fashion
  - Call for a vote via show of hands on each choice
    - In the case of a tie vote use an external source to break the tie such as 'The most popular' on a reputable rating site.
  - Record the votes along with the arguments presented
    - This is important as a reference later when management or team members ask the inevitable "Why did we make that decision?"

### Decide, Present Rationale and Solicit Feedback Strategy
In a situation where management has brought you in to provide guidance and coordinate the efforts of a team you are the one who has to make the decision and communicate it to the team effectively. Often team members are looking for direction and are more interested in consistency than in participating in the actual decision making process. Furthermore including the whole team in all of the details can be distracting and may bog down the proccess to a point of stasis. 

Examples of this are the folder structure of the project or a class inheritance heirarchy. 

As an experienced Architect you are probably used to preparing and presenting complex solutions and the rationale for their adoption. As a new Architect this is a skill that you will need to aquire and hone, so embrace it as a necessary tool in your prefessional toolbox. 

 - Prepare your presentation
   - Use Power Point or equivelent presentation tool so that you can walk the team through your decision making process
   - Break the presentation into sections of 1 to 3(max) pages each:
     - The Problem (or Requirement)
       - What are we trying to solve
       - Past attempts at a solution
       - Gaps in the current solution
     - The Proposed Solution(s)
       - How does it address the problem
       - What is the scope (effort, time $ etc) of the implementation 
       - Benefits & Risks      
       - Side by side comparison if more than one was considered
     - Recommendations
       - My recommendation is...
         - They are looking for your recommendation make it clear
   - The process of preparing the presentation is often a good way to organize the foundations for a decision and to help you to make a sound one
 - Present your proposal to the team and stakeholders in a brief (1hr or less) meeting with a formal agenda: 
   - Presentation
     - Include links to your document so that team members are prepared and can reference it later
   - Questions and Discussion
     - Ask the audience to kindly hold their questions for this dedicated period
   - Decision
      - If you have presented a strong, substantiated argument and there are no major objections the meeting should result in team concensus and stakeholder blessing
      - If not or there are unresolved questions try to get partial concensus and defer any remaining items to a short follow up meeting
   - Documentation for later reference
     - Important!!!
     
## External Authority Strategy
Other smaller decisions are often made on a daily basis by individuals on the team and they just need some consistent guiding principles. 

Examples of this include coding style, naming conventions or source code commit comments. 

It is important to establish and document these pricipals in the form of 'Development Guidelines' and to make them readily available on you team wiki. 

Being especially lazy and willing to reap the benefits of others' work I usually defer to an 'External Authority' on most guildeline policies. 

There are well established norms in most areas that are published and accepted by the industry. The important thing here is to decide on an authority up front and consistently refer to that authority to quickly resolve any opinion based arguments. 

 - Create a 'Developers' Guideline' document on the team wiki
   - List the areas of concern
     - Coding Style
     - Naming Conventions
     - Commit Comments
 - In each section document the the exteral authority to be used with a web link. 
 - Typical authorities are: 
   - [Code Conventions for the JavaScript Programming Language](https://www.crockford.com/javascript/code.html)
   - [Code Conventions for the Java Programming Language](https://www.oracle.com/technetwork/java/javase/documentation/codeconventions-139411.html)
   - [NIEM-National Information Exchange Model](https://www.niem.gov/)
     - Naming conventions and modeling guidance
   - [Use Smart Commits - Jira](https://confluence.atlassian.com/bitbucket/use-smart-commits-298979931.html)
 - Document any exceptions or special guidelines for your team
 
 
## Try and See Strategy
Sometimes you don't have enough knowlege or relevent examples to act as the basis for making a decision. In these cases a try and see strategy can quickly expose the strengths and weaknesses of a single or competing technologies or architectural approaches. This is often refered to as a 'Research Spike' in the Scrum world. The important thing to manage in this strategy is the time alloted for the the 'try' period so that it does not become a lengthy 'College Project'. The steps in implementing this strategy are: 

 - Create the Research Spike in your tracking system with: 
   - Context
     - The problem summary
     - Time limit (or story points) alloted for the spike
   - Goals
     - Specific goals of the spike with:
       - The proposed solution or areas of investigation
       - Tests relevent to proving the solution
       - Documentation and presentation of the results to team
   - Acceptance Criteria
     - The criteria that will be used to make a decision
     - The decision is documented
       - Important!!!
 - Assign team members to investigate and prepare a report and presetation
 - Scheduled a decision meeting at the earliest feasible time

#Conclusion
Establishing and documenting a decision making process is an important step in aligning and focusing your team on the common goal of 'gitn r done' without the distraction of long winded discussion about personal preferences or past methods. 

Save those for apre\`- work get togethers at the pub :) 

... Cheers
