# web-aspnet-simple

# Recipe

FROM codenvy/aspnet

# Commands

Command #1 Download dependencies

cd ${current.project.path}

dnu restore

Command #2 Run

dnx -p project.json


# Preview URL

The app run on port 5004 in the container
