Proof of Concept (PoC) for [MSKINS-234](https://issues.apache.org/jira/browse/MSKINS-234)

1. `git checkout jenkins-2.401.1` (Checkout the tag)
2. `cd core/`
3. `mvn --show-version --batch-mode -DgenerateProjectInfo=false -DgenerateSitemap=false -e clean site:site`

Open the file `core/target/site/index.html` in a browser.
