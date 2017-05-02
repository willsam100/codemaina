***
Codemaina  

***                        
### More Buisiness code, les boiler plate
- Code generation 
- saves time
- legibility 
- generatiity

*** 
### The tool

- atomist
- has a slack bot
- command line - fork from GitHub
- language independant
- Java was used in examples
- write code gen in TypeScript

*** 
### The tool

- Can intregrate with GitHub
- can merge/submit PRs
- Build tools

*** 
### Code gen:

- does not have to be perfect
- compiler/unit tests will catch errors                      
- Ast - antler agreement                        
- Antler grammar*                        
- Also can use a parser                        
- Micro grammars
- regex/find replace most common

*** 
### Code gen means

- The output is still familiar
    - juniors will be able to read/modify it
    - bad abstractions are not created
- effeciency is improved
    - boilplate code cad be removed
- learnings are caputred 
    - maintain the script 
    - update before the next script
- standards can be introducted
    - share the code gen tool
    - update the tool with the new standard

*** 
### Dave Thomas 
#### Accelerating software delivery 

- use structured data
- immutablity for data
- utlize hardware: it's cheap

---
### Accelerating software delivery 

- Table driven programming
- drive code from tables
- toggle switches in DB
- similar to feature switches but for whole application
- extend:
    - Desciion tables 
    - state tables/ state charts

---
### Accelerating software delivery 

- keep stuff simple
- spreadsheets are understood by many
- spreadsheet parser

--- 
### Accelerating software delivery 
#### Testing

- It's still expensive
- test early
- Property-based testing
- compare two implementations


***
### Delivering Value

- NZ companies are using slack bots                        
- NZ companies are caputuring metrics of the code. Checked/enforced at the PR level
- You are not your code - don't be rude.

---
### Delivering Value

- Dev: how will i build this
- QA: how will i break this
- Delta: the difference between prod and tip of master

---
### Delivering Value
#### Features

- use features switches
- keep it simple: if else statement
- clean up the code later
    - use a bot for source code analysis
- repeating code (copy/paste) is not bad
    - DRY applies to code with the same dependencies 
    - features switches are changing dependencies
- url to turn features on in dev/test 
    - don't do this in prod    

---
### Delivering Value
#### Culture is important

- fear of breaking things will paralizye your org
- not trying to be irreesponible 
- incident/morgue report
    - done via wiki (not a meeting where the loudest person wins)
    - performed by the person closest to the incident   
    - contains:
        - scenario/impact
        - timeline
        - discussion
        - mitigations


*** 
### Distruted Databases

- They are all broken
- consistency algorithems are hard
- property-based testing



***
### Property-Based Testing 
- it's hard
- helps to learn the domain
- works at the outside level (intergration tests)
- hard to to create generatores
- excellent for finding edge cases in the systems
- excellent for algroithms/complicated code
- excellent for understanding the domain
- generators are great for mocking data 
    - Just give me a .... (eg valid email)

***
### Property-Based Testing 
#### Sucess story

- Yahoo
- testing email 
- what is a valid email 
- an email address can contain comments (in the local part)
- and email address can contain nested comments 

--- 
### Testing
- test pyramid is not very useful
    - unit tests reduce changed
    - outside/integration tests are more valable
    - optimise outside tests: better value return
- use unit tests to create a good archetecure
    - add in outsitde tests
    - then delete unit tests

*** 
### SOLID: its rubbish
- useful when a jnr
    - require some guidance
- programming is hard
    - can't be dsitillied into 5 steps
- doesn't help to write the next line of code
- focus on the customer
- add abstractions/patterns in after
    - you have something working
    - you understand the domain
    - it's the right abstraction 
- simple code 
    - is easy to change
    - is understood by all
    - is easy to delete 

***
### APIs/APKs
- Use SDK to make web APIs easier to use.                        
- Authenticated api for free - can tell a user that all is being turned off.                        
- Pass through meta data in headers. Allows to figure out what your users are using.        

*** 
### .NET Libraries
- SpecLite                        
    - BDD
    - uses fluent api
    https://github.com/robfe/SpecLight
- PowerAssert    
    - assertion library
    - shows evaluation of failure
    https://github.com/PowerAssert/PowerAssert.Net


*** 
### Data tools

- Aws: red shift                        
- Re-dash                        
- For data                        
- Data warehouse                        
- Useful for sharing sql queries   


*** 
### Mobile tools
- Appsee mobile tool    
    - analytics tool
    - can caputre screen
    - heat maps of user interactions
    https://www.appsee.com/

*** 
### Building Culture
#### For Managers

- Building control - review of your manager                      
- 360 review                        
- Teams results aggregated up                        
- 1 - 5 how slammed are you, useful to monitor trend of individual                      
- One on one's, Coupled with online survey.                        
- 101 one on one questions; use when stricking silence                        
- 'Good authority' Book to read                        
- Work and life are connected                       
- Shared project - Build with team members                        


*** 
### Tools                    
- Metrics - kean.io                        
- Handles offline data                        
- Todoist                        
- Task based app                        
- Slack bot channels for breaking build.                        
- Slack bot learn today.                        
- TIL (Today i learnt a thing)
- Slack bot emoji to post in other channels                        
- Mattermost - self hosting messaging client                        
- Slit.io - feature switches    
                
***
### Personal: Reflect and Refactor
#### Reflect

- 'Drive' - book about discovering what motivates you.                        
- Have 'self retros'
- Focus on different timelines
    - Daily/weekly
    - Monthly
    - Yearly 

---
### Personal: Reflect and Refactor
#### Refactor

- Tune and improve habit loops
- creating new habit loops is hard
- easier to add to exisitng habit loop
- must find the right habit loop to 'hack' 
- must find the right part of the habit loop to 'hack'

---
### Personal: Reflect and Refactor
#### Example with character

- hightlight important character attributes
- assign a numeric value
- graph 
- assign actions with points that will earn
- work on levelling up



*** 
### Career
- Jn/snr -> solution/problem/finder                        
- Search for what makes you happy                                            
- Experience means better people/communication skills                        
- Senior expensive but pair with cheaper junior                        
- Should develop the ability to teach/influence                        
- The real 10x developer 2x all the other developers                        
- Teaching big part.    

*** 
### Thanks to EROAD


--- 

Playing sims- put them in a swimming pool with no laders    
Arbitrary union - type language feature                        
Comes from closujre
Alexa vs Google home battle                        


