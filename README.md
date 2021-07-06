# Radare2
What is better than Radare2?

```console
V - hexdump
	p - dissambler
	p - debugger
	
aaa - analyse binary

afl - analyse function list

s main - seek main

<enter> - goto

u - go back

axt - find data/code reference to address

axf - find data/code reference from address

ii - list imports

iE - list exports

iS - list sections

is - list symbols

iz - get strings from .data section

izz - get strings from entire binary

pf - print formatted data

<shift-a> - modify assembly

<f7> - step into

<f8> - step over

db main - set breakpoint at main

dc - continue execution

do - restart debugging

<.> - go back to instruction pointer

dsf - step until end of frame

VV - graph view
	<letter> - goto the letter's (function) graph view
	<x> - cross reference
		<number> - goto that cross referred address

<;> - comment
	<-> - remove comment
	
afvd - output r2 command for displaying the value of args/locals in the debugger
	afvd [variable] - show recommended command to show value
	pf S @[pointer address] - show value

pf S @ [pointer address] - print value in pointer address

~.. - pipe to less
	 ia~.. - show ia output in less format

~ - pipe to grep
	afl~main - grep main from afl output
	
pdf - print disassembly function

/ad/ [operand] - show all [operand] found in binary
	/ad/ [operand1] [operand2] - show all results where [operand1] and [operand2] exist
```

# Cheatsheet for rabin2

``` console
I - show binary information

H - show file headers

M - main address

z - get strings from .data section

zz - get strings from entire binary
```

# Cheatsheet for rafind2

```console
s - search for specific string and output address
```
