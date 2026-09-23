# instagram-automation-content

Generated Instagram carousel card images for BuildNest's Instagram automation
pipeline. Public on purpose: the Meta Graph API needs a public HTTPS URL to
fetch each card image when publishing a carousel post, and the pipeline's
code/docs repo ([`instagram-automation`](https://github.com/Sourabhlpu/instagram-automation))
stays private.

Nothing here is written by hand — every file under `drafts/` is committed by
Claude Code as part of running a posting cycle. See
[`docs/agents/instagram-cycle.md`](https://github.com/Sourabhlpu/instagram-automation/blob/main/docs/agents/instagram-cycle.md)
in the main repo for the procedure.

## Layout

```
drafts/<draft-id>/card-N.png
```

Each image's public URL:

```
https://raw.githubusercontent.com/Sourabhlpu/instagram-automation-content/main/drafts/<draft-id>/card-N.png
```
