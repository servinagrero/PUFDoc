# PUFDOC Format

## Installing

To install this template as an extension for an existing document, run the following command in your project working directory:

```bash
quarto use template servinagrero/PUFDoc
```

To your Quarto document yaml, add any of the following

```yaml
format:
  pufdoc-html: default
  pufdoc-revealjs: default
  pufdoc-pdf: default
```

## Using

You can render the template.qmd provided to try it out.

```bash
quarto render article.qmd --to pufdoc-pdf
```

## Format Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [example.qmd](example.qmd).
