This repo will be an outline of my home lab configuration both the software and physical layout. I'll include links to any open source projects I'm using.

Physical layout:


```mermaid
graph TD;
    VPS-->Router;
    Router-->'Small Server';
    'Unamanaged Switch'-->Wireless AP 1';
    'Wireless AP 1'-->'Wireless AP 2';
	'Wireless AP 2'-->'Big Server';
```