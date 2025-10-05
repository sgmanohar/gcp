***

# Good Coding Practice for Scientists

Sanjay Manohar
MA MB BChir PhD MRCP MBPsS AFHEA MAcadMEd
Oxford Biology Primer Series, Tools and Techniques

## Contents
test



[Chapter 1: Introduction 9](#chapter-1-introduction)
[1.1. Aims of this book 9](#aims-of-this-book)
[1.2. What makes coding so powerful? 10](#what-makes-coding-so-powerful)
[1.3. Classifying programming languages 11](#what-language-to-choose)
[Functional vs Imperative: 11](#functional-vs-imperative)
[Strongly-typed vs. weakly-typed languages 12](#strongly-typed-vs-weakly-typed-languages)
[Interpreted vs Compiled languages 12](#interpreted-vs-compiled-languages)
[High-level vs Low-level languages 13](#high-level-vs-low-level-languages)
[General-purpose vs Domain-specific languages (DSLs) 13](#general-purpose-vs-domain-specific-languages-dsls)
[Zero vs one-based indexing 13](#zero-vs-one-based-indexing)
[1.4. What language to choose 14](#chapter-summary)
[Chapter summary 15](#_heading=h.lnxbz9)


[Chapter 2: Best Practices 15](#chapter-2-best-practices)


[2.1. What is Good Coding Practice? 15](#21-what-is-good-coding-practice)


[2.2. Why should I bother to write good code? 15](#22-why-should-i-bother-to-write-good-code)


[Software carpentry 16](#software-carpentry)


[2.3. Open Code, Licenses and Publishing Code 16](#23-version-control)

***

[2.4. Version control 17](#_heading=h.3j2qqm3)

***

[Diff 18](#diff)

***

[2.5. Publishing Code 19](#24-publishing-code)

***

[Code security 20](#code-security)

***

[2.6. The Software Development Process 21](#25-open-code-licenses-and-publishing-code)

***

[Chapter summary 21](#_heading=h.3whwml4)

***

[Chapter 3: Preparing to code 21](#chapter-3-preparing-to-code)

***

[3.1. Are you sitting comfortably? 22](#31-are-you-sitting-comfortably)

***

[Adjust your seat 22](#adjust-your-seat)

***

[Keyboard and mouse 22](#keyboard-and-mouse)

***

[Screen position and visibility 22](#screen-position-and-visibility)

***

[Posture 23](#posture)

***

[3.2. Your coding environment 23](#32-your-coding-environment)

***

[Using an IDE 23](#using-an-ide)

***

[Fonts 26](#fonts)

***

[Monospaced fonts 26](#monospaced-fonts)

***

[Font size 26](#font-size)

***

[Hazards of IDEs 26](#hazards-of-ides)

***

[Know where to find help 27](#know-where-to-find-help)

***

[3.3. The Neuroscience of Legibility 27](#33-the-neuroscience-of-legibility)

***

[Screen orientation 27](#screen-orientation)

***

[Spacing 29](#spacing)

***

[Crowding 30](#_heading=h.1v1yuxt)

***

[Tidy code = Tidy mind 31](#tidy-code--tidy-mind)

***

[Black on white, or white on black? 32](#black-on-white-or-white-on-black)

***

[Syntax highlighting 32](#syntax-highlighting)

***

[Organise your files 33](#organise-your-files)

***

[Keeping files a sensible order 33](#keeping-files-in-a-sensible-order)

***

[Theory of mind 34](#theory-of-mind)

***

[Chapter Summary 35](#chapter-summary-2)

***

[Chapter 4: Comments 35](#chapter-4-comments-and-documentation)

***

[4.1. Anatomy of a comment 35](#41-anatomy-of-a-comment)

***

[4.2. Commenting a variable declaration 37](#42-commenting-a-variable-declaration)

***

[4.3. Commenting a function 38](#43-commenting-a-function)

***

[Function inputs 38](#function-inputs)

***

[Function Outputs 39](#function-outputs)

***

[Error conditions 39](#error-conditions)

***

[Header 40](#header)

***

[Functions that take functions 40](#functions-that-take-functions)

***

[4.4. Iffing out 41](#44-iffing-out)

***

[Chapter Summary 41](#chapter-summary-3)

***

[Chapter 5: Choosing a nice name 42](#chapter-5-choosing-names)

***

[5.1. Naming conventions 42](#_heading=h.3cqmetx)

***

[Avoid spaces and minus signs in file names 43](#_heading=h.1rvwp1q)

***

[Naming functions 43](#naming-functions)

***

[5.2. Names are greedy (Huffman coding) 43](#52-names-are-greedy-huffman-coding)

***

[5.3. Long and short names 43](#53-long-and-short-names)

***

[The Readability-Writeability trade-off 45](#the-readability-writeability-trade-off)

***

[5.4. Variable types 45](#54-variable-types)

***

[Naming booleans 45](#naming-booleans)

***

[Naming arrays 45](#naming-arrays)

***

[5.5. Enumerations 46](#55-enumerations)

***

[Chapter summary 47](#chapter-summary-4)

***

[Chapter 6: Conceptualisation 47](#chapter-6-conceptualisation)

***

[6.1. Spotting conceptual errors 47](#61-abstract-vs-explicit-code)

***

[Your code contains “clear” 47](#your-code-contains-clear)

***

[You use global variables 48](#you-use-global-variables)

***

[You use an “eval” statement 48](#you-use-an-eval-statement-pythonmatlab)

***

[Your variable names contain numbers 49](#your-variable-names-contain-numbers)

***

[You needed to copy and paste code 50](#you-needed-to-copy-and-paste-code)

***

[Your functions have a lot of parameters 50](#_heading=h.3vac5uf)

***

[You don’t cover all the cases 50](#you-dont-cover-all-the-cases)

***

[6.2. Abstract](#63-externalisation) [*vs*](#63-externalisation)[. Explicit code 50](#63-externalisation)

***

[Spotting similarities 51](#spotting-similarities)

***

[Pseudocode: transcending language 53](#pseudocode-transcending-language)

***

[6.3. Externalisation 54](#_heading=h.48pi1tg)

***

[Numeric constants 54](#numeric-constants)

***

[String constants 55](#string-constants)

***

[Benefits of externalisation 55](#benefits-of-externalisation)

***

[6.4. Spotting algorithmic similarity 56](#64-spotting-algorithmic-similarity)

***

[Chapter Summary 57](#chapter-summary-5)

***

[Chapter 7: Functions 57](#chapter-7-functions)

***

[7.1. Why bother using functions? 57](#71-why-bother-using-functions)

***

[When to functionise? 58](#when-to-functionise)

***

[When not to functionise? 58](#when-not-to-functionise)

***

[7.2. The Doctrine of Referential Transparency 59](#72-the-doctrine-of-referential-transparency)

***

[Violation of referential transparency 59](#_heading=h.3ep43zb)

***

[Never change directory in a function 60](#never-change-directory-in-a-function)

***

[Writing a function is signing a contract 61](#writing-a-function-is-signing-a-contract)

***

[7.3. Namespaces and pollution 62](#73-namespaces-and-pollution)

***

[The global workspace: Emergency use only! 62](#the-global-workspace-emergency-use-only)

***

[Creating namespaces to avoid pollution 63](#creating-namespaces-to-avoid-pollution)

***

[Caution when loading variables from a file 64](#caution-when-loading-variables-from-a-file)

***

[7.4. Stack frames 64](#74-stack-frames)

***

[Stack frames help to isolate tasks 64](#stack-frames-help-to-isolate-tasks)

***

[What are stack frames? 65](#what-are-stack-frames)

***

[Nested scopes and closures [Advanced Topic] 68](#_heading=h.45jfvxd)

***

[Function arguments from lists 70](#function-arguments-from-lists)

***

[7.5. Debugging with a stack 71](#75-debugging-with-a-stack)

***

[If you can’t use the debugger 72](#if-you-cant-use-the-debugger)

***

[7.6. Returning values 72](#77-building-an-application-programming-interface)

***

[7.7. Building an Application Programming Interface 72](#_heading=h.4iylrwe)

***

[Why hide implementation? Isn’t code supposed to be open? 73](#why-hide-implementation-isnt-code-supposed-to-be-open)

***

[7.8. Refactoring 73](#78-refactoring)

***

[Functions and versions 75](#_heading=h.3x8tuzt)

***

[Introducing parameters 77](#introducing-parameters)

***

[7.9. Ordering code 79](#79-ordering-code)

***

[Chapter summary 80](#chapter-summary-6)

***

[Chapter 8: Data 80](#chapter-8-data)

***

[8.1. What is data? 81](#81-what-is-data)

***

[How to separate code from data? 81](#how-to-separate-code-from-data)

***

[8.2. How do computers see numbers? 82](#82-natural-representations-of-quantities)

***

[Integers 82](#integers)

***

[Double precision formats 83](#double-precision-formats)

***

[Infinity and beyond 84](#infinity-and-beyond)

***

[NaN and her family 84](#nan-and-her-family)

***

[Null and Void (Advanced Topic) 85](#empty-null-and-void-advanced-topic)

***

[How precise are my numbers 88](#how-precise-are-my-numbers)

***

[Complex numbers [Advanced topic] 88](#_heading=h.2hio093)

***

[8.2. Natural representations of quantities 89](#_heading=h.wnyagw)

***

[8.3. Graphical output 90](#84-structures-fields-and-reflection)

***

[8.4. Structures, Fields and Reflection 91](#_heading=h.1vsw3ci)

***

[Dictionaries and dynamic fields 92](#dictionaries-and-dynamic-fields)

***

[Overusing structures 93](#overusing-structures)

***

[Passing by value 93](#passing-by-value)

***

[Looping over variables 94](#looping-over-variables)

***

[8.5. Should I use Long or Short (wide) Form? 94](#85-should-i-use-long-or-short-wide-form)

***

[Converting to long form 96](#structuring-long-form-data)

***

[Converting to short form 97](#converting-to-short-form)

***

[8.6. Recursion [advanced topic] 97](#88-graphical-output)

***

[9. Efficiency 99](#9-efficiency)

***

[9.1. Making code run faster 99](#91-making-code-run-faster-and-use-less-memory)

***

[Check for duplication 99](#run-a-profiler)

***

[Remove any graphical or text output 100](#remove-any-graphical-or-text-output)

***

[Discard intermediates 100](#discard-intermediates)

***

[Preallocate memory for arrays 101](#preallocate-memory-for-arrays)

***

[Vectorisation 101](#vectorisation)

***

[Harness built-ins 101](#harness-built-ins)

***

[Boolean indexing 101](#boolean-indexing)

***

[Parallelise for loops 102](#parallelise-for-loops)

***

[Harness a GPU (Graphics processing unit) 102](#harness-a-gpu-graphics-processing-unit)

***

[Run a Profiler 102](#consider-sparse-arrays)

***

[Consider sparse arrays 104](#_heading=h.1smtxgf)

***

[Operate on small data chunks 105](#operate-on-small-data-chunks)

***

[9.2. Vectorisation 105](#92-vectorisation)

***

[Matrix multiplication 107](#matrix-multiplication)

***

[Boolean masking 108](#boolean-masking)

***

[Singleton Expansion (‘Broadcasting’) 108](#singleton-expansion-broadcasting)

***

[Applying functions to arrays: Mappings 110](#applying-functions-to-arrays-mappings)

***

[9.3. Lambda functions 110](#93-lambda-functions)

***

[9.4. Object-oriented programming 111](#_heading=h.1kc7wiv)

***

[9.5. Event-driven programming 113](#96-user-interfaces)

***

[9.6. User interfaces 114](#97-your-hardware)

***

[How to build a UI 114](#how-to-build-a-ui)

***

[Is a UI really needed? 115](#is-a-ui-really-needed)

***

[Making a long operation more friendly 115](#making-a-long-operation-more-friendly)

***

[Chapter 10: Errors 115](#chapter-10-errors)

***

[10.1. When Errors are a Good Thing! 115](#101-when-errors-are-a-good-thing)

***

[10.2. Anatomy of an Error 117](#102-anatomy-of-an-error)

***

[Understanding error messages 117](#understanding-error-messages)

***

[The Stack trace 118](#the-stack-trace)

***

[Difficult-to-debug situations where you think an error should be thrown, but it is not: 119](#what-if-no-error-is-thrown)

***

[Assertion 119](#assertion)

***

[Generate warnings 120](#generate-warnings)

***

[10.3. Error handlers 120](#103-error-handlers)

***

[Throwing and catching 120](#throwing-and-catching)

***

[Case study 121](#case-study)

***

[10.4. The short, self-contained code example (SSCE) 122](#104-the-short-self-contained-code-example-sscce)

***

[10.5. Spotting some obvious errors 122](#105-spotting-some-obvious-errors)

***

[10.6. Code review 124](#106-code-review)

***

[10.7. Heed the developer tools 125](#107-heed-the-developer-tools)

***

[Heed the Warnings! 125](#heed-the-warnings)

***

[Heed the Lint! 125](#_heading=h.415t9al)

***

[10.8. Strong and Weak Typing 126](#108-strong-and-weak-typing)

***

[Numerical casting 126](#numerical-casting)

***

[Boolean casting 127](#boolean-casting)

***

[10.10. Testing 127](#1010-testing)

***

[Creating test data – How to run a simulation 128](#creating-test-data--how-to-run-a-simulation)

***

[Unit Tests 129](#_heading=h.2tq9fhf)

***

[10.9. Provability 130](#109-provability)

***

[Chapter Summary 131](#chapter-summary-7)

***

[Reference 131](#113-interoperability-advanced-topic)

***

[Glossary 131](#glossary)

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