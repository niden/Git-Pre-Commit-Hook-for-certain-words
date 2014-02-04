GIT - Pre-Commit check for certain words
----------------------------------------

:Author: Nikolaos Dimopoulos <nikos@niden.net>
:Thanks to: Remigijus Jarmalavicius <remigijus(at)jarmalavicius.lt>

About
-----
GIT pre-commit hook for checking the existence of certain words/phrases/functions 
in the code to be committed. 

How to install
--------------
To install hook, copy pre-commit file to your project .git/hooks/pre-commit:

    $ cp pre-commit .git/hooks/pre-commit;
    $ chmod +x .git/hooks/pre-commit;

The hook comes with the "die", "print_r" and "var_dump" functions as the strings to 
be checked prior to the commit. You can add more strings to be checked if you wish 
by modifying the checks array

Bugs
----
For any bugs, please visit:

    https://github.com/niden/Git-Pre-Commit-Hook-for-certain-words/issues
