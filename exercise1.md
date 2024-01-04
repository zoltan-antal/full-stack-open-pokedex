My chosen language for this exercise is Python.

The most commonly used tools for linting Python is Flake8. For testing the code we can use unittest or pytest. Python is an interpreted language, so the code does not need to be compiled, but we can use a build tool such as setuptools for packaging and distribution.

I looked for alternatives to Jenkins / GitHub actions. GitLab CI/CD seems to be a popular tool, seemingly it can do both self-hosting and cloud-hosting, but it is difficult to tell at a glance. Drone seems to be the other go-to tool when it comes to self-hosting. Regarding cloud-based solutions, there seems to be a bigger selection. The traditional alternative is apparently Travis CI. Alternatively, CircleCI seems to be a cloud-hosted solutions that has gained much popularity in recent years.

When it comes to self-hosted vs. cloud-based, it really comes down to the project itself. As mentioned in the material, if there is a need for things like GPUs, self-hosted would be the way to go. However, as setting it up and maintaining can be a pain, it would be best avoided if possible. Assuming the project does not need access to any special resources on a server, I would say a team size of 6 is still fine with a cloud-based solution.
