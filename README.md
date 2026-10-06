# xbox360-streaming

**Research on minimizing DLNA/UPnP delay on an Xbox 360 XOR utilizing RGH/JTAG custom dashboards to stream music from streaming services natively**


Conceptually for the DLNA/UPnP server, the best plan of action would be hosting it locally, while receiving a buffered "live" streamed audio feed from a server

Would greatly increase pre-load times and make it not as snappy as clicking "play", but would solve many issues I faced in the now archived `xbox360streaming` project

Native "game-like" service would most likely be impossible, due to the Xbox 360 having minimal resources

The best plan of action would be to utilize already exposed Aurora dashboard functions and utilities to go on top of the game, taking into account game API calls for radio pausing etc
