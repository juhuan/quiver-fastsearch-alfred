# quiver-fastsearch-alfred
An Alfred workflow that searches Quiver notes by title. Searches run in about 150ms.

Setup: Set your Quiver directory as `path` in the workflow's variables (the *`[x]`* at the top-right of the workflow).

This workflow just wraps a bash script. I wrote this because:
* Other Quiver search workflows I found out there are slow and support too many features
* Built-in Quiver search doesn't rank relevance by title

I was able to speed things up by cutting back to title-only search and parallelizing some text processing.
