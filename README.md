# Sample React App

A sample React project used for testing [Transync](https://github.com/kaisarnajar-driod/translation-automation-tool) — the translation automation tool.

## Clone

```bash
git clone git@github.com:kaisarnajar-driod/sample-react-app.git
```

## String Resources

- **Format:** JSON
- **Path:** `src/locales/en/strings.json`
- **Translated output:** `src/locales/{lang}/strings.json`

## Add to Transync

```bash
transync add sample-react-app git@github.com:kaisarnajar-driod/sample-react-app.git \
  --strings-path src/locales/en/strings.json \
  --languages hi,ar,fr,es
```
