# Dfeich's Org-babel example collection

This is my collection of example documents to demonstrate the usage of org-babel
with different languages.

I have used org and especially the org-babel functionality for writing manuals for

-   writing documentation for **programming projects** (e.g. for python)
-   for documenting **benchmarking** tests
-   documenting the **installation of servers**. E.g. the complete
    installation of an OpenLDAP master and its slaves is an executable
    document. By making smart use of tramp + ssh configuration (check
    the ControlMaster and ProxyCommand options), the code is executed on
    the servers a few hops away. The documentation I publish via my
    **Twiki exporter** on our intranet.
-   creating **OpenDocument documents** from clean templates. This even helped in
    getting a clear basis for a group of people trying to merge a number
    of partial office documents.
-   **Planning a major (at least for us&#x2026; 17 people) IT project** using org
    tables and lisp code for more complex table functions. The cost
    planning and general planning was all done in Org. The project's
    gantt chart had to be done in MS Project due to our institution's
    guidelines, but based on the MS Project csv export, I was able to
    process the MS project data again directly in org. This made the
    committing of changes into the evolving proposal a breeze!
-   use an org table as input to **seed a DB** with and then **run SQL queries** on it.
    Great for DB debugging and documenting.
-   I produce most of my presentations really fast with **beamer**. Being able to copy
    information from all my other org documents into the presentation makes this
    very efficient.

I again have to thank the authors and maintainers of org-mode and all
the community for providing such a versatile and efficient tool. I
hope that others can profit from the examples. Sometimes it took quite
a bit of effort to understand how to do things, and I was glad to find
references. But with Emacs there is also always the option to "Read
the Source, Luke!"&#x2026; and reading the source not only might solve your
problem, but also it often leads to a deeper understanding of the
concepts.

I am glad for feedback and corrections&#x2026; (e.g. if there is anybody with better
knowledge of how to integrate calc)

Have fun hacking away&#x2026;.
Derek