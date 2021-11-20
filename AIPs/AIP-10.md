---
AIP: 10
Title: Draft directory in `agora` repository
Author: Yun Park (@hanlsin)
Status: Final
Category: Agora
Created: 2021-03-16
---

# AIP-10: Draft directory in `agora` repository

## Description

It is ambiguous and difficult that a proposer decides AIP number. AIP number could be duplicated among requested Pull Requests (PRs), and reviewing/voting process also could be taken a long time before deciding AIP.

Additionally, a proposer may want to discuss a subject before proposing. Of course, it might be better to use some other tools such as reddit, telegram, discord, etc., but PR could be an option among them. It will be difficult to decide the number by a proposer only for suggestions or subjects.

I am suggesting creating a draft directory storing AIP candidates excluding AIP number. These candidate documents will be moved in the `AIPs` directory when they are ready to propose and be selected. But, non-chosen proposals don't need to store in the repository, because they would be retained by Github as closed PRs.

## License
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
