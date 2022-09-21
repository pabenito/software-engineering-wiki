# Introduction

## Glossary

### Definitions

- **Formal methods**: Logical and mathematical **reasoning** about the software.
- **Equivalence class**: Subset of the input domain which causes the software to **behave in the same way for all of them**---i.e. correct passwords is an equivalence class, all of them resulting in a correct login.

### Acronyms

- **RT**: Real Time.
- **I/O**: Input/Output.

### Synonyms

- **Bug** (informal but short) / **Software failure** (formal but long). 
- **GUI**: Graphical user interface.

## _Formal methods_ - The good part 

### Goals

- Reliability 
- Security & Safety
- Robustness
- **Verification**
- Efficiency

### Usage

- Definition of **unambiguous** requirements. (ease communication)
- Better systems **understanding** and **testing**. 
- **Lower** development and maintenance **cost**.
- **Model benefits**: Compile model to implementation, equivalence of models, etc. 

### Software problems it solves

There are some software problems that _formal methods_ solve:

- When software reaches an **inconsistent state** (probably a _bug_), rebooting is usually the easiest solution. But many systems cannot be rebooted. 

So it is important to ensure that the system will not reach inconsistent states.

- Many systems are **critical** and **_RT_**. An error in one of these systems implies very high risk---i.e. physical damage to people, fatalities, environmental damage, legal consequences, high monetary costs, etc. 

So it is essential to verify that there are no software faults.

- Most software works with **infinite data domains**, and it is even difficult to find all equivalence classes (use cases). Experimental test (_I/O_) usually focuses on covering all _equivalence classes_ with at least one test for each _equivalence class_. Most of the software _bugs_ comes from unexpected input, belonging to an untested equivalence class---probably because it had not been contemplated. 

So it is crucial to find all _equivalence classes_. _Formal methods_ can find all of them. 

- It is desirable to **prove** properties for the equivalence classes. But typically they are either "proved" inductively---by testing with at least one value of the equivalence class and assuming true for the rest of the equivalence class---or proved manually (non-automatically) for each desired property. 

So it would be useful to prove **all**---even properties that had not been thought of (maybe undesirable)---posible properties of the system automatically. _Formal methods_ can do it.

## _Formal methods_ - The bad part

If it is so useful, why is it not used so much?

### Verification limitations

- The **requirements** or **specification** may be **incorrect**. 
- Assuming the specification is correct. Only can be proves that the mathematical abstraction of the **model is correct, not its implementation**.  
- The most can be said, **only** in the **best case**---if the requirements, system specification, compiler and hardware design are correct---, then the **program will run correctly**.

### Few resources

_Formal methods_ is relatively **recent**, so it presents some problems typical of the new disciplines:

- Few **tools**. Most of them specialized in very specific fields, having to learn and use different technologies for each purpose. ([Maude](https://maude.cs.illinois.edu) aims to solve this problem).
- Few **documentation**.
- Lack of user friendly **_GUIs_**.
- Lack of **standardization**. 
