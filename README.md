Easy code citation from repository hosting service for org-babel.

## Usage

```
#+begin_src git-permalink
https://github.com/emacs-mirror/emacs/blob/a4dcc8b9a94466c792be3743760a4a45cf6e1e61/README#L1-L2
#+end_src
```

↓ evaluate(C-c)

```
#+RESULTS:
: Copyright (C) 2001-2022 Free Software Foundation, Inc.
: See the end of the file for license conditions.
```

## How to get permalink?

[git-link](https://github.com/sshaw/git-link) is very useful.

## Other notation

The results shown below are same.

```
#+caption: Emacs README
#+begin_src git-permalink :url https://github.com/emacs-mirror/emacs/blob/a4dcc8b9a94466c792be3743760a4a45cf6e1e61/README#L1-L2
#+end_src
```

```
#+RESULTS:
: Copyright (C) 2001-2022 Free Software Foundation, Inc.
: See the end of the file for license conditions.
```

## TODO

- support other hosting service(GitLab, Bitbucket...)
