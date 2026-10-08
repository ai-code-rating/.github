# AI Code Rating

**Three simple characters that tell a reader who maintains a project, how much of its code is written by AI, and how closely a human checks the AI's work.**

[![ACR A2b](https://img.shields.io/badge/ACR-A2b-2140B5)](https://aicoderating.com)

A project publishes its rating in an `ACR.md` file at the root of its repository. **ACR A2b**, for example, means:

| Position | Measures | `A2b` |
|---|---|---|
| 1 | **Maintainer Expertise**: who approves the code, `A` (expert) to `E` (non-programmer) | `A` Expert |
| 2 | **AI Share**: how much of the code AI wrote, `0` (none) to `4` (76–100%) | `2` 26–50% |
| 3 | **Oversight**: how closely a person checked the AI's work, `a` (verified) to `e` (unchecked) | `b` Reviewed |

The rating doesn't judge whether using AI is good or bad. It tells readers how the code was made, so they can decide what it means for them.

## Rate Your Project

1. [Get your rating](https://aicoderating.com/#rate): answer three questions and copy the `ACR.md` and README badge.
2. Add `ACR.md` to the root of your repository.
3. [Check the file](https://aicoderating.com/validate/) with the validator.
4. Add the [GitHub Action](https://github.com/ai-code-rating/action) to check it on every push and pull request.
5. [Ask to be listed](https://github.com/ai-code-rating/aicoderating.com/issues/new?template=add-project.yml) in [Rated Projects](https://aicoderating.com/#rated) on the site.

Not sure which levels fit? The [rating examples](https://aicoderating.com/examples/) cover common setups, and the [FAQ](https://aicoderating.com/faq/) covers the edge cases.

## Repositories

- [aicoderating.com](https://github.com/ai-code-rating/aicoderating.com): the website and the [spec](https://aicoderating.com/spec/).
- [action](https://github.com/ai-code-rating/action): a GitHub Action that checks `ACR.md` against the spec.

## Get Involved

The spec is a draft, and feedback now shapes version 1.0. [Open an issue](https://github.com/ai-code-rating/aicoderating.com/issues/new/choose) to suggest a change or ask a question, or read the [contributing guide](https://github.com/ai-code-rating/aicoderating.com/blob/main/CONTRIBUTING.md). Everyone taking part is expected to follow the [code of conduct](https://github.com/ai-code-rating/aicoderating.com/blob/main/CODE_OF_CONDUCT.md).

The spec is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), and the code for the site and the Action under MIT.
