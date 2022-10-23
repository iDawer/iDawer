
<div style="display: flex; justify-content: space-between;">
<div><h2>Ilnur Iskhakov</h2></div>
<div>
e-mail: [job.ilnur.iskhakov@outlook.com](mailto:job.ilnur.iskhakov@outlook.com)
<br/> GitHub: [github.com/iDawer](https://github.com/iDawer)
</div>
</div>

## Software Engineer

I'm looking for **Junior Rust Developer** position.

 - Language: prefer _Russian_, can speak _English_ and planning to take an exam for it.
 - Location: Ufa, Russia. Open for relocation. Prefer full-time remote. Any timezone.
 - Good knowledge in _Rust, Bash, Git, Linux, Python_.
 - Basic knowledge in _C/C++, cryptography primitives, Java, C#,
   JavaScript, HTML/CSS, Lua, SQL, Assembler_.
 - Hobbies: I'm pretty into bicycling.

## Background

### Contributing into Rust infrastructure

I have committed into _rust-analyzer_ worth of top 12 contributors (by GitHub [\[1\]][1]).
My contributions include fixing bugs and adding features into core of _r-a_ [\[2\]][2].
In particular I worked on exhaustiveness check subsystem to synchronize it with Rust compiler,
improved type system implementation and various IDE assists.

I learned _type systems_, _theorem proving_, _abstract syntax tree_ and _git_.

### Making Rust target for ANTLR

ANTLR is a parser generator and I'm using _Java_ to extend ANTLR to generate parsers in Rust language.
It also has Rust runtime I'm writing for generated parsers.
For memory management I got inspirations from _C++_ target and
it showed me how Rust's ownership model restricts one to one translation from other languages.

This is the project where I learned Rust language: _syntax_, _trait system_, _lifetimes_.

### Fixing Linux driver

I revived an old EciAdsl usermode driver for USB ADSL modems [\[3\]][3].
The project is written in _C_ and the last commit is dated 2007.
I had to adopt it to recent Linux kernel changes and adjusted it to make it work with my modem.
I fixed includes and transitioned from deprecated _usbdevfs_ Linux subsystem to new _Linux USB API_.

The instrumentaries I used was _usbcap_ to log USB bus, _gdb_ for debugging and
_Wireshark_ to view _PPP_ packets within USB bus traces.

### Authoring jbeam-flow: Python add-on for Blender [\[4\]][4]

I used _Python_ to extend 3D computer graphic tool _Blender_ to make it understand vehicle files
(in _JSON_-like format) of BeamNG.drive game.
The idea is to map vehicle parts to _Blender_'s 3D primitives to make them editable with visual tools.

I wrote a _parser_ in _EBNF_ with ANTLR and
implemented user interface with help of _Python_'s _metaclasses_.

### Reference

\[1\]: [github.com/rust-lang/rust-analyzer/graphs/contributors][1]
<br/>
\[2\]: [github.com/rust-lang/rust-analyzer/issues?q=author:iDawer][2]
<br/>
\[3\]: [github.com/iDawer/eciadsl-usermode][3]
<br/>
\[4\]: [github.com/iDawer/jbeam-flow][4]

[1]: https://github.com/rust-lang/rust-analyzer/graphs/contributors
[2]: https://github.com/rust-lang/rust-analyzer/issues?q=author:iDawer
[3]: https://github.com/iDawer/eciadsl-usermode
[4]: https://github.com/iDawer/jbeam-flow

<style>
    h2, h3, p, ul {
        margin: 0.3em 0 0.3em;
    }
</style>

