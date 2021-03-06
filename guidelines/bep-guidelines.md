# Open Babel Enhancement Proposals (BEP) Guidelines

## Problem
Enhancements to the Open Babel API, including revisions and backwards-incompatible work are not indexed in a central location.
Some discussion occurs on the mailing list, some on pull requests, some in issues.

## Proposed Enhancement

Open Babel Enhancement Proposals will be used when presenting changes or additions to the API, especially anything causing API breaks.

The format of this README is itself a BEP and can be duplicated for the creation of further BEPs.

## Detail Explanation

### BEP Titles

Babel Enhancement Proposals will be submitted with a title that is no longer than 12-words long. A BEP is uniquely identified by its title and the pull request number associated with it.

### BEP Labels

The pull-request submitted with each BEP will be labeled with the following labels for easy searching:
* `accepted` — this BEP has been accepted and is currently being implemented
* `implemented` — this BEP has been implemented
* `rejected` - this BEP has been rejected and will not be implemented
* `withdrawn` - this BEP has been withdrawn by the submitter but can be re-submitted if someone is willing to champion it
* `active` - this BEP is currently under active discussion within the community

### BEP Structure

When submitting an enhancement proposal, individuals will include the following information in their submission.

1. The problem that this enhancement addresses. If possible include code or anecdotes to describe this problem to readers.
2. A brief (1-2 sentences) overview of the enhancement you are proposing. If possible include hypothetical code sample to describe how the solution would work to readers.
3. A detailed explanation covering relevant algorithms, data structures, an API spec, and any other relevant technical information
4. A list of pros that this implementation has over other potential implementations.
5. A list of cons that this implementation has.
6. A list of individuals who would be interested in contributing to this enhancement should it be accepted.

### BEP Submission Process
1. Create a [Markdown](https://help.github.com/articles/github-flavored-markdown/) write up of the problem, proposed enhancement, detailed technical explanation, pros and cons, and interested contributors of the enhancement you are proposing.
2. Create a fork of this repository.
3. Create a folder with its name set to the BEP title in lower snake-case.
3. Place the markdown file created in step 1 and any supplemental materials in that folder.
4. Submit a pull request to the main repository with your BEP.
5. Once your PR is accepted, it will be labeled `active` per the guidelines above.
6. Your BEP will be added to the BEP Index file in this repository.

## Pros and Cons

Pros associated with this implementation include:
* A higher quality discussion around enhancement proposals
* Individuals are encourage to put more thought into an enhancement proposal before submitting it
* Precedence exists in the form of PEPs (Python Enhancement Proposals) and IPEPs (IPython Enhancement Proposals)

Cons associated with this implementation include:
* Discussion will occur on GitHub rather than on the openbabel-devel mailing list.

## Interested Contributors
@ghutchis
