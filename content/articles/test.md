+++
id = "test"
title = "Test Article"
excerpt = "Article test content."
date = "2022-02-15T16:00:00+01:00"
draft = true
template = "post.html"
+++

Let's go!

# Heading 1

Footnote?[^1]

## Subheading 2

### Subheading 3

<aside>
<p>Your aside content goes here.</p>
</aside>

#### Subheading 4

##### Subheading 5

This is `code`.

And a code[^1][^2] block:

```rust
#[tokio::main]
async fn main() {
    env_logger::init();

    if let Err(e) = try_main().await {
        error!("{}", e);
        std::process::exit(1);
    }
}
```

###### Subheading 6

```mermaid
sequenceDiagram
    Alice ->> Bob: Hello Bob, how are you?
    Bob-->>John: How about you John?
    Bob--x Alice: I am good thanks!
    Bob-x John: I am good thanks!
    Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

    Bob-->Alice: Checking with John...
    Alice->John: Yes... John, how are you?
```

More text

Sources:

[^1]: <https://example.com/>

[^2]: Anekdote
