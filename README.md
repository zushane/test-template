# test-template

## Updating Labels
To update the labels, run the following command:

```
github-label-sync ZuCommunications/{REPO-name} --labels .github/labels.json --access-token $LABELS_GITHUB_API_TOKEN
```

This assumes that 

a) You have [GitHub Label Sync](https://github.com/Financial-Times/github-label-sync) installed globally, and  
b) you have a GitHub Personal Access Token with full `repo` access set as an environment variable in `$LABELS_GITHUB_API_TOKEN`. 
