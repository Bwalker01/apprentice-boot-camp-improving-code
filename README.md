<!--- ORGANISER THINGS TO CONSIDER 
- Which technical competencies, behaviours and knowledge module topics does the bootcamp cover/meet
- Structuring retros so that they can inform thinking for individual's personal learning records (off the job training record tab in their learning logs)
- Introducing some sort of test or quiz on basic concept learning points from the bootcamp to validate that they have taken stuff in, and provide organisation mentors with results to help them focus follow ups
--->

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/4a7907d9b43e4c2cb316833b42b59ff3)](https://app.codacy.com/gh/Bwalker01/apprentice-boot-camp-improving-code?utm_source=github.com&utm_medium=referral&utm_content=Bwalker01/apprentice-boot-camp-improving-code&utm_campaign=Badge_Grade_Settings)

## Competencies, Behaviours and Knowledge units

* **[S1](https://www.instituteforapprenticeships.org/apprenticeship-standards/software-developer-v1-1#S1)**: create logical and maintainable code
* **[S8](https://www.instituteforapprenticeships.org/apprenticeship-standards/software-developer-v1-1#S8)**: create simple software designs to effectively communicate understanding of the program
* **[S11](https://www.instituteforapprenticeships.org/apprenticeship-standards/software-developer-v1-1#S11)**: apply an appropriate software development approach according to the relevant paradigm (for example object oriented, event driven or procedural)
* **[S12](https://www.instituteforapprenticeships.org/apprenticeship-standards/software-developer-v1-1#S12)**: follow software designs and functional or technical specifications
* **[S14](https://www.instituteforapprenticeships.org/apprenticeship-standards/software-developer-v1-1#S14)**: follow company, team or client approaches to continuous integration, version and source control
* **[S15](https://www.instituteforapprenticeships.org/apprenticeship-standards/software-developer-v1-1#S15)**: communicate software solutions and ideas to technical and non-technical stakeholders
* **[B7](https://www.instituteforapprenticeships.org/apprenticeship-standards/software-developer-v1-1#B7)**: Communicates effectively in a variety of situations to both a technical and non-technical audience
* **[B4](https://www.instituteforapprenticeships.org/apprenticeship-standards/software-developer-v1-1#B4)**: Works collaboratively with a wide range of people in different roles, internally and externally, with a positive attitude to inclusion & diversity


## Resources 

* Slides
* Laptops
* Internet access
* Post-its
* Pens
* Whiteboard
* Paper
* QWAN cards (Mark and Alec have sets of these)

## Mentors / Languages
 
Two–three mentors required in addition to leads. These should be able to cover support for the required languages.

## Prep-work for apprentices

* Make sure you can sign in to github.com with your own account
* **Fork** this repo (so you can push your changes later)
* Clone your fork: `git clone https://github.com/[your-username]/apprentice-boot-camp-improving-code.git`
  * ⚠️ Don’t use the IDE to clone the project, as it will open the root of the project which is wrong
* Follow the instructions in the README for your language under the `exercises` directory, **making sure that the tests run and pass**
  * [Java](exercises/java/README.md)
  * [JavaScript](exercises/nodejs/README.md)
  * [C#](exercises/chsarp/README.md)
* It’s normal to have problems with this, so just let us know! :)

## Follow-on tasks

Organisation mentors should look to exercise the knowledge we’ve covered in the boot camp. Below are suggestions for tasks that would do this, but please use your own judgement to work out what to do. There is no need for anything to be returned to MD or the presenters—it’s just a learning exercise.

* Search for code smells in code-bases back at work
* Apply code smell searching and refactoring to portfolio work and document
* Maybe use [QWAN cards](http://www.qwan.eu/shop) as a teaching resource to help organise refactoring work
* Apprentices should deliver a code review, and receive feedback about it
* Configure / review static analysis for an existing reasonably sized project (use [Codacy](https://app.codacy.com/) if no existing system in use and the code is publicly available)
* Java apprentices can also add [Error Prone](https://errorprone.info) to an appropriate project—maybe one in it’s early days so that it is possible to introduce
* You could code review their changes in the Code Smell trivia exercise—they can provide you with the address for their fork
* You can see how they reviewed each other’s changes in the exercise—one again they can provide you with a link to their comments

## Further reading / learning resources

<!--- For end of boot camp: Signposting for apprentices self study, further learning, online resources, practice etc. --->

Books:
* [Working Effectively with Legacy Code, First Edition by Michael Feathers](https://www.oreilly.com/library/view/working-effectively-with/0131177052/)
* [Refactoring: Improving the Design of Existing Code by Martin Fowler](https://www.oreilly.com/library/view/refactoring-improving-the/9780134757681/)
* [Mythical Man-Month, The: Essays on Software Engineering, Anniversary Edition, 2nd Edition by Frederick P. Brooks Jr.](https://www.oreilly.com/library/view/mythical-man-month-the/0201835959/)

Video:
* [The Art of Giving and Receiving Code Reviews (Gracefully)](https://www.youtube.com/watch?v=hfrNmZIPq3E) (30 minutes)

Web:
* [QWAN Code Smells and Refactoring Cue Cards](http://www.qwan.eu/shop)
* [Refactoring Guru’s section on Code Smells](https://refactoring.guru/smells/)—this is an excellent site, and super accessible
* [8 Tips for Great Code Reviews](https://kellysutton.com/2018/10/08/8-tips-for-great-code-reviews.html)—five minute read with some good top level tips, well communicated. Maybe share this at work if review doesn’t go so well?
* [Awesome code review](https://github.com/joho/awesome-code-review): An "Awesome" list of code review resources - articles, papers, tools, etc
* [Reviewing proposed changes in a pull request]](https://help.github.com/en/articles/reviewing-proposed-changes-in-a-pull-request)

## Slides

The slides can be viewed from the link at the top of the repository.

## Exercises

* Reading [Trivia](https://github.com/jbrains/trivia) code base to understand what it does and how it works
* Identifying and removing code smells in Trivia code using refactoring techniques
* Setting up static analysis for codebase to identify and measure violations of automated rulesets
* Identifying and removing more code smells in Trivia code
* Providing code review on each others refactoring work in the Trivia codebase, with emphasis on how to use GitHub to communicate issues and praise effectively

# Briefing for organisation mentors

* Familiarise yourself with following code smells using [this site](https://refactoring.guru/smells/)
    * Uncommunicative Name
    * Duplicate Code
    * Magic Number
    * Long method
    * Conditional complexity
    * Large class
* Familiarise yourself with the [Trivia](https://github.com/jbrains/trivia) code base
    * Maybe try refactoring it?
* Understand what the golden master test does, and how to regenerate the golden masters
    * May need to do this if bugs are identified and fixed
* Try setting up [www.codacy.com](https://www.codacy.com) on one of your repos, or a fork of this one

# Contributing

If you’d like to contribute changes to the slides or exercises, please see [our contributing guidance](CONTRIBUTING.md).
