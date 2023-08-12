# engineering_primer
A path towards software engineering and resources to help

## Computer Science vs Software Engineering
Why do most folks who take a traditional path towards Software Engineering have a Computer Science(Comp Sci) degree? There aren't really any Software Engineering degrees out there, the closest thing we have is a CompSci degree. A CompSci degree in this case acts as a filter to see if you can perform tasks that are offerred to you, complete basic problem solving and are able to program at a moderate level. There are many things that are expected in industry for most folks to know for your every day working environment that are not taught in school or at least weren't when I attended.

## What CompSci Courses I Would Take
- Data Structure Algorithms/Advanced Data Structures and Alogrithms
These give you a decent feel for how data is processed under the hood and how it can be moved. You get an idea of what kinds of operations are expensive so that you don't write loops that blow up in exponential fashions when you start dealing with more data.

- System Design/Computer Architecture
You should know what the basic components of computers are CPU, Memory, Storage and how they interact with each other. What operations are quick and why. What are caches and how much data can live there. What are thread, what are different kinds of memory and what they can be used for. How can graphics cards be used for ML applications.

- Databases
SQL vs NoSQL DBs. How to structure data and how to query it(SQL/filtering). If you want to deal with any data you need to know how to store and query it. Learning the basics of how to do it efficiently can save you down the line. Getting a basic understanding of how this works can really help when you are dealing with Databases later in your career.

- Networking
Data travels over the internet and between systems. How the does it do that, what is TCP/IP and why are they important? You'll learn that here.

- Graph Theory
Nearly everything can be represented as a graph and it lets you get some more practices with algorithms. This can help with some higher level thinking that can allow you to solve problems down the line.

- Project Course in Something
Take a project course in something that you find interesting, ML/AI, Graph Theory, Game Theory, Networking. This should teach you a few things such as how to complete a project and how to work with others on a team. You get to learn that source/version control can be really handy and that working with people can sometimes suck or be great. You will be working with others in the industry like 99.5% of the time, learn how to interact and communicate it will help you go far.

## Recommended Starting Language
tl;dr: Python

Python has a pretty easy learning curve and it has a package for nearly anything. It has a lower barrier to entry since it it basically writing broken english to tell a computer what to do. With the availability of libaries you should be able to get most backend tasks done, APIs, scraping or creating small ML models can all be done with python. Python is also the language that most data scientists utilize as it plays with data nicely. It is not the most performant language so if you eventually need to deal with that you can utilize other languages.

To get the Syntax down the codecademy course works. Then just start tinkering on projects.

## Project Ideas
- Hello World(Command Line)

- Command Line tool to add numbers
  - This shows you how to accept input and you get something running

- Hello World(Web App, APIs, Email)
  - Call weather api to get weather
  - Have a button that you click which will send an email to you based on an email you input from SendGrid


- Web Scraper for a site(reddit)
  - learn about api calls
  - learn how to parse html and how info is stored and read on the internet
  - how to store data if you want to process it later(databases)
  - how to aggregate data using python(analytics/stats/data science)

- Scrapper to see if links on a site are working

- Port Scanner(Only use on your own network)
  - teaches about networking and ports

- Hosted Personal Site
  - How to make a site
  - How to utilize cloud infra if you want to use AWS or Digital Ocean
  - Or just how to get a portfolio site setup

## Getting your first gigs/internships/jobs
Starting you you will be experience poor, make up for that by doing some projects and showcasing what you can do. People care less about your experience at past companies if you can show them you can do the work or have the apptitude to solve their problems. At the end of the day they pay you to solve their problems and make them money.

If you don't have one create a LinkedIn Account. List your current education and projects on there as well as any other relevant technical experience.

### Tier 1/Big Name Companies
Apply to these internships for interviews early like in September - December of the year before the summer you'd work them. These are usually all filled by February. These interviews and even getting a slot for one is highly competitive and you will need to prepare. The path for preparation is pretty nailed down at this point though. You'll end up doing a bunch of questions from a site called Leet Code and a book called Cracking the Coding Interview. These are basically IQ tests to see if you can solve a problem you are given and how you appraoch problems you might not be familiar with. The interviewer wants to see how you approach the problem and if you can find optimal solutions. During these interviews they are trying to find hiring signals and if you would be a good fit for the team you applied to. You will also be asked some behavioral questions and possibly some system design questions.

The grind can be worth it for these internships and jobs. Having a big name on your resume can help boost your career but it is not the only path.

### Local Companies and Startups
Interview for these will be a little more loose and they usually pay a bit more. The double edged sword of these is that you might get to work on anything. This could range from some old crappy systems to architecting new systems for them and working on things that are way above your pay grade but you are the person who knows how to work those damn computers. If you don't get one of the previously mentioned internships or you are applying later target these companies. They might have more behavioral questions for local companies rather than super technical ones. Startups will still have technical programming questions most likely. You can generally apply for these a little later like in the spring before summer but always check what is available early.

Check your school job boards for postings.

## Things they didn't teach you at Uni
- git/GitOps
  - CI/CD
- linting/formatting/type checking
- testing(unit and integration)
- database design(SQL and NoSQL)
- docker
- software architecture/system design
  - BE
  - FE
  - Infrastructure
  - Queues/Distributed Systems
- code reviews
  - PR process and merging
- searching logs
- Observability
  - logs, metrics, traces
- App Security (OWASP)