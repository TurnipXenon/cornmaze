# Infrastructure

We put our general notes about infrastructure here!

Plan:

We can write the ARN for our github to get our code and then give it to the pipeline

Plan:

- We use Github Actions on branches "build/*"
    - build/production
    - build/staging1
- We deploy in those branches.

What we need to do:

- We wanna make a Github Action

Current plan: delay pipelines; prioritize deployment

Flow for deploying Turnip:
Manual:

- https://docs.aws.amazon.com/AmazonECS/latest/userguide/create-container-image.html
- docker push account-id.dkr.ecr.us-east-2.amazonaws.com/turnip
  Github:
- push to build/production

Plan:

We just want to use DigitalOcean. We are no longer having fun.

Changes:

- No more AWS
- No more CDK
    - This would archive turnip_cdk and revert reinhard to empty (for now). We might want to use Pulumi in the future.

Roadmap:

- Deploy the Go backend on DigitalOcean
- Migrate to Postgresql
- Get back to NextJS
