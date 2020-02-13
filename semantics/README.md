# Semantic HTML

Semantic HTML gives meaning to a document; by using the correct element for its containing content, the document is marked-up in a meaningful way, aiding both human and machine.

Since the advent of HTML5, applying semantics to a webpage's content has been made a lot simpler - there is now a plethora of elements to choose from, each suited to a particular piece of text, media or collection of items.

Applying semantics to a chunk of text has always been possible in HTML, just take the following paragraph

> Writers write descriptive paragraphs because their purpose is to describe something. Their point is that something is beautiful or disgusting or strangely intriguing.

#### Semantic Markup

```
<p>Writers write descriptive paragraphs because their purpose is to describe something. Their point is that something is beautiful or disgusting or strangely intriguing.</p>
```

The above snippet demonstrates semantic HTML in action; the content contained by the `<p>`aragraph tags is a block of text.

#### Non-Semantic Markup

The following markup is non-semantic, the right element isn't being used for the content;

```
<div>Writers write descriptive paragraphs because their purpose is to describe something. Their point is that something is beautiful or disgusting or strangely intriguing.</div>
```

It isn't unusual for the `<div>`ision element to be used for any ol' piece of content. and
it wouldn't take much work for the above snippet to render exactly as the sematic example using [CSS](https://github.com/iamdcj/CSS), however using the right element for the content is both sensible, and worthwhile.

## Benefits of Semantics

---

#### References

[Semantic Markup](https://html.com/semantic-markup/)
