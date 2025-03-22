## Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked?

For Ruby projects, linting can be done, for example, with RuboCop. Its key features are bad code and style violation detection, customizable configurations, and seamless integration to Rail projects. There is also StandardRB which is built on top of RuboCop, but it can not be customized, like RuboCop.

Testing for Ruby can be done, for example, with RSpec which is similar to Jest.

Building on Ruby projects can be done with the default build script rake.

## What alternatives are there to set up the CI besides Jenkins and GitHub Actions?

Alternatives for setting up CI besides Jenkins and Github Actions include CricleCI, Azure Pipelines, GitLab CI, GitLap, BuildKite, Travis CI, and Airflow.

## Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

I would opt to use a self-hosted environment because I prefer having privacy and full control over my projects. However, if collaborating with others, I would opt for using cloud-based environments for easier collaboration. Additionally, it allows easier deployment for third parties when the project is out of production phase.