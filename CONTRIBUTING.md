Guideline for Contribution
---

First of all, thank you for taking your time to contribute!
Since I am just an end user of Atom, not a CoffeeScript expert, your help is indispensable to make this package better.

<p align="center">
<b><a href="#reporting-issue">Reporting Issue</a></b>
|
<b><a href="#submitting-pull-request">Submitting Pull Request</a></b>
|
<b><a href="#naming-scheme">Naming Scheme</a></b>
</p>

### Reporting Issue
Please make sure to search for existing issues including those closed before posting a new one.
If there are no duplicates, then please include the following information in your issue:

- OS on which you are running Atom
- Atom version
- Package version
- Syntax theme in use and its version
- Code example that replicates your problem
- Difference between expected and actual result

Regarding the code example, please __post it at least as a text__.
You can of course attach a screenshot of how your snippet looks, but copy-and-pastable text helps me easily test your issue.
<p align="right"><a href="#top">⇧</a></p>

### Submitting Pull Request
If you are willing to contribute with codes, why don't you submit a pull request?

#### Making your change
Clone your fork and make a symlink in `~/.atom/packages` with

```bash
apm uninstall language-tex # if you already have it installed
git clone git@github.com:YOUR_USERNAME/language-tex.git
cd language-tex
apm link .
```

Now, you are almost ready to start coding, but please __do not add your change in `master` branch__.
Create a new one with a comprihensible name describing your change.
Your `master` should be kept for syncing with the upstream `master` so that your pull request will not have conflicts with the base branch.

#### Git commit message

- Use imperative mood.
- Start every line with an uppercased letter.
- Summarize the change in the first line with 50 characters or less.
- Do not end the summary line with a period.
- Make a blank line after the summary if the commit has body text.
- Wrap the body at 72 characters or less.

<p align="right"><a href="#top">⇧</a></p>

### Naming Scheme
Under construction.

<p align="right"><a href="#top">⇧</a></p>
