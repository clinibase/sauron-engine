# Bot identity smoke test

Throwaway file. Verifies that the two Clinibase agent identities can clone,
commit, push, open a pull request and comment, and that GitHub attributes each
action to the right identity.

| | Clive | Alebot |
|---|---|---|
| App | `clinibase-clive` | `clinibase-alebot` |
| Commits as | `Clive <clive@clinibase.com>` | `Alebot <alessandro.biavati+alebot@clinibase.com>` |

This commit was made by Clive.

This second commit was made by Alebot.

Third commit: Clive using the bot noreply address.

Fourth commit: Alebot using the bot noreply address.
