# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.2.0 (2023-06-22)

### New Features

 - <csr-id-e4a77aab6ba47b7e89d1f020ea500ea7ae057ffe/> Allow turning a `Graph` into the underlying map.
   The map associates commit ids with data.

### Changed (BREAKING)

 - <csr-id-f4b0195375db31cc2736fcab9665a0dc2637e74b/> Remove custom `graph::CommitterTimestamp` in favor of `gix-date::SecondsSinceUnixEpoch`.
   After all, these are meant to be the same.

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 8 commits contributed to the release over the course of 11 calendar days.
 - 12 days passed between releases.
 - 2 commits were understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Prepare changelogs prior to release ([`18b0a37`](https://github.com/Byron/gitoxide/commit/18b0a371941aa2d4d62512437d5daa351ba99ffd))
    - Merge branch 'corpus' ([`aa16c8c`](https://github.com/Byron/gitoxide/commit/aa16c8ce91452a3e3063cf1cf0240b6014c4743f))
    - Change MSRV to 1.65 ([`4f635fc`](https://github.com/Byron/gitoxide/commit/4f635fc4429350bae2582d25de86429969d28f30))
    - Merge branch 'gix-revision-graph' ([`036e60a`](https://github.com/Byron/gitoxide/commit/036e60a3ad39ba9b018c0b56454f12fad455c7bb))
    - Allow turning a `Graph` into the underlying map. ([`e4a77aa`](https://github.com/Byron/gitoxide/commit/e4a77aab6ba47b7e89d1f020ea500ea7ae057ffe))
    - Merge branch 'future-dates' ([`8d2e6a9`](https://github.com/Byron/gitoxide/commit/8d2e6a91ac92a033e9e3daad5cffa90263075536))
    - Remove custom `graph::CommitterTimestamp` in favor of `gix-date::SecondsSinceUnixEpoch`. ([`f4b0195`](https://github.com/Byron/gitoxide/commit/f4b0195375db31cc2736fcab9665a0dc2637e74b))
    - Adapt to changes in `gix-date` ([`d575336`](https://github.com/Byron/gitoxide/commit/d575336c26e6026e463cd06d88266bb2bdd3e162))
</details>

## 0.1.0 (2023-06-10)

### Bug Fixes (BREAKING)

 - <csr-id-e9205679ab017699fd2605d4211d7ac2528dbc4b/> rename `PriorityQueue::pop()` to `::pop_value()` and add `::pop()` that also pops the key.
   This aligns the method name with `peek()`, which also pops the key.

### Commit Statistics

<csr-read-only-do-not-edit/>

 - 5 commits contributed to the release.
 - 1 commit was understood as [conventional](https://www.conventionalcommits.org).
 - 0 issues like '(#ID)' were seen in commit messages

### Commit Details

<csr-read-only-do-not-edit/>

<details><summary>view details</summary>

 * **Uncategorized**
    - Release gix-attributes v0.13.1, gix-diff v0.30.1, gix-revwalk v0.1.0, gix-traverse v0.27.0, gix-index v0.18.0, gix-revision v0.15.2, gix-negotiate v0.2.1, gix-pack v0.37.0, gix-odb v0.47.0, gix-protocol v0.33.2, gix-worktree v0.19.0, gix v0.46.0, safety bump 7 crates ([`2560a2c`](https://github.com/Byron/gitoxide/commit/2560a2cc3e1d8c60cd812e15696fa4761d036e19))
    - Prepare changelogs prior to release ([`298f3d7`](https://github.com/Byron/gitoxide/commit/298f3d7359c5b183314d8c584e45dcdd559d88b3))
    - Merge branch 'walk-with-commitgraph' ([`fdee9a2`](https://github.com/Byron/gitoxide/commit/fdee9a22873a13ae644d3dc92f8fe93f8f0266c0))
    - Rename `PriorityQueue::pop()` to `::pop_value()` and add `::pop()` that also pops the key. ([`e920567`](https://github.com/Byron/gitoxide/commit/e9205679ab017699fd2605d4211d7ac2528dbc4b))
    - Add new `gix-revwalk` crate for support types related to revision walking. ([`13ce887`](https://github.com/Byron/gitoxide/commit/13ce887682f5c31d1f78a63613ca97b811e4ffba))
</details>

