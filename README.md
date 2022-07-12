# job-recruitment-exercises
Different exercises for job recruitment
# Exercise 1
1. You need to provision a new Web application
2. This is a simple “hello world” page
3. The architecture should include : NodeJS, MongoDB, Containers.
4. The runtime should be on any Linux distro you prefer
5. Every component of the architecture should run on its own container
6. All the architecture should be fully defined by scripts and code (IaC) saved in github
7. The DB should contain this data:
 [ { "_id": 1, "name": "apples", "qty": 5, "rating": 3 },
  { "_id": 2, "name": "bananas", "qty": 7, "rating": 1, "microsieverts": 0.1 },
  { "_id": 3, "name": "oranges", "qty": 6, "rating": 2 },
  { "_id": 4, "name": "avocados", "qty": 3, "rating": 5 },
]
8. The exercise submission should be this git repo
9. The exercise will be by provisioning the architecure by running the scripts in the repo
10. Tests that the exercise should pass:
  - Provision from scratch of the entire architecture
  - The html returns the number of apples in the DB
  - Visual demonstartion of the architecure (containers, netwrok topology etc..)
11. Bonus
  - Full ci/cd pipeline with one of the cloud providers
  - Readme page in the git repo with guid that explains about the app, architecture design etc..
  - Load balancer 
  - Your own ideas and will be welcome - create a PULL REQUEST to this branch:)
12. At  the end of the demonstration you will be asked about the architecture design and the components to demonstrate the ability to learn and understand new areas and technology 
