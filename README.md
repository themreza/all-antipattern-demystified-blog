# All antipatterns demystified     

I deleted duplicates and categorize them again with alternative name.   
may be some of them be in [Code smells]() but don't worry we investigate them later.      
_______
## Architect anti-patterns.     
1::::Bikeshedding (Death by Planning): wasting your time with non-important debate or sessions (Giving disproportionate weight to trivial 
issues).     
2::::Fear of adding class : you can't seprate or extract concerns in new files.     

3::::Management by Numbers (Management by objectives): relience on numbers, rather more solution or result.     

4::::Useless class (Poltergeists): using OOP too where it can be handled by a function.     

_______
## Organizational anti-patterns.     

5::::Analysis paralysis: Devoting disproportionate effort to the analysis phase of a project.     

6::::Cash cow: A profitable legacy product that often leads to complacency about new products.     

7::::Bleeding edge(The Shiny Toy ): Operating with cutting-edge technologies that are still untested or unstable leading to cost overruns, 
under-performance or delayed delivery.     
8::::**Peter principle**: Continually promoting otherwise well-performing employees up to their level of incompetence, where they remain 
indefinitely.     
9::::Design by committee: The result of having many contributors to a design, but no unifying vision.     

10::::**Escalation of commitment**: Failing to revoke a decision when it proves wrong.     

11::::**Management by perkele**: Authoritarian style of management with no tolerance of dissent(iranian bosses).     

12::::Matrix Management: Unfocused organizational structure that results in divided loyalties and lack of direction.     

13::::Micromanagement: Ineffectiveness from excessive observation, supervision, or other hands-on involvement from management.     

14::::Moral hazard: Insulating a decision-maker from the consequences of his or her decision.     

15::::Seagull management: Management in which managers only interact with employees when a problem arises, when they "fly in, make a lot of 
noise, dump on everyone, do not solve the problem, then fly out".     
16::::Mushroom management: Keeping employees uninformed and misinformed (kept in the dark and fed manure).     

17::::Stovepipe or Silos: A structure that supports mostly up-down flow of data but inhibits cross organizational communication.     

18::::Vendor lock-in: Making a system excessively dependent on an externally supplied component.     

19::::**Typecasting**: Locking successful employees into overly safe, narrowly defined, predictable roles based on their past successes rather 
than their potential.     
_______
## Project management anti-patterns.     
20:::: Walking Through a Minefield:When software is released before it is ready,

21::::The Fast Beats Right:  alleges that it is always better to just get something done, Fast_Beats_Right_Dec_2014regardless of quality, than 
to invest any effort into doing the job right.    
22::::Cart before the horse: Focusing too many resources on a stage of a project out of its sequence.     

23::::Death march: Everyone knows that the project is going to be a disaster – except the CEO. However, the truth remains hidden and the 
project is artificially kept alive until the Day Zero finally comes ("Big Bang"). Alternative definition: Employees are pressured to work late nights and weekends on a project with an unreasonable deadline..     
24::::Groupthink: During groupthink, members of the group avoid promoting viewpoints outside the comfort zone of consensus thinking.     

25::::Smoke and mirrors: Demonstrating how unimplemented functions will appear.     

26::::**Ninety-ninety rule**: Tendency to underestimate the amount of time to complete a project when it is "nearly done".     

27::::Software bloat: Allowing successive versions of a system to demand ever more resources.     

28::::Waterfall model: An older method of software development that inadequately deals with unanticipated change.     

29::::**Overengineering**: Spending resources making a project more robust and complex than is needed.     

30::::**Scope creep**(Feature Creep): Uncontrolled changes or continuous growth in a project's scope, or adding new features to the project 
after the original requirements have been drafted and accepted (also known as requirement creep and feature creep).     
31::::**Brooks's law**: Adding more resources to a project to increase velocity, when the project is already slowed by coordination 
overhead.     
_______
## Analysis anti-patterns

