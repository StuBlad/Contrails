
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

photography

# isEnabled

> Whether this feed should be published by the "Publish Feed Generators" step. Set to `true` or `false`.

true

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

Photography 📸

# description

> This is the description of the feed.

A feed for all things Photography. Only posts with 📸 in them will show up in this feed. Use this to curate your photography uploads to appear in this custom feed.

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- https://bsky.app/profile/stublad.renoproject.org/post/3jzjbouxwz62t
- 📸

# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

true

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar2.png`, but just be sure this CONFIG.md points to the correct file.

![](photography.png)
