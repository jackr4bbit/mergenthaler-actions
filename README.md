# Mergenthaler GitHub Actions

A collection of GitHub Actions to build and test your Mergenthaler feeds.

## Actions Included

### 1. Mergenthaler Test
Validates a Mergenthaler feed's syntax.

```yaml
- name: Test Feed
  uses: jackr4bbit/mergenthaler-actions/test@v1
  with:
    location: "."
```

### 2. Mergenthaler Build
Builds a static site from a Mergenthaler feed.

```yaml
- name: Build Site
  uses: jackr4bbit/mergenthaler-actions/build@v1
  with:
    location: "."
    output: "output"
    nodelete: "true"
```
