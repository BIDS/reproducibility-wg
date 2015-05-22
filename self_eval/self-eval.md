
# Self Evaluation for Reproducible Science

Inspired by the Joel Test and the Software Carpentry version of the Joel Test, 
this work is a checklist of attributes necessary for reproducible science. 
This checklist seeks to help scientists to answer the question: **How 
reproducible is my science?** At the end of the decision tree we seek to
provide something similar to a reproducible research badge for the scientist.

## Goals

1. Identify practices, rather than tools, characterizing reproducibility 
2. Based on these practices, place a study somewhere on the spectrum of
reproducibility
3. Establish domain-specific variance and criteria
4. Given placement on the spectrum, provide a set of recommendations for specific gaps.

## The Decision Tree


**Code**

- [ ] If your laptop exploded, would your research be lost forever?
- [ ] Do you use version controlling for your software?
- [ ] Do you use version controlling for your data?
- [ ] Is your code available and freely accessible to your community?
- [ ] How permissible is your license?
- [ ] If you license is OSS, what kind?
- [ ] Can I tell that your tests are passing (Continuous Integration)?
- [ ] What is your test coverage percentage?
- [ ] Do your tests demonstrate the use of your code?
- [ ] Does it have documentation?
- [ ] Do the public functions in your API have documentation of their parameters?
- [ ] When a user has the most recent version of the code, do they have the most recent version of the documentation?
- [ ] Does your Software have long form docs (e.g. vignettes)
- [ ] Is your code written in a common programming language?
- [ ] Is your code distributed in a centralized software package archive (pypi, CRAN)?
- [ ] Is there an archival journal article covering the features of your software?
- [ ] Do you have separate DOIs for each version release of your software?
- [ ] Can someone outside of your lab/research group build and your software in 1 step? Two steps?
- [ ] Does your software run on MacOSX?  
- [ ] Does your software run on Linux?  
- [ ] Does your software run on Windows?  
- [ ] Do you have a bug tracker? (e.g. email, github issues, etc.)
- [ ] Do you reference bug fixes in software releases?
- [ ] Does your software have a complete readme with install instructions?
- [ ] Does your software rely on only accessible dependencies?
- [ ] Does your software have a license allowing others to use it?
- [ ] Does the license you chose allow others to extend your analysis (e.g. non-viral license).

**Data**

- [ ] Does any of your data rely on expert opinion (i.e., did you make up any of the data? :) 
- [ ] Is your data collection process automated?
    - [ ] If no, is it validated?
- [ ] How much of your data manipulation is automated?
- [ ] How much of your data analysis involves clicking (i.e., is not coded)?
- [ ] If you use data, do you ever enter it by hand? (why does this matter?)
    -  [ ] If yes, are you the only one who enters the data?
- [ ] Does your data collection process include a chain of responsibility?
- [ ] Do you store your data in a database?
- [ ] Is your data downloadable online?
- [ ] Is your data publicly accessible?
- [ ] Is it available at a persistent URL.
- [ ] Is your data part of a persistent data repository? (E.g. Figshare, Dat)
- [ ] Is your raw data available?
- [ ] Do you have separate DOIs for each version release of your data?
- [ ] Does your data have associated metadata?
    - [ ] Has the metadata been validated?
    - [ ] Is the data schema in a common format?
    - [ ] Is it inextricably attached to the data? (E.g. stored in the database like your data)
- [ ] Are there restrictions on your data's usage?  (e.g. Embargoes)
- [ ] Is your data licensed in a manner that allows others to use it in extensions of your work (e.g. PDDL).
- [ ] Do you have a bug tracker in data releases? (email, github issues, etc.)
- [ ] Is your data processing (from acquisition to evaluation) documented?


**Analysis**

- [ ] Do you automate plotting?
- [ ] Does your data analysis involve more than one step?
