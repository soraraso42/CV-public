#TODO add preview and link to pdf CV

# My Resume management system with Git


## Why
As a budding developer in the co-op/intern job market, the current approach to managing application packages leaves me with two unmet needs:

- frequent updates
  - freshman developer and curious learner, I constantly need to add new stack and projects to my resume
  - beyond preserving changes in each version, I want to have a key-turn way of viewing them
 
- multiple versions
  - while keeping track of all of my stack and projects help with my overall professional growth, I do need to tailor resume to each job posting
  - I want to see each tailoring easily and perhaps even notice trends
  - I want to see similar job postings organized in a related way
  - the newest version of 'main database' resume should be readily accessible for each application/type of application

## How

My adaptations to achieve my goals:

- this fork will be a public repo where I update my stack and projects
  - self-contained commits with meaningful commit messages make understanding and locating changes a breeze

- this one is forked from a private repo where
  - each branch is a new job application
  - similar job postings can be a deeper branch ( mindful of keeping total depths within 3 )
  - pull request on the main branch of public repo will update the private repo with new stacks and projects
  - sync with main on this repo will then update all/selected branches

## Reference
Bryan Jenkins [original repo ]((https://github.com/tallguyjenks/CV)) has a breakdown of how the original setup works.
