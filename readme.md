# j2p

Json to php cli converter tool.

## Installion

```bash
composer global require lintaba/j2p
```

## Usage

Convert clipboard's json to php format
```bash
pbpaste | j2p | pbcopy
```

---


Convert from stdin
```bash
echo '{"foo":42}' | j2p

```

Output: 
```php
[
    'foo' => 42,
]
```
