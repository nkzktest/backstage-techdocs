# backstage-techdocs
Example backstage techdocs github actions / workflow


## Create techdocs ci template in github:

First create the following secrets and make them available in your github organization:
S3_BUCKET_NAME=x
S3_ENDPOINT=x
AWS_ACCESS_KEY_ID=x
AWS_SECRET_ACCESS_KEY=x

Ref. https://docs.github.com/en/actions/using-workflows/sharing-workflows-secrets-and-runners-with-your-organization
Profile -> Settings -> Settings (Organization) -> Secrets and variables


Environment variables that must be defined in other repositories:
  SOURCE_DIR=x
  ENTITY_NAME=t
  ENTITY_KIND=x

