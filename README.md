# web-aspnet-simple

# Recipe

FROM [codenvy/aspnet](https://hub.docker.com/r/codenvy/aspnet/)

# Commands

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Download dependencies | `cd ${current.project.path} && dnu restore` |
| 2      | Run      |   `dnx -p ${current.project.path}/project.json web` |

# Preview URL

The app run on port 5004 in the container

# Factory

[![Contribute](https://codenvy.com/factory/resources/codenvy-contribute.svg)](http://beta.codenvy.com/f?id=m9ylnmjtmzvmq99i)