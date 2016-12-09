SSH
---

#### Add ssh key

> cat ~/.ssh/[KEY_NAME].pub | ssh [USER]@[HOST] "mkdir -p ~/.ssh && cat >> ~/.ssh/authorized_keys"

#### Copy ssh key
> cat ~/.ssh/[IDENTITY].pub | pbcopy

#### List identities
> ssh-add -l

#### Add identity if not listed
> ssh-add ~/.ssh/identity
