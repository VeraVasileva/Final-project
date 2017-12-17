
# Title: Access to E-book

## Team Member(s):
Vera Vasileva

# Monte Carlo Simulation Scenario & Purpose:
Sometimes access to electronic books is limited to a particular number of simultaneous users. That means that if the particular number of people already have this resource open in their browser the next person to try to access this resource will be blocked. When this happens, it is necessary to wait a little while and then return to the resource to see if space has become available.

**Purpose:** Apply Monte Carlo method to simulate:
- **a chance to be blocked** (i.e. a probability not to get access to a book, since a maximum number of simultaneous users per book is exceeded) // (using PERT distribution function)
- **a chance to wait** (i.e. a probability that it would be necessary to wait for a book) // (using Normal distribution function)

### Hypothesis before running the simulation:
The greater the number of users, the greater the chance to be blocked
The longer the reading period, the greater the chance of waiting

### Simulation's variables of uncertainty
1. Number of users who read a book
2. Duration of reading a book

## Instructions on how to use the program:


## Sources Used:
- https://ask.library.yale.edu/faq/175294
- https://github.com/iSchool-590PR-2017Fall/590PR-examples/blob/master/Prob_Distributions.ipynb
- https://docs.python.org/3.6/tutorial/index.html
- Summerfield, M. (2009). Programming in Python 3: A Complete Introduction to the Python Language, (2nd ed.). *Addison-Wesley Professional*, 648.
