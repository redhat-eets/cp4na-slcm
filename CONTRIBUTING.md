# Contributing

All contributions are valued and welcomed, whether they come in the form of code, documentation, ideas or discussion.
While we have not applied a formal Code of Conduct to this, or related, repositories, we require that all contributors
conduct themselves in a professional and respectful manner.

## Workflow

The suggested workflow for making a contribution is to branch from `dev` for development and create a Merge Request back
to `dev` when a change is complete. This is well documented elsewhere but to summarise:

1. Create a branch from `dev`. Name it something meaningful and include your initials.
1. Make and test the change on your branch.
1. Submit a Merge Request asking for the change to be merged into the `dev` branch.

All contributions should have as much test coverage as possible and include relevant additions and changes to both
documentation and tooling.

Once a change is implemented, tested, documented, and passing all checks then submit a Merge Request for it to be
reviewed.

**Do not commit directly to `main` or `dev` branches.**

## Peer review

At least one other project member **must** approve a Merge Request prior to it being merged. No Self Review is allowed.

All project contributors are strongly encouraged to review Merge Requests. Everyone is responsible for the quality of
what is produced, and review is also an excellent opportunity to learn.

## Commits

A good commit does a **single** thing, does it completely, concisely, and describes **why**.

The commit message should explain both *what* is being changed and, in the case of anything non-obvious, *why* that
change was made. Commit messages are something that has been extensively written about so need not be discussed in more
detail here but contributors should follow [these seven rules](https://chris.beams.io/posts/git-commit/#seven-rules) and
keep individual commits focussed.

## Merge Requests

A good Merge Request is the same; it also does a single thing, does it completely, and describes **why**. The difference
is that a Merge Request may contain one or more commits that together prepare for and deliver a feature.

How to (re)structure commits to create a clear and understandable set of changes is outside the scope of this document
but there are [many](https://thoughtbot.com/blog/autosquashing-git-commits)
[guides](https://git-scm.com/docs/git-rebase) and [approaches](https://nuclearsquid.com/writings/git-add/) for how to do
it.

## Style Guidelines

- Favour readability over brevity in both naming and structure
- Document the **why** with comments, and the **what** with clear code
