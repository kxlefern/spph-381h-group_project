Expected folders are data/, report/, dashboard/, and milestones/. The public-use CSV will be committed once under data/ and treated as read-only files. R source files will load tidyverse explicitly and use paths relative to the project root.

Another student should be able to open the course Codespace, start at the repository root, and run quarto render on the named source. Generated visual figures, and HTML files will be regenerated from code rather than edited by hand. Any added dependency will be recorded before use.

Feasibility check: the CSV loaded successfully in the course environment with 52,753 rows and 17 columns. R is the project language; a Python version is not needed for the proposed questions.
