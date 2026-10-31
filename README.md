# flatnotes LazyCat community package

Upstream https://github.com/dullage/flatnotes; official candidate in.zhaoj.flatnotes. Package community.lazycat.app.flatnotes,5.5.5,minOS1.5.0,amd64 mirror delivery. Community store only. Intended category: Productivity / Notes13.

Single HTTP8080 container, no external database. Markdown notes and search index persist in /lzcapp/var/data. Upstream entrypoint fixes data ownership and drops to UID1000:1000; native image healthcheck is retained.

LazyCat entry protection stays enabled. Native password authentication uses shared admin account, deployment secret and stable JWT key. /login uses #username/#password autofill, not automatic submit. All authorized app members share the account and all notes; grant access only to trusted members. Updating deployment password changes login credentials. Back up/export before uninstalling.

Build, Release download and independent package SHA256/content verification all run on GitHub, not locally. No smoke job or file interception. Real-device startup, autofill, CRUD, search, attachment and persistence remain unverified.

Initial full dedup7pages628unique apps, no matching name/alias/package/source. Recheck before publication and verify category13 afterwards. SilverBullet, Gatus and changedetection are other unstarted candidates; Glance74 already exists.
