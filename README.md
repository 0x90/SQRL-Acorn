# SQRL-Acorn
Just another attempt to make something useful frin SQRL Acorn boards

## Boards

Initially those boards were created:
- Acorn CLE-101
- Acorn CLE-215
- Acorn CLE-215+

## Connectors


[Connector Housing, DF52 Series, Plug, 20 Ways, 0.8 mm, DF52 Series Contacts](https://www.element14.com/community/view-product.jspa?fsku=2724944&nsku=&COM=noscript)
[Cable Assembly, Wire to Board Receptacle to Wire to Board Receptacle, 6 Ways, 1.2 mm, 1 Row, 600 mm](https://www.element14.com/community/view-product.jspa?fsku=3257286&nsku=&COM=noscript)
I think the JTAG and I/O connectors are Molex Pico-EZMate. Thankfully premade jumper cables are available, so I can initially cut them in half for pigtails.
Molex 0781715006, connector, 6 circuits
Molex 0369200603, 300 mm jumper cable
The mysterious J1 connector seems to be about 0.8 mm pitch. At this point I think it's a Hirose DF52, 20 positions. Unfortunately I haven't been able to find premade cables for this one, and crimping these tiny contacts is not going to be fun, I'm sure.
Hirose DF52-20P-0.8C, connector plug body
Hirose DF52-20S-0.8H(21)‎, connector socket SMT
Hirose ‎DF52-2832PCF‎, crimp terminal


## Links

Research:

https://www.eevblog.com/forum/fpga/sqrl-acorn-as-an-interesting-artix-7-board/

https://www.element14.com/community/community/project14/hardwarehacking/blog/2020/05/24/do-mighty-oaks-from-sqrl-acorns-grow

https://www.element14.com/community/community/project14/hardwarehacking/blog/2020/06/01/sqrl-oak-dev-board-part-2-jtag

https://www.element14.com/community/community/project14/hardwarehacking/blog/2020/06/17/sql-oak-dev-board-part-3-schematic-reverse-engineering

https://www.element14.com/community/community/project14/hardwarehacking/blog/2020/07/13/sqrl-oak-dev-board-finishing-up


Code:


Supported by ltex

https://github.com/litex-hub/litex-boards

https://github.com/d953i/SQRL_ACORN

https://github.com/enjoy-digital/usb3_pipe
