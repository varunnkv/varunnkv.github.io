---
title: "latex using vim: best practices"
---

## latex using vim: best practices
when i began academic writing, my first instinct was to use vim as my editor for latex.
i had been using vim for programming (mostly C and python) for quite a while before i started editing latex.
navigation in vim was too revolutionary a concept for me when i first came across it.
it was just so good that i tried using vimperator on my browser and pdf viewers with vim bindings (zathura) for a time.
i did not even bother with trying out emacs because of how good i found vim as an editor.
but after i came to theoretical research, i have tried out many editors,
*viz* atom, sublime, even emacs for a while, and very recently vscode (which i still consider a viable option; more on this later).

**disclaimer** this post is not trying to make a case for vim as an editor for latex.
rather, this is for the people who are already convinced about using vim to edit latex.
these are some guidelines for writing the code such that it is easier to edit and navigate.
{: .notice--warning}

in this post, i wanted to discuss various *guidelines* i find myself following as i type and edit and navigate latex files more and more.
in doing this, i am at the risk of looking stupid, for there could be more optimal ways to do things that i am trying to do here.
in this case, feel free to embarass me by pointing them out.
also, i am quite aware that this is unnecessarily pedantic, like having/discussing algorithms about best ways to eat a specific dish.
but in my defence, best coding practices is a thing and hence i thing there is some value in this.

#### a line of latex code
the first question we need to as ourselves is about writing text (as opposed to math) in latex.
about 2 to 3 ways suggest themselves.
1. write an entire paragraph as a single line and exploit word wrap of the editor
2. newline at the end of each sentence
3. limit each line to just one line width in the editor
