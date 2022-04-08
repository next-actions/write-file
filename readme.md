# Write contents to a file

Simple action that write contents to a file. Environment variables are
evaluated.

## Inputs

### `working-directory`

Working directory. Defaults to current working directory.

### `path`

File path to write to.

### `contents`

Desired contents.

## Example usage

```yaml
- name: Write to a file
  uses: next-actions/write-file@master
  with:
    path: test.log
    contents: |
      desired contents
```
