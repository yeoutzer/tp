---
layout: page title: Zen's Project Portfolio Page
---

## Project: FlashBack

FlashBack is a desktop flash card application used by students to revise for their examinations. The user
interacts with it using a CLI, and it has a GUI created with JavaFX. It is written in Java, and has about 10 kLoC.

Given below are my contributions to the project.

* **Code contributed**: [RepoSense link](https://nus-cs2103-ay2021s2.github.io/tp-dashboard/?search=zenlyj&sort=groupTitle&sortWithin=title&timeframe=commit&mergegroup=&groupSelect=groupByRepos&breakdown=true&checkedFileTypes=docs~functional-code~test-code~other&since=2021-02-19)

* **New Feature**: Added the ability to allow user to edit flashcards. [#54](https://github.com/AY2021S2-CS2103T-T13-3/tp/pull/54), [#72](https://github.com/AY2021S2-CS2103T-T13-3/tp/pull/72)
    * What it does: Modifies the question, answer, category, priority, tags of flashcards.
    * Justification: It is possible that the user make some mistakes when adding a flashcard, such as setting a wrong priority,
    setting a wrong category, or just minor typos. So instead of having to delete the flashcard and add the flashcard again,
    the edit command allows the user to quickly correct his/her mistakes made.   

* **New Feature**: Added the ability for user to display statistics of flashcards. [#81](https://github.com/AY2021S2-CS2103T-T13-3/tp/pull/81)
    * What it does: Shows the user statistics of an individual flashcard, or the statistics of all flashcards
    in the list. The following information is displayed: 
      1. Number of times the user reviewed the flashcard(s). 
      2. Number of times the user reviewed the flashcard(s) and got the correct answer 
      3. Correct rate of the flashcard(s). i.e. The number of correct answer reviews over the total number of reviews. 
      4. Wrong rate of the flashcard(s). i.e The number of wrong answer reviews over the total number of reviews.
    * Justification: This feature is quite crucial to the product as it allows the user to keep track of his/her
    performance across multiple review sessions, therefore allowing the user to identify areas of weaknesses and work on
    them.
    * Highlights: This feature was highly non-trivial to implement. I had to have a good understanding of the implementation
    of review mode, so that I could extend review mode to allow users to mark a flashcard as correct or wrong during review
    sessions. Additionally, a good grasp of how the UI was implemented was necessary, as I had to extend on
    the existing UI to display the statistics, in pie chart and in text.   
      
* **Project management**:
    * Managed release of `FlashBack v1.3` on github.
    
* **Enhancements to existing features**:
    * Refactored a large proportion of the AddressBook codebase to fit FlashBack. [#54](https://github.com/AY2021S2-CS2103T-T13-3/tp/pull/54)
    
* **Documentation**:
    * Updated the user guide and developer guide with information regarding the Edit functionality. [#64](https://github.com/AY2021S2-CS2103T-T13-3/tp/pull/64) 
    * Updated the user guide and developer guide with information regarding the Statistics functionality. [#90](https://github.com/AY2021S2-CS2103T-T13-3/tp/pull/90)
    * Added non-functional requirements and instruction of manual testing for Edit and Statistics to the developer guide. [#105](https://github.com/AY2021S2-CS2103T-T13-3/tp/pull/105/files)
    * Added use cases for Add functionality in developer guide. [#39](https://github.com/AY2021S2-CS2103T-T13-3/tp/pull/39) 

