# ECS Digital open source policy


ECS Digital firmly believes in producing and contributing to open source software. Not only does it encourage scrutiny on and improvements to the code we write, it also is good for the brand and our engineers. With this in mind we’ve tried to produce some guidelines to help decide if you can open source a project, and some of the practicalities of how.

## Can I open source?

* Is this code written for or on-behalf of a client?
    * Are they paying us to write this software? We need to get explicit agreement from them that they are happy to open source
  
    * If it is a fixed-price engagement is there a high-level contract or agreement with the client which might affect what we can do with code we write for them?
  
* Is this code part of a project from which ECS expects to make money?
    * Get agreement from the Project Manager / Delivery lead that we can open source it
  
* Code being written in catch up weeks or during self-development
    * Discuss with your line manager or practice lead


## I'm happy it's ok - what next?

First make sure you have a good quality README guide in README.md in the root of your repository

### Licensing

Use an appropriate license - we use [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
Make sure this is in a file called LICENSE in the root of your project in GitHub

![apache 2.0 license summary](https://i1.wp.com/researchenterprise.org/wp-content/uploads/2016/09/github-apache.jpg)

### Contributors

See below for guidance on contributions, whatever is decided must be documented in a file called CONTRIBUTING.MD in the root of the repository. [More guidance here](https://help.github.com/en/articles/setting-guidelines-for-repository-contributors)

There are several models to consider here, it's worth thinking about these questions:
  
  * Do you welcome people outside of our company to contribute code? If so, think about how you are going to support this:
    * Do you want them to commit to branches and raise pull requests?
    * How can approve merging back to master? 
    * What quality checks need to be set up to validate?

  Either way, you'll have to configure your repository in GitHub to support your desired model.

  Most of this configuration is achieved in the Branch Protection rule setup on the repository: https://help.github.com/en/articles/configuring-protected-branches


Further reading on Open Source contributions: https://github.com/todogroup/guides/blob/master/participating-in-open-source.md

### Code Owners
Set up a CODEOWNER file to define who is responsible for quality maintainence of the repository. This can also help to work out who is responsible for PRs and issues. More detail here: https://help.github.com/en/articles/about-code-owners



### Commit your code

Create the repository on the Public ECS Digital GitHub https://github.com/ecsdigital and commit/push your code.

## What next?
Publisise your repository if you want people to have a look and contribute, depending on what you've open sourced this might be on the ECS Slack and/or externally

Keep an eye on the repo and any pipelines you've configured and be prepared to help out people that want to contribute