 Here are what to be included in each files you create according to the instructions

0. Hello World
  Script:   #!/bin/bash
    echo Hello, World
1. Confused smiley
Script:   #!/bin/bash
    echo \"\(\Ôo\)\'
2. Let's display a file
Script:   #!/bin/bash
    cat /etc/passwd
3. What about 2?
Script:   #!/bin/bash
    cat /etc/passwd /etc/hosts
4. Last lines of a file
Script:   #!/bin/bash
    tail -10 /etc/passwd
5. I'd prefer the first ones actually
  Script:   #!/bin/bash
    head -10 /etc/passwd
6. Line #2
  Script:   #!/bin/bash
    cat iacta | head -3 | tail -1
7. It is a good file that cuts iron without making a noise
  Script:   #!/bin/bash
    echo "Best School" > '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)'
8. Save current state of directory
  Script:   #!/bin/bash
    ls -la > ls_cwd_content
9. Duplicate last line
  Script:   #!/bin/bash
    tail -1 iacta >> iacta
10. No more javascript
  Script:   #!/bin/bash
    find . -name '*.js' -type f -delete
11. Don't just count your directories, make your directories count
  Script:   #!/bin/bash
    find ./* -type d -print | wc -l
12. What’s new
  Script:   #!/bin/bash
    ls -t | head
13. Being unique is better than being perfect
  Script:   #!/bin/bash
    sort | uniq -u
14. It must be in that file
  Script:   #!/bin/bash
    grep "root" /etc/passwd


15. Count that word
  Script:   #!/bin/bash
    grep bin /etc/passwd | wc -l
16. What's next?
  Script:   #!/bin/bash
    grep -A 3 root /etc/passwd
17. I hate bins
  Script:   #!/bin/bash
    grep -v bin /etc/passwd
18. Letters only please
  Script:   #!/bin/bash
    grep ^[[:alpha:]] /etc/ssh/sshd_config
19. A to Z
  Script:   #!/bin/bash
    tr "Ac" "Ze"
20. Without C, you would live in hiago
  Script:   #!/bin/bash
    tr -d [cC]
21. esreveR
  Script:   #!/bin/bash
    rev
22. DJ Cut Killer
  Script:   #!/bin/bash
    cut -d":" -f 1,6 /etc/passwd | sort
23. Empty casks make the most noise
  Script:   #!/bin/bash
    find . -empty -printf "%f\n"
24. A gif is worth ten thousand words
  Script:   #!/bin/bash
    find . -type f -name "*.gif" -printf "%f\n"| rev | cut -d '.' -f2- | rev | LC_ALL=C sort -f
25. Acrostic
  Script:   #!/bin/bash
    echo -ne $(cut -c-1 | tr -d '\n')'\n'
26. The biggest fan
  Script:   #!/bin/bash
    tail -n +2 | cut -f1 | sort | uniq -c | sort -nr -k 1,1 | cut -c 9- | head -11

Above are the solutions for the shell redirection tasks. Make sure that for each task, you use the command chmod u+x <file name> before you add and commit your changes so that the script can be executable.

See more and follow @github.com/soundn
