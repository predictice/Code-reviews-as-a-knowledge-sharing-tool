# <p align="center">**Code reviews as a knowledge sharing tool**

  
![Compteur de vues de profil](https://komarev.com/ghpvc/?username=Predictice)  

![DESCRIPTION DE L'IMAGE](https://miro.medium.com/max/1050/1*Jmg8-rSSOqbS96JCL5zqQw.jpeg)
  
  
## **How we made merge requests a central part of our knowledge sharing toolbox**
  
Here at Predictice, we recently set up new guidelines on how merge requests (MR, or pull requests in the GitHub world) should be created, reviewed and approved. The goal is to make code review a central part of our knowledge sharing toolbox through common expectations and conventions.
  
  
## **MRs should not undermine efficiency**
Most developers know it, we are most efficient when we can work uninterrupted and dive deeply into the problems that need solving. In this context, impromptu messages and notifications from teammates asking to take a look at their shiny new MR can break our flow and be quite enraging.
  
  
To fight this issue, developers can review MRs in their own time and reviewing code has become an asynchronous process. In practice, that means reducing the number of notifications associated with merge requests to a minimum.
  
  
However, to prevent reviews from piling up, notifications are allowed at least half a day after the MR creation if nobody glanced at it yet.
  
  
## **MRs are great for learning**
Reviewing code is a great way to discover and understand new parts of the codebase. Before we started designing the guidelines, code reviews were experiencing a kind of inbreeding issue: developers were only assigning code reviews to teammates that were already very familiar with the code to review. That was usually great for reducing review time, but this robbed new recruits or curious teammates from great learning opportunities.
  
  
In our new guidelines, MRs get assigned to several teammates, including some that are not already familiar with the code to review. This gives everybody more opportunities to discover new parts of our code base, while also inviting fresh ideas into the review process.
  
  
For an even more hands-on approach, pair code reviews are also encouraged. Reviewers sitting together and discussing the changes introduced by an MR is a great practice for sharing insights and ideas, especially if one of the reviewers is less knowledgeable than the other.
  
  
  
## **Explicit approval requirements**
To further encourage developers to review code outside of their comfort zone, we now require at least two approvals on each MR before merging. Among these approvals, at least one must come from a developer familiar with the code being updated. The other approval is open to anyone, thus giving curious developers time to take a look at the changes, give some feedback and ask their always welcome questions.
  
Requiring multiple approvals also has the benefit of distributing code ownership. When new code has been reviewed by several team members, it becomes the responsibility of the whole team.
  
## **Feedback conventions and open discussion**
Not everyone knows how to give good feedback and not everyone interprets feedback the same way. This can lead to misunderstanding and unnecessary back-and-forths between author and reviewer. To overcome these human limitations, defining a clear set of conventions on how feedback should be given can be extremely helpful. Enter Conventional Comments, a standard for structuring comments in order to convey their meaning more clearly.
  
  
By tagging comments with labels such as question, suggestion or issue, we explicitly indicate the intent of the feedback. Additional tags about the comment being blocking or non-blocking can also give the author further indication of whether the matter should be resolved before proceeding or not. This has been really helpful in avoiding misunderstandings during code reviews. Once comments are clearly worded and easily understood, it becomes way easier to discuss it openly, and the interaction runs faster.
  
  

Code reviews are also a great moment to learn about domain-specific concepts or choices and the question label of the conventional comments framework is a great tool for that.
