<p align="center">
 <img width="100px" src="https://avatars.githubusercontent.com/u/101950250?s=200&v=4" align="center" alt="Legendary Octo Journey" />
 <h3 align="center">Technical Interview Solution</h3>
 <h3 align="center">Made for :octocat: with :heart: + :coffee:</h3>
</p>
  <p align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats/actions">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
    <a href="https://codecov.io/gh/anuraghazra/github-readme-stats">
      <img src="https://codecov.io/gh/anuraghazra/github-readme-stats/branch/master/graph/badge.svg" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/anuraghazra/github-readme-stats?color=0088ff" />
    </a>
    <br />
    <br />
    <a href="https://a.paddle.com/v2/click/16413/119403?link=1227">
      <img src="https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20%E2%86%92-gray.svg?colorA=655BE1&colorB=4F44D6&style=for-the-badge"/>
    </a>
    <a href="https://a.paddle.com/v2/click/16413/119403?link=2345">
      <img src="https://img.shields.io/badge/Supported%20by-Node%20Cli.com%20%E2%86%92-gray.svg?colorA=61c265&colorB=4CAF50&style=for-the-badge"/>
    </a>
  </p>

  <p align="center">
    <a href="#demo">View Demo</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Report Bug</a>
    ·
    <a href="https://github.com/anuraghazra/github-readme-stats/issues/new/choose">Request Feature</a>
  </p>
  <p align="center">
    <a href="/docs/readme_fr.md">Français </a>
    ·
    <a href="/docs/readme_cn.md">简体中文</a>
    ·
    <a href="/docs/readme_es.md">Español</a>
    ·
    <a href="/docs/readme_de.md">Deutsch</a>
    ·
    <a href="/docs/readme_ja.md">日本語</a>
    ·
    <a href="/docs/readme_pt-BR.md">Português Brasileiro</a>
    ·
    <a href="/docs/readme_it.md">Italiano</a>
    ·
    <a href="/docs/readme_kr.md">한국어</a>
    .
    <a href="/docs/readme_nl.md">Nederlands</a>
    .
    <a href="/docs/readme_np.md">नेपाली</a>
    .
    <a href="/docs/readme_tr.md">Türkçe</a>
  </p>
</p>

# Table of Contents

- [Customer scenario](#customer-scenario)

# Customer scenario

Let’s take a look at the customer scenario: "Our security team is asking for help ensuring proper reviews are being done to code being added into our repositories. We have hundreds of repositories in our organization. What is the best way we can achieve at scale? We are new to some of the out-of-the-box settings and the GitHub API. Can you please help us create a solution that will accomplish this for our security team?"

## Background knowledge and assumptions

- You can create and use a new GitHub repository to develop and present the solution
- Assume you are the named GitHub contact for the customer. You will build and present the example to the customer
- GitHub has more than one API interface along with API libraries. Be prepared to explain the hows and whys in your design
- Technical guidance: Organization events and protected branches are useful features to help drive your solution. Also, don’t forget to check the GitHub Docs
- The first branch in a new GitHub repository will be created once a commit has been made. One idea is to have a README created with each new repository, so that the first branch is created
- Documentation is highly valued at GitHub

## Solution requirements

We are most interested in your approach, the mindset you apply, and how the solution is presented to your customer. The technical solution to accomplish this is to listen for organization events to know when a repository has been created. When the repository is created, please automate the protection of the default branch. Notify yourself with an @mention in an issue within the repository that outlines the protections that were added.

## Some things you will need

- A GitHub account
- An organization (you can create one for free)
- A repository to store your solution/presentation. We will look at this together in our next conversation
- A component that listens for webhook deliveries. We don’t require a specific technology/runtime, use languages and tools you are already familiar with We strongly recommend using languages and tools you are already familiar with.
- A README.md file in your web service's repository that documents how to run and use your solution. 

## Challenge delivery

Please use the Greenhouse link in this email to submit the web address of your GitHub org for the solution you created upon completion. If you make the repository public our team members can view the repository.

## Attribution

Feel free to use existing resources to complete this task. If you use external resources please note them in the README of your repository. Let me know if you have any questions.
