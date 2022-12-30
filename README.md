# Continuous Integration and Continuous Delivery (CI/CD)

Continuous Integration (CI) is the practice of software development teams frequently committing their software changes to a shared version control repository. This is supported by a server that manages automation. The server starts an automation task from each commit, to create a build and run low-level tests to quickly ensure expected behaviour. If the build/tests fail, the team can be notified. Automated building and testing through scripts ensure time efficiency and reduces human error. The act of frequently committing code changes reduces time lost to fixing big merge conflicts or build errors. Committing code in small amounts provides fast feedback and assures issues are addressed early and quickly. The regular checking of code in this manner improves code quality.

Continuous Delivery (CD) is complementary to CI; collectively known as the "CI/CD Pipeline". If the build from CI is passing, it moves to the CD stage for further testing. Typically, the same server from CI manages deploying the build through one or more pre-defined test environments to run high-level automated tests. Since deployment is done by a script, the process is easily repeatable, time efficient, and without risk of human error from manual deployments. After all testing is passing in the environments, the release team can manually push the build to production when appropriate. "Continuous Deployment" is an extreme version of this where deployment is completely automated, including the push to production. That is, each code commit is automatically released to customers if all the tests are passing.  This is not appropriate for every software project, but it has its benefits in certain circumstances. Altogether, the pipeline is used to improve the software development process for DevOps teams and deliver quick product changes to customers without losing quality.

### Sources:

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
* [Blog: A Guide to CI/CD Tools -- By Jetbrains](https://www.jetbrains.com/teamcity/ci-cd-guide/ci-cd-tools/)
* [Blog: Testing stages in continuous integration and continuous delivery -- By AWS](https://docs.aws.amazon.com/whitepapers/latest/practicing-continuous-integration-continuous-delivery/testing-stages-in-continuous-integration-and-continuous-delivery.html)
