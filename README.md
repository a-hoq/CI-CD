# Continuous Integration and Continuous Delivery (CI/CD)

Continuous Integration (CI) is the practice of software development teams frequently committing their software changes to a shared version control repository. This is supported by a CI server that automatically creates a build from each commit and runs low-level tests to quickly ensure expected behaviour. Automated building and testing ensures time efficiency and reduces human error. The act of frequently committing changes reduces time lost to big merge conflicts or build errors. Committing code in small amounts provides fast feedback and makes sure issues are addressed early and quickly. Conversely, committing code after long development periods leads to big delays from integration issues and rework. Note that the CI server can be configured to build and test changes _before_ they are committed to the codebase. This enables other changes to be committed without needing time to remove or fix the previous broken commit.

Continuous Delivery (CD) is complementary to CI to make the "CI/CD Pipeline". The pipeline depicts the stages that code goes through, from source code to production. CD starts after the steps of CI; if the build from CI is passing, it is pushed to CD for further testing. A custom script is set up to automatically deploy the build through one or more test environments to run high-level automated tests. Since deployment is done by a script, the process is easily repeatable, changeable, and without risk of human error from manual deployments. After all testing is done in the environments, the release team can manually push the build to production when appropriate. Continuous Deployment is an extreme version of this where deployment is completely automated, including the push to production. This is not appropriate for every software project, but it has its benefits in certain circumstances. Altogether, the pipeline is used to improve the software development process for DevOps teams and deliver quick product changes to customers without losing quality.

[//]: # (As an example, this can be set-up so that GitHub is the shared remote repository, and GitHub Actions is the platform to create and maintain the CI/CD Pipeline.)

<h3>Sources:</h3>

* [Video: What is Continuous Integration? -- By IBM Technology](https://www.youtube.com/watch?v=1er2cjUq1UI)
* [Video: What is Continuous Delivery? -- By IBM Technology](https://www.youtube.com/watch?v=2TTU5BB-k9U)
* [Video: Continuous Deployment vs. Continuous Delivery -- By IBM Technology](https://www.youtube.com/watch?v=LNLKZ4Rvk8w)
* [Blog: Continuous integration vs. delivery vs. deployment -- By Atlassian](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)
* [Blog: What is Continuous Integration (CI)? -- By Jetbrains](https://www.jetbrains.com/teamcity/ci-cd-guide/continuous-integration/)
* [Blog: Understanding Continuous Delivery -- By Jetbrains](https://www.jetbrains.com/teamcity/ci-cd-guide/continuous-delivery/)
* [Blog: What is Continuous Deployment (CD)? -- By Jetbrains](https://www.jetbrains.com/teamcity/ci-cd-guide/continuous-deployment/)
* [Blog: Continuous Integration vs. Delivery vs. Deployment -- By Jetbrains](https://www.jetbrains.com/teamcity/ci-cd-guide/continuous-integration-vs-delivery-vs-deployment/)
* [Blog: Understanding CI/CD Pipelines -- By Jetbrains](https://www.jetbrains.com/teamcity/ci-cd-guide/ci-cd-pipeline/)
* [Blog: What is a CI Server? -- By Jetbrains](https://www.jetbrains.com/teamcity/ci-cd-guide/ci-cd-tools/servers/)
* [Blog: Testing stages in continuous integration and continuous delivery -- By AWS](https://docs.aws.amazon.com/whitepapers/latest/practicing-continuous-integration-continuous-delivery/testing-stages-in-continuous-integration-and-continuous-delivery.html)
