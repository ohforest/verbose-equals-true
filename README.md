# ⚠️This project has moved to a new GitLab rep⚠

This project has migrated to a new GitLab repo in a group:

[https://gitlab.com/verbose-equals-true/django-postgres-vue-gitlab-ecs](https://gitlab.com/verbose-equals-true/django-postgres-vue-gitlab-ecs)

<span>
<a href="https://gitlab.com/briancaffey/verbose-equals-true/commits/master"><img alt="pipeline status" src="https://gitlab.com/briancaffey/verbose-equals-true/badges/master/pipeline.svg" /></a>
</span> <span>&nbsp;</span>
<span>
<a href="https://gitlab.com/briancaffey/verbose-equals-true/commits/master"><img alt="coverage report" src="https://gitlab.com/briancaffey/verbose-equals-true/badges/master/coverage.svg" /></a>
</span>

# Docker, nginx, Django, Vue project

This project is an example of how to set up a containerized Django application using nginx and VueJS. The project uses GitLab for continuous integration.

**A highly detailed explanation of the development of this project can be found in [`documentation/README.md`](/documentation/README.md).**

## Start the project locally

`docker-compose` is used to start either the development or production version. For production, run the following:

```
docker-compose up --build
```

For local development (hot reloading on the Vue and Django applications), run the following command:

```
docker-compose -f docker-compose.dev.yml up --build
```

The project is currently under development. Please feel free to create issues and merge requests.
