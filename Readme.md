Related links:
[Red Hat Best Practices for Kubernetes,Repo](https://github.com/redhat-best-practices-for-k8s/guide)

[Red Hat Best Practices for Kubernetes,Generated](https://redhat-best-practices-for-k8s.github.io/guide/#k8s-best-practices-foreword)

[Red Hat Best Practices Test Suites](https://redhat-best-practices-for-k8s.github.io/certsuite/)

[Michae's presention deck](https://docs.google.com/presentation/d/1wDxmmKZ09RM8Oa6dCQkL902GiTvKRGhh-duY7MdJHkQ/edit?usp=sharing)


Workflow:
1. Michael is the point of contact. He injests new/update best practice. Then he creates a diff document
2.  We take the new/update requirement and compare to our existing test, if there are add/updates then we will create jira tickets
2.  the catalog gets rebuilt after we add/update testcases
3.  we use their release version for our jira epic for that document
4.  The catalog is [generated using makefile](https://github.com/redhat-best-practices-for-k8s/certsuite/blob/main/Makefile#L101)


Other projects
1. [builds and publishes the certsuite-probe image](https://github.com/redhat-best-practices-for-k8s/certsuite-probe)
2. [Offline Catalog Tool for Red Hat's certified containerized artifacts to do offline queries](https://github.com/redhat-best-practices-for-k8s/oct)
Get the minimun requirements from pixies[ click here](https://github.com/redhat-best-practices-for-k8s/oct/blob/main/pkg/certdb/onlinecheck/onlinecheck.go#L42)
3. create clusters

Good to have:
* Security check
* Architecture diagram


Testing Clusters:
* On prem

Release notes:

1. Go to the release pages. [Example of the release notes](https://drive.google.com/file/d/1QY75vHs_BqHTCUy-KbJSQ7KUQ-v5G0zx/view?pli=1)
2. Draft a new release. Currently supports [2 architecture](https://github.com/redhat-best-practices-for-k8s/certsuite/blob/main/.github/workflows/tnf-image.yaml#L249).

