# Homework1: No Silver Bullet reading report
***
### Name: Xiaolan Cai



- Define the term essential difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty.

    Brooks defines the essential difficulties as the difficulties inherent in the nature of software. 
    
    He thinks the essence of a software entity is a construct of interlocking concepts: data sets, relationships among data items, algorithms, and invocations of functions. This essence is abstract in that such a conceptual construct is the same under many different representations. It is nonetheless highly precise and richly detailed. Brooks believes the hard part of building software to be the specification, design, and testing of this conceptual construct, not the labor of representing it and testing the fidelity of the representation. The syntax errors are fuzz compared with the conceptual errors in most systems. If this is true, building software will always be hard and inherently no silver bullet to solve. 
    
    For example,  complexity is one of the essential difficulties. One example is complex property of software comes with the difficulty of communication among team members, which leads to product flaws, cost overruns, schedule delays.

***

- Define the term accidental difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty. 

    Brooks defined the accidental difficulties as those difficulties that today attend its production but are not inherent.  Brooks argues that if we examine the three steps in software technology development that have been most fruitful in the past, we discover that each attacked a different major difficulty in building software, but that those difficulties have been accidental, not essential, difficulties.
    
    For example, the slow turnaround is an accidental rather than an essential difficulty of the software process. The slow turnaround of batch programming means that one inevitably forgets the minutiae, if not the very thrust, of what one was thinking when he stopped programming and called for compilation and execution. This interruption is costly in time, for one must refresh one's memory. The most serious effect may well be the decay of the grasp of all that is going on in a complex system. 

***
- List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.

    The four essential difficulties of developing software systems are:
    
    Complexity:
    
    The fact that digital computers have very large numbers of states. This makes conceiving, describing, and testing them hard. Software systems have orders-of- magnitude more states than computers do. have very large numbers of states. This makes conceiving, describing, and testing them hard. Software systems have orders-of- magnitude more states than computers do.
    
    Example: from the complexity comes the difficulty of enumerating, much less understanding, all the possible states of the program, and from that comes the unreliability.
    
    Conformity:
    
    The fact that much of the complexity that must master is arbitrary complexity, forced without rhyme or reason by the many human institutions and systems to which the interfaces must conform. These differ from interface to interface, and from time to time, not because of necessity but only because they were designed by different people, rather than by God.
    
    Example: in many cases, the software must conform because it is the most recent arrival on the scene.
    
    Changeability:
    
    The fact that the software entity is constantly subject to pressures for change. In short, the software product is embedded in a cultural matrix of applications, users, laws, and machine vehicles. These all change continually, and their changes inexorably force change upon the software product.
    
    Example: successful software survives beyond the normal life of the machine vehicle for which it is first written. If not new computers, then at least new disks, new displays, new printers come along; and the software must be conformed to its new vehicles of opportunity.

    
    Invisibility:
    
    Software is invisible and unvisualizable. Hence, it has no ready geometric representation in the way that land has maps, silicon chips have diagrams, computers have connectivity schematics.
    
    Example: The several graphs may represent the flow of control, the flow of data, patterns of dependency, time sequence, name-space relationships. These graphs are usually not even planar, much less hierarchical.


***
- Define what Brooks means by a silver bullet and reconstruct his argument as to why he believes there is no silver bullet for software engineering.

    What Brooks means by a silver bullet is something to make software costs drop as rapidly as computer hardware costs do and a single development, in either technology or in management technique, that by itself promises improvement in productivity, in reliability, in simplicity.
    
   Brooks thinks that the nature and essential difficulties of software makes it unlikely to be any inventions that can improve  software productivity, reliability, and simplicity. He has discussed from several aspects that are most often considerd as silver bullet and argue that these technical development will not turn into silver bullet as people expect. 
   
   For example, he predicts that Ada and other high-level language advances's greatest contribution will be that switching to it occasioned training programmers in modern software-design techniques because it is after all, just another high-level language, and the biggest payoff from such languages came from the first transition.
   
   He doesn't think Object-oriented programming advances would do more than to remove all the accidental difficulties from the expression of the design. The complexity of the design itself is essential, and such attacks make no change whatever in that.
   
   And while many people expect Artificial intelligence to provide the revolutionary breakthrough that will give order-of-magnitude gains in software productivity and quality, he thinks he hard time seeing how image recognition, for example, will make any appreciable difference in programming practiceThe same problem is true of speech recognition and the hard thing about building software is deciding what one wants to say, not saying it. No facilitation of expression can give more than marginal gains.
   
   He also argues that Expert systems is the most advanced part of AI, so there are many difficulties stand in the way of the early realization of useful expert-system advisors to the program developer. A crucial part of our imaginary scenario is the development of easy ways to get from program-structure specification to the automatic or semiautomatic generation of diagnostic rules.
   
   For Automatic programming, he explains it is hard to see how such techniques generalize to the wider world of the ordinary software system, where cases with such neat properties are the exception. It is hard even to imagine how this breakthrough in generalization could occur.
   
   For Graphical programming, he argues that first, flowchart is a very poor abstraction of software structure. Second,the screens of today are too small, in pixels, to show both the scope and the resolution of any seriously detailed software diagram. More importantly, he thinks that software is very difficult to visualize.
   
   He also doesn't think Program verification would be a silver bullet because the technology does not promise, however, to save labor. Verifications are so much work that only a few substantial programs have ever been verified.
   
   For Environments and tools, he thinks this work is worthwhile, and surely it will bear some fruit in both productivity and reliability. But by its very nature, the return from now on must be marginal.
   
   For Workstations, Brooks thinks the composition and editing of programs and documents is fully supported by today's speeds. Compiling could stand a boost, but a factor of 10 in machine speed would surely leave thinktime the dominant activity in the programmer's day.
          
***
- In lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.

    
    chemist is discovering and identifying the principle of chemistry as a science and chemical engineering is to apply the principle and figure out how to deploye to scientific principle with proper technology to fit the reality and benifit more people. 
    
    Similarly, Computer science is the study of the principle of computing as a science and what's possible in computer science and what isn't in various areas such as theory of computing, programming languages, systems etc. And software engineers have to take that set of scientific priciple and techniques, taking it into production and continuingly diliver to customers.


***
- In lecture, we discussed the importance of the following concepts to software engineers: abstractions, conversations, specification, translation, and iteration. Define each of these concepts as they are related to software engineering and discuss their importance.

    abstraction is the key to the analysis of software-based systems. The file system, an API, a database, are all abstraction. It is important because software engineers solve problems by developing abstractions that break the problem down into something that is understandable and/or by using abstractions developed by others.
    
    conversation is the communication between the user and domain expert, between the developers and/or the document, etc. It is important because it is the key to emphasize the point and the way to understand what abstraction we should write and if our abstraction is working or not.
    
    specification includes requirements, design, code, test plans, and development life cycles of software engineering. It is important because 
    
    translation: the work of software engineering that is one of translation, from one specification to another; from one level of abstraction to another; from one set of structures to another (e.g. problem/design decomposition).
    
    iteration: the work of software engineering that is done iteratively; step by step until we are “done”. Iteration is important because we should learn from the mistakes or lessones from previuos steps and evovle the process and be better step by step. 
    
    
References:

1. No Silver Bullet: Essence and Accidents of Software Engineering,Frederick P. Brooks, Jr.
2. Slides of Foundation of Software Engineering Lecture 1 
    


