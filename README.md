# Project assigment for batch 19
## Project #2 on CI/CD

This repo sets down the following automated actions.

1. Send a Telegram message to me informing me of any commits (IFTTT). - Done. <p>
   Set up through IFTTT GUI.
   <br></br>
   
3. Create a row in my google sheet for each new commit (IFTTT). - Done. <p>
   Set up through IFTTT GUI.
   <br></br>
   
4. Deploy Static content to pages. - Done. <p>
   Setup via GitHug automated actions.
   <br></br>
   
5. Push to AWS. - WIP. <p>
   Set up through aws.yml file.
   
   a) Create an ECR repository to store your images.

   b) Create an ECS task definition, an ECS cluster, and an ECS service.
   
   c) Store your ECS task definition as a JSON file in your repository.
   
   d) Store an IAM user access key in GitHub Actions secrets.

<br></br>

Not tested
1. Sends a greeting to whoever creates their first issue. - Done.
2. Gives a greeting when someone pull the repo. - Done.

<br></br>

Notes
- There is an unexplained delay in items relating to IFTTT actions. Why?

The exploring continues in CI/CD!!!
