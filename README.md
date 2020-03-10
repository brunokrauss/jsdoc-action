# JSDoc Docker Action
This [GitHub Action](https://github.com/features/actions) will build [JSDoc](https://jsdoc.app/) docs from a defined source directory.

## Inputs
### 'jsdoc-path'
**Required** Path to the source directory. Default: `src`.

## Example usage
```yaml
uses: brunokrauss/jsdoc-action@v1
with:
    jsdoc-path: 'src'
```
