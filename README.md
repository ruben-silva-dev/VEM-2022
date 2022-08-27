# Empirical investigation of the influence of continuous integration bad practices on software quality

## Abstract
Continuous Integration (CI) is a powerful tool to leverage software development in a safe, reliable, and efficient way. However, in day-to-day of software development, bad habits can arise in working with CI, which can make CI not reach its full potential in projects. These bad habits we call CI bad practices. This paper presented an exploratory study on closed-source projects to investigate how CI bad practices can affect software quality. We observe (1) the impact on the quality internal attributes after the implantation of CI, (2) the evolution of software quality indicators over time, and (3) the bad practices considered most harmful to the software quality by the development teams. Our results mean that projects affected by CI bad practices will not necessarily have their quality impaired. However, this does not mean that quality will be maintained or improved over time. Our analysis of the quality indicators has allowed us to observe that, generally, they have remained stable, and the number of quality issues reported has not decreased considerably either. Finally, the quality indicator most affected by the CI bad practices was maintainability, followed by reliability and security. In addition, the vast majority of the bad practices analyzed were classified as having a medium level of effort for resolution. In this sense, we also classify bad practices according to the level of effort/impact on the quality that can help prioritize their resolution.

## Artifacts

| Artifact  |  Description  |
| ------------------- | ------------------- |
|  [S1 - Before CI](artifacts/s1-before-ci.csv) | Values of the internal attributes of S1 before CI implementation |
|  [S1 - After CI](artifacts/s1-after-ci.csv) | Values of the internal attributes of S1 after CI implementation |
|  [S2 - Before CI](artifacts/s2-before-ci.csv) | Values of the internal attributes of S2 before CI implementation |
|  [S2 - After CI](artifacts/s2-after-ci.csv) | Values of the internal attributes of S2 after CI implementation |
|  [S4 - Before CI](artifacts/s4-before-ci.csv) | Values of the internal attributes of S4 before CI implementation |
|  [S4 - After CI](artifacts/s4-after-ci.csv) | Values of the internal attributes of S4 after CI implementation |
|  [S6 - Before CI](artifacts/s6-before-ci.csv) | Values of the internal attributes of S6 before CI implementation |
|  [S6 - After CI](artifacts/s6-after-ci.csv) | Values of the internal attributes of S6 after CI implementation |
|  [S8 - Before CI](artifacts/s8-before-ci.csv) | Values of the internal attributes of S8 before CI implementation |
|  [S8 - After CI](artifacts/s8-after-ci.csv) | Values of the internal attributes of S8 after CI implementation |
|  [Main Python File](artifacts/main.py) | Main file of the python script for collecting the quality indicators |
|  [Calc Python File](artifacts/calc.py) | File responsible for calculating the values of the quality indicators |
|  [Questionnaire Answers](artifacts/answers.csv) | Raw values of the answers from the members of the development teams of the analyzed systems |
|  [Impact on Quality Indicators](artifacts/quality-indicators-impact.csv) | Summary of the analysis of the impact of CI bad practices on quality indicators |
|  [Resolution Difficulty](artifacts/resolution-difficulty.csv) | Summary of the analysis of difficulty in resolving CI bad practices |
|  [Impact versus Resolution Difficulty](artifacts/impact-vs-difficulty.csv) | Summary of the CI bad practice resolution prioritization analysis based on impact and difficulty of resolution |