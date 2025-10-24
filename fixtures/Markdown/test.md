# Markdown Test Cases

Note: This rule should only flag markdown syntax in NON-MARKDOWN contexts.

## Should Flag (in non-.md files)

Code block with language:
```python
def example():
    pass
```

Code block without language:
```
code here
```

### Heading Syntax Level 3

#### Heading Syntax Level 4

**Bold Text:** followed by description text

<!-- HTML comment in plain text context -->

Table of contents marker [TOC] for auto-generation

## Should NOT Flag

Normal prose without markdown formatting.

Standard paragraph text.
