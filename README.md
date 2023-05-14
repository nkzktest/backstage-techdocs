# backstage-techdocs
Example backstage techdocs github actions / workflow



Ref. https://docs.github.com/en/actions/using-workflows/sharing-workflows-secrets-and-runners-with-your-organization
You can centrally manage your secrets and variables within an organization, and then make them available to selected repositories. This also means that you can update a secret or variable in one location, and have the change apply to all repository workflows that use it.

When creating a secret or variable in an organization, you can use a policy to limit which repositories can access it. For example, you can grant access to all repositories, or limit access to only private repositories or a specified list of repositories.

To create secrets or variables at the organization level, you must have admin access.

On GitHub.com, navigate to the main page of the organization.

Under your organization name, click  Settings. If you cannot see the "Settings" tab, select the  dropdown menu, then click Settings.

Screenshot of the horizontal navigation bar for an organization. The "Settings" tab is outlined in dark orange.

In the "Security" section of the sidebar, select  Secrets and variables, then click Actions.

Click the Secrets or Variables tab, and create the secret or variable with your desired values and options.

For more information, see "Encrypted secrets" or "Variables."


Create the following secrets:
S3_BUCKET_NAME=x
S3_ENDPOINT=x
AWS_ACCESS_KEY_ID=x
AWS_SECRET_ACCESS_KEY=x

Environment variables in other repositories:
  SOURCE_DIR=x
  ENTITY_NAME=t
  ENTITY_KIND=x
