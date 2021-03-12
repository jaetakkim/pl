### Fri 03/12/21

**What I did/didn't do:**

* Wrote down new language that incorporates all of the variables.
* I created a graph from a specific program example.
* Read a lot of Scargall's *Programming Persistent Memory* Book (not that I understood much).

**Next Goals:**

1. Show and write down in LaTeX that every variable must be followed by a clwb and sfence for it to persist. So clearly they didn't understand what I was saying last week. Show this using both the logic of the PMTest and from the operational semantics from Raad et al. POPL'20. Probably send it over to them in the middle of the week. Figure out if this problem is actually just dumb.
2. If I am right about #1 above, then maybe ask whether there are harder questions or whether the question we've been asking has been dumb all along. Maybe it's more like the POPL'20 paper examples where it was implication and not necessarily persist *guarantee*. There must be a harder language that is at least context-free.
3. Take the core operations from libpmemobj and try to create a reachability algorithm from the CFG.
4. Read up on the PMDK libpmemobj blog posts on pmem.io website.

#### Meeting Notes

* Be more comfortable speaking up when I don't know what they're talking about.
* Remember that this is your project so they haven't read up on it as you have. You have to explain to them in detail your thought process and exactly what you've been doing. It helps to go through it with a pdf of stuff + text document to write random things in.

### Fri 03/05/21

**What I did/didn't do:**

- Didn't get to the whole "not-technically-one-language-reach" thing
- I added to the formulation RMW, sfence, flush
- I briefly looked at PMDK + TX_Ops
- Reread bits of ASPLOS '19 PMTest

**Next Goals:**

1. Create graph from specific code example and show analysis
2. Figure out what Qirun and Yuanbo said about how language is actually different assuming multiple variables + what kind of language is this?
3. Investigate further the actual uses and practices of PMDK library, focusing on how developers use them, and how to show 100% correct memory/persistence analysis on these PMDK ops are hard (in the computational complexity sense)

