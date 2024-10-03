# Release pipelines

I worked at reorganizing and restructuring release pipelines for [kaytu CLI](https://github.com/kaytu-io/kaytu). I  modified the [main workflow](https://github.com/kaytu-io/kaytu/blob/main/.github/workflows/main.yaml) to be portable and efficient. 

I noticed that the CLI used goreleaser for building and distributing the binaries. I updated the [goreleaser configuration](https://github.com/kaytu-io/kaytu/blob/main/.goreleaser.yml) for distributing it to the homebrew tap. I later added the `nfpms configuration` to release `rpm` and `deb` binaries.

