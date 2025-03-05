# Planning Document

## Static Site Generator Selection, March 2025
We want to take these documents and eventually create a site at stl-polyglot-programmers.com using a static site generator.
We need to decide which one to go with.

What we'll do is make a list of possible candidates, then do a vote once we have the list.
As of writing this document, 2025-03-05, we will gather suggestions until the end of the month, 2025-03-31.
Please make PRs to this document for your suggestions.

### Requirements
- Works with GitHub Pages and/or Actions
- Works with markdown files
- Support for custom themes

### Suggestions

#### Hakyll

*Quick Look*

  - [Hakyll home page](https://jaspervdj.be/hakyll/)
  - [Example: haskell.org](https://github.com/haskell-infra/www.haskell.org)
  - [Example: effective-haskell.com](https://github.com/rebeccaskinner/effective-haskell.com)

*Pros*

  - Existing examples of static sites with deployment automation using github actions
  - Existing examples of local development and testing workflows with and without nix
  - Supports custom styles and templates
  - Pandoc support
  - Easily customizable
  - Very low maintenance; the vast majority of content and style changes do not require code changes

*Cons*

  - No existing examples of a CI pipeline that deploys to netifly
  - No pre-built templates (unless you borrow from existing open source websites)
  - Haskell is less widely known than other languages, which could discourage contributions even though it's not required for content changes
