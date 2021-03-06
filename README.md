# Two-reasons-for-using-C-over-C-




For a lot of embedded processors, either there is no C++ compiler, or you have to pay extra for it.
My experience is that a signficant proportion of embedded software engineers have little or no experience of C++ -- either because of (1), or because it tends not to be taught on electronic engineeering degrees -- and so it would be better to stick with what they know.
Also, the original question, and a number of comments, mention the 4 Kb of RAM. For a typical embedded processor, the amount of RAM is (mostly) unrelated to the code size, as the code is stored, and run from, flash.

Certainly, the amount of code storage space is something to bear in mind, but as new, more capacious, processors appear on the market, it's less of an issue than it used to be for all but the most cost-sensitive projects.

On the use of a subset of C++ for use with embedded systems: there is now a MISRA C++ standard, which may be worth a look.
