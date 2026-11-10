# grokbot-template-context

Grok Bot builds the templates of its computers on Tenki. A typed template of Tenki builds only with a Git context. This
repository is that context. It has only this file.

- The builder checks out this repository at `/home/tenki/app`, at a pinned commit.
- The steps of a template do not use these files.
- A build reads this repository with no token, so it must stay public.

Do not add code, data, or secrets to this repository.
