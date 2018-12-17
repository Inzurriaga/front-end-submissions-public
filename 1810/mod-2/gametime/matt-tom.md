# Game Time
* Students: Matt & Tom
* Evaluator: Brittany


### Functional Expectations

* 2 - Application has some missing functionality but no crashes

* Changes make it so that we can only immediately play the bonus round and not fully through the entire game

### User Interface

* 3 - The application has many strong pages/interactions, but a few holes in lesser-used functionality.

* The user flow/interactions are easy to follow which is most important. I would clean up the design a bit by making it a little less busy -- less textures and patterns and differentiate on the colors a bit. Margins & paddings can be cleaned up as well but these are all easy fixes that don't necessarily take away from the intuitiveness of the app.

### Testing

* 4 - Project has a running test suite that exercises the application at multiple levels. The test suite covers almost all aspects of the application and uses mocks and stubs when appropriate. ESLint shows 0 complaints.
* 3 - Project has a running test suite that tests multiple levels but fails to cover some features. All functionality is covered by tests. The application makes some use of integration testing. ESLint shows < 5 complaints.
* 2 - Project has sporadic use of tests at multiple levels. The application contains numerous holes in testing and/or many features are untested. ESLint shows 5+ complaints.
* 1 - There is little or no evidence of testing in this application. ESLint shows 10+ complaints.

### JavaScript Style & OOP

* 4 - Application has exceptionally well-factored code with little or no duplication. SRP (single responsibility principle) and DRY (don’t repeat yourself) principles are utilized. There are zero instances where an instructor would recommend taking a different approach. Application is organized into classes (and correctly uses inheritance) and there are no instances where instructor would suggest moving logic or data to another class. The business-logic code driving functionality is cleanly separated from rendering, view-related code.
* 3 - Application is thoughtfully put together with some duplication and no major bugs. Developer can speak to choices made in the code and knows what every line of code is doing. Application is organized into classes (and correctly uses inheritance) with some misplaced logic and no major bugs. Business-logic code is mostly separated from view-related code. Developer can speak to choices made in the code and knows what each line of code is doing.
* 2 - Your application has a significant amount of duplication and one or more major bugs. Application is organized into classes that do not display a good understanding of encapsulation, and logic is not well-divided. Developer cannot articulate what each line of code is doing. There are one or more major bugs.
* 1 - Your client-side application does not function. Developer writes code with unnecessary variables, operations, or steps that do not increase clarity. Application is not separated into classes, or methods and properties are illogically assigned to classes. Developer writes code with unnecessary variables, operations, or steps that do not increase clarity. Business-side logic and view-related code is not separated at all.


### Workflow

* 3 - The developer/team makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base. The team conducts a DTR (define the relationship) and utilizes a planning tool and pairing practices. Both members contribute meaningfully to the application.

* Git commit messages are a bit vague and often inconsistent style-wise (e.g you should be writing things like 'Add feature x' not just 'feature added.')
* I'd like to see commits like [this](https://github.com/foxwellm/Jeopardy/commit/5a6ff6fc05f4184de071c2d7abb8c85894f80aa2) be a bit smaller. It looks like the code changes in here are mostly all relevant, but try to find ways to break up this functionality into multiple commits -- maybe the first commit is just creating the DailyDouble class, but it's not being utilized anywhere. The second commit could be stubbing out the properties and methods it might have. The third commit could be instantiating a new one that doesn't actually do anything just yet. Fourth one could be adding the fully integrated functionality.