# 5 Useful Tips for Linux Commands

1. Use `mkdir{}` to create multiple combinations of folders by surrounding the path with segments and braces. 
    - E.g.: `mkdir -p ./home/{a,b}/{x,y,z}`.

2. Use `cd -` to go back to the directory you have started working on.

3. If you need to create N files (for example), run `touch {1..N}` being N the total quantity of files desired. 
    - E.g.: "I want to create 100 txt files" → `touch file{1..100}.txt`.

4. Instead of rerunning a log file that's constantly changing, use `tail -f err.log` to follow changes and automatically get updates in real time.

5. Run `history N` to print out your last N commands.