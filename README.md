# learn-go-with-tests

The purpose of this repo is to complete the learn-go-with-test course located [here](https://quii.gitbook.io/learn-go-with-tests/).

I am also interested in learning how to automate semantic versioning of a repo and plan on using SemVer and GitFlow to work on the repo ad GitHub Actions to automate the artifact building of the repo. 

- The artifacts produced will be tarballs of the source code. They will be uploaded to Github. 
- Eventually the artifacts produced will be binary executables created with go build.
- Releases will be automated so that:
  - release branches will auto generate pre-releases on Github
  - merging into master from a release branch and tagging the release version will auto generate a release on Github
- Versioning will be automated using a Github action.
  - [GitVersion](https://gitversion.net/)
  - [GitTools GitVersion Action](https://github.com/marketplace/actions/gittools)