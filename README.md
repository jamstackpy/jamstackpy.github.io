# jamstackpy.github.io

Source of <https://jamstackpy.github.io/>, the jamstack documentation site.

The pages live in [jamstackpy/jamstack](https://github.com/jamstackpy/jamstack/tree/2.0/docs)
and are built with [Zensical](https://zensical.org/). This repository only keeps
the workflow that builds the `2.0` branch and publishes the result to the
`deploy` branch, which GitHub Pages serves.

The scheduled run rebuilds the site every day so documentation changes reach
the public site without a manual step. Use `workflow_dispatch` to publish
immediately.
