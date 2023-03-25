Welcome!
Work on the problem described below. Time box your efforts to a few hours, maximum 10. The goal is to spur a conversation on how you solve problems and organize your code. It's fine if you don't finish.

Problem: Spin up basic services using docker-compose.
Your deliverable should be a docker-compose.yml file and any additional scripts to do the following:

Spin up a server with a Postgres database called experiment_metadata and a table called subjects that contains a subject_id field (primary key), a date_of_birth, species, sex, and background strain fields.
Populate the table using the json data given.
Spin up a front-end component that can be used to view the data in a webapp (Flask, javascript, etc. are all fine)
We'll run docker-compose up locally to test that the services run correctly.

Data folder
We've generated some mock data that mimics what our scientists may collect during their experiements. For each experiment, a subject.json file is included which contains some metadata about the mouse subject. We have created a utility library in python that can be used to help write/parse the json files at aind-data-schema, which can be pip installed as pip install aind-data-schema==0.9.2, but feel free to parse the data however you see fit.

Possible Directions
Given you have a limited amount of time, you can choose to focus on a number of directions to showcase your skills. Feel free to expand on the basic assignment however you like, but we'll list a handful of directions you can take.

Materialized Views - Create a materialized view of the number of subjects of each sex that are born in a given year.

Service robustness - Add loadbalancing, rolling-updates, etc.

Metrics - Add a metrics scraper that can see how many times the backend tables are queried etc.

Front-end - This position is mostly focused on the back-end component, but feel free to polish up the look of the webapp if you like.

Rules of the Road
You can use standard libraries and docker images, but don't use something that does all the work for you. The goal is to see how you structure code and solve problems.

Spend a max of a few hours on this. It's okay if you don't finish - this is meant to spur a conversation on your approach and how you designed your code. If there are things you wanted to do but ran out of time, be prepared to discuss them.
