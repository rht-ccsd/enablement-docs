<!-- .slide: data-background-image="images/RH_NewBrand_Background.png" -->
## DevOps Culture and Practice <!-- {_class="course-title"} -->
### Automated Testing Part 1 <!-- {_class="title-color"} -->
DO500 <!-- {_class="title-color"} -->



## Exercise - What is Automated Testing?...
_Answer the question "What is Automated Testing?"_
1. Everyone grab one sticky note.
2. Answer the question "What is Automated Testing?" with one or two words that first
come to mind.
3. Add your sticky to the wall.



<!-- .slide: data-transition="fade-in slide-out" -->
## Automated Testing is...

                              TDD

                                                                           Test Automation

                                            Unit Test



<!-- .slide: id="tdd" -->
## Test Driven Development



### Test Driven Development
#### _What Is It?_
Test Driven Development (TDD) is a software development process that relies on
the repetition of a very short development cycle.
Requirements are turned into test cases, where the software is developed to pass
the tests.

This practice is particularly powerful when combined with
**Continuous Integration**.



### Test Driven Development
#### _How Does It Help?_
* Creates a detailed specification for the code
* Gives fast feedback
* Indicates whether the last change has broken previously working code
* Allows the design to evolve and adapt as understanding of the problem evolves



![TDD](images/tdd/TDD_Lifecycle.png)



## Test Automation
![Test-Automation](images/test-automation.png) 



### Test Automation
#### _What Is It?_
Test automation allows teams to remove the slow and manual testing cycles related to software development. 
Test automation can include such things as:

* Static code analysis
* Linting
* Unit tests
* End-to-end tests
* Security tests

This practice is particularly powerful when combined with
**Continuous Integration**.



### Test Automation 
#### _Why do Test Automation?_
* It increases the code quality.
* It shortens feedback loops.
* It tells if your change broke some previously working code.
* It reduces or eliminates manual steps and frees up resource for other types of testing.



### Test Automation 
#### _How to do Test Automation?_
These tests are typically executed by a build automation tool, for example Jenkins. 
Easy and quick tests should be ran right after building (compiling) your application, such as unit tests and static code analysis. 
Also many of these tests can be run in parallel, decreasing the overall time taken to run the tests.




<!-- .slide: id="revenge-automated-testing" -->
## Revenge of the Automated Testing



### Lab Demo 3: Revenge of the Automated Testing
This lab helps us:
* Understand the "why" behind Test Automation in general
* Show and Review how we can easily automate UI testing that has traditionally being done by human beings during User acceptance testing



### Tools and Frameworks that can be used?
This depends on programming languages and platform but here are some examples. 
For Python here are some tools that can be used
* **Pytest**: small python testing utility that can be used both for small unit tests as well as functional tests.
* **Robot Framework**: Generic open source automation framework. It is a tool that can be used to conduct UI and functional testing.
Tests can be written using human readable keywords in an easy to use syntax.  
* **Sonarqube**: Tool that can be used to improve code quality and security scan. It can assist with several static analysis concerns 
like linting, security scan of source code and many more ...
* **Anchore**: Tool used for continuous security and compliance scanning of containers (images and runtimes)
* **Fortify**: Similar to Anchore, it is a tool used for automated application security scan. 
* **OpenScap**: Open Source tool that works similar to Anchore and Fortify. It is used to assess, remediate and enforce security baseline.



### Tools and Frameworks that can be used?
For Nodejs or other Javascript based frameworks here are some tools that can also be used
* **Jest**: zero configuration testing platform to test JavaScript code
* **Vue Test Utils**: the official testing utility library for Vue.js
* **Nightwatch.js**: easy to use Node.js based end-to-end testing solution for
browser based apps. It uses the powerful W3C WebDriver API to perform commands
and assertions on DOM elements
* **Mocha**: feature-rich JavaScript test framework running on Node.js and in
the browser, making asynchronous testing simple and fun
* **Sinon**: standalone test spies, stubs, and mocks for JavaScript. Works with
any unit testing framework



### Let's Go!!!
Lab Demo 3: _Revenge of the Automated Testing_



### Intent
Demonstrate/Review the Jenkins output of an automated test run using a Robo Framework container.



### Some annecdotes of when Automated testing or TDD was not done or well done 



### Audience Experience and Anecdotes 
<!-- speaker info
Sometimes people will build something new that breaks an existing test and they either won't have noticed or won't have cared. If this is the case then discuss why tests must always be passing.

Generally not everyone will have done this. They'll be so busy creating interesting requirements that they don't have time to build the five things that the customer actually asked for. Discuss this.

Many times people will have built cool things that they didn't have tests for. We stress again that in TDD, we don't build anything until the test has forced us to do that.

 -->
 - What was your experience with Test Automation? 
 - How did that feel?
 - How can some of the topics and tools discussed here be used on your projects?



<!-- .slide: data-background-image="images/chef-background.png", class="white-style" -->
### DevOps practices used in this section:
- [Test Driven Development](https://openpracticelibrary.com/practice/test-driven-development/)
- [Test Automation](https://openpracticelibrary.com/practice/test-automation/)
