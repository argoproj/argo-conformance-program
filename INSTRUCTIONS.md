# How to submit conformance results

## The Tests
..

## Running Tests

## Submitting Results
Open PR ...

### Contents of PR
```
$project/vX.Y/$offering/README.md
$project/vX.Y/$offering/e2e.log
$project/vX.Y/$offering/PRODUCT.yaml
```

#### README.md
Contacts instructions for how to reproduce the test result, including how to obtain the offering. e.g. offering-cli create argo-cd etc.

#### e2e.log
Contains the logs from running tests.

#### PRODUCT.yaml
| Field | Description | 
|--|--|
| `vendor` | Name of the legal entity certifying. |
| `name` | Name of the product offering certifying |
|`version`|The version of the product being certified, (not the Argo project version it runs).|
|`website_url`|URL to the product information|
| `repo_url` | If your product is open source, this field is necessary to point to the primary GitHub repo containing the source. It's OK if this is a mirror. OPTIONAL |
| `documentation_url` | URL to product documentation |
| `product_logo_url` | URL to the product's logo, (must be in SVG, AI or EPS format -- not a PNG -- and include the product name). OPTIONAL. If not supplied, we'll use your company logo. Please see logo [guidelines](https://github.com/cncf/landscape#logos) |
| `type` | Is your product a distribution, hosted platform, or installer |
| `description` | One sentence description of your offering |

### Private Review
Private review is available for unreleased products. Review will be open to all [Argo Project maintainers](https://github.com/argoproj/argoproj/blob/master/MAINTAINERS.md).

## Issues
...