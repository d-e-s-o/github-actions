github-actions
==============

Reusable GitHub Actions used in the `libbpf` org.

We provide no backwards compatibility guarantees short of not clobbering
`git` commit history. Be sure to pin the snapshot you consume.

Usage
-----

### build-linux

Build a Linux kernel from source with caching support.

```yaml
- uses: libbpf/github-actions@<ref>
  with:
    config: <path-to-config>
```
