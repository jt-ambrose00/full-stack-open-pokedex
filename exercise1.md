The language I chose for this exercise is PHP.

1. For linting: PHP_CodeSniffer, PHPStan, and Psalm are popular choices, with PHP_CodeSniffer seemingly the default standard for many projects. For testing: PHPUnit, Codeception, and Behat are all commonly used, the latter two offering testing options for Behavior Driven Development (BDD). For building: Composer, Phing, and Phar are all viable options, though many will argue that Composer is used more for managing dependencies than it is as a build tool.

2. For alternatives: GitLab CI/CD, CircleCI, and Travis CI all seem to be popular choices which offer a mix of self-hosted and cloud-based CI environments for both regular and open-source projects.

3. In order to determine whether a self-hosted or cloud-based environment would be better, you'd need to know about the size and skill of the team, the security expectations they're expected to meet, the probability of the project scaling in the future, and what resources are available to them to complete their task. That said, it's often claimed that PHP-based applications don't scale particurally well. If that's true, then as a general rule I'd say a cloud-based solution is probably best. In reality, I think a lot of that would be dictated by the demands of the team's internal and external customers.
