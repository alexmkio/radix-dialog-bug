## Bug Report: https://github.com/radix-ui/primitives/issues/2860

### Current Behavior

On a Windows machine using Ctrl + mouse scroll wheel up or mouse scroll wheel down while the Dialog component is open does not zoom the page in or out. 

This hotkey does work while the Dialog is not open, and other hotkeys for zooming in and out (Ctrl + +, Ctrl + -) do work while the Dialog component is open.

### Expected behavior

On a Windows machine I expect that using Ctrl + mouse scroll wheel up or mouse scroll wheel down will zoom the page in or out.

This is standard behavior on Windows: "On Windows, holding down the Control button and scrolling the mouse wheel or trackpad can zoom in or out when viewing a webpage in a browser. To zoom in, roll the scroll wheel forward, and to zoom out, roll it backward."

### Reproducible example

[React minimal reproducible example](https://github.com/alexmkio/radix-dialog-bug)

[Deployment](https://radix-dialog-bug.vercel.app/)

### Suggested solution

No idea, but I did test this hotkey on React Portals and it worked the company I work for will likely pivot to React Portals to achieve this desired functionality for our client.

### Additional context

None

### Your environment

| Software         | Name(s) | Version |
| ---------------- | ------- | ------- |
| Radix Package(s) |    @radix-ui/react-dialog     |   ^1.0.5      |
| React            | n/a     |    ^18.2.0     |
| Browser          |    Chrome     |    124.0.6367.61     |
| Browser          |    Chrome Canary     |     126.0.6435.1    |
| Browser          |    Firefox     |     152.0.2    |
| Assistive tech   |    n/a     |     n/a    |
| Node             | n/a     |    n/a     |
| npm/yarn         |    npm     |    10.5.0     |
| Operating System |    Windows 10 Pro    |    22H2  OS build 19045.4291   |