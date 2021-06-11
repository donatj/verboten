# Verboten

Simple CI Tool to forbid files from matching preg regexes.

## Example Usage

```bash
php vendor/bin/verboten '/overflow.*?:\s*scroll/' -- $(find ~<folder> -name '*.scss')
```
