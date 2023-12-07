Dahl was guided by a few rigid principles:
• A Node program/process runs on a single thread, ordering execution
through an event loop
• Web applications are I/O intensive, so the focus should be on making I/O fast
• Program flow is always directed through asynchronous callbacks
• Expensive CPU operations should be split off into separate parallel processes,
emitting events as results arrive
• Complex programs should be assembled from simpler programs

