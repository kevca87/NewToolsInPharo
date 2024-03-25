# Chapter X: DrTest: Plugins to Enhance the Test Process

A series of tests is the basis of any project. In this chapter, we present DrTest, an extendable plugin-based UI for testing Pharo projects. DrTest offers a suite of functionalities designed to streamline the test process. Our goal is twofold: firstly, to help you make the effective use of DrTest and the associated plugins, and secondly, to equip you with the knowledge to create your own DrTest plugins, thus expanding its capabilities to meet your specific needs.

To achieve these objectives, we will review the existing DrTest plugins. By giving clear examples of usage, we highlight the importance and benefits of integrating these plugins into development workflows and show the functions they bring to test landscapes.

Furthermore, we will review the process of creating DrTest plugins and explain the purpose of the main classes and methods that are involved. With a step-by-step approach, we provide concrete examples, equipping you with the practical know-how to navigate the creation process seamlessly.

By the end of this chapter, you will not only possess a comprehensive understanding of DrTest and its plugins but also manage the competences necessary to use all of its potential in your Pharo projects.

## What is DrTest?
DrTest is a testing analysis tool for Pharos projects that provides a simple user interface for quick test feedback. It consists of several plugins, each offering a different testing perspective. These plugins make it easy to identify improvements, detect potential problems, and optimize project testing. Currently there are six plugins integrated in DrTest: Tests Runner, Test Coverage, Tests Profiler, Rotten green tests finder, Executable comments checker and the Mutation. The following sections delves into the use of each plugin, exploring their functionalities and applications in detail.
## DrTest by example
Since DrTest is a testing tool to show a step by step example we need code to test. In this example we want to test all the code related to Roassal (the graphical engine of Pharo, note that it could be any other packages or classes) this code is distributed in several classes and packages (as shown Figure X-1), which is ideal to show all the potential of DrTest.
![[figure1_classtotestroassal.png]]
### Step 1: Open DrTest
To open DrTest you can select `Browse > DrTest` in the toolbar (as shown in Figure X-2) or just press `Ctrl`+`O`+`U` (`Command`+`O`+`U` for Mac users)
![[figure2_wheretofind.png]]

Once you access the drTest interface, you can navigate to the first drop-down component to explore and select various plugins according to your needs. 

You will encounter... (previous paragraph)  three principal panels. In the first two panels,according to every plugin, you can select packages, classes, or test classes, providing a granular level of control over the scope of your analysis. Once you've made your selections, the third panel will display the results after clicking the "Run Tests" button. 


This intuitive design allows you to precisely target specific elements in your Pharo project, facilitating a focused analysis of tests.

### Using DrTest plugins
Plugins (description)

For each plugin:
- What does it do?
- How to use it? (example)
- Key functionalities (Cool things)

#### Tests Runner
#### Test Coverage
The DrTest coverage plugin provides a report that
shows which statements have been covered (or not) of the classes under analysis. 

// doubt: will be okey to mention the type of selection in the panels?

Upon entering the drTest interface, within the first two panels of the drTest interface, you have the option to select "Test Packages" and "Packages under coverage." This feature enables you to assess the coverage of your test packages within the specific packages you have chosen. 

The following image shows an example of the coverage report that DrTest coverage plugin provides. ..... (copy of my proposal gsoc)

#### Tests Profiler
#### Rotten green tests finder
#### Executable comments checker
#### Mutation plugin (?)
- Installing and configuring plugins



## Creating Custom DrTest Plugins
- Understanding the plugin architecture in DrTest.
    An architecture to build tools around tests
- Guide of the development
- Creating a basic plugin from scratch
- Implementing plugin functionality
- Testing and debugging plugins

### Sharing and Distributing Plugins
- Packaging plugins for distribution
- Publishing plugins on the Pharo ecosystem
- Collaborating with other developers on plugin development


Best Practices for Plugin Development (reference another book or chapter) (or just mention)
- Writing clean and maintainable plugin code
- Testing and documenting plugins
- Handling plugin dependencies and conflicts
- Upgrading and maintaining plugins


### Customizing plugin behavior (???)
- You can modify
- How to modify an existing plugin?

## Conclusion
- Recap of key concepts covered in the chapter
- Encouragement to explore and experiment with plugins in DrTest

In summary, drTest is a valuable tool for Pharo developers looking to improve the quality of their testing. With its modular approach and intuitive user interface, it provides an effective solution to get quick feedback and continuously improve your testing practices.

Explore drTest and take your testing to the next level in Pharo!