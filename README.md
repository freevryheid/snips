snips - snippets archiver
=========================

snips [file]

Snips provides a command line utility to gzip archive source code snippets. These are defined in terms of a name or description and a source code block that can be edited using the system defined EDITOR. Long snippets are sent to the system defined PAGER. You can search snippets using regular expressions. Snippets can be copied to clipboard for use elsewhere: e.g. ipython %paste or psql \e and paste

Syntax is defined in the [file] option that is the snippets filename. This indicates the source code format that is used to allow syntax highlighting in EDITOR, use 'c' for c, 'for' for fortran or whatever extension that triggers specific syntx highlighting within EDITOR.

Snips uses the editor defined in the EDITOR environment variable or nano if this is not defined. I set this in my .bashrc: export EDITOR=vim

hint: set 'less' as your PAGER to search long snippets, etc.
