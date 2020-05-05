# runspaced-blockingcollection
A tiny helper for creating runspaced blocking collections

## What's this

This is a helper for implementing a BlockingCollection<hashtable> so that items may be added to a 'queue' in a thread-safe manner and consumed from a separate thread (runspace). The reason for this is to handle logging, metrics production, etc in a threaded system.