32::::Bystander apathy: When a requirement or design decision is wrong, but the people who notice this do nothing because it affects a larger 
number of people or The phenomenon in which people are less likely to or do not offer help to a person in need when others are present.     
_______
## Software design anti-patterns.    
33:::: Waterfail(waterfall):Waterfall, or Waterfail, is a rigid software development life cycle methodology that moves all activity through a 
series of stages, such as Gather Requirements, Design, Develop, Test, Deliver, Maintain.    
34:::: The Flags Over Objects anti-pattern occurs when behavior is written outside of an object by inspecting flags (such as status codes), 
rather than within the object itself. This violates the Tell, Don’t Ask principle.     

35::::**Abstraction inversion**: Not exposing implemented functionality required by users, so that they re-implement it using higher level 
functions.     

36::::Copy Folder Versioning:  a software development anti-pattern in which source code is updated by simply making copies of the folder.    

37::::Ambiguous viewpoint: Presenting a model (usually Object-oriented analysis and design (OOAD)) without specifying its viewpoint.there are 
three viewpoints: **The business viewpoint** (the information that is domain specific and matters to the end user), the **specification viewpoint** (which defines the exposed interface elements of a class), and the **implementation viewpoint** (which deals with the actual internal implementation of the class).      

38::::Big ball of mud: A system with no recognizable structure.     

39::::**Database-as-IPC**: Using a database as the message queue for routine interprocess communication where a much more lightweight 
mechanism would be suitable.   

40::::Gold plating: Continuing to work on a task or project well past the point at which extra effort is adding value.     

41::::**Inner-platform effect**: A system so customizable as to become a poor replica of the software development platform(Greenspun's tenth 
rule).     

42::::**Input kludge**: Failing to specify and implement the handling of possibly invalid input(lack of validator).     

43::::Interface bloat: Making an interface so powerful that it is extremely difficult to implement.     

44::::Magic pushbutton: Coding implementation logic directly within interface code(submit button in form), without using abstraction.     

45::::Race hazard: Failing to see the consequence of different orders of events.     

46::::Stovepipe system: A barely maintainable assemblage of ill-related components.     

47:::: Frankencode : refers to code that was never designed to work together, being pulled into a single application and held together with 
duct tape, baling wire, and maybe some Adapter design pattern usage.(like Stovepipe)    

48:::: The Duct Tape Coder:  is someone who is able to cobble together software that solves the immediate problem, but without any concern for 
the code’s quality or maintainability.

49:::: straw man :“architecture astronaut” who spends endless amounts of time on design but never actually delivers any software.    

_______
## Object-oriented design anti-patterns.     
50::::Iceberg Class: you encapsulate tooooo much

51::::Anemic Domain Model: The use of domain model without any business logic. The domain model's objects cannot guarantee their correctness 
at any moment, because their validation and mutation logic is placed somewhere outside (most likely in multiple places).     
52::::**BaseBean**: Inheriting functionality from a utility class rather than delegating to it.     

53::::Call super: Requiring subclasses to call a superclass's overridden method.     

54::::Circle-ellipse problem(Square–rectangle problem)(Person prisoner): Subtyping variable-types on the basis of value-subtypes.     

55::::Circular dependency: Introducing unnecessary direct or indirect mutual dependencies between objects or software modules.     

56::::Constant interface: Using interfaces to define constants.     

57::::God object(the blob): Concentrating too many functions in a single part of the design (class).     

58::::**Object cesspool**: Reusing objects whose state does not conform to the (possibly implicit) contract for re-use.     

59::::**Object orgy**: Failing to properly encapsulate objects permitting unrestricted access to their internals.     

60::::Poltergeists: Objects whose sole purpose is to pass information to another object.     

61::::Sequential coupling: A class that requires its methods to be called in a particular order.     

62::::Yo-yo problem: A structure (e.g., of inheritance) that is hard to understand due to excessive fragmentation.     

63::::Hurry up and wait: One or more asynchronous events triggered in the constructor of an object.     

_______
## Programming anti-patterns.     
64::::Accidental complexity: Introducing unnecessary complexity into a solution.     

65::::Action at a distance: Unexpected interaction between widely separated parts of a system.     

66::::Blind faith: Lack of checking of (a) the correctness of a bug fix or (b) the result of a subroutine.     

67::::Boat anchor: Retaining a part of a system that no longer has any use.     

