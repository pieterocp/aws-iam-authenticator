
## Add Release Notes Here


## Release Checklist

### Pre Pull Request

* [] Has the makefile version been bumped?
* [] Has the changelog been update?
* [] Has the image version in `deploy/example.yaml` been bumped up?

## Post Merge Checklist

* [] Has GoReleaser been run?
* [] Are the checksums, binaries and source code in the assets of the release?
* [] Have the images been published in the ECR registry?

## Post Release Checklist

* [] Has a new PR been created to update the ECR images in `deploy/example.yaml`?
* [] Has this PR been merged?
