Proof of Concept (PoC) for [MSKINS-234](https://issues.apache.org/jira/browse/MSKINS-234)

Prerequisites:
- git
- Java 11 or 17
- maven 3.8.1 or higher

1. `git checkout jenkins-2.375.3` (Checkout the tag)
2. `cd core/`
3. `mvn --show-version --batch-mode -DgenerateProjectInfo=false -DgenerateSitemap=false -e clean site:site`

Open the file `core/target/site/index.html` in a browser.
