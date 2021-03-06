# Project info

# [Aragon Monthly](https://monthly.aragon.one/)

### Aragon Monthly is **a community curated monthly digital newspaper about Decentralized Autonomous Organizations** and the [Aragon](https://aragon.one) ecosystem

> **Content curation is the process of gathering information relevant to a particular topic or area of interest.**

Aragon Monthly is **created by the community, for the community**.

**Anyone can contribute** by creating or requesting new content about DAOs and anything related to the Aragon ecosystem.
___
## How does this work?

- **Community members**, [**Contributors**](../contributors/contributors.md) and [**Editors**](../contributors/editors.md) create [Issues](https://github.com/aragon/aragon-monthly/issues) for [News](../news/index.md), [Articles](../articles/index.md) and [Classifieds](../classifieds/index.md)
    - _These [Issues](https://github.com/aragon/aragon-monthly/issues) are **requests for new content** to the upcoming newspaper issue_
    ___
- [Issues](https://github.com/aragon/aragon-monthly/issues) that get "_upvoted_" by the community **get added a [`bounty` label](https://github.com/aragon/aragon-monthly/labels/bounty)** and that **`bounty`** will be **funded to incentivise fulfillment of that request**
    - _Editors can also add the `bounty` label to any [Issue](https://github.com/aragon/aragon-monthly/issues) they consider to be interesting content_
        - _The person who created the [Issue](https://github.com/aragon/aragon-monthly/issues) may also request the [`bounty` label](https://github.com/aragon/aragon-monthly/labels/bounty) to be added if they wish to fund that Issue themselves_
    - _Once a bounty label has been added, **anyone** can send funds (ETH or ERC20 tokens) to the smart contract and help fund that bounty_
    ___
- **Anyone can contribute** to creating the requested content on [Issues](https://github.com/aragon/aragon-monthly/issues) **by creating a new [Pull Request](https://github.com/aragon/aragon-monthly/pulls)** that fills the request
    - _By creating a new [Pull Request](https://github.com/aragon/aragon-monthly/pulls) that `Closes issue #X`, **anyone is free to claim the bounty on that Issue**_
        - _These will be reviewed on a first-come first-served basis_
    - _**Editors** are community members that frequently contribute high quality content and **have priority over other contributors**. They can **assign themselves** to [Issues](https://github.com/aragon/aragon-monthly/issues) in order to signal their intent to fulfill that particular Issue_
    ___
- At the end of the month, [Pull Requests](https://github.com/aragon/aragon-monthly/pulls) are frozen and any open [Issues](https://github.com/aragon/aragon-monthly/issues) are cleaned
    - Editors will evaluate open [Issues](https://github.com/aragon/aragon-monthly/issues) to see if they think it should be carried over to the next newspaper issue and close all remaining ones
    - Reviewers and Editors will review all open [Pull Requests](https://github.com/aragon/aragon-monthly/pulls) and either merge or close those accordingly
    - The [Editor-in-chief](#staff-contributors) makes sure that all completed [Pull Requests](https://github.com/aragon/aragon-monthly/pulls) are merged, compiles the Front Page and ensures that everything is working fine, publishes the Monthly newspaper issue to [https://monthly.aragon.one/](https://monthly.aragon.one/) and sends out the Aragon Monthly Newsletter
___
## How can I contribute?
### By creating new content
There's a few different ways to contribute new content:
  ___
**News**

There's news happening all the time and we're looking to have all the interesting content presented in the newspaper!

- [Submit a Pull Request](https://github.com/aragon/aragon-monthly/pulls) with the News content and wait for it to be reviewed and merged!
    - Make sure your [Pull Request](https://github.com/aragon/aragon-monthly/pulls) follows
        - [Guide for submitting a new Pull Request](../guides/guide_for_submitting_a_new_pull_request.md)
        - [Guide for submitting News](../guides/guide_for_submitting_news.md)
  ___

**Articles**

- If you feel like **writing about a topic that someone else has requested to read about in [Issues](https://github.com/aragon/aragon-monthly/issues)**
    - Create the content
    - [Submit a Pull Request](https://github.com/aragon/aragon-monthly/pulls) to close the Issue and wait for it to be reviewed and merged!
        - Make sure your [Pull Request](https://github.com/aragon/aragon-monthly/pulls)
            - Fills the requested [Issue](https://github.com/aragon/aragon-monthly/issues) and follows
            - [Guide for submitting a new Pull Request](../guides/guide_for_submitting_a_new_pull_request.md)
            - [Guide for submitting Articles](../guides/guide_for_submitting_articles.md)
___
- If you want to contribute **fresh, original, new content for the newspaper**
    - Open a [new Issue](https://github.com/aragon/aragon-monthly/issues/new) describing the kind of content you wish to contribute
    - Create the content
    - [Submit a Pull Request](https://github.com/aragon/aragon-monthly/pulls) to close the Issue you opened and wait for it to be reviewed and merged!
        - Make sure your [Pull Request](https://github.com/aragon/aragon-monthly/pulls) follows
            - [Guide for submitting a new Pull Request](../guides/guide_for_submitting_a_new_pull_request.md)
            - [Guide for submitting Articles](../guides/guide_for_submitting_articles.md)
  ___
### By requesting new content
If you have a topic that you would like to either read about, create a [New Issue](https://github.com/aragon/aragon-monthly/issues/new) with a descriptive Title and a clear description of the type of content you would want to see in Aragon Monthly.

Be sure to include all the details in the new [Issue](https://github.com/aragon/aragon-monthly/issues) as described in the [Guide for submitting a new Issue](../guides/guide_for_submitting_a_new_issue.md)
___
## How do I run a local version of the site for editing?

- Install [MkDocs](http://www.mkdocs.org/)
  - Install mkdocs-material using Python, `pip install mkdocs-material`
- In the `aragon-monthly` directory, run `mkdocs serve`
- Open [http://localhost:8000/](http://localhost:8000/) in your browser
___
## Staff Contributors
> Editor-in-chief is the publication's editorial leader who has final responsibility for its operations and policies.

- Editor-in-chief - [@Smokyish](https://github.com/Smokyish)

> Editors are people that regularly provide content to the publication and make sure that the content is always high quality. They write articles, review [Pull Requests](https://github.com/aragon/aragon-monthly/pulls) and are generally active in the creation of this publication.

- Editor - [@john-light](https://github.com/john-light)

> Reviewers are people who contribute by helping review new content submitted via [Pull Requests](https://github.com/aragon/aragon-monthly/pulls)

- Reviewer: [@lkngtn](https://github.com/lkngtn)
- Reviewer: [@izqui](https://github.com/izqui)

> Columnists are people dedicated to contribute quality content for an extended time, usually on the same subject area or theme each time – that typically contains the author's opinion or point of view.

- Editor/Reviewer/Columnist - _Get your name here by contributing!_
___
## Future goals

- Make Aragon Monthly so successful that there's a demand for Aragon Weekly
- Turn Aragon Monthly into a DAO that fully governs the project
