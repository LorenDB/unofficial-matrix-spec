# The unofficial Matrix spec

The [Matrix spec](https://spec.matrix.org/latest) is great, but sometimes it just isn't enough,
so you take advantage of its extensible design and create a custom event to bring it to its fullest
potential. However, using custom events has one glaring problem: custom events aren't standardized,
so those who aren't using your client might not be able to view the event you send properly (in fact,
they might not be able to view it at all).

The solution? Add your custom event to the unofficial Matrix spec! This repository contains a list of
known custom events that, although they aren't necessarily a good fit for the official Matrix spec,
could very well be a good fit for your client.

## Sections

- [Custom message types](./message-types)
- [Custom events](./event-types)

## Contributing

If you have a custom event type, please feel free to open a pull request to add it to this list!
Unless you have something that is really offensive, NSFW, or otherwise inappropriate, there is no
reason that it can't be added to this list!

## Talk

Come talk about this list of custom events at [#unofficial-matrix-spec:nheko.im](https://matrix.to/#/#unofficial-matrix-spec:nheko.im)!
