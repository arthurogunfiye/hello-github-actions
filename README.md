## Welcome to "Hello World" with GitHub Actions

This course will walk you through writing your first action and using it with a workflow file. 

**Ready to get started? Navigate to the first issue.**

### Actions and Workflows

There are two components to using GitHub Actions that we'll cover:

- the action itself
- a workflow that uses action(s)

A workflow can contain many actions. Each action has its own purpose. We'll put the files relating to the action in their own directories.

### Types of Actions

Actions come in two types: container actions and JavaScript actions.

**Docker container actions** allow the environment to be packaged with the GitHub Actions code and can only execute in the GitHub-Hosted Linux environment.

**JavaScript actions** decouple the GitHub Actions code from the environment allowing faster execution but accepting greater dependency management responsibility.