# Node-Api-Cluster
This project is a Node.js API that handles user tasks with a rate limit of 1 task per second and 20 tasks per minute per user. It utilizes a cluster with two server instances to ensure reliability and scalability. If a user exceeds the rate limit, additional tasks are queued for later processing. Task completions are logged to a file.
