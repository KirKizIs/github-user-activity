# GitHub User activity
*a simple command line interface (CLI) to fetch the recent activity of a GitHub user and display it in the terminal.* [link to roadmap task](https://roadmap.sh/projects/github-user-activity)

## Requirements
*The application should run from the command line, accept the GitHub username as an argument, fetch the user’s recent activity using the GitHub API, and display it in the terminal.*

**The user should be able to:**
- Provide the GitHub username as an argument :
- ```github-activity <username>```
- Fetch the recent activity of the specified GitHub user using the GitHub API.
``` 
# https://api.github.com/users/<username>/events
# Example: https://api.github.com/users/kamranahmedse/events
```
- Output:
```
- Pushed 3 commits to kamranahmedse/developer-roadmap
- Opened a new issue in kamranahmedse/developer-roadmap
- Starred kamranahmedse/developer-roadmap
- ...
```

**Additional features:**
- Errors should be handled gracefully (e.g., invalid usernames or API failures).
- Do not use any external libraries or frameworks to fetch the GitHub activity.