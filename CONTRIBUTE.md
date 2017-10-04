# Contribute to the development process
In General it is allowed and maybe missed, that someone contributes within this project. 
If someone is interested in developing a Software, that is
  * Easy to use
  * Easy to understand (not only for the enduser)   
  
Then (s)he is friendly invited. **But** please stick to some convensions:

## Before Starting
  1. Read carefully the Convensions, if something should be unclear, ask (somehow).
  2. Be sure, that you've understand the architecture.
  3. Stick to the Convensions.

# Convensions

## Code Convensions
The Code should be readable and easy to understand. Most likely orientate yourself at existing files. 
If some Style is really messed up, you'll be notified. But, to avoid this, here's a more formal definition:

### Formal Definition
May Come or be added, if some Contributors are present.

## Code Quality Assurance
It is very important, that a good quality is present. So the following things have to be fulfilled:
  * Every Thing shall be documented.
    + Classes: a brief describtion, which Methods are provided and for what porpose.
    + Interfaces: An extensively description:
      - what is the purpose of the interface
      - which are the characteristics of the interface
      - examples of implementing it.
    + Methods: A Description of the calculation and Meanings of Parameters and return value(s).
  * Write explaining Comments, within Methods.

## Maintenance
In Order that every new contributor or new module could come easily into the project, it could be very useful 
to provide some diagrams, the documentation, and things like that.

## Commit Messages
That the develop process could be easy tracked, it would be nice, if the Commit Messages will stick to a certain structure, 
that may (and shall) use the here defined abbrevations.
### Structure
As a good structure it follows [Ref][Res][Mes], which are defined as: 
  * [Ref]: a Reference, that specifies the Module (and Files), that have been modified, added (or deleted)
    + eg. M:p.f/, where M is the Name of the Module, p the package name, f the Filename.
  * [Res]: a Reason: Why it have been added, modified or even deleted.
    + eg. CodeOpt>, where CodeOpt, stands for Code Optimization
  * [Mes]: A Actual Message, that contains, what have been added, modified or deleted.
    + eg. Removed not needed outcommented code.    
    
So the example Message would be: 'M:p.f/CodeOpt> Removed not needed outcommented code'. 
It could be possible, that 
  * more messages are added, then those should be comma separated. 
  * more Files are effected, that should be semicolon separated.
  * more reasons are underlaying, these should be splash separated.   
  * brackets are used, to asure, that it is understood right.   

#### Example 1
M:p.(f1; f2)/CodeOpt> (RM RED Code, Removed outcommented code)/CQA> RE DOC.
#### Example 2
M:p.(f1/CodeOpt> (RM RED Code, Removed outcommented code); f2/CQA> RE DOC).

### Abbrevations
All Abbrevations appearing should be found here, if some is missing it should be added immediately.
#### Modules
The following Modules are present in the project, that's why they are wanted to be shortened, to be used in
commit messages:
 * ROOT: The *root* folder of the Repository, where the Modules etc. are stored.
 
#### Reasons
The following Reasons are explained:
  * CodeOpt: Stands for *Code Optimization* and should be used, when the code is optimized.
  * CQA: Stands for *Code Quality Assurance* and should be used, if the quality of the code is improved.
  * QA: Stands for *Quality Assurance* and should be used, if the unspecific quality is improved.
  
#### Messages
The following abbrevations are often used, that's why they're wanted to be used:
  * RM: Stands for *removing* (parts of Code), Documentation or Comments
  * MOD: Stands for *modifing* (parts of) Code, Documentation or Comments
  * ADD: Stands for *adding* (parts of) Code, Documentation or Comments
  
  * MENT: Stands for *mentioned*.
  
  * RED: Stands for *redundant*
  * DOC: Stands for *Documentation*
  * COM: Stands for *Comment*
  * DESC: Stands for *Description*
