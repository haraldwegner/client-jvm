# MOVED → client-java (2026-06-11)

The FeedClient facade sprint formerly specified here moved to
**`~/CursorProjects/client-java/docs/ClientJava_Sprint1.md`** when the Java side
became a **complete rewrite** (this fork's upstream, `polygon-io/client-jvm`, ships
no license; the actually-used SDK surface was 3 REST endpoints + the WS path the
facade replaces anyway).

**Status of this repo (the fork):** legacy only. No further development here.
Consumers' escape-hatch path depends on the JitPack **v5.1.2 binary artifact**, not
on this fork; the fork exists for reference/diffing and can be archived once the
escape hatch retires.
