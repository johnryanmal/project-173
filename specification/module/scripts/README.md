# Project-173
[Home]: https://github.com/johnryanmal/project-173
[Specification]: https://github.com/johnryanmal/project-173/tree/main/specification
[Module]: https://github.com/johnryanmal/project-173/tree/main/specification/module
[Home] / [Specification] / [Module] / Scripts

### About

Roughly based on GitHub's [Scripts To Rule Them All](https://github.com/github/scripts-to-rule-them-all):
> If your scripts are normalized by name across all of your projects, your contributors only need to know the pattern, not a deep knowledge of the application. This means they can jump into a project and make contributions without first learning how to bootstrap the project or how to get its tests to run.
> The intricacies of things like test commands and bootstrapping can be managed by maintainers, who have a rich understanding of the project's domain. Individual contributors need only to know the patterns and can simply run the commands and get what they expect.

### Details

`install` sets up the module to be run locally. Retrieves dependencies and the like.

`init` sets or resets a module to be in some initial state.

`update` synchronizes local module with remote data. Typically also executes `install`.

`run` will run the module. Required.

`test` checks if the module runs locally as intended.


