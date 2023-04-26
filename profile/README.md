# Overview

My vision for Juptune is to be a high-performance; @nogc-first collection of foundational D libraries that can be used to grow a small ecosystem of various libraries and applications that all build off of one common foundation.

## Motivation

The D language is great - everything else though... not so much.

The D leadership are terrified of change so parts of the language (e.g. Phobos) are effectively frozen in time. They have 0 interest in building up or endorsing projects that allow people to actually build things in D for the modern cloud-based, web app era, and honestly I think they just lack care in general for the wider community.

One of the outcomes for this is that there is no common basis for anything: event loops, HTTP libraries (that integrate with said event loop), SQL libraries (that integrate with said event loop), etc.

And if libraries do exist, they are often in a state of bit rot; don't integrate with eachother properly due to lack of common basis, and honestly it's just a gamble whether your code will compile a year later.

Being sick of all of these things I've decided to go my own way and carve out my own personal ecosystem with Juptune - with the focus being on things I truly want.
