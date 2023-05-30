
# Here are some of the rest API that used in workflow
1. HTTP (Choose a REST API to invoke.) POST Token https://login.microsoftonline.com/<TenentGUID>/oauth2/v2.0/token
2. HTTP (Choose a REST API to invoke.) Get the commit changes https://dev.azure.com/basantpandey0282/5e49543e-ccea-4d06-929f-02904a22956f/_apis/git/repositories/<repositoryID>/commits/<commitGUID>/changes
3. HTTP (Choose a REST API to invoke.) GET file content https://dev.azure.com/basantpandey0282/5e49543e-ccea-4d06-929f-02904a22956f/_apis/git/repositories/4f874d50-f1ec-4b8a-9da9-548bd61c8e3c/items/README.md?versionType=Commit&version=8ff0cfbcbf69a880088bb72bf08fc60f5469c68e
4. HTTP (Choose a Rest API to Invoke.) Post https://api.openai.com/v1/engines/text-davinci-003/completions
5. HTTP POST https://dev.azure.com/basantpandey0282/5e49543e-ccea-4d06-929f-02904a22956f/_apis/git/repositories/4f874d50-f1ec-4b8a-9da9-548bd61c8e3c/pullRequests/58/threads?api-version=6.0