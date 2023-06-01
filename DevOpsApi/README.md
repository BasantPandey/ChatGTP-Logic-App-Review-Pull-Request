
# Here are some of the rest API that used in workflow
The following ADO REST API endpoints, replacing {organization} with your ADO organization name, {project} with your project name, {repositoryId} with your repository ID, and {commitId}.

1. HTTP (Choose a REST API to invoke.) POST Token https://login.microsoftonline.com/{TenentGUID}/oauth2/v2.0/token
2. HTTP (Choose a REST API to invoke.) Get the commit changes https://dev.azure.com/{organization}/{project}/_apis/git/repositories/{repositoryId}/commits/{commitId}/changes
3. HTTP (Choose a REST API to invoke.) GET file content https://dev.azure.com/{organization}/{project}/_apis/git/repositories/{repositoryId}/items/README.md?versionType=Commit&version={commitId}
4. HTTP (Choose a Rest API to Invoke.) Post https://api.openai.com/v1/engines/text-davinci-003/completions
5. HTTP POST https://dev.azure.com/{organization}/{project}/_apis/git/repositories/{repositoryId}/pullRequests/{pullRequestId}/threads?api-version=6.0