68::::Busy spin(waiting): Consuming CPU while waiting for something to happen, usually by repeated checking instead of messaging.     

69::::Caching failure: Forgetting to reset an error flag when an error has been corrected.     

70::::Broken Windows : Small problems, left uncorrected, signal a lack of care about the state of things.     

71::::**Cargo cult programming** (the Calendar Coder): Using patterns and methods without understanding why.     

72::::Coding by exception: Adding new code to handle each special case as it is recognized.     

73::::**Design pattern**: The use of patterns has itself been called an anti-pattern, a sign that a system is not employing enough 
abstraction.     

74::::Error hiding: Catching an error message before it can be shown to the user and either showing nothing or showing a meaningless 
message.     

75::::Hard code: Embedding assumptions about the environment of a system in its implementation.     

76::::Lava flow: Retaining undesirable (redundant or low-quality) code because removing it is too expensive or has unpredictable 
consequences.     

77::::Loop-switch sequence: Encoding a set of sequential steps using a switch within a loop statement.     

78::::Magic numbers: Including unexplained numbers in algorithms.     

79::::Magic strings: Including literal strings in code, for comparisons, as event types etc.

80::::Soft code: Storing business logic in configuration files rather than source code.     

81::::**Repeating yourself**: Writing code which contains repetitive patterns and substrings over again; avoid with once and only once 
(abstraction principle).     

82::::Spaghetti code: Programs whose structure is barely comprehensible, especially because of misuse of code structures.     

83::::Lasagna code: Programs whose structure consists of too many layers of inheritance.     

84::::**Shooting the messenger**: Throwing exceptions from the scope of a plugin or subscriber in response to legitimate input, especially 
when this causes the outer scope to fail.     

85::::Shotgun surgery: Developer adds features to an application codebase which span a multiplicity of implementors or implementations in a 
single change.     
_______
## Methodological anti-patterns.     

86::::Copy and paste programming(Found on Internet): Copying (and modifying) existing code rather than creating generic solutions.     

87::::**Every fool their own tool**: Failing to use proper software development principles when creating tools to facilitate the software 
development process itself.     

88::::Golden hammer: Assuming that a favorite solution is universally applicable (See: Silver Bullet).     

89::::Improbability factor: Assuming that it is improbable that a known error will occur.     

90::::Not Invented Here (NIH) syndrome: The tendency towards reinventing the wheel (Failing to adopt an existing, adequate solution).     

91::::**Invented here**: The tendency towards dismissing any innovation or less than trivial solution originating from inside the 
organization, usually because of lack of confidence in the staff.     
92::::Premature optimization: Coding early-on for perceived efficiency, sacrificing good design, maintainability, and sometimes even 
real-world efficiency.     

93::::Programming by permutation (or "programming by accident"): Trying to approach a solution by successively modifying the code to see if it 
works.     

94::::Reinventing the wheel: Failing to adopt an existing, adequate solution.     

95::::Reinventing the square wheel: Failing to adopt an existing solution and instead adopting a custom solution which performs much worse 
than the existing one.     

96::::Silver bullet: Assuming that a favorite technical solution can solve a larger process or problem.     

97::::Tester Driven Development: Software projects in which new requirements are specified in bug reports.     

98::::Assumption Driven Programming refers to the developer practice of assuming all users are like them. The best way to avoid falling into 
this trap is to interact with users as much as possible.    
_______
## Configuration management anti-patterns.     

99::::Dependency hell: Problems with versions of required products.     

100::::DLL hell: Inadequate management of dynamic-link libraries (DLLs), specifically on Microsoft Windows.     

101::::Extension conflict: Problems with different extensions to pre-Mac OS X versions of the Mac OS attempting to patch the same parts of the 
operating system.     

102::::JAR hell: Overutilization of the multiple JAR files, usually causing versioning and location problems because of misunderstanding of 
the Java class loading model.     


## links     
https://en.wikibooks.org/wiki/Introduction_to_Software_Engineering/Architecture/Anti-Patterns       
https://wiki.c2.com/?AntiPattern       
https://sourcemaking.com/antipatterns       
https://deviq.com/antipatterns/   
