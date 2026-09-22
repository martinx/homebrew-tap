# martinx/homebrew-tap

```sh
brew install martinx/tap/handrail
```

[Handrail](https://handrail.bitey.ai): policy packs for coding agents — enforced where the agent
allows it, honest where it doesn't.

`Formula/handrail.rb` is updated automatically by the
[release workflow](https://github.com/martinx/handrail/blob/main/.github/workflows/release.yml)
of `martinx/handrail`. Do not edit it by hand.

For enforced policy, prefer the install script, which installs to the root-owned
`/usr/local/bin` (the Homebrew prefix is writable by your user):

```sh
curl -fsSL https://handrail.bitey.ai/install.sh | sh
```
