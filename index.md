---
layout: page
title: initial steps towards reproducible research
---

A minimal standard for data analysis and other scientific computations is
that they be _reproducible_: that the code and data are assembled in a
way so that another group can re-create all of the results (e.g., the
figures in a paper). Adopting a workflow that will make your results
reproducible will ultimately make your life easier; if a problem (or
question) arises somewhere down the line, it will be much easier to
correct (or explain).

Organizing analyses so that they are reproducible is not easy. It
requires diligence and a considerable investment of time: to learn new
computational tools, and to organize and document analyses as you go.

And _partially reproducible_ is better than _not at all
reproducible_. Just try to make your next paper or project better organized
than the last.

There are many paths towards reproducible research, and you shouldn't
try to change all aspects your current practices all at once. Identify
one weakness, adopt an improved approach, refine that a bit, and then
move on to the next thing.

Inspired by
[Christine Bahlai](https://practicaldatamanagement.wordpress.com)'s
&ldquo;[Baby steps for the open-curious](https://practicaldatamanagement.wordpress.com/2014/10/23/baby-steps-for-the-open-curious/),&rdquo;
I thought I'd write some suggestions for the initial steps to take
towards making one's work reproducible.

I'm focusing primarily on [R](http://www.r-project.org), because
that's what I know, but I'll try to at least sketch what a
[python](http://www.python.org) person might do.

You shouldn't try to do these things all at once; start with one, or part of
one. Then in your next project, do that plus another thing.

- [Everything with a script](pages/scripts.html)
- [Organize your data and code](pages/organize.html)
- [Automate the process, and document dependencies](pages/automate.html)
- [Turn scripts into reproducible reports](pages/reports.html)
- [Turn repeated code into functions](pages/functions.html)
- [Package functions for reuse](pages/packages.html)
- [Use version control](pages/version_control.html)
- [Other resources](pages/resources.html)

---


The source for this minimal tutorial is [on github](http://github.com/kbroman/step2rr).
If you have suggestions for changes or improvements,
[submit an issue](https://github.com/kbroman/steps2rr/issues).


Also see my
[git/github guide](http://kbroman.org/github_tutorial),
[knitr in a knutshell tutorial](http://kbroman.org/knitr_knutshell),
[minimal make tutorial](http://kbroman.org/minimal_make),
[simple site tutorial](http://kbroman.org/simple_site),
and [R package primer](http://kbroman.org/pkg_primer).