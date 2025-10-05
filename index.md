***

# Good Coding Practice for Scientists

Sanjay Manohar
MA MB BChir PhD MRCP MBPsS AFHEA MAcadMEd
Oxford Biology Primer Series, Tools and Techniques

## Contents
# [1. Chapter 1: Introduction](chapter_01.html)
  * [1.1. Aims of this book](chapter_01.html#aims-of-this-book)
  * [1.2. What makes coding so powerful?](chapter_01.html#what-makes-coding-so-powerful)
  * [1.3. Classifying programming languages](chapter_01.html#classifying-programming-languages)
    - [Functional vs Imperative](chapter_01.html#functional-vs-imperative)
    - [Strongly-typed vs. weakly-typed languages](chapter_01.html#strongly-typed-vs-weakly-typed-languages)
    - [Interpreted vs Compiled languages](chapter_01.html#interpreted-vs-compiled-languages)
    - [High-level vs Low-level languages](chapter_01.html#high-level-vs-low-level-languages)
    - [General-purpose vs Domain-specific languages (DSLs)](chapter_01.html#general-purpose-vs-domain-specific-languages-dsls)
    - [Zero vs one-based indexing](chapter_01.html#zero-vs-one-based-indexing)
  * [1.4. What language to choose](chapter_01.html#what-language-to-choose)
  * [Chapter summary](chapter_01.html#chapter-summary)

# [2. Chapter 2: Best Practices](chapter_02.html)
  * [2.1. What is Good Coding Practice?](chapter_02.html#what-is-good-coding-practice)
  * [2.2. Why should I bother to write good code?](chapter_02.html#why-should-i-bother-to-write-good-code)
    - [Software carpentry](chapter_02.html#software-carpentry)
  * [2.3. Open Code, Licenses and Publishing Code](chapter_02.html#open-code-licenses-and-publishing-code)
  * [2.4. Version control](chapter_02.html#version-control)
    - [Diff](chapter_02.html#diff)
  * [2.5. Publishing Code](chapter_02.html#publishing-code)
    - [Code security](chapter_02.html#code-security)
  * [2.6. The Software Development Process](chapter_02.html#the-software-development-process)
  * [Chapter summary](chapter_02.html#chapter-summary)

# [3. Chapter 3: Preparing to code](chapter_03.html)
  * [3.1. Are you sitting comfortably?](chapter_03.html#are-you-sitting-comfortably)
    - [Adjust your seat](chapter_03.html#adjust-your-seat)
    - [Keyboard and mouse](chapter_03.html#keyboard-and-mouse)
    - [Screen position and visibility](chapter_03.html#screen-position-and-visibility)
    - [Posture](chapter_03.html#posture)
  * [3.2. Your coding environment](chapter_03.html#your-coding-environment)
    - [Using an IDE](chapter_03.html#using-an-ide)
    - [Fonts](chapter_03.html#fonts)
    - [Monospaced fonts](chapter_03.html#monospaced-fonts)
    - [Font size](chapter_03.html#font-size)
    - [Hazards of IDEs](chapter_03.html#hazards-of-ides)
    - [Know where to find help](chapter_03.html#know-where-to-find-help)
  * [3.3. The Neuroscience of Legibility](chapter_03.html#the-neuroscience-of-legibility)
    - [Screen orientation](chapter_03.html#screen-orientation)
    - [Spacing](chapter_03.html#spacing)
    - [Crowding](chapter_03.html#crowding)
    - [Tidy code = Tidy mind](chapter_03.html#tidy-code--tidy-mind)
    - [Black on white, or white on black?](chapter_03.html#black-on-white-or-white-on-black)
    - [Syntax highlighting](chapter_03.html#syntax-highlighting)
    - [Organise your files](chapter_03.html#organise-your-files)
    - [Keeping files in a sensible order](chapter_03.html#keeping-files-in-a-sensible-order)
    - [Theory of mind](chapter_03.html#theory-of-mind)
  * [Chapter Summary](chapter_03.html#chapter-summary)

# [4. Chapter 4: Comments](chapter_04.html)
  * [4.1. Anatomy of a comment](chapter_04.html#anatomy-of-a-comment)
  * [4.2. Commenting a variable declaration](chapter_04.html#commenting-a-variable-declaration)
  * [4.3. Commenting a function](chapter_04.html#commenting-a-function)
    - [Function inputs](chapter_04.html#function-inputs)
    - [Function Outputs](chapter_04.html#function-outputs)
    - [Error conditions](chapter_04.html#error-conditions)
    - [Header](chapter_04.html#header)
    - [Functions that take functions](chapter_04.html#functions-that-take-functions)
  * [4.4. Iffing out](chapter_04.html#iffing-out)
  * [Chapter Summary](chapter_04.html#chapter-summary)

# [5. Chapter 5: Choosing a nice name](chapter_05.html)
  * [5.1. Naming conventions](chapter_05.html#naming-conventions)
    - [Avoid spaces and minus signs in file names](chapter_05.html#avoid-spaces-and-minus-signs-in-file-names)
    - [Naming functions](chapter_05.html#naming-functions)
  * [5.2. Names are greedy (Huffman coding)](chapter_05.html#names-are-greedy-huffman-coding)
  * [5.3. Long and short names](chapter_05.html#long-and-short-names)
    - [The Readability-Writeability trade-off](chapter_05.html#the-readability-writeability-trade-off)
  * [5.4. Variable types](chapter_05.html#variable-types)
    - [Naming booleans](chapter_05.html#naming-booleans)
    - [Naming arrays](chapter_05.html#naming-arrays)
  * [5.5. Enumerations](chapter_05.html#enumerations)
  * [Chapter summary](chapter_05.html#chapter-summary)

# [6. Chapter 6: Conceptualisation](chapter_06.html)
  * [6.1. Spotting conceptual errors](chapter_06.html#spotting-conceptual-errors)
    - [Your code contains "clear"](chapter_06.html#your-code-contains-clear)
    - [You use global variables](chapter_06.html#you-use-global-variables)
    - [You use an "eval" statement](chapter_06.html#you-use-an-eval-statement)
    - [Your variable names contain numbers](chapter_06.html#your-variable-names-contain-numbers)
    - [You needed to copy and paste code](chapter_06.html#you-needed-to-copy-and-paste-code)
    - [Your functions have a lot of parameters](chapter_06.html#your-functions-have-a-lot-of-parameters)
    - [You don't cover all the cases](chapter_06.html#you-dont-cover-all-the-cases)
  * [6.2. Abstract vs. Explicit code](chapter_06.html#abstract-vs-explicit-code)
    - [Spotting similarities](chapter_06.html#spotting-similarities)
    - [Pseudocode: transcending language](chapter_06.html#pseudocode-transcending-language)
  * [6.3. Externalisation](chapter_06.html#externalisation)
    - [Numeric constants](chapter_06.html#numeric-constants)
    - [String constants](chapter_06.html#string-constants)
    - [Benefits of externalisation](chapter_06.html#benefits-of-externalisation)
  * [6.4. Spotting algorithmic similarity](chapter_06.html#spotting-algorithmic-similarity)
  * [Chapter Summary](chapter_06.html#chapter-summary)

# [7. Chapter 7: Functions](chapter_07.html)
  * [7.1. Why bother using functions?](chapter_07.html#why-bother-using-functions)
    - [When to functionise?](chapter_07.html#when-to-functionise)
    - [When not to functionise?](chapter_07.html#when-not-to-functionise)
  * [7.2. The Doctrine of Referential Transparency](chapter_07.html#the-doctrine-of-referential-transparency)
    - [Violation of referential transparency](chapter_07.html#violation-of-referential-transparency)
    - [Never change directory in a function](chapter_07.html#never-change-directory-in-a-function)
    - [Writing a function is signing a contract](chapter_07.html#writing-a-function-is-signing-a-contract)
  * [7.3. Namespaces and pollution](chapter_07.html#namespaces-and-pollution)
    - [The global workspace: Emergency use only!](chapter_07.html#the-global-workspace-emergency-use-only)
    - [Creating namespaces to avoid pollution](chapter_07.html#creating-namespaces-to-avoid-pollution)
    - [Caution when loading variables from a file](chapter_07.html#caution-when-loading-variables-from-a-file)
  * [7.4. Stack frames](chapter_07.html#stack-frames)
    - [Stack frames help to isolate tasks](chapter_07.html#stack-frames-help-to-isolate-tasks)
    - [What are stack frames?](chapter_07.html#what-are-stack-frames)
    - [Nested scopes and closures [Advanced Topic]](chapter_07.html#nested-scopes-and-closures-advanced-topic)
    - [Function arguments from lists](chapter_07.html#function-arguments-from-lists)
  * [7.5. Debugging with a stack](chapter_07.html#debugging-with-a-stack)
    - [If you can't use the debugger](chapter_07.html#if-you-cant-use-the-debugger)
  * [7.6. Returning values](chapter_07.html#returning-values)
  * [7.7. Building an Application Programming Interface](chapter_07.html#building-an-application-programming-interface)
    - [Why hide implementation? Isn't code supposed to be open?](chapter_07.html#why-hide-implementation-isnt-code-supposed-to-be-open)
  * [7.8. Refactoring](chapter_07.html#refactoring)
    - [Functions and versions](chapter_07.html#functions-and-versions)
    - [Introducing parameters](chapter_07.html#introducing-parameters)
  * [7.9. Ordering code](chapter_07.html#ordering-code)
  * [Chapter summary](chapter_07.html#chapter-summary)

# [8. Chapter 8: Data](chapter_08.html)
  * [8.1. What is data?](chapter_08.html#what-is-data)
    - [How to separate code from data?](chapter_08.html#how-to-separate-code-from-data)
  * [8.2. How do computers see numbers?](chapter_08.html#how-do-computers-see-numbers)
    - [Integers](chapter_08.html#integers)
    - [Double precision formats](chapter_08.html#double-precision-formats)
    - [Infinity and beyond](chapter_08.html#infinity-and-beyond)
    - [NaN and her family](chapter_08.html#nan-and-her-family)
    - [Null and Void (Advanced Topic)](chapter_08.html#null-and-void-advanced-topic)
    - [How precise are my numbers](chapter_08.html#how-precise-are-my-numbers)
    - [Complex numbers [Advanced topic]](chapter_08.html#complex-numbers-advanced-topic)
  * [8.3. Natural representations of quantities](chapter_08.html#natural-representations-of-quantities)
  * [8.4. Graphical output](chapter_08.html#graphical-output)
  * [8.5. Structures, Fields and Reflection](chapter_08.html#structures-fields-and-reflection)
    - [Dictionaries and dynamic fields](chapter_08.html#dictionaries-and-dynamic-fields)
    - [Overusing structures](chapter_08.html#overusing-structures)
    - [Passing by value](chapter_08.html#passing-by-value)
    - [Looping over variables](chapter_08.html#looping-over-variables)
  * [8.6. Should I use Long or Short (wide) Form?](chapter_08.html#should-i-use-long-or-short-wide-form)
    - [Converting to long form](chapter_08.html#converting-to-long-form)
    - [Converting to short form](chapter_08.html#converting-to-short-form)
  * [8.7. Recursion [advanced topic]](chapter_08.html#recursion-advanced-topic)

# [9. Chapter 9: Efficiency](chapter_09.html)
  * [9.1. Making code run faster](chapter_09.html#making-code-run-faster)
    - [Check for duplication](chapter_09.html#check-for-duplication)
    - [Remove any graphical or text output](chapter_09.html#remove-any-graphical-or-text-output)
    - [Discard intermediates](chapter_09.html#discard-intermediates)
    - [Preallocate memory for arrays](chapter_09.html#preallocate-memory-for-arrays)
    - [Vectorisation](chapter_09.html#vectorisation)
    - [Harness built-ins](chapter_09.html#harness-built-ins)
    - [Boolean indexing](chapter_09.html#boolean-indexing)
    - [Parallelise for loops](chapter_09.html#parallelise-for-loops)
    - [Harness a GPU (Graphics processing unit)](chapter_09.html#harness-a-gpu-graphics-processing-unit)
    - [Run a Profiler](chapter_09.html#run-a-profiler)
    - [Consider sparse arrays](chapter_09.html#consider-sparse-arrays)
    - [Operate on small data chunks](chapter_09.html#operate-on-small-data-chunks)
  * [9.2. Vectorisation](chapter_09.html#vectorisation)
    - [Matrix multiplication](chapter_09.html#matrix-multiplication)
    - [Boolean masking](chapter_09.html#boolean-masking)
    - [Singleton Expansion ('Broadcasting')](chapter_09.html#singleton-expansion-broadcasting)
    - [Applying functions to arrays: Mappings](chapter_09.html#applying-functions-to-arrays-mappings)
  * [9.3. Lambda functions](chapter_09.html#lambda-functions)
  * [9.4. Object-oriented programming](chapter_09.html#object-oriented-programming)
  * [9.5. Event-driven programming](chapter_09.html#event-driven-programming)
  * [9.6. User interfaces](chapter_09.html#user-interfaces)
    - [How to build a UI](chapter_09.html#how-to-build-a-ui)
    - [Is a UI really needed?](chapter_09.html#is-a-ui-really-needed)
    - [Making a long operation more friendly](chapter_09.html#making-a-long-operation-more-friendly)

# [10. Chapter 10: Errors](chapter_10.html)
  * [10.1. When Errors are a Good Thing!](chapter_10.html#when-errors-are-a-good-thing)
  * [10.2. Anatomy of an Error](chapter_10.html#anatomy-of-an-error)
    - [Understanding error messages](chapter_10.html#understanding-error-messages)
    - [The Stack trace](chapter_10.html#the-stack-trace)
    - [What if no error is thrown](chapter_10.html#what-if-no-error-is-thrown)
    - [Assertion](chapter_10.html#assertion)
    - [Generate warnings](chapter_10.html#generate-warnings)
  * [10.3. Error handlers](chapter_10.html#error-handlers)
    - [Throwing and catching](chapter_10.html#throwing-and-catching)
    - [Case study](chapter_10.html#case-study)
  * [10.4. The short, self-contained code example (SSCE)](chapter_10.html#the-short-self-contained-code-example-ssce)
  * [10.5. Spotting some obvious errors](chapter_10.html#spotting-some-obvious-errors)
  * [10.6. Code review](chapter_10.html#code-review)
  * [10.7. Heed the developer tools](chapter_10.html#heed-the-developer-tools)
    - [Heed the Warnings!](chapter_10.html#heed-the-warnings)
    - [Heed the Lint!](chapter_10.html#heed-the-lint)
  * [10.8. Strong and Weak Typing](chapter_10.html#strong-and-weak-typing)
    - [Numerical casting](chapter_10.html#numerical-casting)
    - [Boolean casting](chapter_10.html#boolean-casting)
  * [10.9. Provability](chapter_10.html#provability)
  * [10.10. Testing](chapter_10.html#testing)
    - [Creating test data – How to run a simulation](chapter_10.html#creating-test-data--how-to-run-a-simulation)
    - [Unit Tests](chapter_10.html#unit-tests)
  * [Chapter Summary](chapter_10.html#chapter-summary)

# [Reference](reference.html)

# [Glossary](glossary.html)

# [Commonly confused terms](glossary.html#commonly-confused-terms)

# [Index](index.html)

# [References](references.html)

# [About the author](about.html)





***

[Commonly confused terms 134](#commonly-confused-terms)

***

[Index 137](#index)

***

[References 137](#references)

***

[About the author 138](#about-the-author)

***

## Acknowledgements

This book would not have been possible without all my students, who inspired me through their perseverance in the face of mistakes. Nor would it have been possible without my parents, who had the foresight to buy me a computer and gave me the motivation to learn. Many people contributed to this book by reading and commenting, including my brother Sunil who is also a doctor-programmer, Steve Stretton the physicist-philosopher, Mark Jenkinson who is head of neuroimaging at Oxford, Marc Thomas, Shoaib Sufi, Community Lead of the Software Sustainability Institute, Martin Frasch, Andrea Bocincova, Ash Oswal and Jeremy James. Additionally I would like to thank six anonymous reviewers for their time and detailed criticism. All these people contributed insights, perspectives, and anecdotes that are woven into the book.

## About the author

Sanjay Manohar has 35 years of coding experience in C, Java, Python, Bash, Matlab, Javascript, and Basic. By career, he is an Associate Professor in Neuroscience and a Consultant Neurologist at the University of Oxford. He is a fellow of the Software Sustainability Institute, an RCUK-funded body aiming to improve software in academia. Sanjay has taught courses in Good Coding Practices for 7 years, at UCL and Oxford. He is a passionate teacher, an Associate Fellow of the Higher Education Academy, and a Member of the Academy of Medical Educators.