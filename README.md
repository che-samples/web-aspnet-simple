# web-aspnet-simple

# Recipe

FROM [codenvy/aspnet](https://hub.docker.com/r/codenvy/aspnet/)

# Commands

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Download dependencies | `cd ${current.project.path} && dnu restore` |
| 2      | Run      |   `dnx -p ${current.project.path}/project.json` |

# Preview URL

The app run on port 5004 in the container
