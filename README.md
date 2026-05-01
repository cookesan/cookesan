# cookesan

I build small open-source tools around setup docs, CI, and first-run
reliability.

Current project:
[SetupProof](https://github.com/setupproof/setupproof), a CLI and GitHub
Action that tests explicitly marked README quickstarts from a clean workspace.

```sh
go install github.com/setupproof/setupproof/cmd/setupproof@v0.1.0
```

Recent open-source work:

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
