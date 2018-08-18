# Regular Expression

## Negative Lookahead

When you need to match string that are not following by pattern.

The sample below, i want to select all words except 'cat'

```
"(?!cat)\b\w+" => **The** **fat** cat **sat** **on** **the** **concatenation**.
```

The **(?!...)** is negative lookeahead and the **\b\w+** is to select all words