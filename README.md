# cookesan

I build small open-source tools around setup docs, CI, and first-run
reliability.

Current focus:

- [SetupProof](https://github.com/setupproof/setupproof), a CLI and GitHub
  Action that tests explicitly marked README quickstarts from a clean
  workspace.
- GitHub Advisory Database metadata cleanup: small, reviewable fixes for
  package versions, references, and vulnerability record quality.
- Maintainer-friendly docs and CI changes that are easy to audit.

```sh
go install github.com/setupproof/setupproof/cmd/setupproof@v0.1.3
```

Recent open-source work:

- [setupproof/setupproof#56](https://github.com/setupproof/setupproof/pull/56):
  verified native Windows workspace and report compatibility.
- [nodejs/node#63003](https://github.com/nodejs/node/pull/63003): exposed
  writable stream state on HTTP/2 compatibility responses.
- [diesel-rs/diesel#5044](https://github.com/diesel-rs/diesel/pull/5044):
  removed accidental MySQL time serializer debug output.
- [librosa/librosa#2006](https://github.com/librosa/librosa/pull/2006):
  documented `specshow` frequency-axis scaling.
- [beetbox/beets#6586](https://github.com/beetbox/beets/pull/6586):
  corrected MusicBrainz `extra_tags` default documentation.
- [audacity/audacity#10797](https://github.com/audacity/audacity/pull/10797):
  fixed an `.editorconfig` property typo.
- [RogueOneEcho/caesura#228](https://github.com/RogueOneEcho/caesura/pull/228):
  clarified Docker path handling in docs.

I try to keep public work small, tested, and easy for maintainers to review.
